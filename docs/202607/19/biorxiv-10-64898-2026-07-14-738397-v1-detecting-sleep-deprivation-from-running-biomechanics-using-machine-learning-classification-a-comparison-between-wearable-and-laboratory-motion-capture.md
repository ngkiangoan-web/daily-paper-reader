---
title: "Detecting Sleep Deprivation from Running Biomechanics Using Machine Learning Classification: A Comparison Between Wearable and Laboratory Motion Capture"
title_zh: 使用机器学习分类从跑步生物力学中检测睡眠剥夺：可穿戴设备与实验室运动捕捉的对比
authors: "Seynaeve, M., Hendrickx, K., Vanwanseele, B., de Beukelaar, T."
date: 2026-07-15
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.14.738397v1.full.pdf"
tags: ["query:sleep-mental"]
score: 7.0
evidence: 利用可穿戴传感器检测睡眠剥夺
tldr: "睡眠剥夺会损害跑步表现并增加损伤风险，但能否通过可穿戴技术检测其生物力学变化尚不清楚。本研究让21名跑者在正常睡眠和完全睡眠剥夺后跑步，同时使用全身运动捕捉和躯干可穿戴传感器提取特征，并用五种机器学习分类器进行分类。个体内分类中，可穿戴传感器和运动捕捉系统的最佳准确率分别达到85%和83%，表明存在个体一致的生物力学特征。而个体间分类准确率接近随机（约50%），凸显了个体基线数据的重要性。该研究证明个体化、基于基线的监测对检测睡眠剥夺相关步态变化至关重要，并指出单个躯干可穿戴传感器在配对记录下具有实际应用潜力。"
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-14-738397-v1/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1782, \"height\": 453, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-14-738397-v1/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1734, \"height\": 769, \"label\": \"Figure\"}]"
tables_json: "[{\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-14-738397-v1/table-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1660, \"height\": 632, \"label\": \"Table\"}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-14-738397-v1/table-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1725, \"height\": 637, \"label\": \"Table\"}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-14-738397-v1/table-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1565, \"height\": 830, \"label\": \"Table\"}]"
motivation: 现有研究在实验室条件下发现睡眠剥夺改变跑步生物力学，但能否用可穿戴技术检测尚不清楚，需验证其在现实监测中的可行性。
method: 21名跑者采用随机交叉设计，在正常睡眠和完全睡眠剥夺后以次最大速度跑步，同时用全身运动捕捉和躯干可穿戴传感器提取生物力学特征，并使用五种机器学习分类器进行个体内和个体间分类。
result: "个体内分类中，可穿戴传感器最佳准确率85%（逻辑回归），运动捕捉系统83%（随机森林）；个体间分类准确率均接近随机（约50%），表明特征存在个体特异性。"
conclusion: 个体化基线监测是检测睡眠剥夺相关步态变化的关键，单个躯干可穿戴传感器在配对记录下可提供实际可行的解决方案。
---

## 摘要
睡眠剥夺与耐力表现下降及跑步相关损伤风险增加有关。先前研究已在实验室条件下发现，单夜睡眠剥夺后跑步生物力学发生改变。然而，这些生物力学变化是否能通过可穿戴技术检测尚不清楚。21名经常参与娱乐性跑步的受试者在随机交叉设计中完成了正常睡眠和完全睡眠剥夺条件下的次最大强度跑步机跑步。使用全身运动捕捉系统和躯干安装的可穿戴传感器同步提取生物力学特征。评估了五种机器学习分类器在两项分类任务中的表现：受试者内任务（使用同一受试者的配对记录）和受试者间任务（无个体基线数据）。受试者内分类中，两种测量系统的准确率均显著高于随机水平，可穿戴传感器（逻辑回归）最佳准确率为85%，运动捕捉系统（随机森林）为83%。这些发现表明，睡眠剥夺会在跑步过程中产生系统性的、个体一致的生物力学特征。相比之下，几乎所有模型和系统在受试者间分类中均失败，准确率接近随机水平（约50%），表明在没有个性化基线数据的情况下，个体间差异掩盖了睡眠剥夺信号。两个系统均一致地将时间组织、负荷相关变量和步幅间变异性识别为最具判别力的特征域。与预期相反，实验室运动捕捉系统并未优于可穿戴传感器。综上，这些发现表明，对于检测跑步步态中与睡眠剥夺相关的变化，基于个体基线的监测至关重要，并提示当存在配对记录时，单个躯干安装的可穿戴传感器可能为现实监测提供实用解决方案。

## Abstract
Sleep deprivation is associated with impaired endurance performance and an increased risk of running-related injury. Previous research has identified alterations in running biomechanics following a single night of sleep deprivation under laboratory conditions. However, whether these biomechanical changes can be detected using wearable technology remains unknown. Twenty-one recreationally active runners completed submaximal treadmill running under both normal sleep and total sleep deprivation conditions in a randomized crossover design. Biomechanical features were extracted simultaneously using a full-body motion capture system and a trunk-mounted wearable sensor. Five machine learning classifiers were evaluated in two classification tasks: a within-subject task using paired recordings from the same individual, and a between-subject task performed without individual baseline data. Within-subject classification consistently exceeded chance level for both measurement systems, with best accuracies of 85% for the wearable sensor (Logistic Regression) and 83% for the motion capture system (Random Forest). These findings indicate that sleep deprivation produces a systematic and individually consistent biomechanical signature during running. In contrast, between-subject classification failed across nearly all models and systems, with accuracies remaining close to chance level ([~]50%), demonstrating that inter-individual variability obscures the sleep-deprivation signal in the absence of personalized baseline data. Both systems converged on temporal organization, loading-related variables, and stride-to-stride variability as the most discriminative feature domains. Contrary to expectations, the laboratory motion capture system did not outperform the wearable sensor. Together, these findings demonstrate that individualized, baseline-referenced monitoring is essential for detecting sleep-deprivation-related changes in running gait, and suggest that a single trunk-mounted wearable sensor may provide a practical solution for real-world monitoring when paired recordings are available.