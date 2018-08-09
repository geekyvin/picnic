
Picnic
======

This is an reference implementation of The Picnic Signature Algorithm


A Family of Post-Quantum Secure Digital Signature Algorithms
------------------------------------------------------------

The Picnic family of digital signature algorithms is designed to provide security against attacks by quantum computers, in addition to attacks by classical computers. The building blocks are a zero-knowledge proof system (with post-quantum security), and symmetric key primitives like hash functions and block ciphers, with well-understood post-quantum security. Picnic does not require number-theoretic, or structured hardness assumptions.

### Publications

*   Melissa Chase, David Derler, Steven Goldfeder, Claudio Orlandi, Sebastian Ramacher, Christian Rechberger, Daniel Slamanig, Greg Zaverucha. **_Post-Quantum Zero-Knowledge and Signatures from Symmetric-Key Primitives._** [ACM CCS 2017](https://www.sigsac.org/ccs/CCS2017/) (see also [ePrint 2017/279](https://eprint.iacr.org/2017/279)).

*   **_[The Picnic Signature Algorithm Specification](https://github.com/Microsoft/Picnic/tree/master/spec)_**, version 1.0, November 2017.

*   **_[The Picnic Signature Algorithm Design Document](https://github.com/Microsoft/Picnic/tree/master/spec)_**, version 1.0, November 2017.

*   Léo Perrin, Angela Promitzer, Sebastian Ramacher, Christian Rechberger. **_Improvements to the Linear Layer of LowMC: A Faster Picnic._** IACR Cryptology ePrint Archive [Report 2017/1148](https://eprint.iacr.org/2017/1148)

### Libraries Implementing Picnic

*   **[Optimized Implementation](https://github.com/IAIK/Picnic)** An implementation optimized for speed, able to make use of processor specific features.

*   **[Reference Implementation](https://github.com/Microsoft/Picnic)** An implementation that tries to be simple, and follow the spec closely, to illustrate the algorithm.

### Talks

*   Steven Goldfeder, Sebastian Ramacher - **_"Post-Quantum Zero-Knowledge and Signatures from Symmetric-Key Primitives"_** \- [ACM CCS 2017](https://www.sigsac.org/ccs/CCS2017/) ([slides](https://microsoft.github.io/Picnic/picnic-ccs-2017.pdf)).
*   Sebastian Ramacher - **_"Post-Quantum Zero-Knowledge and Signatures from Symmetric-Key Primitives"_** \- [CryptoAction Symposium (COST Action IC1306)](https://cryptoactionsymposium.wordpress.com/).
*   Melissa Chase - **_"Post-Quantum Signatures from Symmetric-Key Primitives"_** \- [Real-World Crypto 2018](https://rwc.iacr.org/2018/index.html) ([recording](https://www.youtube.com/watch?v=_J9ESIy8D2o)).
*   Greg Zaverucha - **_"The Picnic Digital Signature Algorithm"_** \- [NIST First PQC Standardization Conference](https://csrc.nist.gov/Events/2018/First-PQC-Standardization-Conference) ([slides](https://csrc.nist.gov/CSRC/media/Presentations/Picnic/images-media/Picnic-April2018.pdf)).

### Projects and Demos

*   [open-quantum-safe/liboqs:](https://github.com/open-quantum-safe/liboqs) liboqs is a C library for quantum-resistant cryptographic algorithms. It has support for Picnic.
*   HSM Demo: We have experimented with using Picnic on a commercial hardware security module, as described in the Design Document. The software is available [here](picnic_hsm_demo.zip).

### Flexibility of the Picnic Design

Although not directly related to Picnic, other post-quantum secure (privacy enhancing) primitives use the same building blocks as Picnic. We believe that this work nicely demonstrates the flexibility of the basic Picnic design, which is why we list the respective papers below.

*   Dan Boneh, Saba Eskandarian, Ben Fisch. **_Post-Quantum Group Signatures from Symmetric Primitives._** IACR Cryptology ePrint Archive [Report 2018/261](https://eprint.iacr.org/2018/261).
*   David Derler, Sebastian Ramacher, Daniel Slamanig. **_Post-Quantum Zero-Knowledge Proofs for Accumulators with Applications to Ring Signatures from Symmetric-Key Primitives._** [PQCrypto 2018](https://eprint.iacr.org/2017/1154).

Picnic was designed by a group of cryptographers from [Aarhus University](https://www.au.dk/en/), [AIT Austrian Institute of Technology GmbH](https://www.ait.ac.at/), [Graz University of Technology](https://www.tugraz.at/home/), [Microsoft Research](https://www.microsoft.com/en-us/research/), [Princeton University](https://www.princeton.edu/), and [Technical University of Denmark](http://www.dtu.dk/english). The team includes Melissa Chase, David Derler, Steven Goldfeder, Claudio Orlandi, Sebastian Ramacher, Christian Rechberger, Daniel Slamanig, and Greg Zaverucha.

![](au.png)  ![](ait.png)   ![](tug.png)   ![](ms.png)   ![](princeton.png)   ![](dtu.png)
