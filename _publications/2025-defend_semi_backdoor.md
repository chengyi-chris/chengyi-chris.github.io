---
title: "Defending Against Repetitive Backdoor Attacks on Semi-supervised Learning through Lens of Rate-Distortion-Perception Trade-off"
collection: publications
permalink: /publication/2025_defend_semi_backdoor
authors: <strong>Cheng-Yi Lee</strong>, Ching-Chia Kao, Cheng-Han Yeh, Chun-Shien Lu, Chia-Mu Yu, Chu-Song Chen
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2024
date: 2024-02-28  # Also make sure the date format is correct
venue: 'IEEE/CVF Winter Conference on Applications of Computer Vision (<strong>WACV</strong>)'
paperurl: #'/files/2024_AAAI.pdf'
posterlink: #'/files/AAAI24_poster.pdf'
codelink: #'https://github.com/lixi1994/TDBA-VAR'
citation: 'Cheng-Yi Lee, Ching-Chia Kao, Cheng-Han Yeh, Chun-Shien Lu, Chia-Mu Yu, Chu-Song Chen. (2025). "Defending Against Repetitive Backdoor Attacks on Semi-supervised Learning through Lens of Rate-Distortion-Perception Trade-off." <i>WACV</i>.'
header:
  teaser: #"2024_AAAI.png"
---

Semi-supervised learning (SSL) has achieved remarkable performance with a small fraction of labeled data by leveraging vast amounts of unlabeled data from the Internet. 
However, this large pool of untrusted data is extremely vulnerable to data poisoning, leading to potential backdoor attacks. Current backdoor defenses are not yet effective against such a vulnerability in SSL. 
In this study, we propose a novel method, Unlabeled Data Purification (UPure), to disrupt the association between trigger patterns and target classes by introducing perturbations in the frequency domain. 
By leveraging the Rate- Distortion-Perception (RDP) trade-off, we further identify the frequency band, where the perturbations are added, and justify this selection. 
Notably, UPure purifies poisoned unlabeled data without the need of extra clean labeled data. 
Extensive experiments on four benchmark datasets and five SSL algorithms demonstrate that UPure effectively reduces the attack success rate from 99.78% to 0% while maintaining model accuracy.
