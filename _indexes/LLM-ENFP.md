# ENFP 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ENFP/ENFP-成长-自信.md`）
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

## ENFP 详情页导航

### 概述与成长
- wiki/types/ENFP/ENFP-概述-谁是ENFP.md — ENFP 类型全景：从个人成长、人际关系、学业职业四个维度概览其核心特质与生活风格
- wiki/types/ENFP/ENFP-成长-奠基与动机.md — 成长框架：以使命感驱动、人际关系滋养的成长动力与五大成长特质定义
- wiki/types/ENFP/ENFP-成长-自尊.md — 自尊（价值感）：通过同理心联结与利他行为建立价值感、失衡与重塑之道
- wiki/types/ENFP/ENFP-成长-自重.md — 自重（自我接纳）：在践行价值观与展现同理心中获得自我接纳的机制
- wiki/types/ENFP/ENFP-成长-自信.md — 自信：源于真实自我联结的自信、社交真实与身份认同的平衡
- wiki/types/ENFP/ENFP-成长-自我进化.md — 自我进化：将成长视为生命意义的自我完善策略与社群中的规划实施
- wiki/types/ENFP/ENFP-成长-自我负责.md — 自我负责：通过独立决策与道德主动性承担人生责任、克服无助感

### 人际关系
- wiki/types/ENFP/ENFP-友谊-总论.md — 友谊总论：以开放心态和灵活适应性与各类人建立真诚充满活力的深度友谊
- wiki/types/ENFP/ENFP-恋爱-总论.md — 恋爱总论：追寻深度灵魂联结的浪漫理想主义、亲密关系中需关注与平衡

### 育儿
- wiki/types/ENFP/ENFP-育儿-总论与原则.md — 育儿核心原则：以无穷热情与情感坦诚建立深厚亲子纽带，平衡结构、灵活性与宁静时光
- wiki/types/ENFP/ENFP-育儿-婴儿期.md — 婴儿期（0-1.5岁）：建立深厚情感纽带，警惕外部义务牺牲亲子时光
- wiki/types/ENFP/ENFP-育儿-幼儿期.md — 幼儿期（1.5-3岁）：以同理心引导情绪爆发，防范过度纵容的失衡
- wiki/types/ENFP/ENFP-育儿-学龄前.md — 学龄前（3-5岁）：天生的启蒙者和情感导师，管理过盛野心与日程焦虑
- wiki/types/ENFP/ENFP-育儿-学龄期.md — 学龄期（5-12岁）：以热情鼓励引导学业社交成长，克服条理性短板
- wiki/types/ENFP/ENFP-育儿-青春期.md — 青春期（12-18岁）：陪伴身份认同关键期，学会建立界限与坦然放手

### 学业
- wiki/types/ENFP/ENFP-学业-学习方式.md — 学习方式与习惯：直觉型宏观学习者，善于寻求意义，需培养均衡学习习惯与成长型思维
- wiki/types/ENFP/ENFP-学业-高中.md — 高中阶段：热衷高概念思考，需专注聚焦并在既定框架中展示知识
- wiki/types/ENFP/ENFP-学业-大学决策.md — 大学决策：深入反思动机，通过尽职调查找到真正属于自己的道路
- wiki/types/ENFP/ENFP-学业-大学与终身学习.md — 大学适应与终身学习：突破舒适区、克服浅尝辄止，以社交支持坚定持续学习的决心

### 职业
- wiki/types/ENFP/ENFP-职业-总论与选择.md — 职业总论：以信念和同理心驱动，适合教育、医疗、社会工作和创意领域
- wiki/types/ENFP/ENFP-职业-求职与面试.md — 求职与面试策略：兼顾热情与务实准备，以意义驱动化解职业困境
- wiki/types/ENFP/ENFP-职业-职场习惯.md — 职业路径与工作习惯：适合自主创业，以热情与社交力建立合作关系

---

## ENFP 类型间关系

### 友谊
- wiki/relationships/ENFP-NT型人-友谊.md — 与 NT 分析家的友谊：心智共鸣、创意交锋充满乐趣，需弥合沟通风格与情感表达的差异
- wiki/relationships/ENFP-NF型人-友谊.md — 与 NF 外交家的友谊：如镜中自我共享创意纽带，需打破回音室保持独立性
- wiki/relationships/ENFP-SJ型人-友谊.md — 与 SJ 守卫者的友谊：稳定与放飞自我，互利互补共同成长，需尊重不同生活节奏
- wiki/relationships/ENFP-SP型人-友谊.md — 与 SP 探险家的友谊：共享自由冒险与探索新视角，需约束失控行为并尊重不同的优先级

### 恋爱
- wiki/relationships/ENFP-NT型人-恋爱.md — 与 NT 分析家的恋爱：想象力与理性互补，共享抽象讨论的乐趣，需平衡情感表达方式与优先级的差异
- wiki/relationships/ENFP-NF型人-恋爱.md — 与 NF 外交家的恋爱：天生灵魂伴侣共享深厚情感共鸣，需防止情感耗竭与脱离现实
- wiki/relationships/ENFP-SJ型人-恋爱.md — 与 SJ 守卫者的恋爱：互利互补共创丰富人生，需调和随性创意与稳定秩序的生活节奏
- wiki/relationships/ENFP-SP型人-恋爱.md — 与 SP 探险家的恋爱：以好奇心和新奇体验维系活力，需在想象力与务实间找到平衡

### 职场
- wiki/relationships/ENFP-NT型人-职场.md — 与 NT 分析家的职场：创意头脑风暴互补，理性与人文视角结合激发创新
- wiki/relationships/ENFP-NF型人-职场.md — 与 NF 外交家的职场：共享灵感与价值观，以人文关怀推动积极变革
- wiki/relationships/ENFP-SJ型人-职场.md — 与 SJ 守卫者的职场：技能互补充满活力，人文关怀与务实精准的结合
- wiki/relationships/ENFP-SP型人-职场.md — 与 SP 探险家的职场：灵活互补轻松协作，创意愿景与实干能力的结合
