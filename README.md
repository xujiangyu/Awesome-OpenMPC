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

Coming Soon

#### 2.1.1.4 Zero knowledge proof

Coming Soon

### 2.1.2 Specialized cryptography protocols

#### 2.1.2.1 PSI

- [BaRK-OPRF](https://github.com/osu-crypto/BaRK-OPRF) - Private Set Intersection. | [2016/799](https://eprint.iacr.org/2016/799).
- [LibPSI](https://github.com/osu-crypto/libPSI) - Various protocols for performing private set intersection.
- [PSI](https://github.com/encryptogroup/PSI) - Private Set Intersection. | [2014/447](https://eprint.iacr.org/2014/447).
- Bernardo A Huberman, Matt Franklin, and Tad Hogg. Enhancing privacy and trust in electronic communities. EC, 99:78-86, 1999.
- Michael J Freedman, Kobbi Nissim, and Benny Pinkas. Efficient private matching and set intersection. In International conference on the theory and applications of cryptographic techniques, pages 1-19. Springer, 2004.
- Dana Dachman-Soled, Tal Malkin, Mariana Raykova, and Moti Yung. Efficient robust private set intersection. In International Conference on Applied Cryptography and Network Security, pages 125-142. Springer, 2009.
- Emiliano De Cristofaro, Jihye Kim, and Gene Tsudik. Linear-complexity private set intersection protocols secure in malicious model. In International Conference on the Theory and Application of Cryptology and Information Security, pages 213-231. Springer, 2010. 
- Giuseppe Ateniese, Emiliano De Cristofaro, and Gene Tsudik. (if) size matters: Sizehiding private set intersection. In International Workshop on Public Key Cryptography, pages 156-173. Springer, 2011.
- Emiliano De Cristofaro, Paolo Gasti, and Gene Tsudik. Fast and private computation of cardinality of set intersection and union. In International Conference on Cryptology and Network Security, pages 218-231. Springer, 2012.
- Yan Huang, David Evans, and Jonathan Katz. Private set intersection: Are garbled circuits better than custom protocols? In NDSS, 2012.
- Changyu Dong, Liqun Chen, and Zikai Wen. When private set intersection meets big data: an efficient and scalable protocol. In Proceedings of the 2013 ACM SIGSAC conference on Computer & communications security, pages 789-800. ACM, 2013. 
- Benny Pinkas, Thomas Schneider, and Michael Zohner. Faster private set intersection based on OT extension. In Kevin Fu and Jaeyeon Jung, editors, Proceedings of the 23rd USENIX Security Symposium, pages 797-812, 2014.
- Benny Pinkas, Thomas Schneider, Gil Segev, and Michael Zohner. Phasing: Private set intersection using permutation-based hashing. In 24th USENIX Security Symposium, pages 515-530, 2015.
- Vladimir Kolesnikov, Ranjit Kumaresan, Mike Rosulek, and Ni Trieu. Efficient batched oblivious prf with applications to private set intersection. In Proceedings of the 2016 ACM SIGSAC Conference on Computer and Communications Security, pages 818-829. ACM, 2016.
- Peter Rindal and Mike Rosulek. Improved private set intersection against malicious adversaries. In Annual International Conference on the Theory and Applications of Cryptographic Techniques, pages 235-259. Springer, 2017.
- Peter Rindal and Mike Rosulek. Malicious-secure private set intersection via dual execution. In Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security, pages 1229-1242. ACM, 2017. 
- Hao Chen, Kim Laine, and Peter Rindal. Fast private set intersection from homomorphic encryption. In Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security, pages 1243-1255. ACM, 2017.
- Daniel Demmler, Peter Rindal, Mike Rosulek, and Ni Trieu. Pir-psi: Scaling private contact discovery. Proceedings on Privacy Enhancing Technologies, 2018(4):159-178, 2018.
- Brett Hemenway Falk, Daniel Noble, and Rafail Ostrovsky. Private set intersection with linear communication from general assumptions. In Proceedings of the 18th ACM Workshop on Privacy in the Electronic Society, pages 14-25. ACM 2019.
- Benny Pinkas, Thomas Schneider, Christian Weinert, and Udi Wieder. Efficient circuit-based psi via cuckoo hashing. In Annual International Conference on the Theory and Applications of Cryptographic Techniques, pages 125-157. Springer, 2018.
- Satrajit Ghosh and Tobias Nilges. An algebraic approach to maliciously secure private set intersection. In EUROCRYPT, 2019.
- Benny Pinkas, Mike Rosulek, Ni Trieu, and Avishay Yanai. Spot-light: Lightweight private set intersection from sparse ot extension. In Annual International Cryptology Conference, pp. 401-431. Springer, Cham, 2019.
- Benny Pinkas, Mike Rosulek, Ni Trieu, and Avishay Yanai. PSI from paxos: Fast, malicious private set intersection. In EUROCRYPT. Springer, 2020.

#### 2.1.2.2 PIR

Coming Soon

#### 2.1.2.3 PIS

Coming Soon

#### 2.1.2.4 Multiparty ECDSA signing

- [Blockchain-Crypto-MPC](https://github.com/unbound-tech/blockchain-crypto-mpc) - Multiparty ECDSA signing in the cryptocurrency setting, includes an optimized GC library, OT, and more. | [CCS'18](https://eprint.iacr.org/2018/987).
- [MPECDSA](https://gitlab.com/neucrypt/mpecdsa) - Threshold multiparty ECDSA from ECDSA assumptions. | [S&P'19](https://eprint.iacr.org/2019/523.pdf).
- 

#### 2.1.2.5 Oblivous RAM

- [ORAM (Obliv-C)](http://oblivc.org/sqoram/) - Oblivous RAM. | [S&P'16](http://oblivc.org/docs/sqoram.pdf).



### 2.1.3 Federal Learning

- H. Brendan McMahan. [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/abs/1602.05629) [Must Read]
- Qiang Yang. [GDPR, Data Shortage and AI](https://aaai.org/Conferences/AAAI-19/invited-speakers/#yang)
- Google I/O'19. [Federated Learning: Machine Learning on Decentralized Data](https://www.youtube.com/watch?v=89BGjQYA0uE)
- [A Performance Evaluation of Federated Learning Algorithms](https://www.researchgate.net/publication/329106719_A_Performance_Evaluation_of_Federated_Learning_Algorithms) 

### 2.1.4 TEE

Coming Soon

### 2.1.5 BlockChain

Coming Soon

### 2.1.6 PPML

## Linear Regression / Logistic Regression / Neural Network

- SecureML: A System for Scalable Privacy-Preserving Machine Learning - Semi-honest 2PC for linear regression, logistic regression and neural network training protocols. | S&P’17. [Paper]((https://eprint.iacr.org/2017/396)), [Silde](http://users.umiacs.umd.edu/~zhangyp/presentations/SecureML.pptx).
- Privacy-preserving distributed linear regression on high-dimensional data - MPC for linear regression in vertically distributed dataset ; secure against semi-honest adversary. | PETS’17. [Paper](https://www.sciendo.com/article/10.1515/popets-2017-0053).
- Oblivious Neural Network Predictions via MiniONN Transformations - This work gives an oblivious NN to protect not only clients’ input but also servers’ model privacy. | CCS’17. [Paper](https://dl.acm.org/doi/10.1145/3133956.3134056).
- Chameleon: A Hybrid Secure Computation Framework for Machine Learning Applications - A semi-honest 2PC framework for machine learning. e.g. NN. | ASIACCS'18. [Paper](https://dl.acm.org/doi/10.1145/3196494.3196522).
- Privacy-Preserving Deep Learning via Additively Homomorphic Encryption - A novel deep learning system to protect the gradients over semi-honest cloud server by using AHE. | IFS’18. [Paper](https://ieeexplore.ieee.org/abstract/document/8241854).
- SecureNN: 3-Party Secure Computation for Neural Network Training - 3PC model for DNN and CNN. Secure against semi-honest corruption and one malicious corruption. | PETS’19. [Paper](https://eprint.iacr.org/2018/442.pdf).

## K-means Clustering

- [Practical privacy-preserving k-means clustering](https://github.com/osu-crypto/secure-kmean-clustering) - Semi-honest 2PC for k-means clustering protocol. | PETS’19. [Paper](https://eprint.iacr.org/2019/1158.pdf).

## Genomic Privacy

- [Secure genome-wide association analysis using multiparty computation](https://github.com/hhcho/secure-gwas) - Semi-honest 2PC for GWAS protocols. This protocol contains an auxiliary computing party. | Nature Biotechnology, 2018. [Paper](https://www.nature.com/articles/nbt.4108), [Note](https://static-content.springer.com/esm/art%3A10.1038%2Fnbt.4108/MediaObjects/41587_2018_BFnbt4108_MOESM46_ESM.pdf).

**Must read papers about training in PPDT**

- Lindell, Yehuda, and Benny Pinkas. "Privacy preserving data mining." *Annual International Cryptology Conference*. Springer, Berlin, Heidelberg, 2000.
- Lindell, Yehida. "Secure multiparty computation for privacy preserving data mining." *Encyclopedia of Data Warehousing and Mining*. IGI global, 2005. 1005-1009.
- Vaidya, Jaideep, et al. "A random decision tree framework for privacy-preserving data mining." *IEEE transactions on dependable and secure computing* 11.5 (2013): 399-411.
- Akavia, Adi, et al. "Privacy-Preserving Decision Tree Training and Prediction against Malicious Server." *IACR Cryptol. ePrint Arch.* 2019 (2019): 1282.
- Liu, Lin, et al. "Towards practical privacy-preserving decision tree training and evaluation in the cloud." *IEEE Transactions on Information Forensics and Security* 15 (2020): 2914-2929.

**Must read papers about evaluation in PPDT**

- Akavia, A., Leibovich, M., Resheff, Y.S., Ron, R., Shahar, M., Vald, M.: Privacy-preserving decision tree training and prediction against malicious server. IACR Cryptol. ePrint Arch. 2019, 1282 (2019)
- Barni, M., Failla, P., Kolesnikov, V., Lazzeretti, R., Sadeghi, A.R., Schneider, T.: Secure evaluation of private linear branching programs with medical applications. In: European Symposium on Research in Computer Security. pp. 424–439. Springer (2009)
- Brickell, J., Porter, D.E., Shmatikov, V., Witchel, E.: Privacy-preserving remote diagnostics. In: ACM CCS. pp. 498–507 (2007)
- Bost, R., Popa, R.A., Tu, S., Goldwasser, S.: Machine learning classification over encrypted data. In: NDSS. vol. 4324, p. 4325 (2015)
- Wu, D.J., Feng, T., Naehrig, M., Lauter, K.: Privately evaluating decision trees and random forests. Proceedings on Privacy Enhancing Technologies 2016 (4), 335–355 (2016)
- De Cock, M., Dowsley, R., Horst, C., Katti, R., Nascimento, A.C., Poon, W.S., Truex, S.: Efficient and private scoring of decision trees, support vector machines and logistic regression models based on pre-computation. IEEE Transactions on Dependable and Secure Computing 16(2), 217–230 (2017)
- Tai, R.K., Ma, J.P., Zhao, Y., Chow, S.S.: Privacy-preserving decision trees evaluation via linear functions. In: ESORICS. pp. 494–512. Springer (2017)
- Lu, W.j., Zhou, J.J., Sakuma, J.: Non-interactive and output expressive private comparison from homomorphic encryption. In: Proceedings of the 2018 on Asia Conference on Computer and Communications Security. pp. 67–74 (2018)
- Joye, M., Salehi, F.: Private yet efficient decision tree evaluation. In: IFIP Annual Conference on Data and Applications Security and Privacy. pp. 243–259. Springer (2018)
- Li, T., Huang, Z., Li, P., Liu, Z., Jia, C.: Outsourced privacy-preserving classification service over encrypted data. Journal of Network and Computer Applications 106, 100–110 (2018)
- Kiss, A., Naderpour, M., Liu, J., Asokan, N., Schneider, T.: Sok: modular and efficient private decision tree evaluation. Proceedings on Privacy Enhancing Technologies 2019(2), 187–208(2019)
- Tueno, A., Kerschbaum, F., Katzenbeisser, S.: Private evaluation of decision trees using sublinear cost. Proceedings on Privacy Enhancing Technologies 2019 (1), 266–286 (2019)
- Liang, J., Qin, Z., Xiao, S., Ou, L., Lin, X.: Efficient and secure decision tree classification for cloud-assisted online diagnosis services. IEEE Transactions on Dependable and Secure Computing (2019)
- Liu, L., Su, J., Chen, R., Chen, J., Sun, G., Li, J.: Secure and fast decision tree evaluation on outsourced cloud data. In: International Conference on Machine Learning for Cyber Security. pp. 361–377. Springer (2019)
- Zheng, Y., Duan, H., Wang, C.: Towards secure and efficient outsourcing of machine learning classification. In: ESORICS. pp. 22–40. Springer (2019)
- Liu, L., Chen, R., Liu, X., Su, J., Qiao, L.: Towards practical privacy-preserving decision tree training and evaluation in the cloud. IEEE Transactions on Information Forensics and Security15, 2914–2929 (2020)
- Liu, L., Su, J., Zhao, B., Wang, Q., Chen, J., Luo, Y.: Towards an efficient privacy-preserving decision tree evaluation service in the internet of things. Symmetry12(1),  103 (2020)
- Tueno, A., Boev, Y., Kerschbaum, F.: Non-interactive private decision tree evaluation. In: IFIP  Annual  Conference  on  Data  and  Applications  Security  and  Privacy.  pp.  174–194. Springer (2020)
- Wang, C., Wang, A., Xu, J., Wang, Q., Zhou, F.: Outsourced privacy-preserving decision tree classification service over encrypted data. Journal of Information Security and Applications 53, 102517 (2020)
- Xue, L., Liu, D., Huang, C., Lin, X., Shen, X.S.: Secure and privacy-preserving decision tree classification with lower complexity. Journal of Communications and Information Networks 5 (1), 16–25 (2020)
- Liang, J., Qin, Z., Xue, L., Lin, X., & Shen, X. : Efficient and Privacy-Preserving Decision Tree Classification for Health Monitoring Systems. IEEE Internet of Things Journal (2021)
- Ma, J. P., Tai, R. K., Zhao, Y., & Chow, S. S.: Let’s Stride Blindfolded in a Forest: Sublinear Multi-Client Decision Trees Evaluation. *NDSS.* Internet Society (2021)

# Conferences paper for PPML

## S&P

### 2020

- The Value of Collaboration in Convex Machine Learning with Differential Privacy
- Automatically Detecting Bystanders in Photos to Reduce Privacy Risks
- CrypTFlow : Secure TensorFlow Inference
- GAN-Leaks: A Taxonomy of Membership Inference Attacks against Generative Models
- Analyzing Information Leakage of Updates to Natural Language Models
- Information Leakage in Embedding Models
- HopSkipJumpAttack: A Query-Efficient Decision-Based Attack
- Humpty Dumpty: Controlling Word Meanings via Corpus Modifications
- Privacy Risks of General-Purpose Language Models
- Intriguing Properties of Adversarial ML Attacks in the Problem Space

### 2019

- Certified Robustness to Adversarial Examples with Differential Privacy
- DEEPSEC: A Uniform Platform for Security Analysis of Deep Learning Model
- Exploiting Unintended Feature Leakage in Collaborative Learning
- Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks
- Helen: Maliciously Secure Coopetitive Learning for Linear Models
- Comprehensive Privacy Analysis of Deep Learning: Passive and Active White-box Inference Attacks against Centralized and Federated Learning

### 2018

- AI2: Safety and Robustness Certification of Neural Networks with Abstract Interpretation
- Manipulating Machine Learning: Poisoning Attacks and Countermeasures for Regression Learning
- Stealing Hyperparameters in Machine Learning
- A Machine Learning Approach to Prevent Malicious Calls over Telephony Networks
- Surveylance: Automatically Detecting Online Survey Scams

### 2017

- Membership Inference Attacks Against Machine Learning Models
- SecureML: A System for Scalable Privacy-Preserving Machine Learning
- Towards Evaluating the Robustness of Neural Networks
- Is Interaction Necessary for Distributed Private Learning?
- Pyramid: Enhancing Selectivity in Big Data Protection with Count Featurization

## CCS

### 2020

- Gotta Catch'Em All: Using Honeypots to Catch Adversarial Attacks on Neural Networks
- A Tale of Evil Twins: Adversarial Inputs versus Poisoned Models
- DeepDyve: Dynamic Verification for Deep Neural Networks
- Composite Backdoor Attack for Deep Neural Network by Mixing Existing Benign Features
- CrypTFlow2: Practical 2-Party Secure Inference
- GAN-Leaks: A Taxonomy of Membership Inference Attacks against Generative Models
- Analyzing Information Leakage of Updates to Natural Language Models
- Information Leakage in Embedding Models
- MP-SPDZ: A Versatile Framework for Multi-Party Computation

### 2019

- Neural Network Inversion in Adversarial Setting via Background Knowledge Alignment
- Privacy Risks of Securing Machine Learning Models against Adversarial Examples
- MemGuard: Defending against Black-Box Membership Inference Attacks via Adversarial Examples
- Procedural Noise Adversarial Examples for Black-Box Attacks on Deep Convolutional Networks
- QUOTIENT: Two-Party Secure Neural Network Training and Prediction
- Quantitative Verification of Neural Networks and Its Security Applications
- ABS: Scanning Neural Networks for Back-doors by Artificial Brain Stimulation
- Lifelong Anomaly Detection Through Unlearning
- Seeing isn't Believing: Towards More Robust Adversarial Attack Against Real World Object Detectors
- AdVersarial: Perceptual Ad Blocking meets Adversarial Machine Learning
- Attacking Graph-based Classification via Manipulating the Graph Structure
- Latent Backdoor Attacks on Deep Neural Networks

### 2018

- ABY3: A Mixed Protocol Framework for Machine Learning
- Yet Another Text Captcha Solver: A Generative Adversarial Network Based Approach
- Model-Reuse Attacks on Deep Learning Systems
- LEMNA: Explaining Deep Learning based Security Applications
- Effective Program Debloating via Reinforcement Learning
- Tiresias: Predicting Security Events Through Deep Learning
- DeepMem: Learning Graph Neural Network Models for Fast and Robust Memory Forensic Analysis
- Property Inference Attacks on Fully Connected Neural Networks using Permutation Invariant Representations
- Machine Learning with Membership Privacy using Adversarial Regularization

### 2017

- DolphinAttack: Inaudible Voice Commands
- Evading Classifiers by Morphing in the Dark
- MagNet: A Two-Pronged Defense against Adversarial Examples
- Machine Learning Models that Remember Too Much
- Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning
- Oblivious Neural Network Predictions via MiniONN Transformations
- Practical Secure Aggregation for Privacy-Preserving Machine Learning

## USENIX

### 2020

- Fawkes: Protecting Privacy against Unauthorized Deep Learning Models
- Stolen Memories: Leveraging Model Memorization for Calibrated White-Box Membership Inference
- Local Model Poisoning Attacks to Byzantine-Robust Federated Learning
- Justinian's GAAvernor: Robust Distributed Learning with Gradient Aggregation Agent
- Interpretable Deep Learning under Fire
- Updates-Leak: Data Set Inference and Reconstruction Attacks in Online Learning
- Exploring Connections Between Active Learning and Model Extraction
- Hybrid Batch Attacks: Finding Black-box Adversarial Examples with Limited Queries
- High Accuracy and High Fidelity Extraction of Neural Networks
- Adversarial Preprocessing: Understanding and Preventing Image-Scaling Attacks in Machine Learning
- TextShield: Robust Text Classification Based on Multimodal Embedding and Neural Machine Translation

### 2019

- The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks
- Improving Robustness of ML Classifiers against Realizable Evasion Attacks Using Conserved Features
- ALOHA: Auxiliary Loss Optimization for Hypothesis Augmentation
- Why Do Adversarial Attacks Transfer? Explaining Transferability of Evasion and Poisoning Attacks
- Stack Overflow Considered Helpful! Deep Learning Security Nudges Towards Stronger Cryptography
- Seeing is Not Believing: Camouflage Attacks on Image Scaling Algorithms
- CT-GAN: Malicious Tampering of 3D Medical Imagery using Deep Learning
- Misleading Authorship Attribution of Source Code using Adversarial Learning
- Terminal Brain Damage: Exposing the Graceless Degradation in Deep Neural Networks Under Hardware Fault Attacks
- CSI NN: Reverse Engineering of Neural Network Architectures Through Electromagnetic Side Channel

### 2018

- Formal Security Analysis of Neural Networks using Symbolic Intervals
- Turning Your Weakness Into a Strength: Watermarking Deep Neural Networks by Backdooring
- A4NT: Author Attribute Anonymity by Adversarial Training of Neural Machine Translation
- GAZELLE: A Low Latency Framework for Secure Neural Network Inference

## NDSS

### 2020

- Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning
- Secure Sublinear Time Differentially Private Median Computation
- CloudLeak: Large-Scale Deep Learning Models Stealing Through Adversarial Examples
- BLAZE: Blazing Fast Privacy-Preserving Machine Learning

### 2019

- ML-Leaks: Model and Data Independent Membership Inference Attacks and Defenses on Machine Learning Model
- MBeacon: Privacy-Preserving Beacons for DNA Methylation Data
- Stealthy Adversarial Perturbations Against Real-Time Video Classification Systems
- NIC: Detecting Adversarial Samples with Neural Network Invariant Checking
- TextBugger: Generating Adversarial Text Against Real-world Applications
- Graph-based Security and Privacy Analytics via Collective Classification with Joint Weight Learning and Propagation

### 2018

- Automated Website Fingerprinting through Deep Learning
- VulDeePecker: A Deep Learning-Based System for Vulnerability Detection
- Kitsune: An Ensemble of Autoencoders for Online Network Intrusion Detection
- Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks
- Trojaning Attack on Neural Networks



## 2.2 Survey Papers

- Yehuda Lindell. [Secure Multiparty Computation (MPC)](https://eprint.iacr.org/2020/300.pdf), Communications of the ACM, January 2021. This is a general and friendly introduction to secure multiparty computation - what it is, how it works, and what it is used for.
- Yehuda Lindell. [How to Simulate It - A Tutorial on the Simulation Proof Technique](https://eprint.iacr.org/2016/046.pdf), 2016. The simulation paradigm is fundamental to secure computation. However, many have difficulties in understanding how to write simulation proofs. This tutorial explains this proof technique in great detail.
- Manoj Prabhakaran and Amit Sahai (Eds.). [Secure Multi-Party Computation](http://ebooks.iospress.com/volume/secure-multi-party-computation), IOS Press, 2013. This is a compilation of surveys on the topic of multiparty computation. It focuses on theoretical aspects and is highly useful for those wishing to study the theory of MPC.
- H. Brendan McMahan. [Advances and Open Problems in Federated Learning](https://arxiv.org/pdf/1912.04977.pdf).
- [A survey on security and privacy of federated learning](https://www.sciencedirect.com/science/article/pii/S0167739X20329848).
- [Survey of Personalization Techniques for Federated Learning](https://arxiv.org/pdf/2003.08673.pdf) .
- Qinbin Li. [A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection](https://arxiv.org/abs/1907.09693) This survey provides  categorization for federated learning systems according to data distribution, machine learning model, privacy mechanism, communication architecture, scale of federation and motivation of federation.
- Qiang Yang. [Threats to Federated Learning: A Survey](https://arxiv.org/pdf/2003.02133.pdf)  This paper provides an accessible review of FL concept,a unique taxonomy covering threat models and two major attacks on FL: poisoning attacks and inference attacks.
- Qiang Yang. [Federated Machine Learning: Concept and Applications](https://arxiv.org/pdf/1902.04885.pdf) Definitions, architectures and applications for the federated learning framework, and provide a comprehensive survey of existing works on this subject. 
- [SoK: Training Machine Learning Models over Multiple Sources with Privacy Preservation](https://arxiv.org/abs/2012.03386v1) - A review paper for PPML. [Paper](https://arxiv.org/pdf/2012.03386v1.pdf).
- Privacy-Preserving Machine Learning: Threats and Solutions - PPML overview. | S&P'19. [Paper](https://arxiv.org/pdf/1804.11238.pdf).
## 2.3 Books

### 2.3.1 SMPC

- [A Pragmatic Introduction to Secure Multi-Party Computation](https://securecomputation.org/) -The book emphazises the intuition and ideas behind the protocols rather than rigorous proofs.
- [Applications of Secure Multiparty Computation](http://ebooks.iospress.nl/volume/applications-of-secure-multiparty-computation) - Collection of MPC protocols for several real-world tasks such as statistics.
- [Efficient Secure Two-Party Protocols](https://www.springer.com/us/book/9783642143021) - Comprehensive study of efficient protocols and techniques for secure two-party computation – both general constructions that can be used to securely compute any functionality, and protocols for specific problems of interest.
- [Secure Multiparty Computation and Secret Sharing](http://www.cambridge.org/dk/academic/subjects/computer-science/cryptography-cryptology-and-coding/secure-multiparty-computation-and-secret-sharing?format=HB) - Comprehensive treatment of unconditionally secure techniques for multiparty computation (MPC) and secret sharing.

- [Foundations of Cryptography Vol. 2 ](http://www.wisdom.weizmann.ac.il/~oded/foc-vol2.html)- Cambridge University Press, 2004. Chapter 7 of the book introduces two-party and multiparty computation, contains a thorough and comprehensive definitional treatment, provides a full and detailed proof of the GMW construction, and surveys advanced topics. The book's formal and rigorous treatment makes it a must-read for the MPC researcher.
- [Engineering Secure Two-Party Computation Protocols ](https://www.sites.google.com/site/thomaschneider/publications/engineeringsfebook)- Springer, 2012. This book focuses specifically tools for optimizing secure computation in practice, including circuit optimizations, frameworks for constructing protocols, and more. The book provides a very good overview of different techniques and tools that MPC researchers should be familiar with.

### 2.3.2 Federal Learning

- [TOWARDS FEDERATED LEARNING AT SCALE: SYSTEM DESIGN](https://arxiv.org/abs/1902.01046) This paper describes the resulting high-level design, sketch some of the challenges and their solutions, and touch upon the open problems and future directions.
- Sebastian Caldas. [LEAF: A Benchmark for Federated Settings](https://arxiv.org/abs/1812.01097) LEAF includes a suite of open-source federated datasets, a rigorous evaluation framework, and a set of reference implementations, all geared towards capturing the obstacles and intricacies of practical federated environments.
- Chaoyang He. [FedML: A Research Library and Benchmark for Federated Machine Learning](https://arxiv.org/pdf/2007.13518.pdf)FedML is a research-oriented federated learning library and benchmark.
- Qinbin Li. [Federated Learning on Non-IID Data Silos: An Experimental Study](https://arxiv.org/abs/2102.02079) This paper develop a benchmark named NIID-bench and introduce six data partitioning strategies which are much more comprehensive than the previous studies. Furthermore, we conduct comprehensive experiments to compare existing algorithms and demonstrate their strength and weakness.
- Sai Praneeth Karimireddy. [SCAFFOLD: Stochastic Controlled Averaging for Federated Learning](https://arxiv.org/pdf/1910.06378.pdf) SCAFFOLD algorithm.

### 2.3.3 TEE

Coming Soon

### 2.3.4 BlockChain

Coming Soon

## 2.4 Courses

- [Cryptographic Computing Course](http://orlandi.dk/crycom) - Course on MPC, Homomorphic Encryption and related topics given by Claudio Orlandi at Aarhus University.
- [FHE-MPC Advanced Grad Course](https://homes.esat.kuleuven.be/~nsmart/FHE-MPC/) - 'Informal grad course' in FHE and MPC.
- [Secure Computation](http://drona.csa.iisc.ernet.in/~arpita/SecureComputation15.html) - Secure Computation course offered by Indian Institute of Science covering secret sharing schemes, oblivious transfer to impossiblity results and zero-knowledge proofs.
- [Secure Multi-Party Computation at Scale](https://piazza.com/bu/fall2017/cs591v1/home) - Boston University course that covers mathematical and algorithmic foundations of MPC, with an additional focus on deployment of state-of-the-art MPC technologies.
- [The 1st BIU Winter School on Secure Computation and Efficiency](https://cyber.biu.ac.il/event/the-1st-biu-winter-school/), 2011. This series of lectures covers the very basics of secure computation and as such is a useful tool.
- [The 5th BIU Winter School on Advances in Practical Multiparty Computation](https://cyber.biu.ac.il/event/the-5th-biu-winter-school/), 2015. This series of lectures begins with tutorials and includes many more advanced techniques.
- [The Universal Composability Framework](https://m.youtube.com/playlist?list=PLqc9MPlwib9nSuyH4oUIwPsyDiZ4bwuEE), 2016. This series of tutorials introduces the universal composability framework in detail.
- https://people.eecs.berkeley.edu/~sanjamg/classes/cs276-fall14/
- [Applied Cryptography](https://www.udacity.com/course/applied-cryptography--cs387) Learn all about making and breaking puzzles in computing.


# 3 Open Source Framework
- [MOTION](https://github.com/encryptogroup/MOTION)-MOTION - A Framework for Mixed-Protocol Multi-Party Computation.
- [SecMML](https://github.com/FudanMPL/SecMML) - SecMML, a branch of FudanMPL (Multi-Party Computation + Machine Learning) , is a scalable and efficient MPC framework for training machine learning models based on BGW protocol.
- [OpenPEGASUS](https://github.com/Alibaba-Gemini-Lab/OpenPEGASUS) - Pegasus: Bridging Polynomial and Non-polynomial Evaluations in Homomorphic Encryption.
- [Drynx](https://github.com/ldsec/drynx) - Drynx: Decentralized, Secure, Verifiable System for Statistical Queries and Machine Learning on Distributed Datasets.
- [MK-TFHE](Multi-Key Homomophic Encryption from TFHE) - MK-TFHE is a proof-of-concept implementation of a multi-key version of TFHE. The code is written on top of the TFHE library (https://tfhe.github.io/tfhe/).
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

