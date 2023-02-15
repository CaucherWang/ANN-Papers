# ANN-Papers

<div align="center">
<img border="0" src="https://camo.githubusercontent.com/54fdbe8888c0a75717d7939b42f3d744b77483b0/687474703a2f2f6a617977636a6c6f76652e6769746875622e696f2f73622f69636f2f617765736f6d652e737667" />
<img border="0" src="https://camo.githubusercontent.com/1ef04f27611ff643eb57eb87cc0f1204d7a6a14d/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d254630253946253843253946266d6573736167653d496625323055736566756c267374796c653d7374796c653d666c617426636f6c6f723d424334453939" />
<a href="https://github.com/Unstructured-Data-Community/ANN-Papers/issues">     <img border="0" src="https://img.shields.io/github/issues/Unstructured-Data-Community/ANN-Papers" /> </a>
<a href="https://github.com/Unstructured-Data-Community/ANN-Papers/network/members">     <img border="0" src="https://img.shields.io/github/forks/Unstructured-Data-Community/ANN-Papers" /> </a>
<a href="https://github.comUnstructured-Data-Community/ANN-Papers/stargazers">     <img border="0" src="https://img.shields.io/github/stars/Unstructured-Data-Community/ANN-Papers" /> </a>
</div>

# Introduction

The project is a collection of recent research in areas such as ANN(Approximate Nearest Neighbor) and Vector Database, including research reports, academic papers and datasets etc.

