---
layout: post
title:  "VFAE_tensorflow_implementation"
date: 2018-02-10
comments: true
categories: ML
---
![vfae-graph]({{site.url}}/images/vfae-graph.png)

Some links for VFAE material:

- [the original paper](https://arxiv.org/pdf/1511.00830.pdf)
- [a previous post summarizing the paper]({{ site.baseurl }}{% post_url 2018-02-02-zemel-et-al-2016 %})
- [a previous post where I work out some of the math found in the paper]({{ site.baseurl }}{% post_url 2018-02-09-vfaes-math %})

In today's post, I will go over my tensorflow implementation of the VFAE by using
the MNIST dataset.
