---
title: "Awakening Latent Grounding from Pretrained Language Models for Semantic Parsing"
collection: publications
permalink: /publication/2021-05-06-awakening
excerpt: '**Qian Liu**\*, Dejian Yang\*, Jiahui Zhang\*, Jiaqi Guo, Bin Zhou, Jian-Guang Lou<br>In *Findings of the Association for Computational Linguistics: ACL-IJCNLP 2021* (**ACL-2021 Findings**)'
date: 2021-05-06
venue:
---

\[[PAPER](https://aclanthology.org/2021.findings-acl.100.pdf)\]


![Demo](/images/awaken-demo.gif)

Recent years pretrained language models (PLMs) hit a success on several downstream tasks, showing their power on modeling language. To better understand and leverage what PLMs have learned, several techniques have emerged to explore syntactic structures entailed by PLMs. However, few efforts have been made to explore **grounding capabilities** of PLMs, which are also essential. 

In this paper, we highlight the ability of PLMs to discover which token should be grounded to which concept, if combined with our proposed erasing-then-awakening approach. Empirical studies on **four datasets** (including both schema linking and entity linking) demonstrate that our approach can awaken latent grounding which is understandable to human experts, even if it is not exposed to such labels during training. 

More importantly, our approach shows great potential to benefit downstream semantic parsing models. Taking **text-to-SQL** as a case study, we successfully couple our approach with **two off-the-shelf** parsers, obtaining an absolute improvement of up to **9.8%**. 

Cite
===

```latex
@inproceedings{liu-etal-2021-awakening,
    title = "Awakening Latent Grounding from Pretrained Language Models for Semantic Parsing",
    author = "Liu, Qian  and
      Yang, Dejian  and
      Zhang, Jiahui  and
      Guo, Jiaqi  and
      Zhou, Bin  and
      Lou, Jian-Guang",
    booktitle = "Findings of the Association for Computational Linguistics: ACL-IJCNLP 2021",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.findings-acl.100",
    doi = "10.18653/v1/2021.findings-acl.100",
    pages = "1174--1189",
}
```