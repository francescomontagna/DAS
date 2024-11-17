Author repository for the implementation of the DAS algorithm from the [Scalable Causal Discovery with Score Matching](https://www.amazon.science/publications/scalable-causal-discovery-with-score-matching) CLeaR 2023 conference paper.

The code is released as part of the [dodiscover](https://www.pywhy.org/dodiscover/dev/generated/dodiscover.toporder.DAS.html#dodiscover.toporder.DAS) ecosystem. If you find DAS code useful for your work, please consider citing our paper:

```
@InProceedings{pmlr-v213-montagna23b,
  title = 	 {Scalable Causal Discovery with Score Matching},
  author =       {Montagna, Francesco and Noceti, Nicoletta and Rosasco, Lorenzo and Zhang, Kun and Locatello, Francesco},
  booktitle = 	 {Proceedings of the Second Conference on Causal Learning and Reasoning},
  pages = 	 {752--771},
  year = 	 {2023},
  editor = 	 {van der Schaar, Mihaela and Zhang, Cheng and Janzing, Dominik},
  volume = 	 {213},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {11--14 Apr},
  publisher =    {PMLR},
  pdf = 	 {https://proceedings.mlr.press/v213/montagna23b/montagna23b.pdf},
  url = 	 {https://proceedings.mlr.press/v213/montagna23b.html},
  abstract = 	 {This paper demonstrates how to discover the whole causal graph from the second derivative of the log-likelihood in observational non-linear additive Gaussian noise models. Leveraging scalable machine learning approaches to approximate the score function $\nabla \operatorname{log}p(\mathbf{X})$, we extend the work of Rolland et al. (2022) that only recovers the topological order from the score and requires an expensive pruning step removing spurious edges among those admitted by the ordering. Our analysis leads to DAS (acronym for Discovery At Scale), a practical algorithm that reduces the complexity of the pruning by a factor proportional to the graph size. In practice, DAS achieves competitive accuracy with current state-of-the-art while being over an order of magnitude faster. Overall, our approach enables principled and scalable causal discovery, significantly lowering the compute bar. }
}

```
