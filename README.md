# Awesome-OpenMPC

[English](README.md)  [Chinese](README_CN.md)

# 1 Introduction
# 2 Theory

## 2.1 Academic papers

### 2.1.1 General Cryptographic Primitives

#### 2.1.1.1 Oblivious Transfer (OT)

- More Efficient Oblivious Transfer and Extensions for Faster Secure Computation. Doc: [paper](https://eprint.iacr.org/2013/552.pdf), [slide](https://www.cs.cornell.edu/~asharov/slides/ALSZ13.pdf). 

#### 2.1.1.2 Secure Multiparty Computing

SMPC is roughly divided into the following genres: 

- Yao's GC (garbled circuit), a series of confusing circuits created by Academician Yao Qizhi 
- SPDZ (arithmetic circuit), a series of encryption based on secret sharing and limited homomorphism created by Ivan Damgard 
- GMW (boolean circuit), the pioneering paper of boolean sharings 
- ABY (including share conversion of arithmetic, Boolean and confusion circuits), including ABY and ABY3 5. 
- MHE, based on FHE series 

**Garbled Circuit**

1. [Protocols for Secure Computations (Extended Abstract)]( https://crysp.uwaterloo.ca/courses/pet/F11/cache/www.cs.wisc.edu/areas/sec/yao1982-ocr.pdf)
2. [Improved Garbled Circuit: Free XOR Gates and Applications](http://www.cs.toronto.edu/~vlad/papers/XOR_ICALP08.pdf)
3. [FairplayMP – A System for Secure Multi-Party Computation](https://www.cs.huji.ac.il/~noam/FairplayMP.pdf)
4. [Two Halves Make a Whole Reducing Data Transfer in Garbled Circuits using Half Gates](https://eprint.iacr.org/2014/756.pdf)
5. [Fast and Secure Three-party Computation: The Garbled Circuit Approach](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/43888.pdf)

**Arithmetic Circuit**

1. [Multiparty Computation from Somewhat Homomorphic Encryption](https://eprint.iacr.org/2011/535.pdf)
2. [Practical Covertly Secure MPC for Dishonest Majority Or: Breaking the SPDZ Limits](https://eprint.iacr.org/2012/642.pdf) 
3. [SPDZ2k: Efficient MPC mod 2k for Dishonest Majority](https://eprint.iacr.org/2018/482.pdf)

**Boolean Circuit**

1. [How to play any mental game or a completeness theorem for protocols with honest majority (PDF) How to play ANY mental game](https://www.researchgate.net/publication/234778924_How_to_play_ANY_mental_game/link/0deec5232112523fc5000000/download)

**Mix**

1. [ABY – A Framework for Effificient Mixed-Protocol Secure Two-Party Computation](https://encrypto.de/papers/DSZ15.pdf)
2. [ABY3 : A Mixed Protocol Framework for Machine Learning](https://eprint.iacr.org/2018/403.pdf)
3. [BLAZE: Blazing Fast Privacy-Preserving Machine Learning](https://eprint.iacr.org/2020/042)
4. [Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning)
5. [MOTION – A Framework for Mixed-Protocol Multi-Party Computation](https://eprint.iacr.org/2020/1137)

**MFHE**

1. [Threshold Cryptosystems From Threshold Fully Homomorphic Encryption](https://eprint.iacr.org/2017/956.pdf)
2. [Multiparty Homomorphic Encryption: From Theory to Practice](https://eprint.iacr.org/2020/304.pdf)
3. [Efficient Multi-Key Homomorphic Encryption with Packed Ciphertexts with Application to Oblivious Neural Network Inference ](https://eprint.iacr.org/2019/524.pdf)

#### 2.1.1.3 Homomorphic encryption



#### 2.1.1.4 Zero knowledge proof



### 2.1.2 Specialized cryptography protocols

#### 2.1.2.1 PSI

- [BaRK-OPRF](https://github.com/osu-crypto/BaRK-OPRF) - Private Set Intersection. | [2016/799](https://eprint.iacr.org/2016/799).
- [LibPSI](https://github.com/osu-crypto/libPSI) - Various protocols for performing private set intersection.
- [PSI](https://github.com/encryptogroup/PSI) - Private Set Intersection. | [2014/447](https://eprint.iacr.org/2014/447).

#### 2.1.2.2 PIR



#### 2.1.2.3 PIS



#### 2.1.2.4 Multiparty ECDSA signing

- [Blockchain-Crypto-MPC](https://github.com/unbound-tech/blockchain-crypto-mpc) - Multiparty ECDSA signing in the cryptocurrency setting, includes an optimized GC library, OT, and more. | [CCS'18](https://eprint.iacr.org/2018/987).
- [MPECDSA](https://gitlab.com/neucrypt/mpecdsa) - Threshold multiparty ECDSA from ECDSA assumptions. | [S&P'19](https://eprint.iacr.org/2019/523.pdf).
- 

#### 2.1.2.5 Oblivous RAM

- [ORAM (Obliv-C)](http://oblivc.org/sqoram/) - Oblivous RAM. | [S&P'16](http://oblivc.org/docs/sqoram.pdf).



### 2.1.3 Federal Learning



### 2.1.4 TEE



### 2.1.5 BlockChain



### 2.1.6 PPML





## 2.2 Survey Papers

- Yehuda Lindell. [Secure Multiparty Computation (MPC)](https://eprint.iacr.org/2020/300.pdf), Communications of the ACM, January 2021. This is a general and friendly introduction to secure multiparty computation - what it is, how it works, and what it is used for.
- Yehuda Lindell. [How to Simulate It - A Tutorial on the Simulation Proof Technique](https://eprint.iacr.org/2016/046.pdf), 2016. The simulation paradigm is fundamental to secure computation. However, many have difficulties in understanding how to write simulation proofs. This tutorial explains this proof technique in great detail.
- Manoj Prabhakaran and Amit Sahai (Eds.). [Secure Multi-Party Computation](http://ebooks.iospress.com/volume/secure-multi-party-computation), IOS Press, 2013. This is a compilation of surveys on the topic of multiparty computation. It focuses on theoretical aspects and is highly useful for those wishing to study the theory of MPC.

## 2.3 Books

### 2.3.1 SMPC

- [A Pragmatic Introduction to Secure Multi-Party Computation](https://securecomputation.org/) -The book emphazises the intuition and ideas behind the protocols rather than rigorous proofs.
- [Applications of Secure Multiparty Computation](http://ebooks.iospress.nl/volume/applications-of-secure-multiparty-computation) - Collection of MPC protocols for several real-world tasks such as statistics.
- [Efficient Secure Two-Party Protocols](https://www.springer.com/us/book/9783642143021) - Comprehensive study of efficient protocols and techniques for secure two-party computation – both general constructions that can be used to securely compute any functionality, and protocols for specific problems of interest.
- [Secure Multiparty Computation and Secret Sharing](http://www.cambridge.org/dk/academic/subjects/computer-science/cryptography-cryptology-and-coding/secure-multiparty-computation-and-secret-sharing?format=HB) - Comprehensive treatment of unconditionally secure techniques for multiparty computation (MPC) and secret sharing.

- [Foundations of Cryptography Vol. 2 ](http://www.wisdom.weizmann.ac.il/~oded/foc-vol2.html)- Cambridge University Press, 2004. Chapter 7 of the book introduces two-party and multiparty computation, contains a thorough and comprehensive definitional treatment, provides a full and detailed proof of the GMW construction, and surveys advanced topics. The book's formal and rigorous treatment makes it a must-read for the MPC researcher.
- [Engineering Secure Two-Party Computation Protocols ](https://www.sites.google.com/site/thomaschneider/publications/engineeringsfebook)- Springer, 2012. This book focuses specifically tools for optimizing secure computation in practice, including circuit optimizations, frameworks for constructing protocols, and more. The book provides a very good overview of different techniques and tools that MPC researchers should be familiar with.

### 2.3.2 Federal Learning



### 2.3.3 TEE



### 2.3.4 BlockChain



## 2.4 Courses

- [Cryptographic Computing Course](http://orlandi.dk/crycom) - Course on MPC, Homomorphic Encryption and related topics given by Claudio Orlandi at Aarhus University.
- [FHE-MPC Advanced Grad Course](https://homes.esat.kuleuven.be/~nsmart/FHE-MPC/) - 'Informal grad course' in FHE and MPC.
- [Secure Computation](http://drona.csa.iisc.ernet.in/~arpita/SecureComputation15.html) - Secure Computation course offered by Indian Institute of Science covering secret sharing schemes, oblivious transfer to impossiblity results and zero-knowledge proofs.
- [Secure Multi-Party Computation at Scale](https://piazza.com/bu/fall2017/cs591v1/home) - Boston University course that covers mathematical and algorithmic foundations of MPC, with an additional focus on deployment of state-of-the-art MPC technologies.
- [The 1st BIU Winter School on Secure Computation and Efficiency](https://cyber.biu.ac.il/event/the-1st-biu-winter-school/), 2011. This series of lectures covers the very basics of secure computation and as such is a useful tool.
- [The 5th BIU Winter School on Advances in Practical Multiparty Computation](https://cyber.biu.ac.il/event/the-5th-biu-winter-school/), 2015. This series of lectures begins with tutorials and includes many more advanced techniques.
- [The Universal Composability Framework](https://m.youtube.com/playlist?list=PLqc9MPlwib9nSuyH4oUIwPsyDiZ4bwuEE), 2016. This series of tutorials introduces the universal composability framework in detail.
- https://people.eecs.berkeley.edu/~sanjamg/classes/cs276-fall14/



# 3 Open Source Framework

- [ABY](https://github.com/encryptogroup/ABY) - 2PC with secret sharing and garbled circuits; secure against semi-honest adversaries. | [NDSS'15](http://encrypto.de/papers/DSZ15.pdf).
- [ABY3](https://github.com/ladnir/aby3) - 3PC with secret sharing for privacy preserving machine learning and database joins (PSI, Union, etc.); secure against semi-honest adversaries. | [CCS'18](https://eprint.iacr.org/2018/403.pdf), [2019/518](https://eprint.iacr.org/2019/518.pdf).
- [BatchDualEx](https://github.com/osu-crypto/batchDualEx) - 2PC with garbled circuits; secure against malicious adversaries. | eprint: [2016/632](https://eprint.iacr.org/2016/632).
- [CrypTen](https://github.com/facebookresearch/CrypTen) - MPC with secret sharing; secure against semi-honest adversary; focused on building PyTorch applications. | documentation: [link](https://crypten.ai/)
- [EMP-toolkit](https://github.com/emp-toolkit) - 2PC and MPC with garbled circuits; secure against semi-honest adversaries (emp-sh2pc). There are also ones resistant against malicious parties (emp-[ag2pc|m2pc|agmpc]) | eprint: [2017/189](https://eprint.iacr.org/2017/189), [2016/762](https://eprint.iacr.org/2016/762), [2017/030](https://eprint.iacr.org/2017/030).
- [Fancy-Garbling](https://github.com/spaceships/fancy-garbling) - 2PC with arithmetic garbled circuits; secure against semi-honest adversaries. | eprint: [2016/969](https://eprint.iacr.org/2016/969).
- [FRESCO](http://fresco.readthedocs.io/en/latest/) - MPC supporting TinyTables or SPDZ protocols; secure against semi-honest or malicious adversaries. | [Practice'15](http://practice-project.eu/downloads/publications/D22.1-State-of-the-art-analysis-PU-V1.1.pdf).
- [HoneyBadgerMPC](https://github.com/initc3/HoneyBadgerMPC) - Robust MPC-based confidentiality layer for blockchains with guaranteed output delivery; secure against up to t < n/3 malicious parties.
- [JIFF](https://github.com/multiparty/jiff/) - JavaScript client and server libraries for building web-based applications that employ general purpose MPC; secure against semi-honest adversaries. | documentation: [link](https://multiparty.org/jiff/).
- [MP-SPDZ](https://github.com/data61/MP-SPDZ) - MPC with garbled circuits or secret sharing; secure against malicious or semi-honest adversaries with dishonest or honest majority. | [documentation](https://mp-spdz.readthedocs.io/en/latest/) | eprint: [2020/512](https://eprint.iacr.org/2020/521)
- [MPyC](https://www.win.tue.nl/~berry/mpyc/) - BGW honest majority multi-party protocol; secure against semi-honest adversaries. | [TPMPC'18](https://www.win.tue.nl/~berry/mpyc/TPMPC2018.pdf).
- [Obliv-C](http://oblivc.org/) - 2PC with garbled circuits; secure against semi-honest adversaries. | eprint: [2015/1153](http://eprint.iacr.org/2015/1153).
- [SCALE-MAMBA](https://homes.esat.kuleuven.be/~nsmart/SCALE/) - General MPC with secret sharing; secure against various adversaries including malicious with a dishonest majority. Software closer to a production system. | documentation: [link](https://homes.esat.kuleuven.be/~nsmart/SCALE/Documentation.pdf).
- [Sharemind](https://sharemind.cyber.ee/) - 2PC or 3PC with secret sharing; secure against semi-honest adversaries. | [Cyber'13](https://cyber.ee/research/theses/roman_jagomagis_msc.pdf).
- [swanky](https://github.com/GaloisInc/swanky) - A suite of rust libraries for secure multi-party computation (currently includes oblivious transfer, garbled circuits, and private set intersection).
- [Tf-encrypted](https://github.com/mortendahl/tf-encrypted/) - 3PC with secret sharing; secure against semi-honest adversaries; focused on TensorFlow-based applications.

# 4 Framework optimization

## 4.1 SIMD instructions

Single Instruction Multiple Data (SIMD) not only drastically reduces the memory footprint but also the required communication, since sending 1-bit values has significant overhead. This optimization results in a much better amortized efficiency and throughput, which we detail in §8. SIMD instructions are especially relevant for the outsourcing setting, where the outsourcing servers often simultaneously process data of many users.

SIMD instructions have been used for $𝑁 ∈ \{2,3\}$ in:

- [Sharemind: A Framework for Fast Privacy-Preserving Computations. ESORICS’08.](https://eprint.iacr.org/2008/289.pdf)
- [ABY – A Framework for Effificient Mixed-Protocol Secure Two-Party Computation](https://encrypto.de/papers/DSZ15.pdf)
- [GMW vs. Yao? Efficient Secure Two-Party Computation with Low Depth Circuits](https://link.springer.com/content/pdf/10.1007%2F978-3-642-39884-1.pdf)
- [MOTION – A Framework for Mixed-Protocol Multi-Party Computation](https://eprint.iacr.org/2020/1137)

## 4.2 Interleaved Setup and Online Phase.

Circuit evaluation in MPC happens in one of two modes: sequential or interleaved (‘pipelined’). The sequential mode runs the input-dependent online phase only after the input-independent setup has completed. This allows precise measurements of the setup and online phase communication and computation requirements, or full precomputation ahead of the online phase. 

Frameworks like ABY support only this evaluation mode. The interleaved mode, on the other hand, runs both phases in parallel and facilitates possibly more efficient evaluation of the circuit in terms of load balancing, since the gates that otherwise would have been waiting for the setup phase to finish can be evaluated faster, thus improving the protocol latency.

This method is supported in the following frameworks:

- [SCALE-MAMBA](https://homes.esat.kuleuven.be/~nsmart/SCALE/). Doc: [link](https://homes.esat.kuleuven.be/~nsmart/SCALE/Documentation.pdf)
- [MOTION – A Framework for Mixed-Protocol Multi-Party Computation](https://eprint.iacr.org/2020/1137)

## 4.3 Communication Serialization

MOTION is the first MPC framework, whose communication is completely serialized. The most important benefit of the communication serialization is that our framework neither needs to own a separate TCP connection, nor does it rely on TCP (or similar protocols) as transport protocol, as it was the case for all previous MPC frameworks. 

[MOTION – A Framework for Mixed-Protocol Multi-Party Computation](https://eprint.iacr.org/2020/1137)

