# MBTI 知识库 — Schema

> 本文件是 LLM 进入知识库的全局入口。根据当前任务类型，直接跳转到对应指南执行。

---

## 任务路由

**请根据当前任务，仅加载对应指南，不要阅读本文件的其余部分。**

| 当前任务 | 加载指南 | 路径 |
|----------|----------|------|
| 回答用户问题 | LLM 查阅知识库指南 | [[guides/LLM查阅知识库指南]] |
| 收录原始资料 | 原始资料→知识单元指南 | [[guides/原始资料-知识单元指南]] |
| 编译 Wiki 页面 | 知识单元→Wiki 指南 | [[guides/知识单元-WIKI指南]] |
| 维护检查 Wiki | Wiki 维护检查指南 | [[guides/Wiki维护检查指南]] |
| 清洗品牌/版权内容 | 内容清洗指南 | [[guides/内容清洗指南]] |
| 了解知识库架构 | 知识库架构说明 | [[docs/知识库架构说明]] |

---

> 以下内容为架构参考信息，仅在需要时查阅。

## 目录结构

```
MBTI知识库/
├── CLAUDE.md                ← 本文件（全局入口）
├── raw/                     ← 原始素材（人类管理，LLM 只读）
│   ├── books/
│   ├── articles/
│   └── 来源清单.md
├── units/                   ← 知识单元（LLM 生成，按来源文件夹组织）
│   ├── index.md             ← 全局索引（指向各来源文件夹）
│   └── {来源文件夹}/        ← 每份来源一个文件夹（文件夹名=来源文件名去扩展名）
│       ├── index.md         ← 该来源的知识单元清单
│       ├── {TYPE}/          ← 类型专属单元
│       ├── relationships/   ← 关系单元
│       └── *.md             ← 通用理论单元（维度、类型组、策略等）
├── wiki/                    ← 知识 Wiki（LLM 维护）
│   ├── wiki-index.md        ← 语义目录（每条含摘要，LLM 查阅入口）
│   ├── log.md
│   ├── types/               ← 枢纽页 + 详情子页面（按类型子目录）
│   ├── dimensions/
│   ├── functions/
│   ├── type-groups/
│   ├── strategies/          ← 四大策略
│   ├── theory/              ← 理论背景
│   ├── growth/
│   ├── relationships/
│   ├── life-domains/
│   ├── comparisons/
│   └── sources/
├── templates/               ← 页面模板（由指南引用）
├── docs/                    ← 架构说明文档（人类参考）
│   └── 知识库架构说明.md
└── guides/
    ├── 原始资料-知识单元指南.md
    ├── 知识单元-WIKI指南.md
    ├── LLM查阅知识库指南.md
    └── Wiki维护检查指南.md
```

## Wiki 页面约定

### Frontmatter

```yaml
---
title: 页面标题
tags: [mbti, 相关标签]
created: YYYY-MM-DD
updated: YYYY-MM-DD
sources: [来源知识单元 id 列表]
status: draft | active | unreviewed | review
---
```

### 页面状态

| 状态 | 含义 | 谁可设置 |
|------|------|----------|
| `draft` | 收录编译中创建 | LLM |
| `active` | 已审核确认 | 仅人类 |
| `unreviewed` | 查询动态创建 | LLM |
| `review` | 需重新审核 | LLM |

### 页面命名

- 类型页面：`{TYPE}-{中文名}.md`
- 维度页面：`{维度代码}-{全称}.md`
- 认知功能：`{功能代码}-{全称}.md`

### 内部链接

- 使用 Obsidian 双链语法 `[[页面名]]`
- 每个页面底部包含 `## 相关页面` 区块

## 内容规范

- 所有 Wiki 内容使用中文撰写
- 英文专业术语首次出现时标注中文翻译
- 保持客观中立，标注争议性观点的来源
- 知识单元中以 `_` 开头的溯源字段不得纳入用户回答

## 相关页面

- [[log]] — 操作日志
