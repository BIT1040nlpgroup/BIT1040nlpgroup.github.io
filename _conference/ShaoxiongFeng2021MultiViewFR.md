---
title: "Multi-View Feature Representation for Dialogue Generation with Bidirectional Distillation"
collection: conference
permalink: /conference/ShaoxiongFeng2021MultiViewFR
date: 2021-01-01
venue: AAAI
author: Shaoxiong Feng, Xuancheng Ren, Kan Li, Xu Sun.
paperurl: 'https://arxiv.org/abs/2102.10780'
---
Author: Shaoxiong Feng, Xuancheng Ren, Kan Li, Xu Sun

Published in: AAAI

### Abstract

Neural dialogue models suffer from low-quality responses when interacted in practice, demonstrating difficulty in generalization beyond training data. Recently, knowledge distillation has been used to successfully regularize the student by transferring knowledge from the teacher. However, the teacher and the student are trained on the same dataset and tend to learn similar feature representations, whereas the most general knowledge should be found through differences. The finding of general knowledge is further hindered by the unidirectional distillation, as the student should obey the teacher and may discard some knowledge that is truly general but refuted by the teacher. To this end, we propose a novel training framework, where the learning of general knowledge is more in line with the idea of reaching consensus, i.e., finding common knowledge that is beneficial to different yet all datasets through diversified learning partners. Concretely, the training task is divided into a group of subtasks with the same number of students. Each student assigned to one subtask not only is optimized on the allocated subtask but also imitates multi-view feature representation aggregated from other students (i.e., student peers), which induces students to capture common knowledge among different subtasks and alleviates the over-fitting of students on the allocated subtasks. To further enhance generalization, we extend the unidirectional distillation to the bidirectional distillation that encourages the student and its student peers to co-evolve by exchanging complementary knowledge with each other. Empirical results and analysis demonstrate that our training framework effectively improves the model generalization without sacrificing training efficiency.

---

Recommended citation:

**Shaoxiong Feng**, Xuancheng Ren, Kan Li, and Xu Sun. *The 35th AAAI conference on Artificial Intelligence*. **AAAI 2021**.
