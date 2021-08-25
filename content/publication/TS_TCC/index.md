---
title: Time Series Representation Learning via Temporal and Contextual Contrasting
subtitle: International Joint Conference of Artificial Intelligence, IJCAI, 2021
publication_types:
  - "1"
authors:
  - Emadeldeen Eldele
  - Mohamed Ragab
  - Zhenghua Chen
  - Min Wu
  - Chee-Keong Kwoh
  - Xiaoli Li
  - Cuntai Guan
publication: International Joint Conference of Artificial Intelligence, IJCAI, 2021
publication_short: In International Joint Conference of Artificial Intelligence, IJCAI, 2021
abstract: Learning decent representations from unlabeled time-series data with
  temporal dynamics is a very challenging task. In this paper, we propose an
  unsupervised Time-Series representation learning framework via Temporal and
  Contextual Contrasting (TS-TCC), to learn time-series representation from
  unlabeled data. First, the raw time-series data are transformed into two
  different yet correlated views by using weak and strong augmentations. Second,
  we propose a novel temporal contrasting module to learn robust temporal
  representations by designing a tough cross-view prediction task. Last, to
  further learn discriminative representations, we propose a contextual
  contrasting module built upon the contexts from the temporal contrasting
  module. It attempts to maximize the similarity among different contexts of the
  same sample while minimizing similarity among contexts of different samples.
  Experiments have been carried out on three real-world time-series datasets.
  The results manifest that training a linear classifier on top of the features
  learned by our proposed TS-TCC performs comparably with the supervised
  training. Additionally, our proposed TS-TCC shows high efficiency in
  few-labeled data and transfer learning scenarios. The code is publicly
  available at this https URL
draft: false
featured: true
tags:
  - exampe
categories:
  - example
projects:
  - example
slides: example
code: example
image:
  filename: ts_tcc.png
  focal_point: Smart
  preview_only: false
  caption: ""
date: 2021-08-24T07:29:41.915Z
---
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Click the *code* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).