**We also hold regular paper readings together, so feel free to share your ideas. [link](https://github.com/Unstructured-Data-Community/talk/blob/main/paper-reading.md)**

该项目收集了ANN（近似近邻搜索）和向量数据库等领域的最新研究，包括研究报告、学术论文和数据集等。

**我们还会定期举办论文共读活动，欢迎共同交流。[链接](https://github.com/Unstructured-Data-Community/talk/blob/main/paper-reading.md)**

# Contribution

Contributions are always welcome! Make an individual pull request for each suggestion.

# Paper Reading Togeter 🥰
[paper reading list](https://github.com/Unstructured-Data-Community/talk/blob/main/paper-reading.md)

# Content

- 2 [Graph based Index](https://github.com/Unstructured-Data-Community/ANN-Papers#graph-based-index)

  - 2.1 [Query Optimization](https://github.com/Unstructured-Data-Community/ANN-Papers#query-optimization)
  - 2.2 [New hardware acceleration](https://github.com/Unstructured-Data-Community/ANN-Papers#New-hardware-acceleration)
  - 2.3 [kNN-graph](https://github.com/Unstructured-Data-Community/ANN-Papers#kNN-graph)

## Relevant papers

### 2 Graph based Index


(必读)[1] **Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchial Navigable Small World Graphs** HNSW 2020. [paper](https://arxiv.org/pdf/1603.09320.pdf)

*Yu A. Malkov, D. A. Yashunin*

---

[2]（[1]的基础，可作为参考） **Approximate nearest neighbor algorithm based on navigable small world graphs** Information Systems
Volume 45, September 2014, Pages 61-68. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0306437913001300)

*Yury Malkov, Alexander Ponomarenko, Andrey Logvinov, Vladimir Krylov*

---

(必读)[3] **A Comprehensive Survey and Experimental Comparison of Graph-Based Approximate Nearest Neighbor Search** VLDB 2022. [paper](https://arxiv.org/pdf/2101.12631v1.pdf)

*Mengzhao Wang, Xiaoliang Xu, Qiang Yue, Yuxiang Wang*

---

(必读)[4] **Fast Approximate Nearest Neighbor Search With The Navigating Spreading-out Graph** VLDB 2019. [paper](https://arxiv.org/pdf/1707.00143.pdf)

*Cong Fu, Chao Xiang, Changxu Wang, Deng Cai*

---

[5] **HVS: Hierarchical Graph Structure Based on Voronoi Diagrams for Solving Approximate Nearest Neighbor Search** VLDB 2022. [paper](http://www.vldb.org/pvldb/vol15/p246-lu.pdf)

*K Lu, M Kudo, C Xiao, Y Ishikawa*

---

[6] **High Dimensional Similarity Search with Satellite System Graph: Efficiency, Scalability, and Unindexed Query Compatibility** TPAMI 2021. [paper](https://arxiv.org/pdf/1907.06146.pdf)

*Fu, C., Wang, C. and Cai, D*

---

[7] **DiskANN: Fast Accurate Billion-point Nearest Neighbor Search on a Single Node** NIPS 2019. [paper](https://dl.acm.org/doi/pdf/10.5555/3454287.3455520)

*Suhas Jayaram Subramanya, Devvrit, Rohan Kadekodi, Ravishankar Krishaswamy, Harsha Vardhan Simhadri*

---

[8] **FreshDiskANN: A Fast and Accurate Graph-Based ANN Index for Streaming Similarity Search** arXiv 2021. [paper](https://arxiv.org/pdf/2105.09613.pdf)

*Singh, A., Subramanya, S.J., Krishnaswamy, R. and Simhadri, H.V.*

---

[9] **EFANNA : An Extremely Fast Approximate Nearest Neighbor Search Algorithm Based on kNN Graph** arXiv 2016. [paper](https://arxiv.org/pdf/1609.07228.pdf)

*Fu, C. and Cai, D.*

---

[10] **FANNG: Fast Approximate Nearest Neighbour Graphs** CVPR 2016. [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Harwood_FANNG_Fast_Approximate_CVPR_2016_paper.pdf)

*Ben Harwood and Tom Drummond*

---

[11] **Graph-based Nearest Neighbor Search: From Practice to Theory** ICML 2020. [paper](https://arxiv.org/pdf/1907.00845.pdf)

*Liudmila Prokhorenkova, Aleksandr Shekhovtsov*

---

[12] **GraSP: Optimizing Graph-based Nearest Neighbor Search with Subgraph Sampling and Pruning** WSDM 2022. [paper](https://dl.acm.org/doi/abs/10.1145/3488560.3498425)

*Minjia Zhang, Wenhan Wang, Yuxiong He*

---

[14]（small-world溯源，可参考） **The small-world phenomenon: an algorithmic perspective** STOC 2000. [paper](https://dl.acm.org/doi/pdf/10.1145/335305.335325)

*Jon Kleinberg*

---


#### 2.1 Query Optimization


[1] **Learning-based query optimization for multi-probe approximate nearest neighbor search** VLDB 2022. [paper](https://link.springer.com/content/pdf/10.1007/s00778-022-00762-0.pdf)

*Pengcheng Zhang, Bin Yao, Chao Gao, Bin Wu, Xiao He, Feifei Li, Yuanfei Lu, Chaoqun Zhan & Feilong Tang *

---

[2] **Learning Space Partitions for Nearest Neighbor Search** ICLR 2020. [paper](https://arxiv.org/pdf/1901.08544.pdf)

*Yihe Dong, Piotr Indyk, Ilya Razenshteyn, Tal Wagner*

---

[3] **Improving approximate nearest neighbor search through learned adaptive early termination** SIGMOD 2020. [paper](https://dl.acm.org/doi/pdf/10.1145/3318464.3380600)

*C Li, M Zhang, DG Andersen, Y He*

---

[4] **HQANN: Efficient and Robust Similarity Search for Hybrid Queries with Structured and Unstructured Constraints** CIKM '22: Proceedings of the 31st ACM International Conference on Information & Knowledge ManagementOctober 2022. [paper](https://arxiv.org/pdf/2207.07940.pdf)

*Wei Wu, Junlin He, Yu Qiao, Guoheng Fu, Li Liu, Jin Yu*

---

[5] **AUTOMATING NEAREST NEIGHBOR SEARCH CONFIGURATION WITH CONSTRAINED OPTIMIZATION** arXiv. [paper](https://arxiv.org/pdf/2301.01702.pdf)

*Philip Sun, Ruiqi Guo, Sanjiv Kumar*

---

[6] **Learning to Route in Similarity Graphs** ICML 2019. [paper](https://arxiv.org/pdf/1905.10987.pdf)

*Dmitry Baranchuk, Dmitry Persiyanov, Anton Sinitsin, Artem Babenko*

---


#### 2.2 New hardware acceleration


[1] **GPU-accelerated Proximity Graph Approximate Nearest Neighbor Search and Construction** ICDE 2022. [paper](https://ieeexplore.ieee.org/document/9835618)

*Yu, Y., Wen, D., Zhang, Y., Qin, L., Zhang, W. and Lin, X.*

---

[2] **HM-ANN: Efficient Billion-Point Nearest Neighbor Search on Heterogeneous Memory** CIKM 2020. [paper](https://proceedings.neurips.cc/paper/2020/file/788d986905533aba051261497ecffcbb-Paper.pdf)

*Jie Ren, Minjia Zhang, Dong Li*

---

[3] **SONG: Approximate Nearest Neighbor Search on GPU** ICDE 2020. [paper](http://research.baidu.com/Public/uploads/5f5c37aa9c37c.pdf)

*Weijie Zhao, Shulong Tan, Ping Li*

---

[4] **GRIP: Multi-Store Capacity-Optimized High-Performance Nearest Neighbor Search for Vector Search Engine** CIKM 2019. [paper](https://openreview.net/pdf/c148d2307c45c6de6f4f766d14a587efd6bf1d4a.pdf)

*Minjia Zhang,Yuxiong He*

---


#### 2.3 kNN-graph


[1] **Efficient k-nearest neighbor graph construction for generic similarity measures** WWW 2011. [paper](https://www.cs.princeton.edu/cass/papers/www11.pdf)

*Dong, W., Moses, C. and Li, K*

---

[2] **Fast Approximate Nearest-Neighbor Search with k-Nearest Neighbor Graph** IJCAI 2011. [paper](https://www.ijcai.org/Proceedings/11/Papers/222.pdf)

*Kiana Hajebi and Yasin Abbasi-Yadkori and Hossein Shahbazi and Hong Zhang*

---

[3] **Scalable k-NN graph construction for visual descriptors** CVPR 2012. [paper](https://pages.ucsd.edu/~ztu/publication/cvpr12_knnG.pdf)

*Jing Wang; Jingdong Wang; Gang Zeng; Zhuowen Tu; Rui Gan; Shipeng Li*

---


持续更新中……


## Contributors

<a href="https://github.com/Unstructured-Data-Community/ANN-Papers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Unstructured-Data-Community/ANN-Papers" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

## LICENSE

[Apache-2.0 license](./LICENSE)

