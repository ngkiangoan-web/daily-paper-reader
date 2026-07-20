---
title: "Quantifying Physiological Synchrony through Windowed Cross-Correlation Analysis: Statistical and Theoretical Considerations"
title_zh: 通过窗口互相关分析量化生理同步：统计与理论考量
authors: "Behrens, F., Diana, F., Moulder, R. G., Boker, S. M., Kret, M."
date: 2026-07-17
pdf: "https://www.biorxiv.org/content/10.1101/2020.08.27.269746v2.full.pdf"
tags: ["query:sleep-mental"]
score: 6.0
evidence: 窗口互相关分析方法适用于临床研究中的动态评估时间序列数据
tldr: 人际同步研究常用滑动窗口互相关分析，但参数选择缺乏依据。本研究以心率、皮肤电等生理信号为对象，系统评估窗口大小和最大延迟对区分真实同步与伪同步、以及敏感检测条件差异的影响。结果发现小窗口能更好区分同步，延迟影响较小。结合生理边界提供参数优化建议，为后续研究提供参考。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1621, \"height\": 976, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1736, \"height\": 948, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/fig-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1609, \"height\": 1325, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/fig-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1563, \"height\": 1426, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/fig-005.webp\", \"caption\": \"\", \"page\": 0, \"index\": 5, \"width\": 1562, \"height\": 1174, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/fig-006.webp\", \"caption\": \"\", \"page\": 0, \"index\": 6, \"width\": 1562, \"height\": 1437, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/fig-007.webp\", \"caption\": \"\", \"page\": 0, \"index\": 7, \"width\": 1558, \"height\": 1155, \"label\": \"Figure\"}]"
tables_json: "[{\"url\": \"assets/tables/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/table-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1144, \"height\": 541, \"label\": \"Table\"}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-1101-2020-08-27-269746-v2/table-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1731, \"height\": 667, \"label\": \"Table\"}]"
motivation: 滑动窗口互相关分析广泛用于量化生理同步，但参数设置缺乏指导，影响结果可靠性。
method: 系统对比不同窗口大小与最大延迟，基于替代数据分析和组内条件差异检验，在四种生理信号上评估。
result: 小窗口有效区分同步与伪同步；最大延迟影响有限；检测条件差异无显著模式。
conclusion: 建议根据信号生理特性选择较小窗口，确保结果稳健。
---

## 摘要
人际同步是一个广泛研究的现象。一个巨大挑战是如何在统计上捕捉具有波动同步水平和个体反应之间不同延迟的社会交互动态。窗口互相关分析通过将时间序列分割成较小窗口，并将两个交互个体的片段相互偏移至最大滞后，同时考虑了这两个特征。尽管有证据表明这些参数会影响估计的同步水平，但关于使用哪些参数配置的指导仍缺乏。本研究旨在通过比较不同参数配置对两个结果标准的影响来缩小这一知识差距：（1）通过替代数据分析区分同步与伪同步的能力，以及（2）通过两个受试者内条件之间的差异测量的检测同步变化的灵敏度。聚焦于生理同步，我们对心率、皮肤电导水平、瞳孔大小和面部表情数据进行了这些分析。结果显示，一系列参数能够区分同步与伪同步。窗口大小比最大滞后更具影响力，较小的窗口大小显示出更好的区分能力。第二个标准没有出现清晰的模式。结合统计发现以及关于信号生理特性和生物边界的理论考量，我们为针对感兴趣信号优化参数设置提供了建议。

## Abstract
Interpersonal synchrony is a widely studied phenomenon. A great challenge is to statistically capture the dynamics of social interactions with fluctuating levels of synchrony and varying delays between responses of individuals. Windowed Cross-Correlation analysis accounts for both characteristics by segmenting the time series into smaller windows and shifting the segments of two interacting individuals away from each other up to a maximum lag. Despite evidence showing that these parameters affect the estimated synchrony level, there is a lack of guidelines on which parameter configurations to use. The current study aimed to close this knowledge gap by comparing the effect of different parameter configurations on two outcome criteria: (1) the ability to distinguish synchrony from pseudosynchrony by means of surrogate data analyses, and (2) the sensitivity to detect change in synchrony as measured by the difference between two within-subject conditions. Focusing on physiological synchrony, we performed these analyses on heartrate, skin conductance level, pupil size, and facial expressions data. Results revealed that a range of parameters was able to discriminate synchrony from pseudosynchrony. Window size was more influential than the maximum lag with smaller window sizes showing better discrimination. No clear patterns emerged for the second criterion. Integrating the statistical findings and theoretical considerations regarding the physiological characteristics and biological boundaries of the signals, we provide recommendations for optimizing the parameter settings to the signal of interest.