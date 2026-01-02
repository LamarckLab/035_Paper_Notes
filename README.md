## Machine learning methods accurately predict host specificity of coronaviruses based on spike sequences alone

---

## Metadata

- **Zotero Index**: 073  
- **Journal**: *Biochemical and Biophysical Research Communications*  
- **Impact Factor**: 2.2  
- **Publication Year**: 2020  
- **Reading Date**: 2026-01-02  

---

## Overview

> 仅基于冠状病毒 Spike 蛋白序列，利用机器学习方法准确预测病毒的宿主特异性。

---

## Knowledge Nuggets

- 数据源是[Virus Pathogen Database](https://www.viprbrc.org)
- tSVD(Truncated Singular Value Decomposition，截断奇异值分解)和PCA一样，都用于做降维，但是tSVD不需要做中心化,而且更加适合稀疏矩阵
- 通用的氨基酸缩写有25种，其中20种是标准氨基酸，5种是“歧义/特殊”编码
- 如果对氨基酸序列做one-hot encoding，每一个氨基酸变成25位，全0表示gap
