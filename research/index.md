---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Research is most fruitful (and most fun) at the intersection of different fields of research. At the core of our research is the development of methods that
give *global, human-interpretable explanations* for complex machine learning models, as well as the development of *inherently interpretable* machine learning models.
We study these topics touching the fields of *classical XAI, Data Mining, Neural Network Pruning, and Low-dimensional Embeddings*,
merging ideas to for example obtain a better understanding of how information is encoded and propagated inside a neural network, nowadays coined *mechanistic interpretability*, or to inform neuro-symbolic
architecture designs for relevant problems in biology.

Putting our ideas into practice, we study Explainability of models in challenging biomedical tasks around *cancer*, where an understanding of the decision-making process of a model is essential
for a model to be deployed in practice. We further consider Explanability of *foundation models*, which is key to understand their success, but also to understand whether they align with human reasoning and do
not reflect harmful biases. Such an understanding is not only interesting, but soon required by law under the *EU AI act*.

{% include section.html %}

{% capture text %}

*Post-hoc* explainability methods aim to provide explanations of what an already trained model, usually a neural network, learned and how it uses this information to arrive at a prediction.
While not making the network fully transparent, by providing a glimpse into the black box models these methods have the great advantage that they do not compromise performance, which is a desiderata for a neural network. 
The majority of post-hoc explanation approaches, however, focus on *instance-specific explanations*, giving insights into why a decision was made for a particular instance (e.g., saliency maps, GradCam, Integrated Gradients,
LIME, ...).
We are interested in *global explanations* that describe the general information encoded for example by a group of neurons and discovering such feature-encoding neuron groups in the first place.

{% endcapture %}

{%
  include feature.html
  image="images/explainn.png"
  title="Global Explanations"
  text=text
%}


{% include section.html %}

{% capture text %}

*Neuro-symbolic approaches* to machine learning promise full interpretability through *symbolic encodings* in a neural network that can be parsed and understood by a human domain expert. While highly interesting, these approaches remain largely theoretical, as such architectures are hard to define and even harder to optimize. We focus on recent advances for *binarized and ternarized neural network architectures* from different fields, such as ML for embedded devices, and how we can transfer these to neuro-symbolic learning. In several biological applications as well as settings with transactional data, such architectures already provide a fully interpretable approach that allows to derive new insights directly from the network.

{% endcapture %}

{%
  include feature.html
  image="images/binaps.png"
  title="Neuro-symbolic architectures"
  text=text
%}


{% include section.html %}

{% capture text %}

*Sparse neural networks* not only provide more resource-efficient alternatives to their dense counterparts at same performance, captured by the *Lottery Ticket Hypothesis*, but also represent useful information in their network topology compared to the standard fully connected layers in dense networks.
We focus on the question of how we can prune networks to *extreme sparsity*, and how such sparse neural networks can then yield more explainable decision-making.

{% endcapture %}

{%
  include feature.html
  image="images/pruning.png"
  title="Sparse Neural Networks"
  text=text
%}

{% include section.html %}

{% capture text %}
To discover and present *regularities and dependencies in complex, high-dimensional data*, human experts often resort to a visual exploration.
As a visual inspection or presentation is bound to two or three-dimensional spaces, the field of *low-dimensional embeddings* focuses on developing methods
to map high-dimensional data to such low-dimensional, visualizable spaces while *keeping the main structure of the data intact*.
While these approaches enjoy tremendous interest in the sciences, such as biology, the limitations on what structures they preserves and which ones are lost, or which biases are introduced are under constant debate.
We are interested in *studying these limitations* both empirically and theoretically, *develop novel approaches* to this problem, and use those to visually *explore the neural activation landscapes* of neural networks


{% endcapture %}

{%
  include feature.html
  image="images/mnist_dtsne.png"
  title="Low-dimensional Embeddings"
  text=text
%}

{% include section.html %}


## List of Publications

### 2024

