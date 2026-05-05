# MBTI 知识库 — 操作日志

> 按时间倒序记录所有收录、查询、维护操作。
> 格式：`## [YYYY-MM-DD] 操作类型 | 简述`

## [2026-05-03] lint | 维护检查
- 检查 review 页面 0 个，draft 页面 51 个，unreviewed 页面 0 个
- 全部 51 个 draft 页面补充了 `## 相关页面` 双链区块（原均仅有 2 条链接，扩充至 6-16 条）
- 修正 37 个页面的 `sources` 字段（从中文 ID 改为正确的英文知识单元 ID）
- 修正 ENFJ-成长-自重.md 的 title 字段（"自尊"→"自重"）
- 术语检查：未发现不符合术语表的用法
- 结构完整性：wiki-index.md 与实际文件一致，无孤立页面
- overview 同步：draft 页面内容不纳入 overview（未经审核）

## [2026-05-03] restructure-v6 | Wiki 架构重构：枢纽页+详情页、语义目录、轻量发布

- **类型页面重构**：从巨型单页改为枢纽页（300-500字总览+导航）+ 详情页（1:1 对应知识单元）
- **发布机制**：新增"轻量发布"模式（单来源直接发布），保留"综合编译"用于多来源场景
- **wiki-index.md 重写**：从空壳目录改为语义目录（每条 30-50 字摘要，供 LLM 语义匹配）
- **overview.md 重写**：从结构表改为叙事性综述（约 1200 字，覆盖五大维度/16型/策略/认知功能）
- **新增目录**：`wiki/strategies/`（四大策略）、`wiki/theory/`（理论背景）
- **指南更新**：知识单元-WIKI指南新增轻量发布步骤、枢纽页规范、语义目录规范、overview 内容规范
- **模板更新**：`type-profile.md` → `type-hub.md`（枢纽页模板）；新增 `type-detail.md`（详情页模板）
- **辅助文档更新**：CLAUDE.md 目录结构、知识库架构说明、LLM 查阅指南检索路径
- **首批 Wiki 页面发布**（共 51 个内容页面）：
  - overview.md（叙事性综述）
  - theory/：1 个理论页面
  - dimensions/：5 个维度页面
  - type-groups/：4 个类型组页面
  - strategies/：4 个策略页面
  - types/ENFJ/：1 枢纽页 + 22 详情页
  - relationships/：12 个组级别关系页
  - sources/：1 个来源摘要页（S1-ENFJ主人公）

## [2026-05-02] restructure-v5 | 补充维护检查、来源摘要、overview 演化、回填机制

- 新增 `guides/Wiki维护检查指南.md`：以页面状态为驱动的分级检查流程（review→unreviewed→draft），含 overview 同步更新机制、结构完整性检查、检查报告格式
- 修正来源摘要页定位：`wiki/sources/` 对应 `units/` 知识单元而非 `raw/`，模板 `source-summary.md` 更新为 `source_units` 字段
- 编译指南新增：来源摘要页创建为编译必要步骤、overview.md 更新评估规则
- 查阅指南重构第四节：轻量回填机制（四种场景 A/B/C/D），查阅过程中只做记录+标记 unreviewed，不修改已有页面，重活交给维护检查
- CLAUDE.md 任务路由表新增"维护检查 Wiki"条目

## [2026-05-02] restructure-v4 | 文件整理与 templates 关联

- 将知识库架构说明.md 从根目录移入 MBTI知识库/docs/，避免优先级高于 CLAUDE.md
- 新增 docs/ 目录作为架构说明文档存放位置
- 在原始资料指南中明确引用 templates/knowledge-unit.md 作为骨架模板
- 在 WIKI 指南中明确引用 templates/type-profile.md、source-summary.md、comparison.md
- 更新 CLAUDE.md 目录结构和路径引用

## [2026-05-02] restructure-v3 | CLAUDE.md 路由优化与共识机制

- 重构 CLAUDE.md 为任务路由器：顶部"任务路由"表格直接指向对应指南，查询场景下 LLM 无需阅读架构/收录/编译等无关内容
- 在知识单元-WIKI指南中新增"观点共识机制"（第五节）：
  - 四级共识标记：共识（≥3源）、多数（2源）、单源（1源）、分歧
  - 新来源比对规则：一致→升级、全新→单源、补充→独立标注、矛盾→分歧格式
  - 分歧演化规则：当分歧中一方达到共识时，标记为"分歧·倾向明确"
  - 编译操作清单：逐观点比对、级别动态调整、来源追踪
- 更新 LLM 查阅指南：新增共识级别与回答呈现规则，对接共识机制

## [2026-05-02] restructure-v2 | 指南体系重构与架构优化

- 指南体系重构为三份独立指南（各司其职，互不重叠）：
  - `guides/原始资料-知识单元指南.md` — 收录资料的唯一指南（原"书籍-知识单元指南"，扩展兼容文章等来源）
  - `guides/知识单元-WIKI指南.md` — 编译 Wiki 的唯一指南（移除查询相关内容）
  - `guides/LLM查阅知识库指南.md` — 回答用户问题的唯一查阅指南（新建，含双链渐进式查阅规则）
- 新增 `raw/来源清单.md`：登记所有资料的系列标记、内容结构特征
- 新增 `raw/articles/` 目录：兼容文章类来源
- 合并根目录文档：目录层级说明.md + 知识库运作流程说明.md → 知识库架构说明.md
- 明确 status 四状态判定标准（draft/active/unreviewed/review）
- 设计双链渐进式查阅规则：精确查询不延伸、探索性查询最多延伸 2 层、深度控制机制
- 明确原始书籍在查询阶段不可访问，最深只到知识单元层
- 更新 CLAUDE.md 引用新指南名称和目录结构

## [2026-05-02] restructure | 知识库架构重构

- 引入四层架构：raw/ → units/ → wiki/ → CLAUDE.md
- 新增 units/ 知识单元层（shared/、relationships/、按类型子目录）
- 新增 guides/ 执行指南（书籍-知识单元指南、知识单元-WIKI指南）
- 新增 templates/knowledge-unit.md 知识单元模板
- 重组 wiki/ 子目录：新增 type-groups/、growth/、life-domains/；移除 theories/、applications/
- 重写 CLAUDE.md、wiki/wiki-index.md（大分类导航结构）
- 更新 templates/type-profile.md（加入精炼总览段落）
- 清理 raw/ 下多余空目录（articles/、tests/、cases/、assets/）
- 清理所有 .gitkeep.md 占位文件
- 更新根目录 目录层级说明.md 和 知识库运作流程说明.md
- 确立两级检索策略：wiki → units（原始书籍不可查阅）
- 确立 unreviewed 状态机制：查询触发的新 Wiki 条目需人类审核

## [2026-05-02] init | 知识库初始化

- 创建三层目录架构：raw/ → wiki/ → CLAUDE.md
- 创建 wiki-index.md 索引与 log.md 日志
- 创建 overview.md 体系总览
- 创建页面模板：type-profile / source-summary / comparison
- 知识库就绪，等待首批素材收录

## 相关页面

- [[CLAUDE]] — 全局入口与任务路由
