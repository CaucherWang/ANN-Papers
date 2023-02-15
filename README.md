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

### 1 Survey


（必读）[1] **Approximate Nearest Neighbor Search on High Dimensional Data — Experiments, Analyses, and Improvement.** TKDE 2020.[paper](https://arxiv.org/pdf/1610.02455.pdf)

*Wen Li, Ying Zhang , Yifang Sun, Wei Wang, Mingjie Li , Wenjie Zhang , Xuemin Lin*

---

（必读）[2] **New trends in high-D vector similarity search: al-driven, progressive, and distributed** VLDB 2021. [paper](http://vldb.org/pvldb/vol14/p3198-echihabi.pdf)[slid](https://vldb.org/2021/files/slides/tutorial/tutorial5.pdf)

*Karima Echihabi, Kostas Zoumpatianos, Themis Palpanas*

---

[3] **A Comprehensive Survey and Experimental Comparison of Graph-Based Approximate Nearest Neighbor Search.** VLDB 2022. [paper](https://arxiv.org/pdf/2101.12631v1.pdf)

*Mengzhao Wang, Xiaoliang Xu, Qiang Yue, Yuxiang Wang*

---

[4] **Survey on KNN Methods in Data Science**LNCS 2023. [paper](https://link.springer.com/chapter/10.1007/978-3-031-24866-5_28)

*Panos K. Syriopoulos, Sotiris B. Kotsiantis & Michael N. Vrahatis*

---


#### 1.1 System


[1] **Manu: A Cloud Native Vector Database Management System.** VLDB 2022. [paper](https://arxiv.org/pdf/2101.12631v1.pdf)

*Rentong Guo, Xiaofan Luan, Long Xiang, and so on*

---

[2] **LANNS: a web-scale approximate nearest neighbor lookup system** VLDB 2021. [paper](https://arxiv.org/pdf/2010.09426.pdf)

*Ishita Doshi, Dhritiman Das, Ashish Bhutani, Rajeev Kumar, Rushi Bhatt, Niranjan Balasubramanian*

---

[3] **ANNA: Specialized Architecture for Approximate Nearest Neighbor Search** HPCA 2022. [paper](https://ieeexplore.ieee.org/document/9773206)

*Yejin Lee; Hyunji Choi; Sunhong Min; Hyunseung Lee; Sangwon Beak; Dawoon Jeong; Jae W. Lee; Tae Jun Ham*

---


### 2 Graph based Index


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

[5] **HVS: Hierarchical Graph Structure Based on Voronoi Diagrams for Solving Approximate Nearest Neighbor Search.** VLDB 2022. [paper](http://www.vldb.org/pvldb/vol15/p246-lu.pdf)

*K Lu, M Kudo, C Xiao, Y Ishikawa*

---

[6] **High Dimensional Similarity Search with Satellite System Graph: Efficiency, Scalability, and Unindexed Query Compatibility.** TPAMI 2021. [paper](https://arxiv.org/pdf/1907.06146.pdf)

*Fu, C., Wang, C. and Cai, D*

---

[7] **DiskANN: Fast Accurate Billion-point Nearest Neighbor Search on a Single Node.** NIPS 2019. [paper](https://dl.acm.org/doi/pdf/10.5555/3454287.3455520)

*Suhas Jayaram Subramanya, Devvrit, Rohan Kadekodi, Ravishankar Krishaswamy, Harsha Vardhan Simhadri*

---

[8] **FreshDiskANN: A Fast and Accurate Graph-Based ANN Index for Streaming Similarity Search.** *arXiv* 2021. [paper](https://arxiv.org/pdf/2105.09613.pdf)

*Singh, A., Subramanya, S.J., Krishnaswamy, R. and Simhadri, H.V.*

---

[9] **EFANNA : An Extremely Fast Approximate Nearest Neighbor Search Algorithm Based on kNN Graph.** arXiv 2016. [paper](https://arxiv.org/pdf/1609.07228.pdf)

*Fu, C. and Cai, D.*

---

[10] **FANNG: Fast Approximate Nearest Neighbour Graphs.** CVPR 2016. [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Harwood_FANNG_Fast_Approximate_CVPR_2016_paper.pdf)

*Ben Harwood and Tom Drummond*

---

[11] **Graph-based Nearest Neighbor Search: From Practice to Theory.** ICML 2020. [paper](https://arxiv.org/pdf/1907.00845.pdf)

*Liudmila Prokhorenkova, Aleksandr Shekhovtsov*

---

[12] **GraSP: Optimizing Graph-based Nearest Neighbor Search with Subgraph Sampling and Pruning** WSDM 2022. [paper](https://dl.acm.org/doi/abs/10.1145/3488560.3498425)

*Minjia Zhang, Wenhan Wang, Yuxiong He*

---

(small-world溯源，可参考)[14] **The small-world phenomenon: an algorithmic perspective** STOC 2000. [paper](https://dl.acm.org/doi/pdf/10.1145/335305.335325)

*Jon Kleinberg*

---


#### 2.1 Query Optimization


[1] **Learning-based query optimization for multi-probe approximate nearest neighbor search.** VLDB 2022. [paper](https://link.springer.com/content/pdf/10.1007/s00778-022-00762-0.pdf)

*Pengcheng Zhang, Bin Yao, Chao Gao, Bin Wu, Xiao He, Feifei Li, Yuanfei Lu, Chaoqun Zhan & Feilong Tang *

---

[2] **Learning Space Partitions for Nearest Neighbor Search.** ICLR 2020. [paper](https://arxiv.org/pdf/1901.08544.pdf)

*Yihe Dong, Piotr Indyk, Ilya Razenshteyn, Tal Wagner*

---

[3] **Improving approximate nearest neighbor search through learned adaptive early termination.** SIGMOD 2020. [paper](https://dl.acm.org/doi/pdf/10.1145/3318464.3380600)

*C Li, M Zhang, DG Andersen, Y He*

---

[4] **HQANN: Efficient and Robust Similarity Search for Hybrid Queries with Structured and Unstructured Constraints.** CIKM '22: Proceedings of the 31st ACM International Conference on Information & Knowledge ManagementOctober 2022. [paper](https://arxiv.org/pdf/2207.07940.pdf)

*Wei Wu, Junlin He, Yu Qiao, Guoheng Fu, Li Liu, Jin Yu*

---

[5] **AUTOMATING NEAREST NEIGHBOR SEARCH CONFIGURATION WITH CONSTRAINED OPTIMIZATION.** arXiv. [paper](https://arxiv.org/pdf/2301.01702.pdf)

*Philip Sun, Ruiqi Guo, Sanjiv Kumar*

---

[6] **Learning to Route in Similarity Graphs. ** ICML 2019. [paper](https://arxiv.org/pdf/1905.10987.pdf)

*Dmitry Baranchuk, Dmitry Persiyanov, Anton Sinitsin, Artem Babenko*

---


#### 2.2 New hardware acceleration


[1]**GPU-accelerated Proximity Graph Approximate Nearest Neighbor Search and Construction.** ICDE 2022. [paper](https://ieeexplore.ieee.org/document/9835618)

*Yu, Y., Wen, D., Zhang, Y., Qin, L., Zhang, W. and Lin, X.*

---

[2]**HM-ANN: Efficient Billion-Point Nearest Neighbor Search on Heterogeneous Memory** CIKM 2020. [paper](https://proceedings.neurips.cc/paper/2020/file/788d986905533aba051261497ecffcbb-Paper.pdf)

*Jie Ren, Minjia Zhang, Dong Li*

---

[3]**SONG: Approximate Nearest Neighbor Search on GPU** ICDE 2020. [paper](http://research.baidu.com/Public/uploads/5f5c37aa9c37c.pdf)

*Weijie Zhao, Shulong Tan, Ping Li*

---

[4]**GRIP: Multi-Store Capacity-Optimized High-Performance Nearest Neighbor Search for Vector Search Engine** CIKM 2019. [paper](https://openreview.net/pdf/c148d2307c45c6de6f4f766d14a587efd6bf1d4a.pdf)

*Minjia Zhang,Yuxiong He*

---


#### 2.3 kNN-graph


[1] **Efficient k-nearest neighbor graph construction for generic similarity measures.** WWW 2011. [paper](https://www.cs.princeton.edu/cass/papers/www11.pdf)

*Dong, W., Moses, C. and Li, K*

---

[2] **Fast Approximate Nearest-Neighbor Search with k-Nearest Neighbor Graph.** IJCAI 2011. [paper](https://www.ijcai.org/Proceedings/11/Papers/222.pdf)

*Kiana Hajebi and Yasin Abbasi-Yadkori and Hossein Shahbazi and Hong Zhang*

---

[3] **Scalable k-NN graph construction for visual descriptors.** CVPR 2012. [paper](https://pages.ucsd.edu/~ztu/publication/cvpr12_knnG.pdf)

*Jing Wang; Jingdong Wang; Gang Zeng; Zhuowen Tu; Rui Gan; Shipeng Li*

---


### 3 Quantization based Index


（必读）[1] **Product Quantization for Nearest Neighbor Search** TPAMI 2019. [paper](https://hal.inria.fr/inria-00514462v2/document)

*Herve J ´ egou, Matthijs Douze, Cordelia Schmid*

---

（必读）[2] **Optimized Product Quantization** TPAMI 2013. [paper](https://ieeexplore.ieee.org/document/6678503)

*Tiezheng Ge, Kaiming He, Qifa Ke, Jian Sun*

---

（必读）[3] **The Inverted Multi-Index** TPAMI 2014. [paper](https://ieeexplore.ieee.org/document/6915715)

*Artem Babenko, Victor Lempitsky*

---

[4] **Composite Quantization** TPAMI 2017. [paper](https://arxiv.org/pdf/1712.00955.pdf)

*Jingdong Wang, Ting Zhang*

---

[5] **DeltaPQ: lossless product quantization code compression for high dimensional similarity search** VLDB 2020. [paper](https://dl.acm.org/doi/10.14778/3424573.3424580)

*Runhui Wang, Dong Deng*

---

[6] **Online Product Quantization** TKDE 2017. [paper](https://arxiv.org/pdf/1711.10775.pdf)

*Donna Xu, Ivor W. Tsang, Ying Zhang*

---

[7] **Online Optimized Product Quantization** ICDM 2020. [paper](https://arxiv.org/pdf/1711.10775.pdf)

*Donna Xu, Ivor W. Tsang, Ying Zhang*

---

（必读）[8] **Additive Quantization for Extreme Vector Compression** CVPR 2014. [paper](https://ieeexplore.ieee.org/document/6909519/)

*Artem Babenko, Victor Lempitsky*

----

[9] **Revisiting Additive Quantization** ECCV 2016. [paper](https://una-dinosauria.github.io/papers/eccv16.pdf)

*Julieta Martinez, Joris Clement, Holger H. Hoos & James J. Little*

---

[10] **Online Additive Quantization** KDD 2021. [paper](https://dl.acm.org/doi/10.1145/3447548.3467441)

*Qi Liu, Jin Zhang, Defu Lian, Yong Ge, Jianhui Ma, Enhong Chen*

---

[11] **Tree Quantization for Large-Scale Similarity Search and Classification** CVPR 2015. [paper](https://ieeexplore.ieee.org/document/7299052)

*Artem Babenko, Victor Lempitsky*

---

[12] **Link and code: Fast indexing with graphs and compact regression codes** CVPR 2018. [paper](https://arxiv.org/pdf/1804.09996.pdf)

*Matthijs Douze, Alexandre Sablayrolles, Hervé Jégou*

---

[13] **Locally Optimized Product Quantization for Approximate Nearest Neighbor Search** CVPR 2014. [paper](https://ieeexplore.ieee.org/document/6909695)

*Yannis Kalantidis, Yannis Avrithis*

---

[14] **LSQ++: Lower running time and higher recall in multi-codebook quantization** ECCV 2018. [paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Julieta_Martinez_LSQ_lower_runtime_ECCV_2018_paper.pdf)

*Julieta Martinez, Shobhit Zakhmi, Holger H. Hoos & James J. Little*

---

[15] **PQk-means: Billion-scale Clustering for Product-quantized Codes** MM 2017. [paper](http://export.arxiv.org/pdf/1709.03708)

*Yusuke Matsui, Keisuke Ogaki, Toshihiko Yamasaki, Kiyoharu Aizawa*

---

[16] **Scalable Image Retrieval by Sparse Product Quantization** TMM 2015. [paper](https://arxiv.org/pdf/1603.04614.pdf)

*Qingqun Ning, Jianke Zhu, Zhiyuan Zhong, Steven C.H. Hoi, Chun Chen*

---

[17] **Product Quantization Network for Fast Image Retrieval** ECCV 2018. [paper](https://arxiv.org/pdf/2002.11374.pdf)

*Yan Feng, Bin Chen, Tao Dai, Shutao Xia*

---

[18] **Revisiting the Inverted Indices for Billion-Scale Approximate Nearest Neighbors** ECCV 2018. [paper](https://arxiv.org/pdf/1802.02422.pdf)

*Dmitry Baranchuk, Artem Babenko, Yury Malkov*

---

(必读)[19]**Accelerating Large-Scale Inference with Anisotropic Vector Quantization** 	ICML 2020. [paper](https://arxiv.org/pdf/1908.10396.pdf)

*Ruiqi Guo, Philip Sun, Erik Lindgren*

---


#### 3.1 New hardware acceleration


[1] **Tree Quantization for Large-Scale Similarity Search and Classification** arXiv 2018. [paper](https://ieeexplore.ieee.org/document/7299052/)

*Artem Babenko, Victor Lempitsky*

---


#### 3.2 Query Optimization


[1] **Cache locality is not enough: high-performance nearest neighbor search with product quantization fast scan** VLDB 2015. [paper](https://vldb.org/pvldb/vol9/p288-andre.pdf)

*Fabien André, Anne-Marie Kermarrec, Nicolas Le Scouarnec*

---

[2] **Accelerating Product Quantization Query Execution Runtime** SIGMOD 2021. [paper](https://dl.acm.org/doi/10.1145/3448016.3450574)

*Ikraduya Edian*

---


### 4 Hash based Index


[1] **MQH: Locality Sensitive Hashing on Multi-level Qantization Errors for Point-to-Hyperplane Distances.** VLDB 2022. [paper](https://www.vldb.org/pvldb/vol16/p864-lu.pdf)

*Kejing Lu, Yoshiharu Ishikawa, Chuan Xiao*

---

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

[3] **iDEC: indexable distance estimating codes for approximate nearest neighbor search** VLDB 2020. [paper](https://vldb.org/pvldb/vol13/p1483-gong.pdf)

*Long Gong, Huayi Wang, Mitsunori Ogihara, Jun Xu*

---

[4] **VHP: approximate nearest neighbor search via virtual hypersphere partitioning** VLDB 2020. [paper](https://dl.acm.org/doi/10.14778/3397230.3397240)

*Kejing Lu, Hongya Wang, Wei Wang, Mineichi Kudo*

---

[5] **Query-aware locality-sensitive hashing for approximate nearest neighbor search** VLDB 2015. [paper](https://dl.acm.org/doi/abs/10.14778/2850469.2850470)

*Qiang Huang, Jianlin Feng, Yikai Zhang, Qiong Fang, Wilfred Ng*

---

[6] **R2LSH: A Nearest Neighbor Search Scheme Based on Two-dimensional Projected Spaces** ICDE 2020. [paper](https://conferences.computer.org/icde/2020/pdfs/ICDE2020-5acyuqhpJ6L9P042wmjY1p/290300b045/290300b045.pdf)

*Kejing Lu, Mineichi Kudo*

---

[7] **PM-LSH: a fast and accurate in-memory framework for high-dimensional approximate NN and closest pair search** VLDBJ 2021. [paper](https://link.springer.com/article/10.1007/s00778-021-00680-7)

*Bolong Zheng, Xi Zhao, Lianggui Weng, Quoc Viet Hung Nguyen, Hang Liu & Christian S. Jensen*

---

[8] **DSH: Data Sensitive Hashing for High-Dimensional k-NN Search** SIGMOD 2014. [paper](https://arxiv.org/pdf/1205.2930.pdf)

*Jinyang Gao, Hosagrahar Visvesvaraya Jagadish, Wei Lu, Beng Chin Ooi*

---

[9] **Locality-sensitive hashing scheme based on dynamic collision counting** SIGMOD 2012. [paper](https://dl.acm.org/doi/10.1145/2213836.2213898)

*Junhao Gan, Jianlin Feng, Qiong Fang, Wilfred Ng*

---

[10] **Quality and efficiency in high dimensional nearest neighbor search** SIGMOD 2009. [paper](https://dl.acm.org/doi/10.1145/1559845.1559905)

*Yufei Tao, Ke Yi, Cheng Sheng, Panos Kalnis*

---

[11] **Multi-Probe LSH: Efficient Indexing for High-Dimensional Similarity Search** VLDB 2007. [paper](https://www.cs.princeton.edu/cass/papers/mplsh_vldb07.pdf)

*Qin Lv, William Josephson, Zhe Wang, Moses Charikar, Kai Li*

---


#### 4.1 Hardware adaptation


[1] **Implementing and Evaluating E2LSH on Storage.** Published in Proceedings of the 26th International Conference on Extending Database Technology (EDBT), 28th March-31st March, 2023. [paper](https://openproceedings.org/2023/conf/edbt/paper-20.pdf)

*Yu Nakanishi, Kazuhiro Hiwada, Yosuke Bando, and so on*

___

[2] **Randomized Algorithms Accelerated over CPU-GPU for Ultra-High Dimensional Similarity Search** SIGMOD 2018. [paper](https://dl.acm.org/doi/10.1145/3183713.3196925)

*Yiqiu Wang, Anshumali Shrivastava, Jonathan Wang, Junghee Ryu*

---

[3] **GPU-accelerated Proximity Graph Approximate Nearest Neighbor Search and Construction** ICDE 2022. [paper](https://ieeexplore.ieee.org/document/9835618)

*Yuanhang Yu; Dong Wen; Ying Zhang; Lu Qin; Wenjie Zhang; Xuemin Lin*

---


#### 4.2 Query Optimization


**EI-LSH: An early-termination driven I/O efficient incremental c-approximate nearest neighbor search** VLDBJ 2021. [paper](https://link.springer.com/article/10.1007/s00778-020-00635-4)

*Wanqi Liu, Hanchen Wang, Ying Zhang, Wei Wang, Lu Qin & Xuemin Lin*

---



#### 4.3 Learning to Hash (L2H)


待补充


---


### 5 Tree based Index


(必读)[1]**Data Structures and Algorithms for Nearest Neighbor Search in General Metric Spaces** SODA 1993. [paper](https://dl.acm.org/doi/pdf/10.5555/313559.313789)

*Peter N. Yianilos*

---

(必读)[2]**Fast Nearest Neighbor Retrieval for Bregman Divergences** ICML 2008. [paper](https://dl.acm.org/doi/10.1145/1390156.1390171)

*Lawrence Cayton*

---


### 6 Disk based Index


待补充


___
## Contributors

<a href="https://github.com/Unstructured-Data-Community/ANN-Papers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Unstructured-Data-Community/ANN-Papers" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

## LICENSE

[Apache-2.0 license](./LICENSE)

