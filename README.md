# LTD: Low Temperature Distillation for Robust Adversarial Training

The code for the paper [LTD: Low Temperature Distillation for Robust Adversarial Training](https://arxiv.org/abs/2111.02331).

The details will be released soon.


# Performance

## CIFAR-10 (Linf, eps=8/255 without additional data)

| # | Paper | Clean accuracy | Robust accuracy | Architecture | Venue |
|:---:|---|:---:|:---:|:---:|:---:|
| 1 | *[Towards Achieving Adversarial Robustness Beyond Perceptual Limits](https://openreview.net/forum?id=SHB_znlW5G7)* | 85.32% | 58.04% | WideResNet-34-10 | OpenReview, Jun 2021 |
| **2** | *[LTD: Low Temperature Distillation for Robust Adversarial Training](https://arxiv.org/abs/2111.02331)* | 86.03% | 57.71% | WideResNet-34-20 | arXiv, Nov 2021 |
| 3 | *[Uncovering the Limits of Adversarial Training against Norm-Bounded Adversarial Examples](https://arxiv.org/abs/2010.03593)* | 85.29% | 57.20% | WideResNet-70-16 | arXiv, Oct 2020 |
| **4** | *[LTD: Low Temperature Distillation for Robust Adversarial Training](https://arxiv.org/abs/2111.02331)* | 85.21% | 56.94% | WideResNet-34-10 | arXiv, Nov 2021 |
| 5 | *[Uncovering the Limits of Adversarial Training against Norm-Bounded Adversarial Examples](https://arxiv.org/abs/2010.03593)* | 85.64% | 56.86% | WideResNet-34-20 | arXiv, Oct 2020 |

## CIFAR-100 (Linf, eps=8/255 without additional data)

| # | Paper | Clean accuracy | Robust accuracy | Architecture | Venue |
|:---:|---|:---:|:---:|:---:|:---:|
| **1** | *[LTD: Low Temperature Distillation for Robust Adversarial Training](https://arxiv.org/abs/2111.02331)* | 64.07% | 30.59% | WideResNet-34-10 | arXiv, Nov 2021 |
| 2 | *[Towards Achieving Adversarial Robustness Beyond Perceptual Limits](https://openreview.net/forum?id=SHB_znlW5G7)* | 65.73% | 30.35% | WideResNet-34-10 | OpenReview, Jun 2021 |
| 3 | *[Learnable Boundary Guided Adversarial Training](https://arxiv.org/abs/2011.11164)* | 62.55% | 30.20% | WideResNet-34-20 | ICCV 2021 |
| 4 | *[Uncovering the Limits of Adversarial Training against Norm-Bounded Adversarial Examples](https://arxiv.org/abs/2010.03593)* | 60.86% | 30.03% | WideResNet-70-16 | arXiv, Oct 2020 |
| 5 | *[Learnable Boundary Guided Adversarial Training](https://arxiv.org/abs/2011.11164)* | 60.64% | 29.33% | WideResNet-34-10 | ICCV 2021 |
