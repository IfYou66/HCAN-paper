# 结合自注意力与压缩激励网络的桥梁损伤识别

本仓库为论文 **“结合自注意力与压缩激励网络的桥梁损伤识别”** 的代码实现，论文已投稿至 **PCC 2025**。

## 📖 项目简介

- **论文标题**：结合自注意力与压缩激励网络的桥梁损伤识别  

- **投稿会议/期刊**：PCC (2025)  

- **摘要**：  
  > 桥梁是城市交通的重要基础设施，其健康状况直接影响运输的安全；及时且准确的桥梁结构损伤识别，是维持其健康状况的关键。现有针对桥梁损伤识别的研究中，数据驱动方法因其高效、适用性强等优点，已成为主流。现有数据驱动方法在空间特征提取上多依赖卷积神经网络，其固定的卷积核与通道权重难以动态调整；在长程依赖建模上则采用注意力机制，但其计算量随序列长度呈指数级增长，难以兼顾效率与精度。因此，本文提出一种混合模型（Hybrid Convolutional Attention Network，HCAN）。针对现有方法难以自适应调整通道权重，HCAN整合多核卷积与压缩激励网络，以强化局部特征提取、动态调整通道权重，强化关键信息的表征能力；同时使用双重位置编码的轻量级自注意力，高效捕获长程依赖；最后通过时空融合模块将两路特征联合映射为损伤状态。为验证HCAN模型的有效性，本文在两个真实桥梁数据集上进行实证研究。实验结果表明，对比7个基线模型，HCAN识别效果提升显著，如在准确率和F1指标上至少提升了2个百分点。

## 🔧 数据集

### 官方数据集地址

#### Vänersborg数据集：[Dataset from structural health monitoring of a steel bridge in Sweden](https://zenodo.org/records/8300495)

#### Hell数据集：[A data-based structural health monitoring approach for damage detection in steel bridges using experimental data | Journal of Civil Structural Health Monitoring](https://link.springer.com/article/10.1007/s13349-021-00530-8)