---
title: Quantum machine learning for detection of sleep deprivation from EEG signals
title_zh: 量子机器学习用于从脑电图信号检测睡眠剥夺
authors: "Sarma-Sarkar, P., Saini, R., Roy, P. P."
date: 2026-06-18
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.14.732153v1.full.pdf"
tags: ["query:sleep-mental"]
score: 7.0
evidence: 使用脑电图检测睡眠剥夺，直接适用于睡眠质量评估
tldr: "睡眠剥夺影响半数印度人口，EEG可客观捕捉神经变化。本研究采用量子支持向量机和混合量子神经网络，提取频谱、Hjorth参数和功能连接特征并编码为量子核进行分类。混合量子神经网络在epoch级和subject级分别达到96.88%和81.25%准确率，均超越此前结果，展现了量子机器学习在EEG睡眠剥夺检测中的竞争力。"
source: biorxiv
selection_source: fresh_fetch
motivation: 睡眠剥夺普遍影响认知与健康，亟需自动检测方法；量子机器学习有望提升EEG分类性能。
method: 提取频谱、Hjorth参数及功能连接特征，编码为量子态构建核，使用QSVM和HQNN分类。
result: "HQNN epoch级准确率96.88%，subject级81.25%；QSVM分别为93.75%和75.00%。"
conclusion: 量子机器学习是EEG睡眠剥夺检测的有效方法，具实际生物医学应用潜力。
---

## 摘要
据估计，印度约50%的人口经历过睡眠相关障碍。睡眠剥夺是一种常见疾病，对认知表现、神经功能和整体健康产生不利影响。脑电图（EEG）提供了一种客观捕捉与睡眠缺失相关的神经变化的手段，因此非常适用于自动检测框架。在本研究中，我们探索了量子支持向量机和混合量子神经网络在使用静息态脑电图信号对睡眠剥夺与休息充分状态进行分类中的应用。采用全面的特征提取流程，包括频谱带功率、频带比值、Hjorth参数和功能连接性度量。这些特征随后被编码为量子态以构建量子核，进而用于分类。模型性能在试次级别和受试者级别的数据划分方案下进行评估。混合量子神经网络（HQNN）在两种评估设置下均取得了最高性能，试次级别准确率达到96.88%，受试者级别准确率达到81.25%。QSVM模型在试次级别和受试者级别评估中分别达到93.75%和75.00%的准确率。在受试者级别和试次级别评估中，HQNN的性能优于先前报道的结果（68.23%和95.72%）。总体而言，这些发现凸显了量子机器学习作为基于EEG的睡眠剥夺检测的一种有竞争力方法的潜力，对现实世界的生物医学应用具有 promising 的启示。

## Abstract
Approximately 50% of the population in India is estimated to experience sleep-related disorders. Sleep deprivation is a prevalent condition that adversely impacts cognitive performance, neural functioning, and overall health. Electroencephalography (EEG) offers an objective means of capturing neural alterations associated with sleep loss, making it well-suited for automated detection frameworks. In this study, we explore the application of a Quantum Support Vector Machine and Hybrid Quantum Neural Networks to classify sleep-deprived and well-rested states using resting-state EEG signals. A comprehensive feature extraction pipeline is employed, incorporating spectral band power, band ratios, Hjorth parameters, and functional connectivity measures. These features are subsequently encoded into quantum states to construct a quantum kernel, which is then utilized for classification. Model performance is evaluated under both epoch-level and subject-level data partitioning schemes. The Hybrid Quantum Neural Network (HQNN) achieves the highest performance across both evaluation settings, attaining an accuracy of 96.88% at the epoch level and 81.25% at the subject level. The QSVM model achieves accuracies of 93.75% and 75.00% for epoch-level and subject-level evaluations, respectively. At subject-level and epoch-level evaluation, HQNN outperforms previously reported results (68.23% and 95.72%). Overall, these findings highlight the potential of quantum machine learning as a competitive approach for EEG-based sleep deprivation detection, with promising implications for real-world biomedical applications.