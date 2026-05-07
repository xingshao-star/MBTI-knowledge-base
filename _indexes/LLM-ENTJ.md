# ENTJ 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ENTJ/ENTJ-成长-自信.md`）
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

## ENTJ 详情页导航

### 概述与成长
- wiki/types/ENTJ/ENTJ-概述-核心特征.md — ENTJ 类型全景：核心特质、人际关系风格、学业与职业中的领导力倾向、成长突破方向
- wiki/types/ENTJ/ENTJ-成长-自尊.md — 自尊（价值感）：通过行动力与效率建立自我价值、失衡时的补偿表现与重塑方式
- wiki/types/ENTJ/ENTJ-成长-自我尊重.md — 自我尊重（自我喜爱）：在执行到位时最能自我认可的内在机制
- wiki/types/ENTJ/ENTJ-成长-自信.md — 自信：果断决策与掌控局面是其信心源泉，不会轻易被外部质疑动摇
- wiki/types/ENTJ/ENTJ-成长-自我进化.md — 自我进化：突破僵化框架、以跨学科广度优化自身能力的成长策略
- wiki/types/ENTJ/ENTJ-成长-自我责任.md — 自我责任：将人生视为个人战略来管理，主动承担决策后果

### 育儿
- wiki/types/ENTJ/ENTJ-育儿-概述.md — 育儿总论：高标准的支持者角色、直面养育挑战的决心、期望管理与情感支持的平衡
- wiki/types/ENTJ/ENTJ-育儿-婴儿期.md — 婴儿期（0-1.5岁）：信任与依恋纽带建立中的 ENTJ 父母行为与注意事项
- wiki/types/ENTJ/ENTJ-育儿-幼儿期.md — 幼儿期（1.5-3岁）：自主性发展阶段的引导方式与过度管控风险
- wiki/types/ENTJ/ENTJ-育儿-学龄前.md — 学龄前（3-5岁）：主动性与创造力培养、游戏与好奇心引导中的角色
- wiki/types/ENTJ/ENTJ-育儿-学龄期.md — 学龄期（6-12岁）：勤奋感培养、学业期望设定与子女独立性的平衡
- wiki/types/ENTJ/ENTJ-育儿-青春期.md — 青春期：身份认同形成期、理性引导与情感支持的双重挑战

### 学业
- wiki/types/ENTJ/ENTJ-学业-学习方式.md — 学习方式：目标驱动、系统化吸收知识、偏好有明确反馈的学习模式
- wiki/types/ENTJ/ENTJ-学业-高中.md — 高中阶段：领导力初显、与权威关系的处理、学术竞争力的建立
- wiki/types/ENTJ/ENTJ-学业-升学就业.md — 升学与就业选择：战略规划大学与职业路径、权衡理性与长期愿景
- wiki/types/ENTJ/ENTJ-学业-大学.md — 大学阶段：自主驱动的深度学习、社交与领导机会的把握、专业聚焦
- wiki/types/ENTJ/ENTJ-学业-终身学习.md — 终身学习：将学习视为竞争优势工具、不断刷新知识以应对变革

### 职业
- wiki/types/ENTJ/ENTJ-职业-领导力.md — 领导力与职业概述：天生的战略领导者、激励团队的风格与可能的管理盲区
- wiki/types/ENTJ/ENTJ-职业-挑战与思考.md — 职业挑战与思考：在权威与共情间寻求平衡、应对挫折的策略与反思
- wiki/types/ENTJ/ENTJ-职业-求职-自我认知.md — 求职：自我认知——明确自身核心优势与职业愿景是 ENTJ 求职第一步
- wiki/types/ENTJ/ENTJ-职业-求职-建立联系.md — 求职：建立联系——利用社交资本与战略人脉拓展职业机会
- wiki/types/ENTJ/ENTJ-职业-求职-业余爱好.md — 求职：业余爱好——将个人兴趣转化为职业竞争力的方式
- wiki/types/ENTJ/ENTJ-职业-求职-面试准备.md — 求职：面试准备——展现自信与能力的策略、常见陷阱与应对
- wiki/types/ENTJ/ENTJ-职业-适合领域.md — 适合职业领域：管理、金融、法律、科技等适合 ENTJ 特质的具体行业与岗位
- wiki/types/ENTJ/ENTJ-职业-挑战特质.md — 职业挑战特质：过于强势、缺乏耐心、忽视情感因素等需觉察的职业行为模式
- wiki/types/ENTJ/ENTJ-职业-创业与自雇.md — 创业与自雇：企业家精神与自主掌控的驱动力、创业中的优势与风险
- wiki/types/ENTJ/ENTJ-职业-协作-NT.md — 职场协作：与NT型人——智识联盟与高效协同，需注意竞争与理念分歧
- wiki/types/ENTJ/ENTJ-职业-协作-NF.md — 职场协作：与NF型人——互补合作中逻辑与人文的结合，需注意沟通风格差异
- wiki/types/ENTJ/ENTJ-职业-协作-SJ.md — 职场协作：与SJ型人——秩序导向的合作方式，效率与传统的张力管理
- wiki/types/ENTJ/ENTJ-职业-协作-SP.md — 职场协作：与SP型人——行动派协作，当下反应与长期规划的协调

---

## ENTJ 类型间关系

### 友谊
- wiki/relationships/ENTJ-NT型人-友谊.md — 与 NT 分析家的友谊：基于智力共鸣和共同价值观，思想碰撞中互相激励
- wiki/relationships/ENTJ-NF型人-友谊.md — 与 NF 外交家的友谊：理性与情感互补，直率可能造成裂痕，通过认可与支持修复关系
- wiki/relationships/ENTJ-SJ型人-友谊.md — 与 SJ 守卫者的友谊：基于忠诚与行动力的互补，涵盖传统与创新冲突的化解
- wiki/relationships/ENTJ-SP型人-友谊.md — 与 SP 探险家的友谊：随性冒险与理性规划互补共生，控制欲与自由精神之间的张力化解

### 恋爱
- wiki/relationships/ENTJ-NT型人-恋爱.md — 与 NT 分析家的恋爱：直觉型与思考型特质心意相通，需警惕优越感和过度分析倾向
- wiki/relationships/ENTJ-NF型人-恋爱.md — 与 NF 外交家的恋爱：理性与情感碰撞激发彼此潜能，需以共情沟通面对表达差异
- wiki/relationships/ENTJ-SJ型人-恋爱.md — 与 SJ 守卫者的恋爱：远见者与传统者的互补组合，均重视秩序与可靠性
- wiki/relationships/ENTJ-SP型人-恋爱.md — 与 SP 探险家的恋爱：远见者与实干家的组合，需接纳差异而非试图改变对方
