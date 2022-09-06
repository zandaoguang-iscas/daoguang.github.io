---
title: "RECPARSER: A Recursive Semantic Parsing Framework for Text-to-SQL Task"
collection: publications
permalink: /publication/2020-06-12-recparser
excerpt: 'Yu Zeng, Yan Gao, Jiaqi Guo, Bei Chen, **Qian Liu**, Jian-Guang Lou, Fei Teng, Dongmei Zhang<br>In *Twenty-ninth International Joint Conference on Artificial Intelligence (**IJCAI-2020**)*'
date: 2020-06-12
venue:
---

\[[PAPER](https://www.microsoft.com/en-us/research/uploads/prod/2020/06/RECPARSER.pdf)\]


<div style="width:100%;">
    <img src="/images/recparser-demo.JPG" style=" display: block;height:300px;vertical-align: middle;margin-left: auto;margin-right: auto;">
</div>

Neural semantic parsers usually fail to parse long and complicated utterances into nested SQL queries, due to the large search space. In this paper, we propose a novel recursive semantic parsing framework called RECPARSER to generate the nested SQL query layer-by-layer. It decomposes the complicated nested SQL query generation problem into several progressive non-nested SQL query generation problems. Furthermore, we propose a novel Question Decomposer module to explicitly encourage RECPARSER to focus on different components of utterance when predicting SQL queries in different layers. Experiments on Spider dataset show that our approach is more effective compared to the previous works at predicting the nested SQL queries. In addition, we obtain an overall accuracy that is comparable with the state-of-the-art approaches.


Cite
===

```latex
@inproceedings{yu2020recparser,
  title={RECPARSER: A Recursive Semantic Parsing Framework for Text-to-SQL Task},
  author={Yu Zeng, Yan Gao, Jiaqi Guo, Bei Chen, **Qian Liu**, Jian-Guang Lou, Fei Teng, Dongmei Zhang},
  booktitle={IJCAI},
  year={2020}
}
```