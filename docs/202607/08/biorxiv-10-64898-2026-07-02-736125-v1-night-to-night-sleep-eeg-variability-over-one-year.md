---
title: Night-to-night sleep EEG variability over one year
title_zh: 一年内夜际睡眠脑电变异性
authors: "Rosenblum, Y., Bovy, L., Hemmsen, M. C., Duun-Henriksen, J., Ahrens, E., Dresler, M."
date: 2026-07-08
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.02.736125v1.full.pdf"
tags: ["query:sleep-mental"]
score: 9.0
evidence: 睡眠脑电变异分析提供客观睡眠质量测量
tldr: "本研究基于20名健康参与者一年内6429晚皮下脑电数据，通过动态时间规整分析整晚睡眠宏观结构（非周期斜率、sigma波和慢波功率）的夜间变异性。发现整体睡眠宏观模式夜间相似度约80%，但时间对齐需扭曲约60%才能匹配；较低的宏观结构变异与更好主观睡眠质量相关。进一步比较不同尺度指标，表明睡眠指标的夜间变异性更多取决于度量本身而非分析尺度，反映了特质与动态特征的区分。"
source: biorxiv
selection_source: fresh_fetch
motivation: 探究整晚睡眠宏观结构在一年内的夜间变异性，尤其关注时间模式的一致性与个体差异。
method: 分析20人6429晚皮下脑电，提取非周期斜率、sigma波和慢波功率的时间序列，用动态时间规整计算夜间差异。
result: "整体宏观结构相似度约80%，时间对齐变异大；宏观结构变异与主观睡眠质量负相关；不同指标变异性差异显著。"
conclusion: 睡眠指标的夜间变异性更多是度量特异性而非尺度依赖性，提示特质与动态特征的区分。
---

## 摘要
本研究旨在通过分析20名健康参与者一年内（每人205-388夜，共6429夜）的皮下脑电图（sqEEG），探索多尺度睡眠模式的夜际变异性。我们利用非周期斜率、西格玛和慢波功率的时间序列作为新的整夜睡眠宏观结构单元。使用动态时间规整，计算这些时间序列之间的距离（差异）来评估夜际睡眠宏观结构的不相似性。我们发现，整体睡眠宏观结构模式在夜间相对相似（20%的不相似性），而它们的时间对齐变化相当大（最佳对齐时时间序列扭曲约60%）。宏观结构不相似性的较低变化与更好的主观睡眠质量相关（r=-0.25）。然后，我们定性比较了宏观尺度、微观尺度（睡眠阶段比例、平均频谱功率）和中尺度（睡眠周期时长）指标的年度变化。我们发现，个体内夜际变异性：频谱功率、睡眠时长、N2和REM睡眠为“低”（变异系数<20%）；N3和宏观结构不相似性为“中等”（20-40%）；睡眠周期时长、清醒和N1为“高”（>40%）。总之，不同的睡眠指标表现出不同的夜际变异性，这更偏向于指标特异性而非尺度依赖性。这可能反映了睡眠中更像特质与更动态变化特征之间的区别，尽管这一假设需要进一步澄清。

## Abstract
This study aimed to explore night-to-night variability of multiscale sleep patterns by analyzing subcutaneous electroencephalography (sqEEG) from 20 healthy participants over one year (205-388 nights per participant, 6,429 nights in total). We utilized the time series of aperiodic slopes, sigma and slow-wave power as a new whole-night unit of sleep macrostructure. Using dynamic time warping, we calculated the distances (differences) between those time series to assess night-to-night sleep macrostructure dissimilarity. We found that the overall sleep macrostructural patterns were relatively similar across nights (20% dissimilarity), while their temporal alignment was quite variable (time series warped by ~60% for the best alignment). Lower variation in macrostructure dissimilarity was associated with better subjective sleep quality (r=-0.25). Then, we qualitatively compared yearlong variation in macroscale, microscale (sleep stage proportions, mean spectral power) and mesoscale (sleep cycle duration) metrics. We found that intra-individual night-to-night variation was '"low (coefficients of variation < 20%) for spectral power, sleep duration, N2 and REM sleep; ''medium'' (20-40%) - for N3 and macrostructure dissimilarity; and "high" (>40%) - for sleep cycle duration, wake and N1. In summary, different sleep metrics showed differential night-to-night variability, which was more metric-specific than scale-dependent. This might reflect a distinction between more trait-like versus more dynamically varying features of sleep, although this assumption needs further clarification.

---

## 论文详细总结（自动生成）

# 论文详细中文总结

## 1. 论文的核心问题与整体含义

