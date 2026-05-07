# ESTP 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ESTP/ESTP-成长-自信.md`）
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

## ESTP 详情页导航

### 概述与成长
- wiki/types/ESTP/ESTP-概述-谁是ESTP.md — ESTP 性格类型的核心特质总览，涵盖个人成长中的冒险与自律、人际关系中的魅力与直率、学术职业中的即兴天赋与规划短板
- wiki/types/ESTP/ESTP-成长-奠基与动机.md — 个人成长的三大维度（自尊、自信、动机）框架，理解 ESTP 如何从行动与体验中获得成长动力
- wiki/types/ESTP/ESTP-成长-自尊与能力.md — 能力感与精通感作为自尊基石，平衡时驱动成长、失衡时可能牺牲人际关系的双面性
- wiki/types/ESTP/ESTP-成长-自尊与即兴.md — 临场应变与即兴解决问题的能力如何支撑自尊，失衡时冒险寻求危险以证明价值的风险
- wiki/types/ESTP/ESTP-成长-自信.md — 胆识与拥抱变化的自信来源，过度自信导致鲁莽决策的风险，使命宣言助力重塑平衡
- wiki/types/ESTP/ESTP-成长-人际效能.md — 凭借观察力与即兴应变在社交中游刃有余，但需警惕操纵倾向，培养情商与真诚沟通
- wiki/types/ESTP/ESTP-成长-规划.md — 灵活应变与长期规划的张力，借助他人专业能力弥补结构化短板，兼顾自由与稳定
- wiki/types/ESTP/ESTP-成长-随机应变.md — 高压下解决问题的临场能力，滥用灵活性导致缺乏承诺的风险，关注重要之人的需求以实现平衡
- wiki/types/ESTP/ESTP-成长-总结.md — 个人成长总结：通过实际行动实现自我精进，学会停下脚步、规划生活并关注他人

### 人际关系
- wiki/types/ESTP/ESTP-友谊-总论.md — 聚会灵魂人物，随和宽容、热爱探索，崇尚行动与刺激，与几乎所有人相处融洽的社交风格
- wiki/types/ESTP/ESTP-恋爱-总论.md — 热情而难以预测的恋爱风格，即兴发挥让关系永不乏味，对刺激的渴求与回避长期规划对关系稳定的考验

### 育儿
- wiki/types/ESTP/ESTP-育儿-总论.md — ESTP 型父母活泼开朗、热爱动手实践，能成为孩子理想父母，但需注意情感联结方面的挑战与弥合策略

### 学业
- wiki/types/ESTP/ESTP-学业-学习方式.md — 动手实践和即兴体验中学习效果最佳，传统结构化课堂的不适应，灵活教学与小组合作的激发作用
- wiki/types/ESTP/ESTP-学业-高中.md — 高中阶段充满活力善于交际，动手实践和课外活动中表现出色，传统课堂的格格不入与兴趣结合策略
- wiki/types/ESTP/ESTP-学业-大学.md — 大学阶段社交生活与学业目标的平衡，定制课程、应对枯燥课程的能力培养，终身学习习惯的养成

### 职业
- wiki/types/ESTP/ESTP-职业-总论与特质.md — 亲力亲为的务实工作者，善于社交和临场决策，敢于冒险且具备隐形领导力，耐心和结构化环境容忍度的挑战
- wiki/types/ESTP/ESTP-职业-选择与创业.md — 适合商业销售、应急服务、法律政治等高活跃度职业，自主创业释放冒险精神，人脉建立与兴趣关联的求职策略
- wiki/types/ESTP/ESTP-职业-求职与面试.md — 避免过度依赖即兴发挥，提前准备面试问题和技巧，全面展现优势以在竞争中脱颖而出

---

## ESTP 类型间关系

### 恋爱
- wiki/relationships/ESTP-NT型人-恋爱.md — ESTP 与 NT 型人的恋爱互动模式
- wiki/relationships/ESTP-NF型人-恋爱.md — ESTP 与 NF 型人的恋爱互动模式
- wiki/relationships/ESTP-SJ型人-恋爱.md — ESTP 与 SJ 型人的恋爱互动模式
- wiki/relationships/ESTP-SP型人-恋爱.md — ESTP 与 SP 型人的恋爱互动模式

### 友谊
- wiki/relationships/ESTP-NT型人-友谊.md — ESTP 与 NT 型人的友谊互动模式
- wiki/relationships/ESTP-NF型人-友谊.md — ESTP 与 NF 型人的友谊互动模式
- wiki/relationships/ESTP-SJ型人-友谊.md — ESTP 与 SJ 型人的友谊互动模式
- wiki/relationships/ESTP-SP型人-友谊.md — ESTP 与 SP 型人的友谊互动模式

### 育儿
- wiki/relationships/ESTP-NT型人-育儿.md — ESTP 与 NT 型孩子的亲子互动模式
- wiki/relationships/ESTP-NF型人-育儿.md — ESTP 与 NF 型孩子的亲子互动模式
- wiki/relationships/ESTP-SJ型人-育儿.md — ESTP 与 SJ 型孩子的亲子互动模式
- wiki/relationships/ESTP-SP型人-育儿.md — ESTP 与 SP 型孩子的亲子互动模式

### 职场协作
- wiki/relationships/ESTP-NT型人-职场.md — ESTP 与 NT 型同事的职场协作模式
- wiki/relationships/ESTP-NF型人-职场.md — ESTP 与 NF 型同事的职场协作模式
- wiki/relationships/ESTP-SJ型人-职场.md — ESTP 与 SJ 型同事的职场协作模式
- wiki/relationships/ESTP-SP型人-职场.md — ESTP 与 SP 型同事的职场协作模式
