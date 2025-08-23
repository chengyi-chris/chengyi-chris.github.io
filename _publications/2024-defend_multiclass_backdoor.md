---
title: "Defending against Clean-Image Backdoor Attack in Multi-Label Classification"
collection: publications
category: conferences
permalink: /publication/2024_defend_multiclass_backdoor
authors: <strong>Cheng-Yi Lee</strong>, Cheng-Chang Tsai, Ching-Chia Kao, Chun-Shien Lu, Chia-Mu Yu
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2024
date: 2024-04-14
venue: 'IEEE International Conference on Acoustics, Speech and Signal Processing (<strong>ICASSP</strong>)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10447895'
posterlink: #'/files/AAAI24_poster.pdf'
citation: 'Cheng-Yi Lee, Cheng-Chang Tsai, Ching-Chia Kao, Chun-Shien Lu, Chia-Mu Yu. (2024). "Defending against Clean-Image Backdoor Attack in Multi-Label Classification" <i>ICASSP</i>.'

---

Deep neural networks (DNNs) are known to be vulnerable to backdoor attacks. Specifically, the attacker endeavors to implant backdoors in the DNN model by injecting a set of poisoning samples such that the malicious model predicts target labels once the backdoor is triggered. 
The clean-image attack has recently emerged as a threat in multi-label classification, where an attacker is able to poison training labels without tampering with image contents. 
In this paper, we propose a simple but effective method to alleviate clean-image backdoor attacks. Considering the difference in weight convergence between the benign model and backdoor model, our method relies on partial weight initialization and fine-tuning to mitigate the backdoor behaviors of a suspicious model. 
The fine-tuned model sustains its clean accuracy through knowledge distillation over a few iterations. Importantly, our approach does not require extra clean images for purification. 
Extensive experiments demonstrate the effectiveness of our defenses against clean-image attacks for multi-label classifications across two benchmark datasets.
