# INTJ 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/INTJ/INTJ-成长-自信.md`）
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

## INTJ 详情页导航

### 概述与成长
- wiki/types/INTJ/INTJ-概述-核心特征.md — 类型全景：稀有度分布、核心特质（远见者/战略家/幕后操纵者）、典型职业与浪漫关系初览、著名 INTJ 人物
- wiki/types/INTJ/INTJ-成长-优势.md — 极强自信、心智敏捷多才多艺、独立果断、战略想象力、诚实直率思想开放等核心优势
- wiki/types/INTJ/INTJ-成长-劣势.md — 傲慢与自信一线之隔、完美主义拖慢节奏、过度分析一切、缺乏同理心、浪漫关系困难
- wiki/types/INTJ/INTJ-成长-自尊.md — 以智力为自我价值基石，失衡时机智过热变傲慢，以"人类学家心理游戏"重塑
- wiki/types/INTJ/INTJ-成长-自我尊重.md — 独立独断独行是自尊源泉，极端厌恶从众时需用"我能从中获得什么"思考重塑
- wiki/types/INTJ/INTJ-成长-自信.md — 意志力与心智信任驱动，在逻辑无法掌控的领域易丧失自信，宁静祷文式练习可重获平静
- wiki/types/INTJ/INTJ-成长-善用特质.md — 平衡直觉与思考、保持专注、善用幽默、警惕优越感与完美主义、培养社交与情感表达

### 人际关系
- wiki/types/INTJ/INTJ-友谊-概述.md — 偏好少数深度智力交流而非庞大社交圈，不擅情感支持，讽刺幽默风格，与 NF 和 NT 型最易结盟
- wiki/types/INTJ/INTJ-友谊-NT型朋友.md — 天生智力共鸣与竞争性思维碰撞，需警惕空谈不行动与无休止争论
- wiki/types/INTJ/INTJ-友谊-NF型朋友.md — 直觉共鸣驱动神秘吸引力，理性与人文互补，需警惕冷愤世嫉俗伤害理想主义者
- wiki/types/INTJ/INTJ-友谊-SJ型朋友.md — 宏观战略与务实执行互补需时间磨合，社会习俗重视程度差异是主要挑战
- wiki/types/INTJ/INTJ-友谊-SP型朋友.md — 非一拍即合但互补成长，SP 教 INTJ 热情好奇，ISTP 技术型合作最有乐趣
- wiki/types/INTJ/INTJ-恋爱-概述.md — 以智慧洞察力评估伴侣，情感深厚但不传统表达，忠诚诚实热衷改善关系，需精神激发与身体刺激并重
- wiki/types/INTJ/INTJ-恋爱-内倾型伴侣.md — 共享独立与独处，但双方均难带动社交且易积压负面情感
- wiki/types/INTJ/INTJ-恋爱-外倾型伴侣.md — 能量维度互补，但需理解彼此对独处与社交的相反需求
- wiki/types/INTJ/INTJ-恋爱-直觉型伴侣.md — 无需言语的默契联结，但日常实际事务易引发紧张
- wiki/types/INTJ/INTJ-恋爱-实感型伴侣.md — 最具挑战也最富回报，直觉远见与务实行动互补
- wiki/types/INTJ/INTJ-恋爱-思考型伴侣.md — 冷静理性无戏剧冲突，但情感表达成为主要挑战
- wiki/types/INTJ/INTJ-恋爱-情感型伴侣.md — 冷硬事实与温暖和谐互补，须尊重彼此视角差异
- wiki/types/INTJ/INTJ-恋爱-计划型伴侣.md — 高度稳定方向一致，但双计划型僵化需灵活平衡
- wiki/types/INTJ/INTJ-恋爱-灵活型伴侣.md — 规划执着与随性自发的核心张力，互补得当可化差异为优势
- wiki/types/INTJ/INTJ-恋爱-身份变体.md — 自信型×自信型最直接、自信型×动荡型互补、动荡型×动荡型需减压策略

### 育儿
- wiki/types/INTJ/INTJ-育儿-概述.md — 理性引导代替传统温暖，鼓励自主决策培养批判思维，需刻意学习情感素养
- wiki/types/INTJ/INTJ-育儿-分析师子女.md — 直觉思考双重共鸣顺畅，但缺乏情感表达示范可能导致情感发育受阻
- wiki/types/INTJ/INTJ-育儿-外交官子女.md — 共享想象力与道德直觉，但直率犀利易伤敏感 NF 子女，批评须表达爱意
- wiki/types/INTJ/INTJ-育儿-SJ型和SP型子女.md — SJ 子女在取悦与自我间两难，SP 子女随性考验耐心但共享精通与独立

### 学业
- wiki/types/INTJ/INTJ-学业-学习方式.md — 直觉型思考者的点彩派式宏观综合，逻辑验证筛选，热爱难题与制定计划
- wiki/types/INTJ/INTJ-学业-高中.md — 概念化能力觉醒与卓越成就，科学/技术/艺术偏好，社交困扰与霸凌挑战
- wiki/types/INTJ/INTJ-学业-大学.md — 学位需求与无形价值权衡，科学/技术/经济/法律等推荐专业，自主权享受与派对试探

### 职业
- wiki/types/INTJ/INTJ-职业-概述.md — 将复杂原理转清晰方案的战略家，以效率能力为最高准则，需警惕错误路径
- wiki/types/INTJ/INTJ-职业-职业发展.md — 战略求职、倾听内心、善用知识吸收优势、平衡人际与专业能力
- wiki/types/INTJ/INTJ-职业-替代方案.md — 创业消除企业社交服从障碍，想象力与独特关联产生创新商业创意
- wiki/types/INTJ/INTJ-职业-适合的职业.md — 工程/设计、研究/科学、医学诊断、策略咨询四大领域具体职位
- wiki/types/INTJ/INTJ-职业-不适合的职业.md — 规则僵化限制性环境、过度依赖面对面社交接触的岗位
- wiki/types/INTJ/INTJ-职业-职场习惯.md — 作为同事极度独立追求效率，作为管理者给予高度自由尊重合理论点，作为下属只认能力
- wiki/types/INTJ/INTJ-职业-沟通-四角色组.md — NT/NT 智力共鸣与竞争，NT/NF 理性与人文互补，NT/SJ 愿景与执行协同，NT/SP 理论与动手协作

---

## INTJ 类型间关系

### 恋爱
- wiki/relationships/INTJ-NT型人-恋爱.md — 以智力刺激为核心联结，互为围城外慰藉之地，警惕过度分析与决策纠结
- wiki/relationships/INTJ-NF型人-恋爱.md — 直觉共鸣迅速联结，NF 温暖平衡 NT 理性，浪漫表达认知差异是核心挑战
- wiki/relationships/INTJ-SJ型人-恋爱.md — NT 远见创新与 SJ 稳定务实互补，NT 需警惕居高傲视伤害 SJ 付出
- wiki/relationships/INTJ-SP型人-恋爱.md — 理论难题与现实挑战互补，共享对社会习俗的无视，需初期明确家务分工
