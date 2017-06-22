# GraphMiningResources
### Yajun Huang, 黄亚军

## The Mian Guilt-by-Association Approaches: 
Guilt-by-Association approaches can be divided to three topics:
- Random Walk with Restarts: provides a good relevance score between two nodes in a weighted graph
- Semi-Supervised Learning
- Belief Propagation

### Random Walk with Restarts, PageRank
Page, Lawrence and Brin, Sergey and Motwani, Rajeev and Winograd, Terry (1999). The PageRank Citation Ranking: Bringing Order to the Web. Technical Report. Stanford InfoLab. [citations: 2434]

Hanghang Tong, Christos Faloutsos, and Jia-Yu Pan. Fast Random Walk with Restart and Its Application. ICDM 2006. Longer version (Technical report): http://repository.cmu.edu/cgi/viewcontent.cgi?article=1533&context=compsci

Main References:
- J. He, M. Li, H. Zhang, H. Tong, and C. Zhang. Manifold-ranking based image retrieval. In ACM Multimedia, pages 9–16, 2004.
- J.-Y. Pan, H.-J. Yang, C. Faloutsos, and P. Duygulu. Au-tomatic multimedia cross-modal correlation discovery. In KDD, pages 653–658, 2004.
- J. Sun, H. Qu, D. Chakrabarti, and C. Faloutsos. Neighbor-hood formation and anomaly detection in bipartite graphs. In ICDM, pages 418–425, 2005
- H.Tongand C.Faloutsos. Center-piece subgraphs: Problem definition and fast solutions. In KDD, 2006.

### Belief Propagation (Node Classification)

__Theory papers__

- Frank R. Kschischang, Brendan J.Frey, ect. Factor graph and sum-product algorithm. IEEE Transactions on Information Theory, 47:498-519, 2001.
- J. S. Yedidia, W. T. Freeman, and Y. Weiss. Understanding
belief propagation and its generalizations. pages 236–239. 2003.
- J. Yedidia, W. Freeman, and Y. Weiss. Constructing free-energy approximations and generalized belief propagation algorithms. IEEE Transactions on Information Theory, 51(7):2282–2312, 2005.

__Appplication papers__
- S. Pandit, D. H. Chau, S. Wang, and C. Faloutsos. Netprobe: a fast and scalable system for fraud detection in online auction networks. In WWW, pages 201–210, 2007

__Efficient improvement papers__
- D. Koutra, T.-Y. Ke, U. Kang, D. H. P. Chau, H.-K. K. Pao, and C. Faloutsos. Unifying guilt-by-association approaches: Theorems and fast algorithms. In ECML PKDD, pages 245–260, 2011.
- W. Gatterbauer, S. Gu ̈nnemann, D. Koutra, and C. Faloutsos. Linearized and single-pass belief propagation. PVLDB, 8(5):581–592, 2015. 
- Y. Yamaguchi, C. Faloutsos, and H. Kitagawa. Camlp: Confidence-aware modulated label propagation. SDM, 2016.
- D. Eswaran, S. Gu ̈nnemann, C. Faloutsos, D. Makhija and M. Kumar. ZooBP: Belief Propagation for Heterogeneous Networks. PVLDB, Vol. 10, No. 5, 2017

### Semi-Supervised Learning (Node Classification)

Avrim Blum and Shuchi Chawla. Learning from Labeled and Unlabeled Data Using Graph Mincuts. In Proceedings of the 18th International Conference on Machine Learning, pages 19–26. Morgan Kaufmann, San Francisco, CA, 2001.

Dengyong Zhou, Bernhard Schölkopf, Thomas Hofmann. Semi-supervised Learning on Directed Graphs. NIPS 2004: 1633-1640
Other readings:

Xiaojin Zhu. Semi-Supervised Learning Literature Survey, 2006. Survey.

## Deep learning for graph node representation
用 Random Walk 在图上根据图的拓扑结构进行采样，样本是一段RW经过的 vertex sequence，类比成NLP的sentence。然后使用 word2vector 算法处理 vertex sequences 得到每个顶点的向量。</br>
Bryan Perozzi, Rami Al-Rfou, and Steven Skiena. 2014. DeepWalk: online learning of social representations. In Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining (KDD '14).</br> CODE:http://www.gitxiv.com/posts/xRKq4MuZyDtS3wR4k/deepwalk-deep-learning-for-graphs

Deepwalk 的改进算法 </br>
node2vec: Scalable Feature Learning for Networks. A. Grover, J. Leskovec. ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), 2016.

Fei Tian, Bin Gao, Qing Cui, Enhong Chen, Tie-Yan Liu. Learning Deep Representations for Graph Clustering. AAAI 2014: 1293-1299

## Spectrum clustering for graph

U. von Luxburg. A tutorial on spectral clustering. Statistics and Computing, 17(4):395–416, 2007.

L. Tang and H. Liu. Leveraging social media networks for classification. Data Mining and Knowledge Discovery, 23(3):447–478, 2011.

## Bipartite dense-subgraph detection

Hooi, B., Song, H.A., Beutel, A., Shah, N., Shin, K., Faloutsos, C.: Fraudar: bounding graph fraud in the face of camouflage. In: KDD (2016) </br>
CODE: http://www.andrew.cmu.edu/user/bhooi/code/camo.zip

N. Shah, A. Beutel, B. Gallagher, and C. Faloutsos. Spotting suspicious link behavior with fbox: An adversarial perspective. arXiv preprint arXiv:1410.3915, 2014.

B. Prakash, M. Seshadri, A. Sridharan, S. Machiraju, and C. Faloutsos. Eigenspokes: Surprising patterns and community structure in large graphs. PAKDD, 2010a, 84, 2010.

M. Jiang, P. Cui, A. Beutel, C. Faloutsos, and S. Yang, "CatchSync: Catching Synchronized Behavior in Large Directed Graphs," in Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining, 2014, pp. 941-950.

M. Jiang, P. Cui, A. Beutel, C. Faloutsos, and S. Yang, "Inferring Strange Behavior from Connectivity Pattern in Social Networks," in PAKDD, 2014.

## Related Resources

CMU fraud and spam detection lab: http://db.cs.cmu.edu/projects/spam-and-fraud-detection

http://web.eecs.umich.edu/~dkoutra/courses/F15_598/#resources

UIUC Data-Driven Behavioral Analytics: Observations, Representations and Models: http://www.meng-jiang.com/tutorial-cikm16.html
