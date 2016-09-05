+++
client_name = ""
date = "2016-04-03"
image = ""
image_preview = ""
summary = "Stochastic Average Gradient Descent: mini-batch and distributed implementations"
tags = []
title = "Mini-batch and distributed SAGA"
external_link = ""

+++

This is a small project with [Michaël Defferrard](https://people.epfl.ch/michael.defferrard) for the [Advanced Topics in Data Sciences](http://lions.epfl.ch/cms/site/lions2/lang/en/advanced_topics_data_2016) course. It explored two approaches to improve the [SAGA incremental
gradient algorithm](https://papers.nips.cc/paper/5258-saga-a-fast-incremental-gradient-method-with-support-for-non-strongly-convex-composite-objectives.pdf):

1. Take gradients over mini-batches to reduce the memory requirement.
2. Compute gradients in parallel on multiple CPU cores to speed it up.

You can find a Python implementation of our mini-batch
approach, a MATLAB implementation of our distributed approach, a 4 page report, and our presentation slides in [our SAGA github repository](https://github.com/mdeff/saga). 
