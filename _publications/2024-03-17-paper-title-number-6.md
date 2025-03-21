---
title: "Automatic Link Selection in Multi-Channel Multiple Access with Link Failures"
collection: publications
category: reports
permalink: /publication/2024-03-17-paper-title-number-6
excerpt: 'This paper focuses on the problem of automatic link selection in multi-channel multiple access control using bandit feedback.'
date: 2025-01-24
venue: 'arXiv preprint'
paperurl: 'https://mevanwijewardena.github.io/files/paper6.pdf'
citation: 'Wijewardena, M., & Neely, M. J. (2025). Automatic Link Selection in Multi-Channel Multiple Access with Link Failures. arXiv preprint arXiv:2501.14971.'
---

## Abstract

This paper focuses on the problem of automatic link selection in multi-channel multiple access control using bandit feedback. In particular, a controller assigns multiple users to multiple channels in a time slotted system, where in each time slot at most one user can be assigned to a given channel and at most one channel can be assigned to a given user. Given that user ${i}$ is assigned to channel ${j}$, the transmission fails with a fixed probability ${f_{i,j}}$. The failure probabilities are not known to the controller. The assignments are made dynamically using success/failure feedback. The goal is to maximize the time average utility, where we consider an arbitrary (possibly nonsmooth) concave and entrywise nondecreasing utility function. The problem of merely maximizing the total throughput has a solution of always assigning the same user-channel pairs and can be unfair to certain users, particularly when the number of channels is less than the number of users. Instead, our scheme allows various types of fairness, such as proportional fairness, maximizing the minimum, or combinations of these by defining the appropriate utility function. We propose two algorithms for this task. The first algorithm is adaptive and gets within ${O(\log(T)/T^{1/3})}$ of optimality over any interval of ${T}$ consecutive slots over which the success probabilities do not change. The second algorithm has faster ${O(\log(T)/\sqrt{T})}$ performance over the first ${T}$ slots, but does not adapt well if probabilities change.


