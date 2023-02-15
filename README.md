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

- 1 [Survey](https://github.com/Unstructured-Data-Community/ANN-Papers#survey)
  - 1.1 [System](https://github.com/Unstructured-Data-Community/ANN-Papers#system)

- 2 [Graph based Index](https://github.com/Unstructured-Data-Community/ANN-Papers#graph-based-index)

  - 2.1 [Query Optimization](https://github.com/Unstructured-Data-Community/ANN-Papers#query-optimization)
  - 2.2 [New hardware acceleration](https://github.com/Unstructured-Data-Community/ANN-Papers#New-hardware-acceleration)
  - 2.3 [kNN-graph](https://github.com/Unstructured-Data-Community/ANN-Papers#kNN-graph)

- 3 [Quantization based Index](https://github.com/Unstructured-Data-Community/ANN-Papers#Quantization-based-index)

  - 3.1 [New hardware acceleraton](https://github.com/Unstructured-Data-Community/ANN-Papers#New-hardware-acceleraton)
  - 3.2 [Query Optimization](https://github.com/Unstructured-Data-Community/ANN-Papers#Query-Optimization)

- 4 [Hash based Index](https://github.com/Unstructured-Data-Community/ANN-Papers#hash-based-index)

  - 4.1 [New hardware adaptation](https://github.com/Unstructured-Data-Community/ANN-Papers#new-hardware-adaptation)
  - 4.2 [Query Optimization](https://github.com/Unstructured-Data-Community/ANN-Papers#Query-Optimization)
  - 4.3 [Learning to Hash(L2H)](https://github.com/Unstructured-Data-Community/ANN-Papers#Learning-to-Hash(L2H))
  
- 5 [Tree based Index](https://github.com/Unstructured-Data-Community/ANN-Papers#tree-based-index)

- 6 [Disk based Index](https://github.com/Unstructured-Data-Community/ANN-Papers#dish-based-index)

## Relevant papers

### 1 Survey [more](./Survey.md)


（必读）[1] **Approximate Nearest Neighbor Search on High Dimensional Data — Experiments, Analyses, and Improvement.** TKDE 2020.[paper](https://arxiv.org/pdf/1610.02455.pdf)

*Wen Li, Ying Zhang , Yifang Sun, Wei Wang, Mingjie Li , Wenjie Zhang , Xuemin Lin*

---

（必读）[2] **New trends in high-D vector similarity search: al-driven, progressive, and distributed** VLDB 2021. [paper](http://vldb.org/pvldb/vol14/p3198-echihabi.pdf)[slid](https://vldb.org/2021/files/slides/tutorial/tutorial5.pdf)

*Karima Echihabi, Kostas Zoumpatianos, Themis Palpanas*

---


#### 1.1 System


待补充

---


### 2 Graph based Index [more](./Graph-based-Index.md)


(必读)[1] **Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchial Navigable Small World Graphs.** HNSW 2020. [paper](https://arxiv.org/pdf/1603.09320.pdf)

*Yu A. Malkov, D. A. Yashunin*

---

[2]（[1]的基础，可作为参考） **Approximate nearest neighbor algorithm based on navigable small world graphs.** Information Systems
Volume 45, September 2014, Pages 61-68. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0306437913001300)

*Yury Malkov, Alexander Ponomarenko, Andrey Logvinov, Vladimir Krylov*

---

（必读）[3] **A Comprehensive Survey and Experimental Comparison of Graph-Based Approximate Nearest Neighbor Search.** VLDB 2022. [paper](https://arxiv.org/pdf/2101.12631v1.pdf)

*Mengzhao Wang, Xiaoliang Xu, Qiang Yue, Yuxiang Wang*

---

（必读）[4] **Fast Approximate Nearest Neighbor Search With The Navigating Spreading-out Graph.** VLDB 2019. [paper](https://arxiv.org/pdf/1707.00143.pdf)

*Cong Fu, Chao Xiang, Changxu Wang, Deng Cai*

---


#### 2.1 Query Optimization


待补充

---


#### 2.2 New hardware acceleration


待补充

---


#### 2.3 kNN-graph


待补充

---


### 3 Quantization based Index [more](./Quantization-based-Index.md)


（必读）[1] **Product Quantization for Nearest Neighbor Search** TPAMI 2019. [paper](https://hal.inria.fr/inria-00514462v2/document)

*Herve J ´ egou, Matthijs Douze, Cordelia Schmid*

---

（必读）[2] **Optimized Product Quantization** TPAMI 2013. [paper](https://ieeexplore.ieee.org/document/6678503)

*Tiezheng Ge, Kaiming He, Qifa Ke, Jian Sun*

---

（必读）[3] **The Inverted Multi-Index** TPAMI 2014. [paper](https://ieeexplore.ieee.org/document/6915715)

*Artem Babenko, Victor Lempitsky*

---

（必读）[4] **Additive Quantization for Extreme Vector Compression** CVPR 2014. [paper](https://ieeexplore.ieee.org/document/6909519/)

*Artem Babenko, Victor Lempitsky*

----

(必读)[5]**Accelerating Large-Scale Inference with Anisotropic Vector Quantization** 	ICML 2020. [paper](https://arxiv.org/pdf/1908.10396.pdf)

*Ruiqi Guo, Philip Sun, Erik Lindgren*

---


#### 3.1 New hardware acceleration


待补充

---


#### 3.2 Query Optimization


待补充

---


### 4 Hash based Index [more](./Hash-based-Index.md)


(必读)[1] **Similarity Search in High Dimensions via Hashing** VLDB 1999. [paper](https://www.vldb.org/conf/1999/P49.pdf)

*Aristides Gionis, Piotr Indyk, Rajeev Motwani*

---

(必读)[2] **SRS: solving c -approximate nearest neighbor queries in high dimensional euclidean space with a tiny index** VLDB 2014. [paper](https://vldb.org/pvldb/vol8/p1-sun.pdf)

*Yifang Sun, Wei Wang, Jianbin Qin, Ying Zhang, Xuemin Lin*

---

(必读)[3] **Locality-Sensitive Hashing Scheme Based on p-Stable Distributions** SCG 2004.[paper](https://dl.acm.org/doi/10.1145/997817.997857)

*Mayur Datar, Nicole Immorlica, Piotr Indyk, Vahab S. Mirrokni*

---

(必读)[4] **Query-aware locality-sensitive hashing for approximate nearest neighbor search** VLDB 2015. [paper](https://dl.acm.org/doi/10.14778/2850469.2850470)

*Qiang Huang, Jianlin Feng, Yikai Zhang*

---


#### 4.1 Hardware adaptation


待补充

---


#### 4.2 Query Optimization


待补充

---



#### 4.3 Learning to Hash (L2H)


待补充


---


### 5 Tree based Index [more](./Tree-based-Index.md)


(必读)[1]**Data Structures and Algorithms for Nearest Neighbor Search in General Metric Spaces** SODA 1993. [paper](https://dl.acm.org/doi/pdf/10.5555/313559.313789)

*Peter N. Yianilos*

---

(必读)[2]**Fast Nearest Neighbor Retrieval for Bregman Divergences** ICML 2008. [paper](https://dl.acm.org/doi/10.1145/1390156.1390171)

*Lawrence Cayton*

---


### 6 Disk based Index [more](./Disk-based-Index.md)


待补充


___
## Contributors

<a href="https://github.com/Unstructured-Data-Community/ANN-Papers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Unstructured-Data-Community/ANN-Papers" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

## LICENSE

[Apache-2.0 license](./LICENSE)

