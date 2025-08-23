---
title: "Privacy-enhanced Data Sharing Systems from Hierarchical ID-based Puncturable Functional Encryption with Inner Product Predicates"
collection: publications
permalink: /publication/2024_HIBP-IPFE
authors: <strong>Cheng-Yi Lee</strong>, Zi-Yuan Liu, Masahiro Mambo, Raylin Tso
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2024
date: 2024-10-01  # Also make sure the date format is correct
venue: 'IET Information Security'
paperurl: #'/files/2024_AAAI.pdf'
posterlink: #'/files/AAAI24_poster.pdf'
codelink: 'https://github.com/chengyi-chris/HIBP-IPFE'
citation: 'Cheng-Yi Lee, Zi-Yuan Liu, Masahiro Mambo, Raylin Tso. (2024). "Privacy-enhanced Data Sharing Systems from Hierarchical ID-based Puncturable Functional Encryption with Inner Product Predicates." <i>IET Information Security</i>.'
---

The emergence of cloud computing enables users to upload data to remote clouds and compute them. This drastically reduces computing and storage costs for users. Considering secure computing for multi-level users in enterprises, the notion of hierarchical identity-based inner product functional encryption (HIB-IPFE) is proposed. 
In this cryptosystem, a sender can encrypt a vector $\vec{x}$ into a ciphertext with a hierarchical identity, while a receiver who possesses a secret key corresponding to the same hierarchical identity and a vector $\vec{y}$ can decrypt the ciphertext and obtain the inner product $\langle \vec{x}, \vec{y} \rangle$. However, HIB-IPFE is not sufficient to capture flexible data sharing and forward security. 
In this study, we present a notion of hierarchical identity-based puncturable inner product functional encryption (HIBP-IPFE). Furthermore, we present a formal definition and security model of HIBP-IPFE to guarantee data confidentiality and receiver anonymity. 
Compared with HIB-IPFE, our proposed scheme enables users to puncture keys on specific tags ensuring that the punctured keys cannot be used to decrypt the ciphertexts associated with those tags. 
The proposed scheme is provably secure under $d$-DBDHE assumption in the standard model. The experimental results indicate that our scheme is more practical in cloud computing, with superior functionality.
