---
title: On DNN Resiliency and GNN Representations Recoverability — Two Talks

#event: Wowchemy Conference
#event_url: https://example.org

#location: Wowchemy HQ
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: ''
abstract: 'First talk: Embracing the Resiliency of Deep Neural Networks–Rethinking Old Mechanisms. Deep neural networks (DNNs) have gained tremendous
momentum in recent years, both in academia and industry. Yet, DNNs are compute intensive and may require billions of multiply-and-accumulate
operations for a single input query. Limited resources, such as those in IoT devices, latency constraints, and high input throughput, all
drive research and development of efficient computing methods for DNN execution. In our research, we rethink two well-known CPU
methods – simultaneous multithreading (SMT) and value prediction – and map them to the new environment introduced by DNNs, by leveraging
their unique characteristics. With SMT, we propose a new concept of non-blocking SMT (NB-SMT), in which execution units are shared among
several computational flows to avoid idle MAC operations due to zero-valued operands. We present and discuss the path from a data-driven
“blocking” SMT design to the concept of NB-SMT, to a fine-tuned sparsity-aware quantization method. As for value prediction, we present
prediction schemes which leverage the inherent spatial correlation in CNN feature maps to predict zero-valued activations. By speculating
which activations will be zero-valued, we potentially reduce the required MAC operations.


Second talk: On a Recoverability of Graph Neural Network Representations. Despite their growing popularity, graph neural networks (GNNs) still have multiple
unsolved problems, including finding more expressive aggregation methods, propagation of information to distant nodes, and training on
large-scale graphs. Understanding and solving such problems require developing analytic tools and techniques. In this work, we propose
the notion of recoverability, which is tightly related to information aggregation in GNNs, and based on this concept, develop the method
for GNN embedding analysis. We define recoverability theoretically and propose a method for its efficient empirical estimation.
We demonstrate, through extensive experimental results on various datasets and different GNN architectures, that estimated recoverability
correlates with aggregation method expressivity and graph sparsification quality. Therefore, we believe that the proposed method could
provide an essential tool for understanding the roots of the aforementioned problems, and potentially lead to a GNN design that overcomes them.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-03-22T13:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - Dr. Gil Shomron
  - Dr. Chaim Baskin
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/ZiQkhI7417A)'
  focal_point: Right

links:
  - icon: youtube
    icon_pack: fab
    name: Watch
    url: https://youtu.be/_ONHs6Qm974
#  - icon: desktop
#    icon_pack: fas
#    name: Slides (Talk)
#    url: https://drive.google.com/file/d/1GWJ2B3_m8ykz5RV4_qsSujQu1BdmdbMn/view?usp=sharing
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---
