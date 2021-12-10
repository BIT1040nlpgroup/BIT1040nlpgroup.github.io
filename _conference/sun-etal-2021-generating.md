---
title: "Generating Relevant and Coherent Dialogue Responses using Self-Separated Conditional Variational AutoEncoders"
collection: conference
permalink: /conference/sun-etal-2021-generating
date: 2021-01-01
venue: ACL
author: Bin Sun, Shaoxiong Feng, Yiwei Li, Jiamou Liu, Kan Li.
paperurl: 'https://aclanthology.org/2021.acl-long.437/'
---
Author: Bin Sun, Shaoxiong Feng, Yiwei Li, Jiamou Liu, Kan Li

Published in: ACL

### Abstract

Conditional Variational AutoEncoder (CVAE) effectively increases the diversity and informativeness of responses in open-ended dialogue generation tasks through enriching the context vector with sampled latent variables. However, due to the inherent one-to-many and many-to-one phenomena in human dialogues, the sampled latent variables may not correctly reflect the contexts’ semantics, leading to irrelevant and incoherent generated responses. To resolve this problem, we propose Self-separated Conditional Variational AutoEncoder (abbreviated as SepaCVAE) that introduces group information to regularize the latent variables, which enhances CVAE by improving the responses’ relevance and coherence while maintaining their diversity and informativeness. SepaCVAE actively divides the input data into groups, and then widens the absolute difference between data pairs from distinct groups, while narrowing the relative distance between data pairs in the same group. Empirical results from automatic evaluation and detailed analysis demonstrate that SepaCVAE can significantly boost responses in well-established open-domain dialogue datasets.

---

Recommended citation:

```
@inproceedings{sun-etal-2021-generating,
    title = "Generating Relevant and Coherent Dialogue Responses using Self-Separated Conditional Variational {A}uto{E}ncoders",
    author = "Sun, Bin  and
      Feng, Shaoxiong  and
      Li, Yiwei  and
      Liu, Jiamou  and
      Li, Kan",
    booktitle = "Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.acl-long.437",
    doi = "10.18653/v1/2021.acl-long.437",
    pages = "5624--5637",
    abstract = "Conditional Variational AutoEncoder (CVAE) effectively increases the diversity and informativeness of responses in open-ended dialogue generation tasks through enriching the context vector with sampled latent variables. However, due to the inherent one-to-many and many-to-one phenomena in human dialogues, the sampled latent variables may not correctly reflect the contexts{'} semantics, leading to irrelevant and incoherent generated responses. To resolve this problem, we propose Self-separated Conditional Variational AutoEncoder (abbreviated as SepaCVAE) that introduces group information to regularize the latent variables, which enhances CVAE by improving the responses{'} relevance and coherence while maintaining their diversity and informativeness. SepaCVAE actively divides the input data into groups, and then widens the absolute difference between data pairs from distinct groups, while narrowing the relative distance between data pairs in the same group. Empirical results from automatic evaluation and detailed analysis demonstrate that SepaCVAE can significantly boost responses in well-established open-domain dialogue datasets.",
}
```
