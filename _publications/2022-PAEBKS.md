---
title: "Privacy-preserving bidirectional keyword search over encrypted data for cloud-assisted IIoT"
collection: publications
category: manuscript
permalink: /publication/2022-PAEBKS
authors: <strong>Cheng-Yi Lee</strong>, Zi-Yuan Liu, Raylin Tso, Yi-Fan Tseng
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
year: 2022
date: 2022-09-01
venue: 'Journal of Systems Architecture'
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1383762122001631'
codelink: 'https://github.com/chengyi-chris/PAEBKS'
citation: 'Cheng-Yi Lee, Zi-Yuan Liu, Raylin Tso, Yi-Fan Tseng. (2022). "Privacy-preserving bidirectional keyword search over encrypted data for cloud-assisted IIoT." <i>Journal of Systems Architecture</i>. 130 (2022): 102642.'
---

Cloud-assisted industrial Internet of Things (IIoT) technology is increasingly used by related enterprises. To preserve the privacy of sensitive data, IIoT devices must encrypt data before sending them to a cloud server. Public-key encryption with keyword search (PEKS) provides an important search function over cloud-assisted IIoT, allowing users to search for encrypted data without decryption. 
To increase practical functionality, Zhang et al. recently proposed the concept of public-key encryption with bidirectional keyword search, which supports both sender and receiver searches. However, their scheme provides insufficient security because it cannot resist keyword guessing attacks (KGA). 
Additionally, their scheme requires time-consuming bilinear pairing operations, resulting in high computational costs. In this study, a novel concept called public-key authenticated encryption with bidirectional keyword search was devised for multi-user settings. 
The system definition and security requirements are formally defined to ensure that no adversary can overcome the indistinguishability against chosen-keyword attacks or KGA. Furthermore, we propose a pairing-free semi-generic construction, combining a multiparty non-interactive protocol and authenticated functionality, which has proven to be secure under the standard model. 
The experimental results reveal that, compared with other state-of-the-art schemes, the proposed scheme is more practical, secure, and suitable for use with cloud-assisted IIoT systems.