Hossain, I‡, Fischer, J‡, Burkholz, R\*, Quackenbush, J\*, ***Pruning neural network models for gene regulatory dynamics using data and domain knowledge*** accepted at NeurIPS 2024. (25.8% acceptance rate, Core A*) \[[preprint](https://arxiv.org/abs/2403.04805)\]\
‡\*equal contribution

Fischer, J, Ma, R, ***Sailing in high-dimensional spaces: Low-dimensional embeddings through angle preservation*** preprint: arXiv:2406.09876, 2024. \[[preprint](https://arxiv.org/abs/2406.09876)\]

Fanfani, V, Shutta, KH, Mandros, P, Fischer, J, Saha, E, Micheletti, S, Chen, C, Guebila, MB, Lopes-Ramos, CM, Quackenbush, J, ***Reproducible processing of TCGA regulatory networks*** preprint: bioRxiv:2024.11.05.622163 \[[preprint](https://www.biorxiv.org/node/4205022.full)\]

Fischer, J, Shutta, KH, Chen, C, Fanfani, V, Saha, E, Mandros, P, Guebila, MB, Xiu, J, Nieva, J, Liu, S, Uprety, D, Spetzler, D, Lopes-Ramos, CM, DeMeo, D, Quackenbush, J, ***Selective loss of Y chromosomes in lung adenocarcinoma modulates the tumor immune environment through cancer/testis antigens*** bioRxiv:10.1101/2024.09.19.613876v1, 2024. \[[preprint](https://www.biorxiv.org/content/10.1101/2024.09.19.613876v1)\]

Lin, Y, Breuer, K, Weichenhan, D, Lafrenz, P, Wilk, A, Chepeleva, M, Mücke, O, Schönung, M, Petermann, F, Kensche, P, Weiser, L, Thommen, F, Giacomelli, G, Nordstroem, K, Gonzales-Avalos, E, Merkel, A, Kretzmer, H, Fischer, J, Krämer, S, Iskar, M, Wolf, S, Buchhalter, I, Esteller, M, Lawerenz, C, Twardziok, S, Zapatka, M, Hovestadt, V, Schlesner, M, Schulz, M, Hoffmann, S, Gerhauser, C, Walter, J, Hartmann, M, Lipka, DB, Assenov, Y, Bock, C, Plass, C, Toth, R, Lutsik, P ***Pipeline Olympics: continuable benchmarking of computational workflows for DNA methylation sequencing data against an experimental gold-standard*** bioRxiv:10.1101/2024.09.16.609142, 2024. \[[preprint](https://www.biorxiv.org/content/10.1101/2024.09.16.609142v1)\]

Mandros, P, Gallagher, I, Fanfani, V, Chen, C, Fischer, J, Ismail, A, Hsu, L, Saha, E, DeConti, DK, Quackenbush, J, ***node2vec2rank: Large Scale and Stable Graph Differential Analysis via Multi-Layer Node Embeddings and Ranking*** preprint: bioRxiv:10.1101/2024.06.16.599201v1, 2024. \[[preprint](https://www.biorxiv.org/content/10.1101/2024.06.16.599201v1)\]

Walter, NP, Fischer, J, Vreeken, J, ***Finding Interpretable Class-Specific Patterns through Efficient Neural Search*** AAAI Conference on Artificial Intelligence (AAAI), 2024. (23.8% acceptance rate, Core A*) \[[Article](https://ojs.aaai.org/index.php/AAAI/article/view/28756)\]


Saha, E‡, Fanfani, V‡, Mandros, P, Guebila, MB, Fischer, J, Shutta, KH, Glass, K, DeMeo, DL, Lopes-Ramos, CM, Quackenbush, J, ***Bayesian inference of sample-specific coexpression networks*** Genome Research, CSHL, 2024. (IF: 6.70, 2022) \[[PDF](https://genome.cshlp.org/content/early/2024/08/10/gr.279117.124.full.pdf)\]\
‡equal contribution

Saha, E‡, Fanfani, V‡, Mandros, P, Guebila, MB, Fischer, J, Shutta, KH, Glass, K, DeMeo, DL, Lopes-Ramos, CM, Quackenbush, J, ***Bayesian Optimized sample-specific Networks Obtained By Omics data (BONOBO)*** Conference for Research in Computational Molecular Biology (RECOMB), 2024. (16.5% acceptance rate) \[[Conference paper](https://link.springer.com/chapter/10.1007/978-1-0716-3989-4_23)\]\
‡equal contribution

Saha, E, Guebila, MB, Fanfani, V, Fischer, J, Shutta, KH, Mandros, P, DeMeo, DL, Quackenbush, J, Lopes-Ramos, CM, ***Gene regulatory Networks Reveal Sex Difference in Lung Adenocarcinoma*** Biology of Sex Differences 15(62), 2024. (IF: 8.24, 2022) \[[preprint](https://www.biorxiv.org/content/10.1101/2023.09.22.559001v1)\] \[[Article](https://link.springer.com/article/10.1186/s13293-024-00634-y)\]


Hossain, I, Fanfani, V, Fischer, J, Quackenbush, J, Burkholz, J, ***Biologically informed NeuralODEs for genome-wide regulatory dynamics*** Genome Biology 25(127), BMC, 2024. (IF: 17.4, 2022) \[[Article](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03264-0)\]


### 2023

Hedderich, M‡, Fischer, J‡, Klakow, D, Vreeken, J, ***Understanding and Mitigating Classification Errors Through Interpretable Token Patterns*** Empirical Methods in Natural Language Processing (EMNLP) BlackboxNLP workshop, 2023. \[[preprint](https://arxiv.org/abs/2311.10920)\]\
‡equal contribution

Kamp, M, Fischer, J, Vreeken, J, ***Federated Learning from Small Datasets***. International Conference on Learning Representations (ICLR), OpenReview, 2023. (31.8% acceptance rate, Core A*) \[[PDF](https://openreview.net/forum?id=hDDV1lsRV8)\]

Fischer, J, Burkholz, R, Vreeken, J, ***Preserving local densities in low-dimensional embeddings***. preprint: arXiv:2301.13732, 2023.  \[[preprint](https://arxiv.org/abs/2301.13732)\]

Fischer, J, Schulz, MH, ***Efficiently Quantifying DNA Methylation for Bulk- and Single-cell Bisulfite Data***. Bioinformatics 39(6), Oxford University Press, 2023. (IF: 5.8, 2023) \[[Article](https://academic.oup.com/bioinformatics/article/39/6/btad386/7199582)\]

### 2022

Hedderich, M‡, Fischer, J‡, Klakow, D, Vreeken, J, ***Label-Descriptive Patterns and their Application to Characterizing Classification Errors***. In: Proceedings of the International Conference on Machine Learning (ICML), PMLR, 2022. (21.9% acceptance rate, Core A*)  \[[PDF](https://proceedings.mlr.press/v162/hedderich22a/hedderich22a.pdf)\]\
‡equal contribution

Fischer, J, Burkholz, R, ***Plant 'n' Seek: Can You Find the Winning Ticket?***
International Conference on Learning Representations (ICLR), OpenReview, 2022. (32.9% acceptance rate, Core A*)  \[[PDF](https://openreview.net/pdf?id=9n9c8sf0xm)\]

Marx, A, Fischer, J, ***Estimating Mutual Information via Geodesic kNN.***
SIAM Conference on Data Mining (SDM), SIAM, 2022. (27.9% acceptance rate, Core A)  \[[Article](https://epubs.siam.org/doi/abs/10.1137/1.9781611977172.47)\]

### 2021

Fischer, J, Vreeken, J, ***Differentiable Pattern Set Mining***. In: Proceedings of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), ACM, 2021. (15.4% acceptance rate, Core A*)  \[[Article](https://dl.acm.org/doi/10.1145/3447548.3467348)\]

Fischer, J, Oláh, A, Vreeken, J, ***What's in the Box? Explaining Neural Networks with Robust Rules***. In: Proceedings of the International Conference on Machine Learning (ICML), PMLR, 2021. (21.4% acceptance rate, Core A*)  \[[PDF](https://proceedings.mlr.press/v139/fischer21b/fischer21b.pdf)\]

Fischer, J, Ardakani, FB, Kattler, K, Walter, J, Schulz, MH, ***CpG content-dependent associations between transcription factors and histone modifications***. Plos ONE 16(4): e0249985, 2021. (IF: 3.7, 2023)  \[[Article](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0249985)\]

Fischer, J‡, Gadhikar‡, A, Burkholz, R, ***Lottery Tickets with Nonzero Biases***. preprint: arXiv:2110.11150, 2021.  \[[preprint](https://arxiv.org/abs/2110.11150)\]\
‡equal contribution

Heiter, E, Fischer, J, Vreeken, J, ***Factoring out prior knowledge from low-dimensional embeddings***. preprint: arXiv:2103.01828, 2021.  \[[preprint](https://arxiv.org/abs/2103.01828)\]

### 2020

Fischer, J, Vreeken, J, ***Discovering Succinct Pattern Sets Expressing Co-Occurrence and Mutual Exclusivity***. In: Proceedings of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), ACM, 2020. (16.8% acceptance rate, Core A*)  \[[Article](https://dl.acm.org/doi/10.1145/3394486.3403124)\]

### 2019

Fischer, J, Vreeken, J, ***Sets of Robust Rules, and How to Find Them*** In: Proceedings of the European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Data (ECMLPKDD), Springer, 2019. (17.7% acceptance rate, Core A, ==selected plenary talk==, <5% of accepted papers)  \[[Article](https://link.springer.com/chapter/10.1007/978-3-030-46150-8_3)\]

Fischer, J, Schulz, MH, ***Fast and accurate bisulfite alignment and methylation calling for mammalian genomes***. Talk at ISMB/ECCB, Basel, Switzerland, 2019.

### 2018

Ardakani, FB Kattler, K, Nordström, KJ, Gasparoni, N, Gasparoni, G, Fuchs, S, Sinha, A, Barann, M, Ebert, P, Fischer, J, Hutter, B, Zipprich, G, Imbusch, CD, Felder, B, Eils, J, Brors, B, Lengauer, T, Manke, T, Rosenstiel, P, Walter, J, Schulz, MH, ***Integrative analysis of single-cell expression data reveals distinct regulatory states in bidirectional promoters***. Epigenetics & Chromatin 11(1): 66, 2018. (IF: 5.5, 2023)  \[[Article](https://epigeneticsandchromatin.biomedcentral.com/articles/10.1186/s13072-018-0236-7)\]

Fischer, J, Schulz, MH, ***Fast and accurate bisulfite alignment and methylation calling for mammalian genomes***. Short talk/poster at RECOMB-seq/RECOMB, Paris, France, 2018.



### Theses

Fischer, J, More than the sum of its parts – pattern mining, neural networks, and how they complement each other. Doctoral Dissertation, 2022.  \[[PDF](https://publikationen.sulb.uni-saarland.de/handle/20.500.11880/33893?locale=en)\]