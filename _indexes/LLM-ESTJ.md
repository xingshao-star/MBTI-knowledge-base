# ESTJ 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ESTJ/ESTJ-成长-自信.md`）
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

## ESTJ 详情页导航

### 概述与成长
- wiki/types/ESTJ/ESTJ-概述-核心概述.md — ESTJ性格全貌，涵盖个人成长、人际关系、学术与职业三大领域的核心特质与典型表现
- wiki/types/ESTJ/ESTJ-成长-动力与发展.md — ESTJ的内在驱动力来源、个人成长路径与不同阶段的发展方向指引
- wiki/types/ESTJ/ESTJ-成长-自尊.md — ESTJ的自尊心特征、如何建立健康的自尊以及常见的自尊挑战与提升策略
- wiki/types/ESTJ/ESTJ-成长-自重.md — ESTJ对自我价值的认知与尊重，包括对自身能力、成就和贡献的认同与保护
- wiki/types/ESTJ/ESTJ-成长-自信.md — ESTJ的自信表现方式、自信的来源基础以及在不确定情境中的自我信念维持
- wiki/types/ESTJ/ESTJ-成长-自我进化.md — ESTJ的持续自我提升之路、适应环境变化与拓展自身能力边界的方法
- wiki/types/ESTJ/ESTJ-成长-自我责任.md — ESTJ对个人责任的理解与承担方式，以及如何在过度负责任中保护自己的边界

### 人际关系
- wiki/types/ESTJ/ESTJ-友谊-友谊总论.md — ESTJ在友谊中的表现特征：忠诚可靠、以行动示友情、社交责任感强以及与其他类型建立友谊的要点
- wiki/types/ESTJ/ESTJ-恋爱-恋爱总论.md — ESTJ在恋爱关系中的整体表现：务实表达爱意、尊重传统承诺、情感沟通的挑战与成长方向

### 育儿
- wiki/types/ESTJ/ESTJ-育儿-育儿总论.md — ESTJ作为父母的整体风格：以结构、规则和传统为核心的家庭教育理念与实践
- wiki/types/ESTJ/ESTJ-育儿-婴儿期.md — ESTJ父母在婴儿期的养育方式、对新生儿需求的响应模式与亲子互动特征
- wiki/types/ESTJ/ESTJ-育儿-幼儿期.md — ESTJ父母在幼儿阶段建立规则意识、培养良好习惯的具体养育方法
- wiki/types/ESTJ/ESTJ-育儿-学龄前.md — ESTJ父母在学龄前儿童教育中的引导策略、活动安排与发展支持
- wiki/types/ESTJ/ESTJ-育儿-学龄期.md — ESTJ父母在学龄期对子女的学业督导、纪律培养与社交生活管理
- wiki/types/ESTJ/ESTJ-育儿-青少年期.md — ESTJ父母在青少年阶段面临的亲子关系变化、权威挑战与独立性培养的平衡

### 学业
- wiki/types/ESTJ/ESTJ-学业-学术总论.md — ESTJ的学术风格总览：专注高效、遵守规则、偏好结构化学习环境的整体特征
- wiki/types/ESTJ/ESTJ-学业-学习习惯.md — ESTJ的学习方法与习惯特征：计划性强的学习安排、纪律性以及对实践性内容的偏好
- wiki/types/ESTJ/ESTJ-学业-高中阶段.md — ESTJ在高中阶段的学业表现、课程偏好、课外活动参与及社交平衡
- wiki/types/ESTJ/ESTJ-学业-工作或上大学.md — ESTJ在高中毕业后面临的人生十字路口：直接就业与接受高等教育的利弊权衡
- wiki/types/ESTJ/ESTJ-学业-大学与终身学习.md — ESTJ在大学阶段的专业选择倾向、学习方式适应与终身学习的持续动力

### 职业
- wiki/types/ESTJ/ESTJ-职业-职业发展.md — ESTJ的职业选择偏好、适合的工作环境类型、团队中的管理风格表现与职业成长路径

---

## ESTJ 类型间关系

### 友谊
- wiki/relationships/ESTJ-NT型人-友谊.md — ESTJ与理性分析型同伴在友谊中的互动模式与相互理解
- wiki/relationships/ESTJ-NF型人-友谊.md — ESTJ与理想主义感召型同伴在友谊中的互补与磨合
- wiki/relationships/ESTJ-SJ型人-友谊.md — ESTJ与同类务实守卫者在友谊中的共鸣与潜在僵化风险
- wiki/relationships/ESTJ-SP型人-友谊.md — ESTJ与自由灵活探索型同伴在友谊中的张力与相互欣赏

### 恋爱
- wiki/relationships/ESTJ-NT型人-恋爱.md — ESTJ与NT型人恋爱关系中的逻辑共鸣、情感距离与适配要点
- wiki/relationships/ESTJ-NF型人-恋爱.md — ESTJ与NF型人恋爱关系中务实与理想的碰撞、情感表达差异与调和方式
- wiki/relationships/ESTJ-SJ型人-恋爱.md — ESTJ与SJ型人恋爱关系中共同价值观的契合、传统共识与可能缺乏的激情
- wiki/relationships/ESTJ-SP型人-恋爱.md — ESTJ与SP型人恋爱关系中稳定与自由的拉扯、相互吸引与长期挑战

### 职场
- wiki/relationships/ESTJ-NT型人-职场.md — ESTJ与NT型人在职场中的高效协作、理性分工与潜在的战略分歧
- wiki/relationships/ESTJ-NF型人-职场.md — ESTJ与NF型人在职场中务实执行与人文理想的平衡协作之道
- wiki/relationships/ESTJ-SJ型人-职场.md — ESTJ与SJ型人在职场中的高度默契与避免同质化创新的警示
- wiki/relationships/ESTJ-SP型人-职场.md — ESTJ与SP型人在职场中的管控与灵活之间的微妙协作艺术
