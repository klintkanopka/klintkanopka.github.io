---
layout: page
title: CAT Item Pools
description: A network-based approach to item pool maintenance in computer adaptive tests
img: assets/img/projects/cat_pool.png
importance: 1
category: current
related_publications: false
---

Computer adaptive testing has delivered enormous advances in measurement efficiency and test security, though new issues persist. Maintaining a sufficiently large item pool requires constantly managing item exposure patterns, rotating out overexposed items, and calibrating new items. Additionally, parameter drift presents an additional maintenance task of pool recalibration, further complicated by potential bias in estimated parameters due to item delivery that prioritizes testing efficiency.

We propose representing the state of the item pool as a network. Here, individual items are nodes with edges connecting items with responses from the same individual, weighted by the inverse number of co-respondents. This builds a natural sense of distance, giving the shortest weighted path between two items the interpretation of an indicator of the magnitude of potential relative calibration error. Additionally, it provides a natural metric to optimize when selecting items to deliver for pool quality maintenance: network diameter, or the longest-shortest path between items. New item selection algorithms can balance pool maintenance and maximum information on the fly. Finally, network structure allows for the adaptation of message passing from graph neural networks to engage in local online item recalibration, combating parameter drift.