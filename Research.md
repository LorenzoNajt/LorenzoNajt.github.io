# Research:


## Redistricting and gerrymandering:

Some of this work was featured [here](https://grad.wisc.edu/2020/04/23/mathematics-research-builds-better-ways-to-identify-gerrymandering/).

### [Complexity and Geometry of Sampling Connected Graph Partitions](https://arxiv.org/abs/1908.08881)
In this paper, we prove intractability results about sampling from the set of partitions of a planar graph into connected components. Our proofs are motivated by a technique introduced by Jerrum, Valiant, and Vazirani. Moreover, we use gadgets inspired by their technique to provide families of graphs where the "flip walk" Markov chain used in practice for this sampling task exhibits exponentially slow mixing. Supporting our theoretical results we present some empirical evidence demonstrating the slow mixing of the flip walk on grid graphs and on real data. Inspired by connections to the statistical physics of self-avoiding walks, we investigate the sensitivity of certain popular sampling algorithms to the graph topology. Finally, we discuss a few cases where the sampling problem is tractable. Applications to political redistricting have recently brought increased attention to this problem, and we articulate open questions about this application that are highlighted by our results.
### [The Gerrymandering Jumble: Map Projections Permute Districts' Compactness Scores](https://arxiv.org/abs/1905.03173)
In political redistricting, the compactness of a district is used as a quantitative proxy for its fairness. Several well-established, yet competing, notions of geographic compactness are commonly used to evaluate the shapes of regions, including the Polsby-Popper score, the convex hull score, and the Reock score, and these scores are used to compare two or more districts or plans. In this paper, we prove mathematically that any map projection from the sphere to the plane reverses the ordering of the scores of some pair of regions for all three of these scores. Empirically, we demonstrate that the effect of using the Cartesian latitude-longitude projection on the order of Reock scores is quite dramatic.

# Papers in Progress:

## Polytope Algorithms:

### [Uniformly sampling vertices of a polytope of bounded branchwidth is still hard (Draft)](Documents/Polytope_Paper_Draft.pdf)
Abstract: We consider the complexity of sampling vertices of a polytope. A theorem of Khachiyan uses the circulation polytope of a directed graph to show that this sampling problem is NP-hard, in the sense that a polynomial time sampler would imply NP = RP. It is known, also by work of Khachiyan et al., that the vertex enumeration problem is NP-hard for polyhedra, while it remains open for polytopes. However, bounding the branchwidth has been shown to provide a total polynomial time algorithm for the polytope vertex enumeration problem, and it is therefore natural to ask whether bounding branchwidth makes vertex sampling tractable. We investigate this question and demonstrate the NP-hardness of uniformly sampling vertices of a polytope given by $\{ Ax = b x \geq 0 \}$, where $A$ has branchwidth <= 4. To do so, we develop gadgets that build bounded branchwidth polytopes that have many vertices over certificates of an NP-hard problem. In an appendix, we apply this gadget to provide an alternative proof a recent theorem of Guo and Jerrum about sampling vertices from another class of polytopes. We also study some related questions, such as the branchwidth of the circulation polytope, and show that the vertices of a circulation polytope of bounded branchwidth can be sampled efficiently.

## Expected geometry of random connected partitions:
(Coming soon?)
