# INFJ 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/INFJ/INFJ-成长-自信.md`）
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

## INFJ 详情页导航

### 概述与成长
- wiki/types/INFJ/INFJ-概述-谁是INFJ.md — INFJ 人格类型全景概览：个人成长中理想与现实的张力、人际关系中的深度联结、学业与职业中的助人驱动力及意义追寻
- wiki/types/INFJ/INFJ-成长-奠基与动机.md — INFJ 个人成长的根基：内在价值体系如何塑造行为动机，理想主义驱动力的来源与演变
- wiki/types/INFJ/INFJ-成长-自尊.md — INFJ 的自尊来源与脆弱面：基于原则的自尊在遭遇外部否定时的表现及其重塑路径
- wiki/types/INFJ/INFJ-成长-自重.md — INFJ 对自我价值的感知：如何在理想与现实差距中保持自重，以及他人反馈的影响
- wiki/types/INFJ/INFJ-成长-自信.md — INFJ 的自信建立机制：从内在信念走向外部行动过程中的自信波动与巩固
- wiki/types/INFJ/INFJ-成长-自我进化.md — INFJ 的自我迭代路径：以反思和内省驱动的成长模式，以及拥抱变化的能力
- wiki/types/INFJ/INFJ-成长-自我负责.md — INFJ 的自我负责意识：从责任感到行动边界的觉察，避免过度承担他人负担

### 人际关系
- wiki/types/INFJ/INFJ-友谊-总论.md — INFJ 的友谊模式总览：深度而非广度的人际联结、忠诚慷慨的交友风格及与各类型的友谊特征
- wiki/types/INFJ/INFJ-恋爱-总论.md — INFJ 的恋爱风格全貌：理想化的爱情追求、深沉的情感投入、亲密关系中的优势与成长点

### 育儿
- wiki/types/INFJ/INFJ-育儿-总论与原则.md — INFJ 作为父母的核心理念：将人类未来希望寄托于子女的养育哲学，高标准与深度关怀的结合
- wiki/types/INFJ/INFJ-育儿-婴儿期.md — INFJ 父母在婴儿期的育儿风格：情感连接与安全感的建立，为未来奠定精神基础
- wiki/types/INFJ/INFJ-育儿-幼儿期.md — INFJ 父母面对幼儿自主探索阶段：引导与保护的平衡，价值观的早期渗透
- wiki/types/INFJ/INFJ-育儿-学龄前.md — INFJ 父母在学龄前的教育方式：想象力激发与道德启蒙，为社会化做准备的策略
- wiki/types/INFJ/INFJ-育儿-学龄期.md — INFJ 父母应对学校阶段的挑战：学业关怀与人格培养并重，理想标准与现实适应的调和
- wiki/types/INFJ/INFJ-育儿-青春期.md — INFJ 父母面对子女青春期的独立诉求：理想与叛逆的冲突，共情引导与放手信任的成长

### 学业
- wiki/types/INFJ/INFJ-学业-学习方式.md — INFJ 的学习偏好与方法：深度理解优于广度涉猎、意义驱动的学习动机构成其学业核心
- wiki/types/INFJ/INFJ-学业-高中.md — INFJ 在高中阶段的学业表现：体制内的适应与挑战、社交圈的选择及课外活动的意义追寻
- wiki/types/INFJ/INFJ-学业-大学决策.md — INFJ 的大学及专业选择：价值观匹配优先于功利计算，长期愿景在高等教育路径中的作用
- wiki/types/INFJ/INFJ-学业-大学与终身学习.md — INFJ 在大学阶段及终身学习中的表现：深度学术探索、与他人的知识互动及持续成长的驱动力

### 职业
- wiki/types/INFJ/INFJ-职业-总论与选择.md — INFJ 的职业适配方向：助人行业优先、有意义挑战的渴求、创造性与结构化并存的理想工作环境
- wiki/types/INFJ/INFJ-职业-求职与面试.md — INFJ 的求职策略与面试表现：真诚展示内在热情与价值观、识别符合个人使命的组织文化
- wiki/types/INFJ/INFJ-职业-职场习惯.md — INFJ 在职场中的行事风格：勤勉尽责与对等级制度的排斥、团队合作中的协调者角色

---

## INFJ 类型间关系

### 友谊
- wiki/relationships/INFJ-NT型人-友谊.md — INFJ 与 NT 分析家的友谊：理性与洞察的智力共鸣，战略思维与人文关怀的交汇
- wiki/relationships/INFJ-NF型人-友谊.md — INFJ 与 NF 外交家的友谊：共享理想的心灵盟友，同理心共鸣与过度投入的平衡
- wiki/relationships/INFJ-SJ型人-友谊.md — INFJ 与 SJ 守卫者的友谊：务实支持与愿景引导的互补，传统与革新的对话
- wiki/relationships/INFJ-SP型人-友谊.md — INFJ 与 SP 探险家的友谊：深度思考与行动体验的对比，互相学习活在当下与放眼未来

### 恋爱
- wiki/relationships/INFJ-NT型人-恋爱.md — INFJ 与 NT 分析家的恋爱：价值观驱动与逻辑分析间的互补火花，理想的共鸣与务实表达的磨合
- wiki/relationships/INFJ-NF型人-恋爱.md — INFJ 与 NF 外交家的恋爱：共同理想主义下的深度情感联结，相似性带来的和谐与盲区
- wiki/relationships/INFJ-SJ型人-恋爱.md — INFJ 与 SJ 守卫者的恋爱：远见与传统间的张力与互补，稳定承诺与变革愿景的统一
- wiki/relationships/INFJ-SP型人-恋爱.md — INFJ 与 SP 探险家的恋爱：深度与即兴的碰撞，灵魂探索与现实体验的不同步与相互吸引

### 职场
- wiki/relationships/INFJ-NT型人-职场.md — INFJ 与 NT 分析家的职场协作：战略远见与逻辑分析的黄金组合，创新驱动与执行路径的协同
- wiki/relationships/INFJ-NF型人-职场.md — INFJ 与 NF 外交家的职场协作：价值观驱动的人本主义合作，情感智力与理想目标的一致性
- wiki/relationships/INFJ-SJ型人-职场.md — INFJ 与 SJ 守卫者的职场协作：愿景规划与秩序维护的分工，变革推动与稳定执行的平衡
- wiki/relationships/INFJ-SP型人-职场.md — INFJ 与 SP 探险家的职场协作：深层洞察与敏捷行动的搭配，长期目标与即时应对的互补
