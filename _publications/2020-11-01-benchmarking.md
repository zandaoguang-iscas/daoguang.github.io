---
title: "Benchmarking Meaning Representations in Neural Semantic Parsing"
collection: publications
permalink: /publication/2020-11-01-benchmarking
excerpt: 'Jiaqi Guo, **Qian Liu**, Jian-Guang Lou, Zhenwen Li, Xueqing Liu, Tao Xie, Ting Liu<br>In *Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing* (**EMNLP-2020**)'
date: 2020-11-01
venue:
---

\[[PAPER](https://www.aclweb.org/anthology/2020.emnlp-main.118.pdf)\] \[[CODE](https://github.com/JasperGuo/Unimer)\]


![Demo](/images/benchmarking-demo.jpg)

Meaning representation is an important component of semantic parsing.
Although researchers have designed a lot of meaning representations, recent work focuses on only a few of them. Thus, the impact of meaning representation on semantic parsing is less understood. Furthermore, existing work’s performance is often not comprehensively evaluated due to the lack of readily-available execution engines. Upon identifying these gaps, we propose , a new unified benchmark on meaning representations, by integrating existing semantic parsing datasets, completing the missing logical forms, and implementing the missing execution engines. The resulting unified benchmark contains the complete enumeration of logical forms and execution engines over three datasets × four meaning representations. **A thorough experimental study on Unimer reveals that neural semantic parsing approaches exhibit notably different performance when they are trained to generate different meaning representations**. Also, program alias and grammar rules heavily impact the performance of different meaning representations.

Cite
===

```latex
@inproceedings{guo2020benchmarking,
  title={Benchmarking Meaning Representations in Neural Semantic Parsing},
  author={Guo, Jiaqi and Liu, Qian and Lou, Jian-Guang and Li, Zhenwen and Liu, Xueqing and Xie, Tao and Liu, Ting},
  booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  pages={1520--1540},
  year={2020}
}
```