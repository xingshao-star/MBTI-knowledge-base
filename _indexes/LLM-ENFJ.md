# ENFJ 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ENFJ/ENFJ-成长-自信.md`）
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

## ENFJ 详情页导航

### 概述与成长
- wiki/types/ENFJ/ENFJ-概述-谁是ENFJ.md — 类型全景：成长驱动力、人际魅力、学业职业中的理想主义
- wiki/types/ENFJ/ENFJ-成长-奠基与动机.md — 成长框架：创造性与反应性平衡、五大成长特质定义
- wiki/types/ENFJ/ENFJ-成长-自尊.md — 自尊（价值感）：通过慈悲建立价值感、失衡与重塑
- wiki/types/ENFJ/ENFJ-成长-自重.md — 自重（自我喜爱）：为他人行善时最喜爱自己的机制
- wiki/types/ENFJ/ENFJ-成长-自信.md — 自信：真实自我体现是自信来源
- wiki/types/ENFJ/ENFJ-成长-自我进化.md — 自我进化：充分发挥潜能的成长策略
- wiki/types/ENFJ/ENFJ-成长-自我负责.md — 自我负责：自主掌控决策与后果

### 人际关系
- wiki/types/ENFJ/ENFJ-友谊-总论.md — 友谊总论：深厚坚韧的情谊与非凡期待
- wiki/types/ENFJ/ENFJ-恋爱-总论.md — 恋爱总论：联结感与深度、伴侣期待

### 育儿
- wiki/types/ENFJ/ENFJ-育儿-总论与原则.md — 育儿核心原则与总体框架
- wiki/types/ENFJ/ENFJ-育儿-婴儿期.md — 婴儿期（0-1.5岁）：依恋纽带建立
- wiki/types/ENFJ/ENFJ-育儿-幼儿期.md — 幼儿期（1.5-3岁）：自主性发展
- wiki/types/ENFJ/ENFJ-育儿-学龄前.md — 学龄前（3-5岁）：主动性与创造力
- wiki/types/ENFJ/ENFJ-育儿-学龄期.md — 学龄期（6-12岁）：勤奋感培养
- wiki/types/ENFJ/ENFJ-育儿-青春期.md — 青春期：身份认同与放手

### 学业
- wiki/types/ENFJ/ENFJ-学业-学习方式.md — 学习方式：使命驱动、社交型学习风格
- wiki/types/ENFJ/ENFJ-学业-高中.md — 高中阶段：社交领导力与学业平衡
- wiki/types/ENFJ/ENFJ-学业-大学决策.md — 大学选择：意义感与人际互动导向
- wiki/types/ENFJ/ENFJ-学业-大学与终身学习.md — 大学与终身学习

### 职业
- wiki/types/ENFJ/ENFJ-职业-总论与选择.md — 职业总论：使命感驱动的选择与适合领域
- wiki/types/ENFJ/ENFJ-职业-求职与面试.md — 求职与面试策略
- wiki/types/ENFJ/ENFJ-职业-职场习惯.md — 职场习惯与协作风格

---

## ENFJ 类型间关系

### 友谊
- wiki/relationships/ENFJ-NT型人-友谊.md — 与NT分析家的友谊：建立在互补想象力上，挑战在于理想主义破灭和情感差异
- wiki/relationships/ENFJ-NF型人-友谊.md — 与NF外交家的友谊：建立在共同理想主义上，挑战在于相互强化的理想化期望
- wiki/relationships/ENFJ-SJ型人-友谊.md — 与SJ守卫者的友谊：理想主义与务实稳定互补，挑战在于对变化和传统的不同态度
- wiki/relationships/ENFJ-SP型人-友谊.md — 与SP探险家的友谊：充满活力的伙伴关系，挑战在于深度期待与享受当下的态度落差

### 恋爱
- wiki/relationships/ENFJ-NT型人-恋爱.md — 与NT分析家的恋爱：深度思考与情感互补，挑战在于琐事分工和情感表达落差
- wiki/relationships/ENFJ-NF型人-恋爱.md — 与NF外交家的恋爱：深度契合、共同追求意义与成长，挑战在于双方过于理想化
- wiki/relationships/ENFJ-SJ型人-恋爱.md — 与SJ守卫者的恋爱：稳定与激情形成张力，需尊重SJ对传统和安全感的需求
- wiki/relationships/ENFJ-SP型人-恋爱.md — 与SP探险家的恋爱：激情与自由并存，需接受SP不愿被"改造"的本性

### 职场
- wiki/relationships/ENFJ-NT型人-职场.md — 与NT分析家的职场：以构想和同理心互补，挑战在于陷入理念争论
- wiki/relationships/ENFJ-NF型人-职场.md — 与NF外交家的职场：价值观高度一致，挑战在于缺乏务实执行力
- wiki/relationships/ENFJ-SJ型人-职场.md — 与SJ守卫者的职场：愿景与执行力互补，挑战在于变革热情与既有流程的坚守
- wiki/relationships/ENFJ-SP型人-职场.md — 与SP探险家的职场：灵活应变与使命感互补，挑战在于长远规划与即时行动的风格差异
