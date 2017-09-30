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
|German|x|x|x|x|
|French|x|x|x|x|
|Russian|x|x|x| |
|Italian|x|x|x|x|
|Dutch|x|x|x|x| |
|Chinese|x|x|x| |
|Portuguese|x|x|x|x|
|Swedish|x|x|x|x|
|Spanish|x|x|x|x|
|Arabic|x|x|x| |
|Farsi(Persian)|x|x|x| |


## Citing Indra
Please cite Indra, if you use it in your experiments or project.

```
@Inbook{Freitas2016,
author="Freitas, Andr{\'e}
and Barzegar, Siamak
and Sales, Juliano Efson
and Handschuh, Siegfried
and Davis, Brian",
editor="Blomqvist, Eva
and Ciancarini, Paolo
and Poggi, Francesco
and Vitali, Fabio",
title="Semantic Relatedness for All (Languages): A Comparative Analysis of Multilingual Semantic Relatedness Using Machine Translation",
bookTitle="Knowledge Engineering and Knowledge Management: 20th International Conference, EKAW 2016, Bologna, Italy, November 19-23, 2016, Proceedings",
year="2016",
publisher="Springer International Publishing",
address="Cham",
pages="212--222",
isbn="978-3-319-49004-5",
doi="10.1007/978-3-319-49004-5_14",
url="http://dx.doi.org/10.1007/978-3-319-49004-5_14"
}
```
