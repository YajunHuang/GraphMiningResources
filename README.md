# GraphMiningResources
### Yajun Huang, 黄亚军

I create this repository for collecting study resources and wirting notes about graph mining. 

## Deep Learning Self-study:
http://web.eecs.umich.edu/~dkoutra/courses/F15_598/#resources

### Note: The Mian Guilt-by-Association Approaches: 
- Random Walk with Restarts: provides a good relevance score bwtween two nodes in a weighted graph
- Semi-Supervised Learning
- Belief Propagation: an algorithm for Markov Random Field Model

### Random Walk with Restarts, PageRank
Page, Lawrence and Brin, Sergey and Motwani, Rajeev and Winograd, Terry (1999). The PageRank Citation Ranking: Bringing Order to the Web. Technical Report. Stanford InfoLab. [citations: 2434]

Hanghang Tong, Christos Faloutsos, and Jia-Yu Pan. Fast Random Walk with Restart and Its Application. ICDM 2006. Longer version (Technical report): http://repository.cmu.edu/cgi/viewcontent.cgi?article=1533&context=compsci

Main References:
- J. He, M. Li, H. Zhang, H. Tong, and C. Zhang. Manifold-ranking based image retrieval. In ACM Multimedia, pages 9–16, 2004.
- J.-Y. Pan, H.-J. Yang, C. Faloutsos, and P. Duygulu. Au-tomatic multimedia cross-modal correlation discovery. In KDD, pages 653–658, 2004.
- J. Sun, H. Qu, D. Chakrabarti, and C. Faloutsos. Neighbor-hood formation and anomaly detection in bipartite graphs. In ICDM, pages 418–425, 2005
- H.Tongand C.Faloutsos. Center-piece subgraphs: Problem definition and fast solutions. In KDD, 2006.

### Node Classification: Belief Propagation

Shashank Pandit, Duen Horng Chau, Samuel Wang, and Christos Faloutsos. NetProbe: A Fast and Scalable System for Fraud Detection in Online Auction Networks. In Proceedings of the 16th International Conference on World Wide Web (WWW), Alberta, Canada, pages 201-210, 2007.

Danai Koutra, Tai-You Ke, U Kang, Duen Horng (Polo) Chau, Hsing-Kuo Kenneth Pao, and Christos Faloutsos. Unifying Guilt-by-Association Approaches: Theorems and Fast Algorithms. ECML PKDD, Athens, Greece, Sep. 2011. Easier to read chapter 4 of "Exploring and Making Sense of Large Graphs." (dissertation).

### Node Classification: Semi-Supervised Learning

Avrim Blum and Shuchi Chawla. Learning from Labeled and Unlabeled Data Using Graph Mincuts. In Proceedings of the 18th International Conference on Machine Learning, pages 19–26. Morgan Kaufmann, San Francisco, CA, 2001.

Dengyong Zhou, Bernhard Schölkopf, Thomas Hofmann. Semi-supervised Learning on Directed Graphs. NIPS 2004: 1633-1640
Other readings:

Xiaojin Zhu. Semi-Supervised Learning Literature Survey, 2006. Survey.

### Deep learning for graphs
用 Random Walk 在图上根据图的拓扑结构进行采样，样本是一段RW经过的 vertex sequence，类比成NLP的sentence。然后使用 word2vector 算法处理 vertex sequences 得到每个顶点的向量。</br>
Bryan Perozzi, Rami Al-Rfou, and Steven Skiena. 2014. DeepWalk: online learning of social representations. In Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '14). [CODE:http://www.gitxiv.com/posts/xRKq4MuZyDtS3wR4k/deepwalk-deep-learning-for-graphs]

Fei Tian, Bin Gao, Qing Cui, Enhong Chen, Tie-Yan Liu. Learning Deep Representations for Graph Clustering. AAAI 2014: 1293-1299

### Spectrum clustering for graph

L. Tang and H. Liu. Leveraging social media networks for classification. Data Mining and Knowledge Discovery, 23(3):447–478, 2011.
