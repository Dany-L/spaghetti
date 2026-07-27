---
title: "Robust Recurrent Neural Network to Identify Ship Motion in Open Water with Performance Guarantees"
collection: publications
permalink: /publication/2022-11-30-robust-sysid-ship-motion
excerpt: 'We represent a recurrent neural network as a linear time-invariant system with nonlinear disturbances and introduce parameter constraints that guarantee finite gain stability, applied to learning ship motion in open water.'
date: 2022-11-30
venue: 'Technical report, arXiv'
paperurl: 'https://arxiv.org/abs/2212.05781'
citation: 'Frank, D., Aspandi Latif, D., Muehlebach, M., Unger, B., &amp; Staab, S. (2022). &quot;Robust recurrent neural network to identify ship motion in open water with performance guarantees.&quot; Technical report, <i>arXiv:2212.05781</i>.'
---
Recurrent neural networks are capable of learning the dynamics of an unknown nonlinear system purely from input-output measurements. However, the resulting models do not provide any stability guarantees on the input-output mapping. In this work, we represent a recurrent neural network as a linear time-invariant system with nonlinear disturbances. By introducing constraints on the parameters, we can guarantee finite gain stability and incremental finite gain stability. We apply this identification method to learn the motion of a four-degrees-of-freedom ship that is moving in open water and compare it against other purely learning-based approaches with unconstrained parameters. Our analysis shows that the constrained recurrent neural network has a lower prediction accuracy on the test set, but it achieves comparable results on an out-of-distribution set and respects stability conditions.

[Download paper here](https://arxiv.org/abs/2212.05781)

Frank, D., Aspandi Latif, D., Muehlebach, M., Unger, B., &amp; Staab, S. (2022). "Robust recurrent neural network to identify ship motion in open water with performance guarantees." Technical report, <i>arXiv:2212.05781</i>.
