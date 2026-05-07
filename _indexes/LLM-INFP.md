# INFP 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/INFP/INFP-成长-自信.md`）
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

## INFP 详情页导航

### 概述与成长
- wiki/types/INFP/INFP-概述-谁是INFP.md — INFP 的核心特质、人际关系模式及学术与职业发展总览
- wiki/types/INFP/INFP-成长-总论.md — 调停者个人成长的核心理念与整体方向
- wiki/types/INFP/INFP-成长-自尊.md — INFP 如何建立健康的自尊，在自我接纳中找到力量
- wiki/types/INFP/INFP-成长-自爱.md — 调停者学会善待自己、平衡付出与自我关怀的成长课题
- wiki/types/INFP/INFP-成长-自信.md — INFP 克服社交不安、将内在创造力转化为外在自信的路径
- wiki/types/INFP/INFP-成长-自我进化.md — 调停者在成长中持续迭代自我、实现潜能的方法
- wiki/types/INFP/INFP-成长-自我负责.md — INFP 学会为自己的选择与人生承担责任的成长旅程

### 人际关系
- wiki/types/INFP/INFP-友谊-总论.md — INFP 在友谊中的特质：真诚、深度联结、对挚友视如家人般的付出
- wiki/types/INFP/INFP-恋爱-总论.md — 调停者在恋爱关系中的理想主义、深情付出与情感需求

### 育儿
- wiki/types/INFP/INFP-育儿-总论.md — INFP 作为父母的核心理念：以共情和开放心态滋养子女成长
- wiki/types/INFP/INFP-育儿-发展阶段.md — INFP 父母在子女各成长阶段的教养策略与挑战

### 学业
- wiki/types/INFP/INFP-学业-总论.md — INFP 的学习风格：好奇心驱动、创造力优先、追求知识的意义
- wiki/types/INFP/INFP-学业-高中.md — 调停者在高中阶段的学业表现、挑战与适应策略
- wiki/types/INFP/INFP-学业-大学.md — INFP 在大学环境中的学术探索、专业选择与成长
- wiki/types/INFP/INFP-学业-终身学习.md — 调停者终身学习的动力、方式与持续成长路径

### 职业
- wiki/types/INFP/INFP-职业-总论.md — INFP 的职业选择偏好、理想工作环境与职业发展路径
- wiki/types/INFP/INFP-职业-职场角色.md — 调停者在职场中的角色定位、团队贡献与领导风格

### 维度特质
- wiki/types/INFP/INFP-维度特质-综合特质.md — INFP 五大维度的综合表现及身份维度（-A/-T）的影响

---

## INFP 类型间关系

### 友谊
- wiki/relationships/INFP-NT型人-友谊.md — 与 NT 分析家的友谊：理想主义与理性分析的碰撞与互补
- wiki/relationships/INFP-NF型人-友谊.md — 与 NF 外交家的友谊：共享理想与价值观的灵魂共鸣
- wiki/relationships/INFP-SJ型人-友谊.md — 与 SJ 守卫者的友谊：理想主义与现实主义的互相学习
- wiki/relationships/INFP-SP型人-友谊.md — 与 SP 探险家的友谊：共同探索新鲜体验与当下乐趣的伙伴

### 恋爱
- wiki/relationships/INFP-NT型人-恋爱.md — 与 NT 分析家的恋爱：情感深度与逻辑思维的浪漫交锋
- wiki/relationships/INFP-NF型人-恋爱.md — 与 NF 外交家的恋爱：深度情感联结与共同成长的关系
- wiki/relationships/INFP-SJ型人-恋爱.md — 与 SJ 守卫者的恋爱：浪漫梦想与务实安稳的平衡艺术
- wiki/relationships/INFP-SP型人-恋爱.md — 与 SP 探险家的恋爱：感官体验与情感深度的交织

### 职场
- wiki/relationships/INFP-NT型人-职场.md — 与 NT 分析家的职场协作：创意同理心与战略思维的配合
- wiki/relationships/INFP-NF型人-职场.md — 与 NF 外交家的职场协作：和谐共情、以人为本的合作模式
- wiki/relationships/INFP-SJ型人-职场.md — 与 SJ 守卫者的职场协作：创新灵活与传统有序的互补
- wiki/relationships/INFP-SP型人-职场.md — 与 SP 探险家的职场协作：灵活适应与即兴创造的组合