- **研究动机**：传统睡眠研究依赖单夜或少数几夜的实验室多导睡眠图（PSG）快照，缺乏对睡眠夜际变异性和长期睡眠规律性的了解。近年研究表明，睡眠规律性（而非仅睡眠时长）对身心健康至关重要。皮下脑电图（sqEEG）设备使得超长期连续EEG监测成为可能，但此前缺乏对健康人群长达一年睡眠宏微观结构的系统变异性分析。
- **核心问题**：健康个体在长达一年的时间跨度内，整晚睡眠宏观结构（基于EEG时间序列）的夜际稳定性/变异性如何？这种变异性在不同尺度（微观、中观、宏观）的睡眠指标之间是否存在差异？是否与主观睡眠质量相关？
- **整体含义**：通过引入新的整晚睡眠宏观结构度量（非周期斜率、sigma波和慢波功率的时间序列）及其夜际不相似性指标（基于动态时间规整），本研究揭示了睡眠结构的“模式相似、时间对齐高度可变”的特征，并发现不同睡眠指标的变异性更多是指标特异性而非尺度依赖性的，可能反映了睡眠中“特质样”（稳定遗传）与“状态样”（动态波动）特征的区分，为个体化睡眠监测和临床诊断提供基础。

## 2. 论文提出的方法论

- **核心思想**：将整晚睡眠EEG视为一个宏观结构单元，用时间序列（30秒分辨率）表示，通过动态时间规整（DTW）量化相邻夜晚之间的不相似性；同时计算多个微观、中观指标的夜际变异系数（CV），比较不同尺度的变异性。
- **关键技术细节**：
  - **EEG预处理**：双通道sqEEG信号（TP9/TP10、T9/T10、FT9/FT10，三触点电极），平均至单通道，每30秒计算频谱功率。使用“不规则重采样自谱分析”（IRASA）将总功率分解为振荡和去周期性分量，在1–28 Hz范围内计算去周期性斜率（幂律指数）。
  - **宏观结构单元**：对每夜，提取z归一化并Savitzky-Golay平滑后的去周期性斜率时间序列（或sigma功率、慢波功率SWA时间序列），作为整晚睡眠宏观结构的表征。
  - **夜际不相似性度量**：对相邻夜晚的5小时睡眠时间序列（从入睡后开始，统一长度），使用DTW算法（Matlab内置dtw函数，默认参数）进行非线性对齐（允许拉伸/压缩），计算对齐后的欧几里得距离之和，并除以时间序列长度（300分钟）得到归一化不相似度（百分比）。同时记录对齐所需的扭曲量（warping amount）。
  - **变异系数（CV）**：对于各睡眠指标（微观：睡眠阶段比例、平均频谱功率、去周期性斜率；中观：睡眠周期参数如时长、幅度；宏观：REM/NREM比、总睡眠时长、DTW不相似度），计算个体内（每夜）和个体间的CV。分类标准：CV<0.1为“极低”，0.1–0.2为“低”，0.2–0.4为“中”，>0.4为“高”。
- **算法流程**（文字说明）：
  1. 读取每夜EEG数据，计算30秒频谱。
  2. 对每夜，用IRASA分解，得到去周期性斜率时间序列、sigma和SWA功率时间序列。
  3. 对每夜的时间序列进行z归一化和Savitzky-Golay平滑。
  4. 将每夜时间序列截断至入睡后前5小时。
  5. 对每对相邻夜晚，使用DTW对齐，计算归一化DTW距离（不相似度）和扭曲量。
  6. 计算所有睡眠指标的夜际CV（对每个参与者，对每个指标计算SD/Mean）。
  7. 将每月平均的主观睡眠质量与每月计算的CV进行Spearman相关分析（Benjamini-Hochberg校正）。

## 3. 实验设计

- **数据集**：
  - 主要数据：Ultra-Long-Term Sleep项目，20名健康参与者（11女性，平均32±13岁），每人连续一年记录sqEEG（205–388夜，共6429夜）。设备：24/7 EEG SubQ（UNEEG Medical A/S），采样率207 Hz，带通0.5–48 Hz。自动睡眠分期采用适配sqEEG的U-Sleep算法。
  - 补充验证（复现）：使用两个独立的多导睡眠图数据集（3夜）和一个可穿戴EEG数据集（最多15连续夜），见原文Supplemental Table 2。
- **Benchmark**：未使用传统基准方法对比，而是将新引入的宏观结构不相似性度量与已有常见睡眠指标（微观、中观尺度）的变异性进行比较。此外，与Leguia et al. (2025)的30天sqEEG研究进行了定性比较（复现了其“个体内不相似性小于个体间”的发现）。
- **对比方法**：主要对比不同睡眠指标（微观、中观、宏观）的夜际CV，以及不同尺度之间的变异性模式。未与其他DTW变体或睡眠规律性指标（如睡眠规律性指数SRI、日间稳定性IS）进行直接数值比较。

## 4. 资源与算力

- 文中未明确提及使用的GPU型号、数量、训练时长等计算资源信息。分析主要基于MATLAB（R2021b）和Fieldtrip工具箱，以及自定义脚本和开源代码。因此，无法报告具体算力消耗。

## 5. 实验数量与充分性

- **实验数量**：
  - 主分析：20名参与者，每人平均322夜（DTW分析需5小时以上睡眠，得到283对相邻夜），共6429夜（DTW分析使用5656对夜）。
  - 对所有23个睡眠指标计算了CV（包括微观11个、中观6个、宏观6个）。
  - 相关分析：主观睡眠质量（每月平均）与每月CV的Spearman相关，共23个检验，进行了多重比较校正。
  - 复现分析：在2个独立PSG数据集（3夜）和1个可穿戴EEG数据集（15夜）中重复了DTW分析，结果一致。
