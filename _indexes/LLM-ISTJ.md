# ISTJ 检索导航

> 本文件供检索LLM使用。根据用户问题，从下方导航中定位相关页面，使用 read_file 工具读取后输出结构化知识。

---

## 检索规则

1. 你是**内容提取者**：定位页面 → 读取内容 → 客观精炼输出
2. 工具调用上限：最多 **3次** read_file
3. 路径格式：相对于知识库根目录（如 `wiki/types/ISTJ/ISTJ-成长-自信.md`）
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

## ISTJ 详情页导航

### 概述与成长
- wiki/types/ISTJ/ISTJ-概述-谁是ISTJ.md — ISTJ人格全貌：核心特质、人际关系风格、学术与职业发展方向，帮你建立对这一类型的第一印象
- wiki/types/ISTJ/ISTJ-成长-奠基与动机.md — 安全感与稳定性如何驱动ISTJ的人生选择，以及其核心价值观的来源
- wiki/types/ISTJ/ISTJ-成长-自尊.md — ISTJ如何通过可靠表现和履行承诺来建立自我价值感，以及失衡时的过度自责倾向
- wiki/types/ISTJ/ISTJ-成长-自重.md — 在坚守规则与关怀自我之间寻找平衡，警惕以牺牲自身需求为代价的过度奉献
- wiki/types/ISTJ/ISTJ-成长-自信.md — 基于事实能力和过往成就的扎实自信，如何避免因抗拒陌生领域而限制自我发展
- wiki/types/ISTJ/ISTJ-成长-自我责任.md — 独立承担与坚持到底的责任感表现，以及学会适时分派任务和寻求帮助的成长方向
- wiki/types/ISTJ/ISTJ-成长-自我进化.md — 在恪守传统优势的同时拥抱适度变革，实现个人成长与新旧的有机融合

### 人际关系
- wiki/types/ISTJ/ISTJ-友谊-总论.md — ISTJ如何以忠诚可靠为基石筛选和经营友谊，在结构化环境中自然建立深层连接
- wiki/types/ISTJ/ISTJ-恋爱-总论.md — ISTJ以承诺和安全感为核心的恋爱观，情感表达的内敛方式及亲密关系中的成长课题

### 育儿
- wiki/types/ISTJ/ISTJ-育儿-总论与原则.md — ISTJ父母以责任感和稳定性为核心的教育理念，以及提升情商与灵活性的育儿方向
- wiki/types/ISTJ/ISTJ-育儿-婴儿期.md — 婴儿期通过可靠照料建立牢固依恋纽带，需注意给予充分亲昵和合理发育期望
- wiki/types/ISTJ/ISTJ-育儿-幼儿期.md — 在安全规则与尊重孩子试探界限之间取得平衡，培养负责任的独立性
- wiki/types/ISTJ/ISTJ-育儿-学龄前.md — 以天生的教师角色引导学龄前儿童，需提升灵活性、接纳自由游戏的价值
- wiki/types/ISTJ/ISTJ-育儿-学龄期.md — 发挥导师优势陪伴学龄期成长，避免过度关注成就与缺点，共同建立更全面的成功定义
- wiki/types/ISTJ/ISTJ-育儿-青春期.md — 面对青春期子女的独立诉求，在坚守原则与给予自主空间之间寻找平衡

### 学业
- wiki/types/ISTJ/ISTJ-学业-学习方式.md — 以结构化、循序渐进和动手实践为核心的学习风格，如何最大化发挥事实记忆优势
- wiki/types/ISTJ/ISTJ-学业-高中.md — 高中阶段的ISTJ在规则环境中如鱼得水，需注意拓展课外视野和培养独立思考
- wiki/types/ISTJ/ISTJ-学业-大学决策.md — 如何依据自身务实特质和长期目标做出理性的大学和专业选择
- wiki/types/ISTJ/ISTJ-学业-大学与终身学习.md — 大学期间的专注与适应，以及终身学习中在深耕与拓展之间的持续精进

### 职业
- wiki/types/ISTJ/ISTJ-职业-总论与选择.md — 适合ISTJ的职业领域与具体岗位推荐，以及应避开的职业环境特征
- wiki/types/ISTJ/ISTJ-职业-自主创业.md — ISTJ自主创业的优势与挑战，如何在既定框架内开辟自己的事业路径
- wiki/types/ISTJ/ISTJ-职业-职场习惯.md — ISTJ在职场中的工作风格、团队协作倾向和处理压力与冲突的典型模式

---

## ISTJ 类型间关系

### 恋爱
- wiki/relationships/ISTJ-NT型人-恋爱.md — 与分析家型人的浪漫关系：效率共鸣与创新保守之间的互补与张力
- wiki/relationships/ISTJ-NF型人-恋爱.md — 与外交家型人的浪漫关系：务实根基与理想主义之间的相互滋养与磨合
- wiki/relationships/ISTJ-SJ型人-恋爱.md — 与同组守卫者的浪漫关系：共同价值观下的高度默契与可能陷入固化的风险
- wiki/relationships/ISTJ-SP型人-恋爱.md — 与探险家型人的浪漫关系：稳定与自发两种生活节奏的碰撞与融合

### 友谊
- wiki/relationships/ISTJ-NT型人-友谊.md — 与分析家型人的友谊：理性共振与相互尊重，共享对效率和成果的追求
- wiki/relationships/ISTJ-NF型人-友谊.md — 与外交家型人的友谊：务实支持与理想关怀的互补，在价值观分歧处寻求理解
- wiki/relationships/ISTJ-SJ型人-友谊.md — 与同组守卫者的友谊：自然可靠的情谊基础，需注意思维僵化与情感支持不足
- wiki/relationships/ISTJ-SP型人-友谊.md — 与探险家型人的友谊：稳重与随性的相互吸引，在差异中拓展彼此的生活视角

### 职场
- wiki/relationships/ISTJ-NT型人-职场.md — 与分析家型人的职场协作：执行力与创新思维的黄金互补，警惕社交智能的共同盲区
- wiki/relationships/ISTJ-NF型人-职场.md — 与外交家型人的职场协作：实际需求与人文关怀的结合，在共同目标下弥合务实与理想的差距
- wiki/relationships/ISTJ-SJ型人-职场.md — 与同组守卫者的职场协作：风格相近的高效合作，需警惕集体固守成规的倾向
- wiki/relationships/ISTJ-SP型人-职场.md — 与探险家型人的职场协作：稳定后方与灵活应变的分工，纪律与自发性之间的动态平衡
