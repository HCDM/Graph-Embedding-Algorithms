# graph-embedding

This repo includes graph embedding related models developed by our team. The detailed instructions and implementations of each model can be found in corresponding directories listed below.

1. [UGE-Unbiased-Graph-Embedding](https://github.com/HCDM/graph-embedding/tree/main/UGE-Unbiased-Graph-Embedding) [1] generates unbiased node embedding when the graph topology is biased by sensitive node attributes.
2. SPAC-SPectral-AttaCk [2] generates adversarial structural perturbation by maximizing the spectral distance between original and perturbed graphs.
3. GraphHAM-Graph-Hierarchical-Attentive-Membership [3] jointly learns node embedding and hierarchical membership of nodes toward hidden groups.
4. CGAT-Channel-aware-Graph-Attention-Network [4] captures the textual content on edges to enable a channel-aware attention mechanism on GNNs.


# Reference

[1] Nan Wang, Lu Lin, Jundong Li and Hongning Wang. "Unbiased Graph Embedding with Biased Graph Observations." arXiv preprint arXiv:2110.13957 (2021).

[2] Lu Lin, Ethan Blaser and Hongning Wang. "Graph Structural Attack by Spectral Distance." arXiv preprint arXiv:2111.00684 (2021).

[3] Lu Lin, Ethan Blaser, and Hongning Wang. 2022. Graph Embedding with Hierarchical Attentive Membership. In Proceedings of the Fifteenth ACM International Conference on Web Search and Data Mining (WSDM '22). Association for Computing Machinery, New York, NY, USA, 582–590. DOI:https://doi.org/10.1145/3488560.3498499

[4] Lu Lin and Hongning Wang. 2020. Graph Attention Networks over Edge Content-Based Channels. In <i>Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery &amp; Data Mining</i> (<i>KDD '20</i>). Association for Computing Machinery, New York, NY, USA, 1819–1827. DOI:https://doi.org/10.1145/3394486.3403233
