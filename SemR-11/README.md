## Distributional Semantic Models 

Distributional Semantic Models (DSM) are consolidating themselves as fundamental components for supporting automatic semantic interpretation in different application scenarios in natural language processing. From **Question Answering Systems**, to **Semantic Search** and **Text Entailment**, distributional semantic models support a scalable approach for representing the meaning of words, which can automatically capture comprehensive associative commonsense information by analysing word-context patterns in large-scale corpora in an unsupervised or semi-supervised fashion.

## Gold Standard
Gold Standards provide a way of measuring how well Distributional Semantic Models compute semantic similarity or relatedness.

There are several datasets that have been widely adopted for the evaluation of DSMs over English. Such as **Miller & Charles** ([MC](http://www.tandfonline.com/doi/abs/10.1080/01690969108406936#.Uu_392SwIyV)), **Rubenstein & Goodenough** ([RG](http://dl.acm.org/citation.cfm?id=365657)), **WordSimilarity 353** ([WS-353](http://www.cs.technion.ac.il/~gabr/resources/data/wordsim353/)) and **[Simlex-999](http://www.cl.cam.ac.uk/~fh295/simlex.html)**.



### Multi-lingual Gold Standard
With growing the number of multi-lingual pages on the web having multi-lingual test collections to evaluate Multi-lingual Distributional Semantic Models are necessary.
The most of test collection are originally in English, except for [a few languages](http://wordvectors.org/suite.php).
We created four test collections such as WS-353, MC, RG and Simlex-999 over 11 language (7 European language for Simlex-999 Dataset). The word pairs were translated and reviewed with the help of paid professional translators (Lionbridge Natural Language Solutions), skilled in data localisation tasks. 

This repo contains 4 multi-lingual gold standards over 11 languages to measure how well Distributional Semantic Models (DSMs) capture semantic similarity or relatedness.


|Language|MC|RG|WS-353|Simlex-999|
|--------|-----|------|------|-------|
|German|✓|✓|✓|✓|
|French|✓|✓|✓|✓|
|Russian|✓|✓|✓| |
|Italian|✓|✓|✓|✓|
|Dutch|✓|✓|✓|✓| |
|Chinese|✓|✓|✓| |
|Portuguese|✓|✓|✓|✓|
|Swedish|✓|✓|✓|✓|
|Spanish|✓|✓|✓|✓|
|Arabic|✓|✓|✓| |
|Farsi(Persian)|✓|✓|✓| |


## Citing Indra
Please cite our paper, if you use it in your experiments or project.

```
@InProceedings{barzegar2018semr11,
author="Barzegar, Siamak and Davis, Brian and Zarrouk, Manel and Handschuh, Siegfried and Freitas, Andr{\'e} and ",
title="SemR-11: A Multi-Lingual Gold-Standard for Semantic Similarity and Relatedness for Eleven Languages",
booktitle = {Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018)},
month     = {May},
year      = {2018},
address   = {Miyazaki, Japan},
publisher = {European Language Resources Association (ELRA)},
}
```
