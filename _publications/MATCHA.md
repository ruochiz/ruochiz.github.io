---
title: "Probing multi-way chromatin interaction with hypergraph representation learning"
collection: publications
permalink: /publication/matcha
venue: '<b>RECOMB 2020</b>'
citation: '<b>Ruochi Zhang</b>, Jian Ma.'

---  
[[PDF (available soon)]]() [[Code(available soon)]]()


## Abstract
The advances in high-throughput genome organization mapping have enabled genome-wide characterization of chromatin interactions in 3D space within the nucleus.  However, proximity ligation based mapping approaches for pairwise chromatin interaction such as Hi-C cannot capture multi-way interactions, which are highly informative to delineate higher-order genome organization and gene regulation mechanisms.  The very recent development of multi-way chromatin interaction mapping methods such as ChIA-Drop and SPRITE has offered new opportunities to uncover simultaneous interactions involving multiple genomic loci. Unfortunately, existing methods for analyzing multi-way chromatin interaction data have limited capability of handling data noise and typically decompose each multi-way contact into pairwise ones, leading to a dramatic loss of higher-order information.Here we develop a new computational method called MATCHA based on hypergraph representation learning where multi-way chromatin interactions are represented as hypergraphs.   Applications toChIA-Drop and SPRITE data suggest that MATCHA is able to achieve accurate predictions of multi-way chromatin interactions (i.e., hyperedges). We further demonstrate the effectiveness of MATCHA for denoising and de novo hyperedge prediction, reducing the potential false positives and false negatives from the original data.  Importantly, we show that MATCHA is able to distinguish between multi-way interactions (hyperedges) and combinations of pairwise interactions (cliques).  Taken together, MATCHA provides a promising framework to significantly improve the analysis of multi-way chromatin interaction data and has the potential to offer new insights into nuclear genome structure and function.