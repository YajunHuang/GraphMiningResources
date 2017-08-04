# Belif Propagation Algorithm

## Reading Resources

### Theory
- Frank R. Kschischang, Brendan J.Frey, ect. Factor graph and sum-product algorithm. IEEE Transactions on Information Theory, 47:498-519, 2001.
- J. S. Yedidia, W. T. Freeman, and Y. Weiss. Understanding
belief propagation and its generalizations. pages 236–239. 2003.
- J. Yedidia, W. Freeman, and Y. Weiss. Constructing free-energy approximations and generalized belief propagation algorithms. IEEE Transactions on Information Theory, 51(7):2282–2312, 2005.

### Appplications
- S. Pandit, D. H. Chau, S. Wang, and C. Faloutsos. Netprobe: a fast and scalable system for fraud detection in online auction networks. In WWW, pages 201–210, 2007

### Improve Efficiency
- D. Koutra, T.-Y. Ke, U. Kang, D. H. P. Chau, H.-K. K. Pao, and C. Faloutsos. Unifying guilt-by-association approaches: Theorems and fast algorithms. In ECML PKDD, pages 245–260, 2011.
- W. Gatterbauer, S. Gu ̈nnemann, D. Koutra, and C. Faloutsos. Linearized and single-pass belief propagation. PVLDB, 8(5):581–592, 2015. 
- Y. Yamaguchi, C. Faloutsos, and H. Kitagawa. Camlp: Confidence-aware modulated label propagation. SDM, 2016.
- D. Eswaran, S. Gu ̈nnemann, C. Faloutsos, D. Makhija and M. Kumar. ZooBP: Belief Propagation for Heterogeneous Networks. PVLDB, Vol. 10, No. 5, 2017

### Extension
- Bayesian Reasoning and Machine Learning, David Barber, Cambridge University Press 2012. Free online.
- [seminar web page](http://cs.brown.edu/courses/csci2420/)

## Open Source Software

### Understanding
- [pyfac](https://github.com/rdlester/pyfac): factor graph, python
- [ZooBP](http://www.cs.cmu.edu/~deswaran/code/zoobp.zip): ZooBP, C++(Eigen)
- [Label Propagation](https://github.com/yamaguchiyuto/label_propagation): label propagation, python
- [Loopy BP](http://nghiaho.com/?page_id=1366): BP, C++(OpenCV)

### Application
- [GraphLab](http://select.cs.cmu.edu/code/graphlab/)
- [libDAI](http://www.libdai.org/)
- [More](http://cs.brown.edu/courses/csci2420/resources/)


### Conclusion
|   Theory    |   Open Code   |   Implementation  |
--------------|---------------|-------------------|
| Sum-Product | pyfac         |       -           |
| BP          | LBP/LibDAI    |   LBP/LibDAI      |
| ZooBP       | ZooBP         |   __ZooBP__       |
| GaBP        | GraphLab      |   __GraphLab__    |
| LinBP       | -             | -                 |


### Study steps:

* Step 1: Sum-Product, pyfac code. _(Almost done)_
* Step 2: BP, LBP code. _(Done)_
* Step 3: LBP, ZooBP, ZooBP code.
* Step 4: GaBP.
* Step 4: GraphLab, PageRank and GaBP code





# Probabilistic graphical model
## Open library
- libDAI: [code](https://bitbucket.org/jorism/libdai.git)
- pgmpy: [github](https://github.com/pgmpy/pgmpy) | [doc](http://pgmpy.org/)
- PGMs: [homepage](http://www.cs.cmu.edu/~jkbradle/projects/PGMs.html)


# Graph Embedding
__Lab of Media and Network, Tsinghua Univ.__
 
Community Preserving Network Embedding.
X Wang, P Cui, J Wang, J Pei, W Zhu, S Yang. (AAAI 2017)

Structural deep network embedding.
D Wang, P Cui, W Zhu. (SIGKDD 2016)

Asymmetric Transitivity Preserving Graph Embedding.
M Ou, P Cui, Z Zhang, J Pei, W Zhu. (SIGKDD 2016)

Non-transitive Hashing with Latent Similarity Components.
M Ou, P Cui, F Wang, J Wang, W Zhu. (SIGKDD 2015)

Comparing Apples to Oranges: A Scalable Solution with Heterogeneous Hashing.
M Ou, P Cui, F Wang, J Wang, W Zhu, S Yang. (SIGKDD 2013)
