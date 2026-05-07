# ISTP 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ISTP/ISTP-成长-自信.md`）
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

## ISTP 详情页导航

### 概述与成长
- wiki/types/ISTP/ISTP-概述-谁是ISTP.md — ISTP类型全景概述，涵盖个人成长中的矛盾特质与冲动倾向、人际关系中难以捉摸的社交模式，以及学术与职业发展中偏好动手实践与即兴创造的领域优势
- wiki/types/ISTP/ISTP-成长-奠基与动机.md — ISTP个人成长的底层动力：如何通过自我觉察审视行为对长远的影响，在自尊、自信与自我接纳三者间寻求平衡，以积极变化替代消极循环
- wiki/types/ISTP/ISTP-成长-自尊.md — 自尊建立在技能精通与临场应变之上：平衡时驱动卓越追求，失衡时因过度掌控而损耗人际关系，修复需重塑全局视角并"精通"与他人协作之道
- wiki/types/ISTP/ISTP-成长-自信.md — 通过大胆行动积累自信，热爱创新与变化，但需警惕为大胆而大胆的倾向，借助使命宣言设定方向作为冲动的制衡
- wiki/types/ISTP/ISTP-成长-自我进化.md — 综合进阶：克服过度乐观与鲁莽，培养情商理解他人情绪，发挥即兴天赋，在自由探索中建立持久根基

### 人际关系
- wiki/types/ISTP/ISTP-恋爱-总论.md — ISTP的恋爱观与亲密关系模式：吸引力来源、对承诺的回避倾向、激情且多变的关系特征，以及如何识别并管理伴侣期望以建立持久的感情
- wiki/types/ISTP/ISTP-友谊-总论.md — ISTP的友谊观与社交模式：低调随和但难以被真正了解，以务实帮助和幽默感维系友谊，内倾特质使其需要独处以恢复社交能量

### 育儿
- wiki/types/ISTP/ISTP-育儿-总论与原则.md — ISTP作为父母的整体理念与核心原则
- wiki/types/ISTP/ISTP-育儿-分析家型子女.md — 养育NT分析家型子女的特点、优势与策略
- wiki/types/ISTP/ISTP-育儿-外交家型子女.md — 养育NF外交家型子女的特点、优势与策略
- wiki/types/ISTP/ISTP-育儿-SJ型子女.md — 养育SJ守卫者型子女的特点、优势与策略
- wiki/types/ISTP/ISTP-育儿-SP型子女.md — 养育SP探险家型子女的特点、优势与策略

### 学业
- wiki/types/ISTP/ISTP-学业-学习方式.md — ISTP的学习风格与方法偏好：偏好动手实践而非抽象理论学习，通过试验、摸索和实际操作掌握知识
- wiki/types/ISTP/ISTP-学业-高中.md — ISTP在高中阶段的表现与挑战：对抽象课程和传统教学方式的适应难点及应对策略
- wiki/types/ISTP/ISTP-学业-大学.md — ISTP在大学阶段的表现与挑战：在自主性更强的环境中如何发挥实践导向的学习优势

### 职业
- wiki/types/ISTP/ISTP-职业-总论与选择.md — ISTP的职业方向总览：适合的行业领域、工作环境偏好、核心竞争力与职业选择原则
- wiki/types/ISTP/ISTP-职业-求职与面试.md — ISTP的求职策略与面试表现：如何在求职各环节中展现即兴应变能力与专业技能

---

## ISTP 类型间关系

### 恋爱
- wiki/relationships/ISTP-NT型人-恋爱.md — ISTP与NT分析家型（INTJ、INTP、ENTJ、ENTP）在恋爱中的互动模式与适配性
- wiki/relationships/ISTP-NF型人-恋爱.md — ISTP与NF外交家型（INFJ、INFP、ENFJ、ENFP）在恋爱中的互动模式与适配性
- wiki/relationships/ISTP-SJ型人-恋爱.md — ISTP与SJ守卫者型（ISTJ、ISFJ、ESTJ、ESFJ）在恋爱中的互动模式与适配性
- wiki/relationships/ISTP-SP型人-恋爱.md — ISTP与SP探险家型（ISTP、ISFP、ESTP、ESFP）在恋爱中的互动模式与适配性

### 友谊
- wiki/relationships/ISTP-NT型人-友谊.md — ISTP与NT分析家型在友谊中的互动模式与共鸣点
- wiki/relationships/ISTP-NF型人-友谊.md — ISTP与NF外交家型在友谊中的互动模式与共鸣点
- wiki/relationships/ISTP-SJ型人-友谊.md — ISTP与SJ守卫者型在友谊中的互动模式与共鸣点
- wiki/relationships/ISTP-SP型人-友谊.md — ISTP与SP探险家型在友谊中的互动模式与共鸣点

### 职场协作
- wiki/relationships/ISTP-NT型人-职场.md — ISTP与NT分析家型在职场中的协作模式、优势互补与潜在摩擦
- wiki/relationships/ISTP-NF型人-职场.md — ISTP与NF外交家型在职场中的协作模式、优势互补与潜在摩擦
- wiki/relationships/ISTP-SJ型人-职场.md — ISTP与SJ守卫者型在职场中的协作模式、优势互补与潜在摩擦
- wiki/relationships/ISTP-SP型人-职场.md — ISTP与SP探险家型在职场中的协作模式、优势互补与潜在摩擦
