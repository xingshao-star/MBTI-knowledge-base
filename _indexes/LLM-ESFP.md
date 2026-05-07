# ESFP 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ESFP/ESFP-成长-自信.md`）
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

## ESFP 详情页导航

### 概述与成长
- wiki/types/ESFP/ESFP-概述-核心特征.md — 类型全景：个人成长驱动力、人际关系风格、学业与职业发展中的随性热情
- wiki/types/ESFP/ESFP-成长-自尊-他人认可.md — 自尊（他人认可）：通过他人的欣赏和反馈建立价值感
- wiki/types/ESFP/ESFP-成长-自尊-解决问题.md — 自尊（解决问题）：通过实际行动帮助他人带来的成就感和价值认同
- wiki/types/ESFP/ESFP-成长-自信.md — 自信：随性行动与适应力带来的自信源泉
- wiki/types/ESFP/ESFP-成长-人际交往能力.md — 人际交往：社交魅力的培养与真实连接的建立
- wiki/types/ESFP/ESFP-成长-思维敏捷.md — 思维敏捷：快速反应与即兴发挥能力的提升
- wiki/types/ESFP/ESFP-成长-情绪管理.md — 情绪管理：面对批评与冲突时的情绪调适和稳定性

### 人际关系
- wiki/types/ESFP/ESFP-恋爱-总论.md — 恋爱总论：多情随性的恋爱风格、承诺挑战与关系中的优势

### 育儿
- wiki/types/ESFP/ESFP-育儿-总览.md — 育儿总览：育儿风格、优势与挑战

### 学业
- wiki/types/ESFP/ESFP-学业-学习习惯.md — 学习习惯：动手实践型学习偏好与理论抽象概念的应对策略
- wiki/types/ESFP/ESFP-学业-高中阶段.md — 高中阶段：学术环境中的挑战与天赋发现
- wiki/types/ESFP/ESFP-学业-大学阶段.md — 大学阶段：兴趣驱动的专业选择与终身学习路径

### 职业
- wiki/types/ESFP/ESFP-职业-总论.md — 职业总论：适合的工作环境、职业优势与发展方向
- wiki/types/ESFP/ESFP-职业-职业选择.md — 职业选择：具体职业推荐与选择策略

---

## ESFP 类型间关系

### 友谊
- wiki/relationships/ESFP-NT型人-友谊.md — 与 NT 分析家的友谊：热情行动与理性战略结合，务实与抽象思辨之间调和
- wiki/relationships/ESFP-NF型人-友谊.md — 与 NF 外交家的友谊：热情行动与理想主义相互激发，日常务实层面需互补支撑
- wiki/relationships/ESFP-SJ型人-友谊.md — 与 SJ 守卫者的友谊：随性探索与恪守传统的对立，转化为互相成就的深厚友谊
- wiki/relationships/ESFP-SP型人-友谊.md — 与 SP 探险家的友谊：共同活在当下的激情与乐趣，需警惕相似性带来的舒适圈风险

### 恋爱
- wiki/relationships/ESFP-NT型人-恋爱.md — 与 NT 分析家的恋爱：差异吸引力与自由空间的平衡，需化解批评模式
- wiki/relationships/ESFP-NF型人-恋爱.md — 与 NF 外交家的恋爱：梦想家与行动派的碰撞，情感共鸣与自由灵魂的吸引力
- wiki/relationships/ESFP-SJ型人-恋爱.md — 与 SJ 守卫者的恋爱：灵活与计划的碰撞，新奇与安全互补，需欣赏与尊重重塑平衡
- wiki/relationships/ESFP-SP型人-恋爱.md — 与 SP 探险家的恋爱：共同冒险的兴奋与激情，需通过稳定与回忆初心重建平衡

### 职场协作
- wiki/relationships/ESFP-NT型人-职场.md — 与 NT 分析家的职场：务实行动与宏观系统思维互补，接纳方法差异是关键
- wiki/relationships/ESFP-NF型人-职场.md — 与 NF 外交家的职场：务实创新与理想主义互补，理解彼此动机与价值观
- wiki/relationships/ESFP-SJ型人-职场.md — 与 SJ 守卫者的职场：随机应变与稳定守序互补，在规则与创新之间找到平衡
- wiki/relationships/ESFP-SP型人-职场.md — 与 SP 探险家的职场：行动驱动的务实创新，需警惕固守同类思维导致视野狭隘

### 育儿（亲子关系）
- wiki/relationships/ESFP父母-NT子女.md — 与 NT 分析家型子女的亲子关系动态
- wiki/relationships/ESFP父母-NF子女.md — 与 NF 外交家型子女的亲子关系动态
- wiki/relationships/ESFP父母-SJ子女.md — 与 SJ 守卫者型子女的亲子关系动态
- wiki/relationships/ESFP父母-SP子女.md — 与 SP 探险家型子女的亲子关系动态
