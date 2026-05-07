# ESFJ 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ESFJ/ESFJ-成长-自信.md`）
4. 跨类型需求：如需其他类型信息，先读取 `_indexes/LLM-{TYPE}.md` 获取该类型的导航
5. 通用知识（维度/策略/类型组/理论）：参见同时提供的 LLM-common.md

## 输出格式

```
【置信度】高/中/低
【来源页面】
- [主要] 文件路径
- [补充] 文件路径（如有）
【覆盖度】完整/部分/未覆盖

---

[精炼知识内容]

---

【未覆盖说明】（仅在部分/未覆盖时填写）
```

---

## ESFJ 详情页导航

### 概述与成长
- wiki/types/ESFJ/ESFJ-概述-核心特征.md — ESFJ 的核心人格特质、社交归属感需求、务实服务精神、具体世界中的坚定信念及潜在挑战
- wiki/types/ESFJ/ESFJ-概述-人际关系.md — ESFJ 在人际交往中的风格特点、社交生活中的角色定位、与他人建立信任与联结的方式
- wiki/types/ESFJ/ESFJ-概述-学业与职业.md — ESFJ 在学业和职业领域中的核心驱动力、优势与面临的挑战
- wiki/types/ESFJ/ESFJ-概述-结语.md — 对 ESFJ 人格类型的总结性评述，概括其整体特质、人生主题与成长方向
- wiki/types/ESFJ/ESFJ-成长-自我责任.md — ESFJ 对自我责任的认知与实践方式、如何掌控自身人生与承担义务
- wiki/types/ESFJ/ESFJ-成长-自主性.md — ESFJ 培养自主决策与独立行动能力的成长路径
- wiki/types/ESFJ/ESFJ-成长-自我调节.md — ESFJ 在压力与情绪管理中的自我调节策略与方法
- wiki/types/ESFJ/ESFJ-成长-自我认知.md — ESFJ 对自身优势、局限与内在动机的深度认知过程
- wiki/types/ESFJ/ESFJ-成长-工具与测试.md — 有助于 ESFJ 个人成长的实用工具、测试方法与自我评估手段

### 人际关系
- wiki/types/ESFJ/ESFJ-友谊-概述.md — ESFJ 作为朋友的风格特征、对友谊的期望与投入方式、维系友谊的核心动力
- wiki/types/ESFJ/ESFJ-恋爱-概述.md — ESFJ 在恋爱中的核心特质、对承诺与稳定的重视、和谐关系的构建方式
- wiki/types/ESFJ/ESFJ-恋爱-单身.md — ESFJ 在单身阶段的情感状态、自我探索与对理想伴侣的期待
- wiki/types/ESFJ/ESFJ-恋爱-卧室亲密.md — ESFJ 在亲密关系中的身体与情感亲密表达方式
- wiki/types/ESFJ/ESFJ-恋爱-分手.md — ESFJ 面对感情破裂时的应对方式、情感处理与恢复过程

### 育儿
- wiki/types/ESFJ/ESFJ-育儿-概述.md — ESFJ 作为父母的核心育儿理念、对子女的期望与养育方式的总体特征
- wiki/types/ESFJ/ESFJ-育儿-建立依恋.md — ESFJ 在子女 0-1.5 岁阶段建立安全依恋关系的育儿方式
- wiki/types/ESFJ/ESFJ-育儿-试探界限.md — ESFJ 在子女 1.5-3 岁阶段应对界限试探行为的育儿策略
- wiki/types/ESFJ/ESFJ-育儿-求知欲.md — ESFJ 在子女 3-5 岁阶段激发与引导求知欲的育儿方法
- wiki/types/ESFJ/ESFJ-育儿-培养能力.md — ESFJ 在子女 5-12 岁阶段培养各项能力的育儿重点
- wiki/types/ESFJ/ESFJ-育儿-寻找自我.md — ESFJ 在子女 12-18 岁青春期阶段支持其寻找自我的育儿方式

### 学业
- wiki/types/ESFJ/ESFJ-学业-学习方式.md — ESFJ 偏好的学习方式与信息接收风格、适合的教学方法
- wiki/types/ESFJ/ESFJ-学业-学习习惯.md — ESFJ 在学习过程中的习惯性行为模式与高效学习策略
- wiki/types/ESFJ/ESFJ-学业-高中阶段.md — ESFJ 在高中阶段的学业表现、挑战与适应策略
- wiki/types/ESFJ/ESFJ-学业-大学与终身学习.md — ESFJ 在大学阶段及终身学习过程中的特点与成长方向

### 职业
- wiki/types/ESFJ/ESFJ-职业-概述.md — ESFJ 在职业领域的整体特征、适合的职业类型与工作环境偏好
- wiki/types/ESFJ/ESFJ-职业-职业技能.md — ESFJ 在工作中展现的核心职业技能与优势领域
- wiki/types/ESFJ/ESFJ-职业-作为下属.md — ESFJ 在职场中作为下属时的行为风格、工作态度与上级互动模式
- wiki/types/ESFJ/ESFJ-职业-作为同事.md — ESFJ 在职场中作为同事时的团队协作风格与人际互动特点
- wiki/types/ESFJ/ESFJ-职业-作为管理者.md — ESFJ 作为管理者时的领导风格、管理优势与潜在盲区
- wiki/types/ESFJ/ESFJ-职业-职场协作.md — ESFJ 在职场协作中的沟通方式、团队角色与跨部门合作特点

---

## ESFJ 类型间关系

### 友谊
- wiki/relationships/ESFJ-NT型人-友谊.md — 与 NT 分析家的友谊：理性与情感互补，需通过清晰沟通与共享活动重建平衡
- wiki/relationships/ESFJ-NF型人-友谊.md — 与 NF 外交家的友谊：同理共鸣与务实支持，规则与理想冲突下以相互尊重维系友谊
- wiki/relationships/ESFJ-SJ型人-友谊.md — 与 SJ 守卫者的友谊：共同的可靠性与传统价值观带来稳固支持，需尊重边界并共同探索
- wiki/relationships/ESFJ-SP型人-友谊.md — 与 SP 探险家的友谊：稳重与即兴互补，SP 带来灵活与冒险，需相互尊重界限

### 恋爱
- wiki/relationships/ESFJ-NT型人-恋爱.md — 与 NT 分析家的恋爱：效率共鸣与忠诚契合，细节与全局冲突下需尊重需求
- wiki/relationships/ESFJ-NF型人-恋爱.md — 与 NF 外交家的恋爱：务实与理想互补、共同关怀，情绪化冲突下以开放心态化解分歧
- wiki/relationships/ESFJ-SJ型人-恋爱.md — 与 SJ 守卫者的恋爱：舒适承诺与默契守护，通过共同探索与相互妥协实现成长
- wiki/relationships/ESFJ-SP型人-恋爱.md — 与 SP 探险家的恋爱：安全与探索的反差吸引，需分担责任、相互借鉴修复关系
