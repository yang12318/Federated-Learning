## README

### 总览

#### 《中国计算机学会推荐国际学术会议和期刊目录-2019》

- 英文期刊与会议的CCF评级列表，以后查论文等级可以通过这个PDF查询。

### 传统联邦学习

#### 《Communication-Efficient Learning of Deep Networksfrom Decentralized Data》

- 2017年AISTATS（CCF C）的论文，联邦学习的开山之作;
- 提出了最经典的FedAvg算法。

#### 《Federated Optimization in Heterogeneous Networks》

- 2020年MLSys（业界大牛联合创办）的论文；
- 提出了FedProx算法，以添加正则项的思路来优化FedAvg。

#### 《Model-Contrastive Federated Learning》

- 2021年CVPR（CCF A）的论文；
- 提出了MOON算法，利用对比学习来优化FedAvg。

### 个性化联邦学习

#### 《Towards Personalized Federated Learning》

- 2022年TNNLS（CCF B）的论文；
- 个性化联邦学习的综述。

#### 《Think Locally, Act Globally: Federated Learning with Local and Global Representations》

- 2019年NIPS（CCF A）的论文；
- 提出了LG-FedAvg算法，共享全连接层。

#### 《Exploiting Shared Representations for Personalized Federated Learning》

- 2021年ICML（CCF A）的论文；
- 提出了FedRep算法，共享除全连接层以外部分。

#### 《Ditto: Fair and Robust Federated Learning Through Personalization》

- 2021年ICML（CCF A）的论文；
- 提出了Ditto算法，引入正则项平衡公平性和鲁棒性要求。

#### 《FedProto: Federated Prototype Learning across Heterogeneous Clients》

- 2022年AAAI（CCF A）的论文；
- 提出了FedProto算法，是小样本联邦学习。

### 联邦学习防御

#### 《Byzantine-Robust Distributed Learning: Towards Optimal Statistical Rates》

- 2018年ICML（CCF A）的论文；
- 一些基础的后门攻击防御方法。

#### 《The Limitations of Federated Learning in Sybil Settings》

- 2020年RAID（CCF B）的论文；
- 提出了FoolsGold算法，使用余弦相似度测量更新之间的角度距离。

#### 《Robust Federated Learning with Attack-Adaptive Aggregation》

- 2021年IJCAI（CCF A）的论文；
- 利用QKV向量计算余弦相似度。

#### 《Defending against Backdoors in Federated Learning with Robust Learning Rate》

- 2021年AAAI（CCF A）的论文；
- 提出了RLR算法，根据梯度符号来调整客户端学习率。

#### 《Secure Partial Aggregation: Making Federated Learning More Robust for Industry 4.0 Applications》

- 2022年T IND INFORM（SCI 1区）的论文；
- 提出了PartFedAvg算法，限制参数上传比例。

### 联邦学习攻击

#### 《How To Backdoor Federated Learning》

- 2020年PMLR（机器学习顶刊，不在CCF列表）的论文；
- 首个针对模型投毒的联邦学习后门攻击。

#### 《Attack of the Tails: Yes, You Really Can Backdoor Federated》

- 2020年NIPS（CCF A）的论文；
- 提出了基于边界情况的各种后门攻击。

