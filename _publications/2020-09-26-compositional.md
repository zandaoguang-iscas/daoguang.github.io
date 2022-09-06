---
title: "Compositionality Generalization by Learning Analytical Expressions"
collection: publications
permalink: /publication/2020-09-26-compositional
excerpt: '**Qian Liu**\*, Shengnan An\*, Jian-Guang Lou, Bei Chen, Zeqi Lin, Yan Gao, Bin Zhou, Nanning Zheng, Dongmei Zhang<br> In *Advances in Neural Information Processing Systems 34 (**NeurIPS-2020**,<span style="color:red;"><b>Spotlight</b></span>)*'
date: 2020-09-26
venue:
---

\[[PAPER](https://arxiv.org/pdf/2006.10627.pdf)\] \[[CODE](https://github.com/microsoft/ContextualSP/tree/master/compositional_generalization)\] \[[MEDIA](https://mp.weixin.qq.com/s/8Cv76I4SUfnPm88cAqrBRg)\]



![Demo](/images/compositional-demo.JPG)

Compositional generalization is a basic but essential intellective capability of human beings, which allows us to recombine known parts readily.
However, existing neural network based models have been proven to be extremely deficient in such a capability.
Inspired by work in cognition which argues compositionality can be captured by variable slots with symbolic functions, we present a refreshing view that connects a memory-augmented neural model with analytical expressions, to achieve compositional generalization.
Our model consists of two cooperative neural modules Composer and Solver, fitting well with the cognitive argument while still being trained in an end-to-end manner via a hierarchical reinforcement learning algorithm.
Experiments on a well-known benchmark SCAN demonstrate that our model seizes a great ability of compositional generalization, **solving all challenges addressed by previous works with 100% accuracies**.

Cite
===

```latex
@inproceedings{qian2020compositionality,
  title={Compositionality Generalization by Learning Analytical Expressions},
  author={Liu, Qian and An, Shengnan and Lou, Jian-Guang and Chen, Bei and Lin, Zeqi and Gao, Yan and Zhou, Bin and Zheng, Nanning and Zhang, Dongmei},
  booktitle={NeurIPS},
  year={2020}
}
```