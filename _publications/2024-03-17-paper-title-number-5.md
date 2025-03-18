---
title: "Multi-Player Resource-Sharing Games with Fair Reward Allocation"
collection: publications
category: reports
permalink: /publication/2024-03-17-paper-title-number-5
excerpt: 'This paper develops online algorithms for a multi-player resource-sharing game with bandit feedback.'
date: 2024-02-07
venue: 'arXiv preprint'
paperurl: 'http://mevanwijewardena.github.io/files/paper5.pdf'
citation: 'Wijewardena, M., & Neely, M. (2024). Multi-Player Resource-Sharing Games with Fair Reward Allocation. arXiv preprint arXiv:2402.05300.'
---

## Abstract 
This paper considers an online multi-player resource-sharing game with bandit feedback. Multiple players choose from a finite collection of resources in a time slotted system. In each time slot, each resource brings a random reward that is equally divided among the players who choose it. The reward vector is independent and identically distributed over the time slots. The statistics of the reward vector are unknown to the players. During each time slot, for each resource chosen by the first player, they receive as feedback the reward of the resource and the number of players who chose it, after the choice is made. We develop a novel Upper Confidence Bound (UCB) algorithm that learns the mean rewards using the feedback and maximizes the worst-case time-average expected reward of the first player. The algorithm gets within O(log(T)/T−−√) of optimality within T time slots. The simulations depict fast convergence of the learnt policy in comparison to the worst-case optimal policy.