- **充分性与客观性**：
  - 优点：样本量在夜数上很大（>6000夜），且时间跨度长达一年，远超以往研究。对不同尺度指标进行了统一的CV分类，比较合理。
  - 局限性：样本量仅有20人，个体间差异的统计效力有限。相关分析中相关系数较弱（r<0.3），且未进行方向性因果推断。主观睡眠质量仅用单一Likert条目，信度有限。未与客观睡眠规律性指数（如SRI、IS）进行直接比较，缺乏对“睡眠规律性”这一概念的全面验证。此外，DTW距离仅针对前5小时睡眠，可能漏掉后期REM睡眠的变异；且只使用了相邻夜对比，未考虑更长时间间隔的变异性。

## 6. 论文的主要结论与发现

1. **宏观结构夜际变异**：整晚睡眠宏观结构模式（去周期性斜率、sigma功率、SWA的时间序列形状）在相邻夜晚之间平均只有约20%的不相似性（即80%相似），但时间对齐需要大幅扭曲（平均扭曲量约60%），说明差异主要体现在时间偏移而非模式本身。
2. **变异系数的分类**：
   - “非常低”变异（CV<0.1）：sigma功率（N2）、SWA（N2和N3）、N2/N3/REM的去周期性斜率。这些指标高度稳定，可能反映遗传特质。
   - “低”变异（0.1–0.2）：睡眠时长、N2和REM比例、去周期性斜率在N1。
   - “中”变异（0.2–0.4）：N3比例、REM/NREM比、宏观结构不相似度（DTW距离）、睡眠周期幅度。
   - “高”变异（>0.4）：WASO、N1比例、睡眠周期时长（特别是上升部分）。高变异反映了这些指标受干扰影响大。
3. **变异性模式**：不同睡眠指标的变异性更多是指标特异性而非尺度依赖性（例如微观尺度的频谱功率非常稳定，而微观尺度的WASO/N1变异高；宏观尺度的DTW不相似度中等，而中尺度的周期时长变异高）。
4. **与主观睡眠质量的关系**：较低的宏观结构不相似度变异、较低的N1/WASO去周期性斜率变异与更好的主观睡眠质量相关；而较高的N3比例变异、较高的频谱功率变异（N2/N3的sigma、SWA、去周期性斜率）与更好的主观睡眠质量正相关（所有相关r<0.3，弱相关）。作者解释为：非常稳定的指标（CV极低）的正相关可能反映其对睡眠质量的保护作用，而中等变异指标（CV中）的负相关可能说明一定波动有益。
5. **主观幸福感**：WHO-5和MDI与EEG指标CV无显著相关，可能由于健康参与者存在天花板效应。

## 7. 优点

- **数据规模空前**：首次对健康个体进行一年连续sqEEG监测，提供了最丰富的夜际变异性数据（6429夜）。
- **方法创新**：引入基于DTW的宏观结构不相似性度量，能够区分“模式相似性”与“时间对齐变异性”，比传统仅比较睡眠阶段比例或功率平均值更全面。
- **多尺度系统比较**：统一使用CV对微观、中观、宏观指标进行定量比较，揭示了指标特异性而非尺度依赖性的模式，为理解睡眠规律性的不同维度提供了新视角。
- **复现验证**：在独立短时间数据集中复现了DTW结果，增加了结论的可靠性。
- **与主观问卷结合**：探讨了客观EEG变异与主观睡眠质量的关系，具有生态效度。

## 8. 不足与局限

- **样本限制**：仅20名健康参与者（年龄19-62岁，平均32岁），缺乏年龄、性别、职业等因素的充分分层，个体间变异的统计推断能力弱，结论外推至临床人群或老年人需谨慎。
- **技术限制**：sqEEG仅有双通道，空间分辨率低，无法分析脑区差异。自动睡眠分期（U-Sleep）存在一定误差，尤其对WASO和N1分期可能不准确。DTW分析仅限前5小时睡眠，未覆盖完整整夜（特别是后期REM富集时段），可能放大或缩小某些变异成分。
- **理论假设的局限性**：将CV分为四个类别（0.1/0.2/0.4阈值）具有主观性，虽然引用了其他领域文献，但缺乏睡眠领域的独立验证。此外，并未直接证明“指标特异性”优于“尺度依赖性”，只是定性观察。
- **相关性分析较弱**：主观睡眠质量仅用1个Likert问题（每天早晨“我的睡眠很好”，1-5级），信度有限；相关效应量小（r<0.3），且未控制混杂因素（如年龄、性别、昼夜节律偏好）。多重比较校正后仍有部分显著，但需谨慎解读。
- **缺乏因果机制**：研究为观察性，无法建立变异与睡眠质量之间的因果关系；也未探讨社会节律、光照、用药等外部因素对变异的影响。
- **开放性问题**：未直接量化“相似性”与“不相似性”的数学关系（如说明20%不相似不等于80%相似），也未与现有睡眠规律性指标（如SRI、IS、社会时差）进行方法比较，新指标的实际增量价值有待验证。

（完）
