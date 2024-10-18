---
title: "Design and Embedded Implementation of Secure Image Encryption Scheme Using DWT and 2D-LASM"
collection: publications
category: manuscripts
permalink: /publication/Design and Embedded Implementation of Secure Image Encryption Scheme Using DWT and 2D-LASM
excerpt: 'IF:2.738  SCIE  JCR-Q2  中科院3区  \(2022\)'
date: 2022-09-22
venue: 'Entropy'
# slidesurl: 'https://donotwanttogrowup.github.io/YitingLin.github.io/files/slides1.pdf'
paperurl: 'https://donotwanttogrowup.github.io/files/Design and Embedded Implementation of Secure Image Encryption Scheme Using DWT and 2D-LASM.pdf'
citation: 'Wen, H., Chen, Z., Zheng, J., Huang, Y., Li, S., Ma, L., Lin, Y., Liu, Z., Li, R., Liu, L., Lin, W., Yang, J., Zhang, C., & Yang, H. (2022). Design and Embedded Implementation of Secure Image Encryption Scheme Using DWT and 2D-LASM. In Entropy (Vol. 24, Issue 10, p. 1332). MDPI AG. https://doi.org/10.3390/e24101332
'
---

In order to further improve the information effectiveness of digital image transmission, an image-encryption algorithm based on 2D-Logistic-adjusted-Sine map (2D-LASM) and Discrete Wavelet Transform (DWT) is proposed. First, a dynamic key with plaintext correlation is generated using Message-Digest Algorithm 5 (MD5), and 2D-LASM chaos is generated based on the key to obtain a chaotic pseudo-random sequence. Secondly, we perform DWT on the plaintext image to map the image from the time domain to the frequency domain and decompose the low-frequency (LF) coefficient and high-frequency (HF) coefficient. Then, the chaotic sequence is used to encrypt the LF coefficient with the structure of “confusion-permutation”. We perform the permutation operation on HF coefficient, and we reconstruct the image of the processed LF coefficient and HF coefficient to obtain the frequency-domain ciphertext image. Finally, the ciphertext is dynamically diffused using the chaotic sequence to obtain the final ciphertext. Theoretical analysis and simulation experiments show that the algorithm has a large key space and can effectively resist various attacks. Compared with the spatial-domain algorithms, this algorithm has great advantages in terms of computational complexity, security performance, and encryption efficiency. At the same time, it provides better concealment of the encrypted image while ensuring the encryption efficiency compared to existing frequency-domain methods. The successful implementation on the embedded device in the optical network environment verifies the experimental feasibility of this algorithm in the new network application.