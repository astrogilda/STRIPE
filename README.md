# STRIPE: Shape and Time diverRsIty in Probabilistic forEcasting
[Vincent Le Guen](https://www.linkedin.com/in/vincentleguen/),  [Nicolas Thome](http://cedric.cnam.fr/~thomen/)

Code for our NeurIPS 20120 paper "Probabilistic Time Series Forecasting with Structured Shape and Temporal Diversity"

![](https://github.com/vincent-leguen/STRIPE/blob/main/fig_stripe.png)

If you find this code useful for your research, please cite our [paper](https://papers.nips.cc/paper/2020/file/2f2b265625d76a6704b08093c652fd79-Paper.pdf):

```
@incollection{leguen20stripe,
title = {Probabilistic Time Series Forecasting with Structured Shape and Temporal Diversity},
author = {Le Guen, Vincent and Thome, Nicolas},
booktitle = {Advances in Neural Information Processing Systems},
year = {2020}
}
```

## Abstract
Probabilistic forecasting consists in predicting a distribution of possible future
outcomes. In this paper, we address this problem for non-stationary time series,
which is very challenging yet crucially important. We introduce the STRIPE
model for representing structured diversity based on shape and time features,
ensuring both probable predictions while being sharp and accurate. STRIPE is
agnostic to the forecasting model, and we equip it with a diversification mechanism
relying on determinantal point processes (DPP). We introduce two DPP kernels
for modeling diverse trajectories in terms of shape and time, which are both
differentiable and proved to be positive semi-definite. To have an explicit control
on the diversity structure, we also design an iterative sampling mechanism to
disentangle shape and time representations in the latent space. Experiments carried
out on synthetic datasets show that STRIPE significantly outperforms baseline
methods for representing diversity, while maintaining accuracy of the forecasting
model. We also highlight the relevance of the iterative sampling scheme and the
importance to use different criteria for measuring quality and diversity. Finally,
experiments on real datasets illustrate that STRIPE is able to outperform state-ofthe-
art probabilistic forecasting approaches in the best sample prediction.

