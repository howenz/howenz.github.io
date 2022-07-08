# Graph wavefront algorithm

Recently, we have proposed graph wavefront algorithm, which is an efficient sequence-to-graph alignment algorithm in practice. The implementation termed Gwfa is available [here](https://github.com/lh3/gwfa). Tested on 4 real sequence graphs, Gwfa with a pruning heuristic achieved up to 5 orders of magnitude speedup compared with other sequence-to-graph alignment methods.

Though the Gwfa [preprint](https://arxiv.org/abs/2206.13574) contains a formal description of the algorithm, it might not be easy for one without any experience in wavefront alignment algorithm (WFA) to understand. Therefore, I made a [tutorial video](https://youtu.be/ycS2oNUpt0g) to explain the idea on how Gwfa works with an example. The slides are available [here](/assets/Gwfa%20tutorial.pdf). Hope these material can be helpful.
