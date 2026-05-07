# ENTP 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ENTP/ENTP-成长-自信.md`）
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

## ENTP 详情页导航

### 概述与成长
- wiki/types/ENTP/ENTP-概述-谁是ENTP.md — ENTP 类型全景：核心特质、人际关系风格、学术职业倾向与个人成长方向概览
- wiki/types/ENTP/ENTP-成长-奠基与动机.md — 成长框架：以智力探索为驱动动机，涵盖自尊、自重、自信、自我进化、自我负责五大要素
- wiki/types/ENTP/ENTP-成长-自尊.md — 自尊（喜欢自己）：通过理性创造力与内在和谐建立自我欣赏，化解情感忽视与辩论依赖的失衡
- wiki/types/ENTP/ENTP-成长-自重.md — 自重（价值认同）：以独立思考与价值践行建立自重，克服极端反抗与项目搁置的倾向
- wiki/types/ENTP/ENTP-成长-自信.md — 自信（行动动力）：以理性运用与好奇探索驱动行动，避免回避情感与无谓争辩的能量消耗
- wiki/types/ENTP/ENTP-成长-自我进化.md — 自我进化：自觉拓展潜能、审视自我的成长过程，提升能力与幸福感
- wiki/types/ENTP/ENTP-成长-自我负责.md — 自我负责：通过承担改善现状的责任掌控生活，以有意识的行动创造理想人生

### 人际关系
- wiki/types/ENTP/ENTP-友谊-总论.md — 友谊总论：以新颖见解和慷慨支持建立充满活力的友谊关系
- wiki/types/ENTP/ENTP-友谊-NT型人.md — NT 型人友谊：与同组分析家的理性交流与心智碰撞
- wiki/types/ENTP/ENTP-友谊-NF型人.md — NF 型人友谊：与外交家的思想对话与情感互补
- wiki/types/ENTP/ENTP-友谊-SJ型人.md — SJ 型人友谊：与守卫者的规则协商与稳定性互补
- wiki/types/ENTP/ENTP-友谊-SP型人.md — SP 型人友谊：与探险家的即兴互动与体验共享
- wiki/types/ENTP/ENTP-恋爱-总论.md — 恋爱总论：以智力吸引与开放心态经营浪漫关系的核心模式
- wiki/types/ENTP/ENTP-恋爱-NT型人.md — NT 型人恋爱：与分析家的理性共鸣与深度契合
- wiki/types/ENTP/ENTP-恋爱-NF型人.md — NF 型人恋爱：与外交家的情感激发与浪漫互补
- wiki/types/ENTP/ENTP-恋爱-SJ型人.md — SJ 型人恋爱：与守卫者的秩序对话与平衡之道
- wiki/types/ENTP/ENTP-恋爱-SP型人.md — SP 型人恋爱：与探险家的自由探索与激情互动

### 育儿
- wiki/types/ENTP/ENTP-育儿-总论与原则.md — 育儿核心原则：以开放思维和智力启蒙建立亲子纽带，平衡自由探索与结构支持
- wiki/types/ENTP/ENTP-育儿-婴儿期.md — 婴儿期（0-1.5岁）：建立情感联系的第一阶段
- wiki/types/ENTP/ENTP-育儿-幼儿期.md — 幼儿期（1.5-3岁）：引导好奇心与自主性发展的关键期
- wiki/types/ENTP/ENTP-育儿-学龄前.md — 学龄前（3-5岁）：启蒙智力探索与社交能力培养
- wiki/types/ENTP/ENTP-育儿-学龄期.md — 学龄期（5-12岁）：支持学业兴趣发展与独立思考习惯
- wiki/types/ENTP/ENTP-育儿-青春期.md — 青春期（12-18岁）：陪伴身份认同与价值观形成的关键阶段

### 学业
- wiki/types/ENTP/ENTP-学业-学习方式.md — 学习方式与习惯：理论驱动型学习风格，善于宏观理解与概念联结
- wiki/types/ENTP/ENTP-学业-高中.md — 高中阶段：应对结构化课程与发挥创造性思维的平衡
- wiki/types/ENTP/ENTP-学业-大学与终身学习.md — 大学适应与终身学习：突破浅尝辄止，保持持续学习的专注力

### 职业
- wiki/types/ENTP/ENTP-职业-总论与选择.md — 职业总论：以创新思维和策略能力驱动的职业方向与适配环境

---

## ENTP 类型间关系

### 友谊
- wiki/relationships/ENTP-NT型人-友谊.md — 与 NT 分析家的友谊：智力共犯共享深邃讨论与愉快辩论，需警惕空谈取代沟通和情感隔阂
- wiki/relationships/ENTP-NF型人-友谊.md — 与 NF 外交家的友谊：理性与理想主义互补，NF 带来情感洞察，ENTP 提供逻辑聚焦
- wiki/relationships/ENTP-SJ型人-友谊.md — 与 SJ 守卫者的友谊：思维碰撞视角互补，需尊重彼此敏感点与生活节奏
- wiki/relationships/ENTP-SP型人-友谊.md — 与 SP 探险家的友谊：理念创造力与即兴行动力激发活力，需给予空间尊重独立方向

### 恋爱
- wiki/relationships/ENTP-NT型人-恋爱.md — 与 NT 分析家的恋爱：共享智力激荡与宏大构想，需表达欣赏而非过度分析
- wiki/relationships/ENTP-NF型人-恋爱.md — 与 NF 外交家的恋爱：理性与共情互补，需克服情感表达方式与浪漫观念的差异
- wiki/relationships/ENTP-SJ型人-恋爱.md — 与 SJ 守卫者的恋爱：新点子与稳定性融合，SJ 的务实激励 ENTP 将构想落地
- wiki/relationships/ENTP-SP型人-恋爱.md — 与 SP 探险家的恋爱：共破常规携手解决问题，SP 以行动力平衡 ENTP 分析倾向

### 职场
- wiki/relationships/ENTP-NT型人-职场.md — 与 NT 分析家的职场：语言相通，系统性头脑风暴激发创意协同，需防范回音室效应
- wiki/relationships/ENTP-NF型人-职场.md — 与 NF 外交家的职场：共享直觉型视野，理性分析与人文关怀互补协作
- wiki/relationships/ENTP-SJ型人-职场.md — 与 SJ 守卫者的职场：变革构想与执行力互补，以实践成果赢取信任
- wiki/relationships/ENTP-SP型人-职场.md — 与 SP 探险家的职场：理念构思与务实行动协同创新，共享探索精神激发活力
