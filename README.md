# Generation and Statistical Analysis of Quantum Random Numbers Using IBM Quantum Computers
## [QOSF Mentorship Program](https://qosf.org/)

**Cohort**: 9

**Mentor**: [Cameron Foreman](https://github.com/cforeman-cqc)

A [technical document](https://github.com/philipilono/increasing_randomness/blob/main/RNG_Cloud_Quantum_Computers.pdf) was produced as the main deliverable of this project and aims to provide a thorough description and analysis of the protocols implemented within the porject.

## Project Overview:
The project explores the generation and evaluation of random numbers using quantum mechanical principles, specifically leveraging IBM’s quantum computers. Random number generation (RNG) is an essential part of many computing techniques, simulations, and cryptography. True randomness may not be guaranteed by traditional RNG techniques, which rely on pseudo-random algorithms or deterministic processes. Quantum mechanics, on the other hand, offers an essentially probabilistic framework that can result in outcomes that are essentially random. Using these quantum concepts, this research creates random numbers, examines their statistical characteristics, and applies algorithmic post-processing to enhance their quality. Two-source extractors are the primary implementation tool, and the [cryptomite library](https://github.com/CQCL/cryptomite) offers a practical and open-source way to use them.

## Statistical Analysis:

The lower bound of entropy of bitstrings was used as the metric to evaluate randomness. An open-source tool for estimating entropy of RNGs is the [SP800-90B_EntropyAssessment](https://github.com/usnistgov/SP800-90B_EntropyAssessment) package. It offers statistical testing and analytical techniques that are in compliance with NIST recommendations. It is commonly used in academic research on randomness and entropy, compliance testing, and cryptographic development. It's respective [documentation](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-90B.pdf) also provides a thorough guide and description of analystical tests.

## References:

[1] C. Foreman, R. Yeung, and F. J. Curchod, “Statistical testing of random number generators and their improvement
using randomness extraction,” arXiv preprint arXiv:2403.18716, 2024.
