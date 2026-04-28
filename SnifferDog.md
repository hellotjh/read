# SnifferDog: Comprehensively Learning Heterogeneous Features of Network Traffic to Identify Malicious Flows

## 基本信息
- 类型：研究论文
- 作者：Luo, Xi and Yin, Lihua and Yang, Hongyu and Liu, Zeyan and Chen, Weizhe and Jia, Shijie and Luo, Bo and Xiang, Hongli
- 会议/期刊：IEEE Transactions on Information Forensics and Security (TIFS), Vol. 20
- 年份：2025
- CCF等级：A
- DOI:
  10.1109/TIFS.2025.3620640(代码与数据：https://github.com/ciat-gzhu/SnifferDog)

## 摘要
深度学习近年来在网络入侵检测领域引起了广泛关注。尽管已取得大量优进展，但以往的研究难以全面学习网络流量流的特征，导致在不同环境和攻击场景下的性能表现不一致。
为解决这些局限，本研究提出SniferDog——一种新型网络攻击检测系统，该系统以原始数据包为输入，理性提取并整合数据包、流量及拓扑结构中的异构特征。
系统同步对数据包和流量进行格式化处理，以实现特征学习的高层次整合；随后开发了一个由 LSTM 层、自注意力层和交叉注意力层组成的流量预训练模型，
用于学习序列性和非序列性的数据包间关系特征作为初始流量向量；最后通过节点间和节点到边的注意力层，增强归纳式GNN模型，动态将流量间及流量与拓扑结构的关系特征嵌入流量向量中。
生成的流量向量包含了数据包间、流间以及流与拓扑结构之间的全面信息，从而实现了高效的检测性能。基于来自不同环境的八个数据集进行的实验室实验表明，SniferDog的优效优于现有解决方案。
部署在本研究所网络中的可扩展原型系统误报率仅为0.08%，验证了SniferDog在实际应用场景中的实用性。

