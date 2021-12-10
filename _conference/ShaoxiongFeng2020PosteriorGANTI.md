---
title: "Posterior-GAN: Towards Informative and Coherent Response Generation with Posterior Generative Adversarial Network"
collection: conference
permalink: /conference/ShaoxiongFeng2020PosteriorGANTI
date: 2020-01-01
venue: AAAI
author: Shaoxiong Feng, Hongshen Chen, Kan Li, Dawei Yin.
paperurl: 'https://readpaper.com/paper/2997955173'
---
Author: Shaoxiong Feng, Hongshen Chen, Kan Li*, Dawei Yin

Published in: AAAI

### Abstract

Neural conversational models learn to generate responses by taking into account the dialog history. These models are typically optimized over the query-response pairs with a maximum likelihood estimation objective. However, the query-response tuples are naturally loosely coupled, and there exist multiple responses that can respond to a given query, which leads the conversational model learning burdensome. Besides, the general dull response problem is even worsened when the model is confronted with meaningless response training instances. Intuitively, a high-quality response not only responds to the given query but also links up to the future conversations, in this paper, we leverage the query-response-future turn triples to induce the generated responses that consider both the given context and the future conversations. To facilitate the modeling of these triples, we further propose a novel encoder-decoder based generative adversarial learning framework, Posterior Generative Adversarial Network (Posterior-GAN), which consists of a forward and a backward generative discriminator to cooperatively encourage the generated response to be informative and coherent by two complementary assessment perspectives. Experimental results demonstrate that our method effectively boosts the informativeness and coherence of the generated response on both automatic and human evaluation, which verifies the advantages of considering two assessment perspectives.

---

Recommended citation:

```
@inproceedings{ShaoxiongFeng2020PosteriorGANTI,
  title={Posterior-GAN: Towards Informative and Coherent Response Generation with Posterior Generative Adversarial Network},
  author={Shaoxiong Feng and Hongshen Chen and Kan Li and Dawei Yin},
  booktitle={National Conference on Artificial Intelligence},
  year={2020}
}
```
