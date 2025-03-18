---
title: "Sequence-to-short Sequence Learning with Attention Based Autoencoders for Non-Intrusive Load Monitoring"
collection: publications
category: writeups
permalink: /publication/2024-03-17-paper-title-number-7
excerpt: 'This write up presents a novel attention based auto-encoder model for non-intrusive load monitoring.'
date: 2022-03-01
paperurl: 'http://mevanwijewardena.github.io/files/paper7.pdf'
citation: 'Wijewardena, M., Pathiranage, S., Nanyakkara, T., Rajapakshe, I. (2022). Sequence-to-short Sequence Learning with Attention Based Autoencoders for Non-Intrusive Load Monitoring.'
---

## Abstract 

Non-intrusive load monitoring (NILM) involves inferring the appliance level power
usage of a consumer given the aggregate power consumption. Different methodologies have been proposed for NILM and recently the focus has shifted towards
deep learning-based approaches. These models utilize sliding window-based approaches for sequence modelling due to limitations in dealing with long input
sequences. This paper proposes sequence-to-short sequence learning, where a
sub-sequence of an appliance level power window corresponding to the input window is expected as the output from the learning model. Due to the recent success
of attention-based models in sequence modelling, a novel attention-based autoencoder architecture with multiple attention heads is proposed. The attention heads
can extract the relevant signatures of the input sequence by learning to forget the
irrelevant signatures. The paper explores how the attention-based autoencoder architecture in conjunction with sequence-to-short sequence learning can be used to
improve both the accuracy and the real-time capability of NILM systems. The performance of our model is evaluated by comparing it with a state-of-the-art model.
In addition, the robustness of our model to noisy data is empirically evaluated
using a custom dataset.




