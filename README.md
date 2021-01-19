# Blockchain Papers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of blockchain-related academic papers. Papers with 🎓 have been
peer-reviewed and presented in academic conferences.

Thanks to the excellent work of [decrypto-org/blockchain-papers](https://github.com/decrypto-org/blockchain-papers). This repository is forked from their repository, but continuously add great papers and makes a more reasonable organization based on the content and source of papers.

If you want to join with us, please feel free to contact me. Then, remember to read `CONTRIBUTING.md` before adding papers.

## News

- **Added NDSS'21!**
- **Added ACSAC'20!**
- **Added ASE'20!**
- **Added PODC'20!**
- **Added ESORICS'20!**
- **Added CoNEXT'20!**

## Conference Information

### CCF A

> Conference

- [USENIX Security(Usenix Security Symposium)](#usenix-security-a) <= 2020
- [S&P(IEEE Security and Privacy)](#sp-a) <= 2020
- [CCS(ACM Conference on Computer and Communications Security)](#ccs-a) <= 2020
- [NDSS(Network and Distributed System Security)](#ndss-a) <= 2021
- [CRYPTO(International Cryptology Conference)](#crypto-a) <= 2020
- [EUROCRYPT(European Cryptology Conference)](#eurocrypt-a) <= 2020
- [INFOCOM(IEEE International Conference on Computer Communications)](#infocom-a) <= 2020
- [SOSP(ACM Symposium on Operating Systems Principles)](#sosp-a) <= 2019 (No schedule in 2020)
- [NSDI(USENIX Symposium on Networked Systems Design and Implementation)](#nsdi-a) <= 2020
- [VLDB(International Conference on Very Large Data Bases)](#vldb-a) <= 2020
- [OSDI(USENIX Symposium on Operating Systems Design and Implementations)](#osdi-a) <= 2020
- [SIGMOD(ACM Conference on Management of Data)](#sigmod-a) <= 2020
- [ASE(International Conference on Automated Software Engineering)](#ase-a) <= 2020

> Journal

- [TOCS(ACM Transactions on Computer Systems)](#tocs-a) <= 2019
- [TOPLAS(ACM Transactions on Programming Languages & Systems)](#toplas-a) <= 2019
- [JACM(Journal of the ACM)](#jacm-a) <= 2019
- [Journal of Cryptology](#journal-of-cryptology-a) <= 2019
- [TDSC(IEEE Transactions on Dependable and Secure Computing)](#tdsc-a) <= 2019

### CCF B

> Conference

- [ASIACRYPT(International Conference on the Theory and Application of Cryptology and Information Security)](#asiacrypt-b) <= 2019 (Calling for paper in 2020)
- [ESORICS(European Symposium on Research in Computer Security)](#esorics-b) <= 2020
- [ACSAC(Annual Computer Security Applications Conference)](#acsac-b) <= 2020
- [EuroSys(European Conference on Computer Systems)](#eurosys-b) <= 2020
- [ICDCS(IEEE International Conference on Distributed Computing Systems)](#icdcs-b) <= 2019
- [PODC(ACM Symposium on Principles of Distributed Computing)](#podc-b) <= 2020
- [CoNEXT(ACM Conference on Emerging Networking EXperiments and Technologies)](#conext-b) <= 2020

### CCF C

> Conference

- [ACNS(Applied Cryptography and Network Security)](#acns-c) <= 2019
- [FC(Financial Cryptography and Data Security)](#fc-c) <= 2020

### [Other](#others)

- CoRR
- T&I(Telematics and Informatics)
- EC
- IACR
- EuroS&P <= 2020

## Content Labels

- _`Composition`_
  - _`System`_
  - _`Network`_, _`Wallets`_, _`Mining`_, _`Smart Contracts`_
  - _`Consensus`_:
    - _`BFT`_, _`PoW`_(Proof of Work), _`PoS`_(Proof of Stake), _`Proof-of-X`_, _`DAG`_
- _`Privacy`_
  - _`Mixing`_, _`Ring Signature`_, _`RingCT`_
  - _`ZKP`_(Zero-Knowledge Proof)
  - _`Blind Signature`_
  - _`sMPC`_, _`Threshold Signature`_
  - _`TEE`_
- _`Scalability`_:
  - _`Layer 2`_
    - _`Payment Channel`_, _`Payment Channel Networks`_
  - _`Sidechains`_, _`Programmability`_
- _`Interoperability`_
- _`Security`_
  - _`Multi-signature`_, _`Threshold Signature`_
  - _`Formal Methods`_
  - _`Post-quantum`_
- _`Applications`_
  - _`Crime`_, _`Economics`_, _`Marketplaces`_, _`Sociological`_, _`Anthropological`_
- _`Attacks`_

> - **Article Types**:
>   - _`SoK`_(Systematization of Knowledge), _`Survey`_, _`Review`_
>   - _`Empirical`_
>   - _`Research`_(default), _`Industrial`_, _`Tool`_
>   - _`Short`_, _`Workshop`_, _`Demo`_

---

## USENIX Security (A)

- 🎓 [ETHBMC: A Bounded Model Checker for Smart Contracts](https://www.usenix.org/system/files/sec20-frank.pdf) Joel Frank, Cornelius Aschermann, and Thorsten Holz, Ruhr-University Bochum. USENIX Security'20.

  - Keyword: _`Smart Contracts`_, _`Formal Methods`_

- 🎓 [An Ever-evolving Game: Evaluation of Real-world Attacks and Defenses in Ethereum Ecosystem](https://www.usenix.org/system/files/sec20-zhou-shunfan.pdf) Shunfan Zhou, Zhemin Yang, and Jie Xiang, Fudan University; Yinzhi Cao, Johns Hopkins University; Min Yang and Yuan Zhang, Fudan University. USENIX Security'20.

  - Keyword: _`Attacks`_，_`Smart Contracts`_

- 🎓 [TXSPECTOR: Uncovering Attacks in Ethereum from Transactions](https://www.usenix.org/system/files/sec20-zhang-mengya.pdf) Mengya Zhang, Xiaokuan Zhang, Yinqian Zhang, and Zhiqiang Lin, The Ohio State University. USENIX Security'20.

  - Keyword: _`Attacks`_

- 🎓 [Remote Side-Channel Attacks on Anonymous Transactions](https://www.usenix.org/system/files/sec20-tramer.pdf) Florian Tramer and Dan Boneh, Stanford University; Kenny Paterson, ETH Zurich. USENIX Security'20.

  - Keyword: _`Anonymity Privacy`_, _`Attacks`_

- 🎓 [BlockSci: Design and applications of a blockchain analysis platform](https://www.usenix.org/system/files/sec20-kalodner.pdf) Harry Kalodner, Malte Möser, and Kevin Lee, Princeton University; Steven Goldfeder, Cornell Tech; Martin Plattner, University of Innsbruck; Alishah Chator, Johns Hopkins University; Arvind Narayanan, Princeton University. USENIX Security'20.

  - Keyword: _`Security`_

- 🎓 [The Ballot is Busted Before the Blockchain: A Security Analysis of Voatz, the First Internet Voting Application Used in U.S. Federal Elections](https://www.usenix.org/system/files/sec20-specter.pdf) Michael A. Specter, James Koppel, and Daniel Weitzner, MIT. USENIX Security'20.

  - Keyword: _`Security`_

- 🎓 [Pixel: Multi-signatures for Consensus](https://smeiklej.com/files/usenix19.pdf). Manu Drijvers, DFINITY; Sergey Gorbunov, Algorand and University of Waterloo; Gregory Neven, DFINITY; Hoeteck Wee, Algorand and CNRS, ENS, PSL. USENIX Security'20.

  - Keyword: **Pixel**, _`Multi-signature`_, _`PoS`_

- 🎓 [Tracing Transactions Across Cryptocurrency Ledgers](https://smeiklej.com/files/usenix19.pdf). Haaroon Yousaf, George Kappos, and Sarah Meiklejohn. USENIX Security'19.

  - Keyword: _`Transaction Analysis`_

- 🎓 [StrongChain: Transparent and Collaborative Proof-of-Work Consensus](https://arxiv.org/pdf/1905.09655.pdf). Pawel Szalachowski, Daniël Reijsbergen, and Ivan Homoliak, Siwei Sun. USENIX Security'19.

  - Keyword: _`Consensus`_

- 🎓 [BITE: Bitcoin Lightweight Client Privacy using Trusted Execution](https://www.usenix.org/system/files/sec19fall_matetic_prepub.pdf). Sinisa Matetic, Karl Wüst, Moritz Schneider, and Kari Kostiainen, Ghassan Karame, Srdjan Capkun. USENIX Security'19.

  - Keyword: _`Privacy`_

- 🎓 [FastKitten: Practical Smart Contracts on Bitcoin](https://www.usenix.org/system/files/sec19fall_das_prepub.pdf). Poulami Das, Lisa Eckey, Tommaso Frassetto, David Gens, Kristina Hostáková, Patrick Jauernig, Sebastian Faust, and Ahmad-Reza Sadeghi. USENIX Security'19.
  - Keyword: _`Smart Contracts`_

* 🎓 [teEther: Gnawing at Ethereum to Automatically Exploit Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-krupp.pdf). Johannes K, Christian R. USENIX Security'18.

  - Keyword: _`Smart Contracts`_

* 🎓 [Enter the Hydra: Towards Principled Bug Bounties and Exploit-Resistant Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-breidenbach.pdf). Lorenz B, Philip D, Florian T, Ari J. USENIX Security'18.

  - Keyword: _`Smart Contracts`_

* 🎓 [Arbitrum: Scalable, private smart contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kalodner.pdf). Harry K, Steven G, Xiaoqi C, S. Matthew W, Edward W. F. USENIX Security'18.

  - Keyword: _`Smart Contracts`_

* 🎓 [Erays: Reverse Engineering Ethereum's Opaque Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-zhou.pdf). Yi Z, Deepak K, Surya B, Joshua M, Andrew M, Michael B. USENIX Security'18.
  - Keyword: _`Smart Contracts`_

- 🎓 [An Empirical Analysis of Anonymity in Zcash](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kappos.pdf). George Kappos, Haaroon Yousaf, Mary Maller, and Sarah Meiklejohn. USENIX Security'18 Security Symposium.
  - Keyword: _`Anonymity Privacy`_

* 🎓 [Smartpool: Practical decentralized pooled mining](https://eprint.iacr.org/2017/019.pdf). Luu L, Velner Y, Teutsch J, Saxena P. USENIX Security'17.

  - Keyword: _`Mining`_

* 🎓 [REM: Resource-Efficient Mining for Blockchains](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-zhang.pdf). Fan Z, Ittay E, Robert E, Ari J, Robbert van R. USENIX Security'17.

  - Keyword: _`Mining`_

* 🎓 **[Enhancing Bitcoin Security and Performance with Strong Consistency via Collective Signing](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kokoris-kogias.pdf)**. Kogias EK, Jovanovic P, Gailly N, Khoffi I, Gasser L, Ford B. USENIX Security'16.

  - Keyword: **ByzCoin**, _`Consensus`_, _`PoS`_

* 🎓 [Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf). Eyal I, Gencer AE, Sirer EG, Van Renesse R. USENIX'16.
  - Keyword: _`Scalability`_

- 🎓 [Eclipse Attacks on Bitcoin's Peer-to-Peer Network](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-heilman.pdf). Heilman E, Kendler A, Zohar A, Goldberg S. USENIX Security'15.
  - Keyword: _`Network`_

* 🎓 [Measuring the Longitudinal Evolution of the Online Anonymous Marketplace Ecosystem](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-soska-updated.pdf). Soska K, Christin N. USENIX Security'15.
  - Keyword: _`Marketplaces`_

## S&P (A)

- 🎓 [OHIE: Blockchain Scaling Made Simple](https://www.comp.nus.edu.sg/~prateeks/papers/Ohie.pdf). Haifeng Yu (National University of Singapore); Ivica Nikolic (National University of Singapore); Ruomu Hou(National University of Singapore); Prateek Saxena (National University of Singapore). S&P'20.

  - Keyword: **OHIE**, _`Scalaility`_, _`Consensus`_

- 🎓 [A Stealthier Partitioning Attack against Bitcoin Peer-to-Peer Network](https://www.comp.nus.edu.sg/~kangms/papers/erebus-attack.pdf). Muoi Tran (National University of Singapore); Inho Choi (National University of Singapore); Gi Jun Moon (Korea University); Anh V. Vu (Japan Advanced Institute of Science and Technology); Min Suk Kang (National University of Singapore). S&P'20.

  - Keyword: **EREBUS**, _`Attacks`_

- 🎓 [VERISMART: A Highly Precise Safety Verifier for Ethereum Smart Contracts](https://arxiv.org/pdf/1908.11227.pdf). Sunbeom So (Korea University); Myungho Lee (Korea University); Jisu Park (Korea University); Heejo Lee (Korea University); Hakjoo Oh (Korea University). S&P'20.

  - Keyword: **VERISMART**, _`Smart Contracts`_, _`Formal Methods`_

- 🎓 [FlyClient: Super-Light Clients for Cryptocurrencies](https://eprint.iacr.org/2019/226.pdf). Benedikt Bünz (Stanford University); Lucianna Kiffer (Northeastern University); Loi Lu (Kyber Network); Mahdi Zamani (Visa Research). S&P'20.

  - Keyword: **FlyClient**, _`Scalaility`_, _`Wallets`_

- 🎓 [VerX: Safety Verification of Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/sp20-verx.pdf). Anton Permenev (ChainSecurity); Dimitar Dimitrov (ETH Zurich); Petar Tsankov (ChainSecurity); Dana Drachsler-Cohen (ETH Zurich); Martin Vechev (ETH Zurich). S&P'20.

  - Keyword: **VerX**, _`Smart Contracts`_, _`Formal Methods`_

- 🎓 [Threshold ecdsa from ecdsa assumptions: The multiparty case](http://www.firstlight.cn/upload/plusfile/20195/21/201952184227868.pdf). Doerner J, Kondi Y, Lee E, et al. S&P'19.

  - Keyword: _`Wallets`_, _`Threshold Signature`_

- 🎓 [Flash Boys 2.0: Frontrunning in Decentralized Exchanges, Miner Extractable Value, and Consensus Instability](https://arxiv.org/pdf/1904.05234.pdf). Philip Daian (Cornell Tech, USA); Steven Goldfeder (Cornell Tech, USA); Tyler Kell (Cornell Tech, USA); Yunqi Li (UIUC, USA); Xueyuan Zhao (Carnegie Mellon University, USA); Iddo Bentov (Cornell Tech, USA); Lorenz Breidenbach (ETH Zurich, Switzerland); Ari Juels (Cornell Tech, USA)

  - Keyword: _`Attacks`_

- 🎓 [Proof-of-Stake Sidechains](https://eprint.iacr.org/2018/1239.pdf). Peter Gaži, Aggelos Kiayias, Dionysis Zindros. IEEE S&P'19.
  - Keyword: _`Sidechain`_

* 🎓 [Blind Certificate Authorities](https://shelat.ccis.neu.edu/dl/WAPRS-blindca.pdf). Liang W, Gilad A, Rafael P, Thomas R, Abhi S. S&P '19.

  - Keyword: _`Privacy`_

* 🎓 [Bitcoin vs. Bitcoin Cash: Coexistence or Downfall of Bitcoin Cash?](https://arxiv.org/pdf/1902.11064.pdf). Yujin K, Hyoungshick K, Jinwoo S, Yongdae K. S&P '19.
  - Keyword: _`Mining`_

- 🎓 [Perun: Virtual payment hubs over cryptocurrencies](https://eprint.iacr.org/2017/635.pdf) Dziembowski S, Eckey L, Faust S, Malinowski D. IEEE S&P'19.

  - Keyword: _`Payment Channel Networks`_

- 🎓 [Lay Down the Common Metrics: Evaluating Proof-of-Work Consensus Protocols’ Security](https://www.esat.kuleuven.be/cosic/publications/article-3005.pdf) Ren Zhang, Bart Preneel. IEEE S&P'19.

  - Keyword: _`Consensus`_, _`PoW`_

- 🎓 [Redactable Blockchain in the Permissionless Setting](https://arxiv.org/abs/1901.03206). Dominic Deuber, Bernardo Magri, Sri Aravinda Krishnan Thyagarajan. IEEE S&P'19.

  - Keyword: _`Consensus`_

- 🎓 [Ouroboros Crypsinous: Privacy-Preserving Proof-of-Stake](https://eprint.iacr.org/2018/1132). Thomas Kerber and Markulf Kohlweiss and Aggelos Kiayias and Vassilis Zikas. IEEE S&P'19.

  - Keyword: _`Consensus`_, _`Privacy`_

- 🎓 [XCLAIM: Decentralized, Interoperable, Cryptocurrency-Backed Assets](https://eprint.iacr.org/2018/643.pdf).
  Alexei Zamyatin, Dominik Harz, Joshua Lind, Panayiotis Panayiotou, Arthur Gervais, William J. Knottenbelt. IEEE S&P'19. + Keyword: _`Scalaility`_

- 🎓 [OmniLedger: A Secure, Scale-Out, Decentralized Ledger via Sharding](https://eprint.iacr.org/2017/406.pdf). E. Kokoris-Kogias and P. Jovanovic and L. Gasser and N. Gailly and E. Syta and B. Ford. S&P'18.

  - Keyword: _`System`_

- 🎓 [Secure two-party threshold ECDSA from ECDSA assumptions](https://eprint.iacr.org/2018/499.pdf). Doerner J, Kondi Y, Lee E, et al. S&P'18.
  - Keyword: _`Wallets`_, _`Threshold Signature`_

* 🎓 [Hijacking Bitcoin: Routing Attacks on Cryptocurrencies](https://arxiv.org/pdf/1605.07524v2). Apostolaki M, Zohar A, Vanbever L. S&P'17.
  - Keyword: _`Network`_

- 🎓 [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](https://eprint.iacr.org/2015/675.pdf). Kosba A, Miller A, Shi E, Wen Z, Papamanthou C. S&P'16

  - Keyword: _`Privacy`_

- 🎓 [The Miner's Dilemma](https://arxiv.org/abs/1411.7099). Ittay Eyal. S&P'15

  - Keyword: _`Consensus`_, _`PoW`_, _`Mining`_

- 🎓 **[SoK: Research Perspectives and Challenges for Bitcoin and Cryptocurrencies](http://www.jbonneau.com/doc/BMCNKF15-IEEESP-bitcoin.pdf)**. Bonneau J, Miller A, Clark J, Narayanan A, Kroll JA, Felten EW. S&P'15

  - Keyword: _`SoK`_

- 🎓 [Permacoin: Repurposing bitcoin work for data preservation](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956582.pdf). Miller A, Juels A, Shi E, Parno B, Katz J. Permacoin. S&P'14.

  - Keyword: _`Consensus`_, _`PoW`_

- 🎓 [Zerocash: Decentralized anonymous payments from bitcoin](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956581.pdf). Sasson EB, Chiesa A, Garman C, Green M, Miers I, Tromer E, Virza M. S&P'14.
  - Keyword: _`Privacy`_

* 🎓 [Zerocoin: Anonymous distributed e-cash from bitcoin](http://ieeexplore.ieee.org/iel7/6547086/6547088/06547123.pdf). Miers I, Garman C, Green M, Rubin AD. S&P'13.
  - Keyword: _`Privacy`_

## CCS (A)

- 🎓 [eThor: Practical and Provably Sound Static Analysis of Ethereum Smart Contracts](https://arxiv.org/pdf/2005.06227.pdf).
  Clara Schneidewind (TU Wien); Markus Scherer (TU Wien); Ilya Grishchenko (TU Wien); Matteo Maffei (TU Wien)

  - Keyword: _`Smart Contracts`_

- 🎓 [ACE: Asynchronous and Concurrent Execution of Complex Smart Contracts](https://eprint.iacr.org/2019/835.pdf). Karl Wüst (ETH Zurich); Sinisa Matetic (ETH Zurich); Silvan Egli (ETH Zurich); Kari Kostiainen (ETH Zurich); Srdjan Capkun (ETH Zurich)

  - Keyword: _`Smart Contracts`_

- 🎓 [BDoS: Blockchain Denial-of-Service Attacks](https://arxiv.org/pdf/1912.07497.pdf). Michael Mirkin (Technion); Yan Ji (Cornell Tech); Jonathan Pang (Cornell University); Ariah Klages-Mundt (Cornell University); Ittay Eyal (Technion); Ari Juels (Cornell Tech). CCS'20.

  - Keyword: _`Attacks`_

- 🎓 [Dumbo: Faster Asynchronous BFT Protocols](https://eprint.iacr.org/2020/841.pdf). Bingyong Guo (Institute of Software, Chinese Academy of Sciences; State Key Laboratory of Cryptology; School of Computer Science and Technology, University of Chinese Academy of Sciences; JDD-NJIT-ISCAS Joint Blockchain Lab); Zhenliang Lu (New jersey institute of technology; JDD-NJIT-ISCAS Joint Blockchain Lab); Qiang Tang (New Jersey Institute of Technology; JDD-NJIT-ISCAS Joint Blockchain Lab); Jing Xu (Institute of Software, Chinese Academy of Sciences; JDD-NJIT-ISCAS Joint Blockchain Lab); Zhenfeng Zhang (Institute of Software, Chinese Academy of Sciences; JDD-NJIT-ISCAS Joint Blockchain Lab). CCS'20

  - Keyword: _`Consensus`_

- 🎓 [Efficient Publicly Verifiable 2PC over a Blockchain with Applications to Financially-Secure Computations](http://homes.sice.indiana.edu/yh33/mypub/pvc.pdf). Ruiyu Zhu, Changchang Ding, Yan Huang. CCS'19.

  - Keyword: _`Consensus`_, _`sMPC`_

- 🎓 [Erlay: Efficient Transaction Relay for Bitcoin](https://www.ece.ubc.ca/~sasha/papers/ccs19.pdf). Gleb Naumenko, Gregory Maxwell, Pieter Wuille, Alexandra (Sasha) Fedorova, Ivan Beschastnikh. CCS'19.

  - Keyword: **Erlay**, _`Scalability`_, _`Network`_

- 🎓 [HyperService: Interoperability and Programmability across Heterogeneous Blockchains](https://arxiv.org/pdf/1908.09343). Zhuotao Liu, Yangxi Xiang,Jian Shi, Peng Gao, Haoyu Wang, Xusheng Xiao, Bihan Wen, Yih-Chun Hu. CCS'19.

  - Keyword: **HyperService**, _`Sidechain`_, _`Interoperability`_, _`Programmability`_

- 🎓 [MatRiCT: Efficient, Scalable and Post-Quantum Blockchain Confidential Transactions Protocol](https://eprint.iacr.org/2019/1287.pdf). Muhammed F. Esgin, Raymond K. Zhao, Ron Steinfeld, Joseph K. Liu, Dongxi Liu. CCS'19.

  - Keyword: **MatRiCT**, _`Privacy`_, _`Wallets`_, _`RingCT`_, _`Post-quantum`_

- 🎓 [Omniring: Scaling Up Private Payments Without Trusted Setup — Formal Foundations and a Construction of Ring Confidential Transactions with Log-size Proofs](https://eprint.iacr.org/2019/580.pdf). Russell W. F. Lai, Viktoria Ronge, Tim Ruffing, Dominique Schröder, Sri Aravinda Krishnan Thyagarajan, Jiafan Wang. CCS'19.

  - Keyword: **Omniring**, _`Payment`_, _`RingCT`_

- 🎓 [Prism: Deconstructing the Blockchain to Approach Physical Limits](https://arxiv.org/pdf/1810.08092). Vivek Bagaria, Sreeram Kannan, David Tse, Giulia Fanti, Pramod Viswanath. CCS'19.

  - Keyword: **Prism**, _`Consensus`_, _`PoW`_

- 🎓 [Learning to Fuzz from Symbolic Execution with Application to Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/ccs19-ilf.pdf). Jingxuan He, Mislav Balunovic, Nodar Ambroladze, Petar Tsankov, Martin Vechev. CCS'19.

  - Keyword: _`Smart Contracts`_

- 🎓 [zkay: Specifying and Enforcing Data Privacy in Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/ccs19-zkay.pdf). Samuel Steffen, Benjamin Bichsel, Mario Gersbach, Noa Melchior, Petar Tsankov, Martin Vechev. CCS'19.

  - Keyword: **zkay**, _`Smart Contracts`_

- 🎓 [SAMPL: Scalable Auditability of Monitoring Processes using Public Ledgers](https://www.cs.nmsu.edu/~roopa/sampl.pdf). Roopa Vishwanathan, Gaurav Panwar, Satyajayant Misra, Austin Bos. CCS'19.

  - Keyword: **SAMPL**, _`Ledger`_

- 🎓 [Atomic Multi-Channel Updates with Constant Collateral in Payment-Channel Networks](https://eprint.iacr.org/2019/583.pdf). Christoph Egger, Pedro Moreno-Sanchez, Matteo Maffei. CCS'19.

  - Keyword: _`Payment Channel Networks`_

- 🎓 [Fast multiparty threshold ecdsa with fast trustless setup](https://eprint.iacr.org/2019/114.pdf). Gennaro R, Goldfeder S. CCS'18.

  - Keyword: _`Wallets`_, _`Threshold Signature`_

- 🎓 [Fast secure multiparty ecdsa with practical distributed key generation and applications to cryptocurrency custody](https://eprint.iacr.org/2018/987.pdf). Lindell Y, Nof A. CCS'18.

  - Keyword: _`Wallets`_, _`Threshold Signature`_

- 🎓 [General State Channel Networks](https://eprint.iacr.org/2018/320.pdf) Dziembowski S, Faust S, Hostáková K. CCS'18.
  - Keyword: _`Payment Channel Networks`_

* 🎓 [Ouroboros Genesis: Composable Proof-of-Stake Blockchains with Dynamic Availability](https://eprint.iacr.org/2018/378.pdf). Badertscher C, Gazi P, Kiayias A, Russell A, Zikas V. CCS'18.
  - Keyword: _`PoS`_

- 🎓 [FairSwap: How to fairly exchange digital goods](https://eprint.iacr.org/2018/740) Dziembowski S, Faust S, Eckey L. CCS'18.

  - Keyword: _`System`_

- 🎓 [RapidChain: Scaling Blockchain via Full Sharding](https://dl.acm.org/ft_gateway.cfm?ftid=2008927&id=3243853). Mahdi Zamani, Mahnush Movahedi, Mariana Raykova. CCS'18.
  - Keyword: _`System`_

* 🎓 [The Gap Game](http://delivery.acm.org/10.1145/3250000/3243737/p713-tsabary.pdf). Tsabary I., Eyal I. CCS'18.

  - Keyword: _`Economics`_

* 🎓 [Concurrency and Privacy with Payment-Channel Networks](https://eprint.iacr.org/2017/820.pdf). Malavolta G, Moreno-Sanchez P, Kate A, Maffei M, Ravi S. CCS '17.
  - Keyword: _`Payment Channel Networks`_

- 🎓 [Revive: Rebalancing Off-Blockchain Payment Channel Networks](https://eprint.iacr.org/2017/823.pdf). Khalil, R., & Gervais, A. CCS'17.
  - Keyword: _`Payment Channel Networks`_

* 🎓 [Bolt: Anonymous Payment Channels for Decentralized Currencies](https://eprint.iacr.org/2016/701.pdf) Green M, Miers I. CCS'16.
  - Keyword: _`Payment Channel Networks`_

- 🎓 [The Honey Badger of BFT Protocols](https://infoscience.epfl.ch/record/222858/files/199.pdf). Miller A, Xia Y, Croman K, Shi E, Song D. CCS'16.
  - Keyword: _`System`_

* 🎓 [A secure sharding protocol for open blockchains](https://www.comp.nus.edu.sg/~prateeks/papers/Elastico.pdf). Luu L, Narayanan V, Zheng C, Baweja K, Gilbert S, Saxena P. CCS '16.

  - Keyword: **Elastico**, _`Sharding`_, _`Scalability`_

* 🎓 **[On the instability of Bitcoin without the block reward](http://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf)**. Carlsten M, Kalodner H, Weinberg SM, Narayanan A. CCS'16.

  - Keyword: _`Economics`_

* 🎓 [On the Security and Performance of Proof of Work Blockchains](https://eprint.iacr.org/2016/555.pdf). Gervais A, Karame GO, Wüst K, Glykantzis V, Ritzdorf H, Capkun S. CCS '16.
  - Keyword: _`Mining`_

- 🎓 [Making Smart Contracts Smarter](https://www.comp.nus.edu.sg/~loiluu/papers/oyente.pdf). Luu L, Chu DH, Olickel H, Saxena P, Hobor A. CCS'16.
  - Keyword: _`Smart Contracts`_

* 🎓 [The Honey Badger of BFT Protocols](https://infoscience.epfl.ch/record/222858/files/199.pdf). Miller A, Xia Y, Croman K, Shi E, Song D. CCS'16.
  - Keyword: _`Network`_

- 🎓 [On the instability of Bitcoin without the block reward](http://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf). Carlsten M, Kalodner H, Weinberg SM, Narayanan A. CCS'16.

  - Keyword: _`Economic`_

- 🎓 [Town crier: An authenticated data feed for smart contracts](http://delivery.acm.org/10.1145/2980000/2978326/p270-zhang.pdf?ip=46.176.188.9&id=2978326&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E594C525CFFA2AFAF&CFID=923932938&CFTOKEN=56121949&__acm__=1492299159_38039f3afa858f241818fdcf190e0200). Zhang F, Cecchetti E, Croman K, Juels A, Shi E. CCS'16.
  - Keyword: _`Smart Contracts`_

* 🎓 **[Making Smart Contracts Smarter](https://www.comp.nus.edu.sg/~loiluu/papers/oyente.pdf)**. Luu L, Chu DH, Olickel H, Saxena P, Hobor A. CCS'16.

  - Keyword: **Oyente**, _`Smart Contracts`_

* 🎓 [The Ring of Gyges: Investigating the Future of Criminal Smart Contracts](http://www.initc3.org/files/Gyges.pdf). Juels A, Kosba A, Shi E. CCS'16.

  - Keyword: _`Smart Contracts`_

* 🎓 [Town crier: An authenticated data feed for smart contracts](https://eprint.iacr.org/2016/168.pdf). Zhang F, Cecchetti E, Croman K, Juels A, Shi E. CCS'16.
  - Keyword: _`Smart Contracts`_

- 🎓 [On the Security and Performance of Proof of Work Blockchains](https://eprint.iacr.org/2016/555.pdf). Gervais A, Karame GO, Karl Wüst, Glykantzis V, Ritzdorf H, Capkun S. CCS'16.

  - Keyword: _`Privacy`_

- 🎓 [A Secure Sharding Protocol For Open Blockchains](https://www.comp.nus.edu.sg/~loiluu/papers/elastico.pdf). Loi Luu, Viswesh Narayanan, Chaodong Zheng, Kunal Baweja, Seth Gilbert, Prateek Saxena. CCS'16.

  - Keyword: _`System`_

- 🎓 [Demystifying incentives in the consensus computer](https://eprint.iacr.org/2015/702). Loi Luu, Jason Teutsch, Raghav Kulkarni and Prateek Saxena. CCS'15

  - Keyword: _`Economic`_

- 🎓 [Tampering with the Delivery of Blocks and Transactions in Bitcoin](https://eprint.iacr.org/2015/578.pdf).Gervais, Arthur and Ritzdorf, Hubert and Karame, Ghassan O. and Capkun, Srdjan. CCS'15

  - Keyword: _`Network`_, _`Consensus`_, _`PoW`_

- 🎓 [Non-outsourceable Scratch-Off Puzzles to Discourage Bitcoin Mining Coalitions](http://soc1024.ece.illinois.edu/nonoutsourceable_full.pdf). Andrew Miller, Elaine Shi, Ahmed Kosba, and Jonathan Katz. CCS'15

  - Keyword: _`Consensus`_, _`PoW`_, _`Mining`_

- 🎓 [Provisions: Privacy-preserving proofs of solvency for Bitcoin exchanges](https://eprint.iacr.org/2015/1008.pdf). Dagher GG, Bünz B, Bonneau J, Clark J, Boneh D. CCS'15

  - Keyword: _`Privacy`_

- 🎓 [Deanonymisation of Clients in Bitcoin P2P Network](https://arxiv.org/pdf/1405.7418.pdf). Biryukov A, Khovratovich D, Pustogarov I. CCS'14.

  - Keyword: _`Privacy`_

- 🎓 [Double-Spending Fast Payments in Bitcoin](https://www.eecis.udel.edu/~ruizhang/CISC859/S17/Paper/p9.pdf). Karame, Ghassan O. and Androulaki, Elli and Capkun, Srdjan. CCS'12.
  - Keyword: _`Consensus`_, _`PoW`_, _`Mining`_

## NDSS (A)

- 🎓 As Strong As Its Weakest Link: How to Break Blockchain DApps at RPC Service. Kai Li, Jiaqi Chen, Xianghong Liu, and Yuzhe Tang (Syracuse University); XiaoFeng Wang (Indiana University Bloomington); Xiapu Luo (The Hong Kong Polytechnic University). NDSS'21

  - Keyword: _`Attacks`_, _`Network`_

- 🎓 [Bitcontracts: Supporting Smart Contracts in Legacy Blockchains](https://eprint.iacr.org/2019/857.pdf). Karl Wüst, Loris Diana, and Kari Kostiainen (ETH Zurich); Ghassan Karame (NEC Laboratories Europe GmbH); Sinisa Matetic and Srdjan Capkun (ETH Zurich). NDSS'21

  - Keyword: _`Smart Contracts`_

- 🎓 [SquirRL: Automating Attack Analysis on Blockchain Incentive Mechanisms with Deep Reinforcement Learning](https://arxiv.org/pdf/1912.01798.pdf). Charlie Hou (CMU, IC3); Mingxun Zhou (Peking University); Yan Ji and Phil Daian (Cornell Tech, IC3); Florian Tramèr (Stanford University); Giulia Fanti (CMU, IC3); Ari Juels (Cornell Tech, IC3). NDSS'21

  - Keyword: _`Attacks`_, _`Mining`_

- 🎓 [Bobtail: Improved Blockchain Security with Low-Variance Mining](https://www.ndss-symposium.org/wp-content/uploads/2020/02/23095.pdf). George Bissias (University of Massachusetts Amherst), Brian N. Levine (University of Massachusetts Amherst). NDSS'20

  - Keyword: _`Mining`_

- 🎓 [Snappy: Fast On-chain Payments with Practical Collaterals](https://arxiv.org/abs/2001.01278.pdf). Vasilios Mavroudis (University College London), Karl Wüst (ETH Zurich), Aritra Dhar (ETH Zurich), Kari Kostiainen (ETH Zurich), Srdjan Capkun (ETH Zurich). NDSS'20

  - Keyword: _`Scalability`_

- 🎓 [The Attack of the Clones Against Proof-of-Authority](https://arxiv.org/abs/1902.10244.pdf). Parinya Ekparinya (University of Sydney), Vincent Gramoli (University of Sydney and CSIRO-Data61), Guillaume Jourjon (CSIRO-Data61). NDSS'20

  - Keyword: _`Attacks`_

- 🎓 [Broken Metre: Attacking Resource Metering in EVM](https://arxiv.org/abs/1909.07220.pdf).
  Daniel Perez (Imperial College London), Benjamin Livshits (Imperial College London, UCL Centre for Blockchain Technologies, and Brave Software). NDSS'20 + Keyword: _`Attacks`_

- 🎓 [SODA: A Generic Online Detection Framework for Smart Contracts](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24449.pdf). Ting Chen (University of Electronic Science and Technology of China), Rong Cao (University of Electronic Science and Technology of China), Ting Li (University of Electronic Science and Technology of China), Xiapu Luo (The Hong Kong Polytechnic University), Guofei Gu (Texas A&M University), Yufei Zhang (University of Electronic Science and Technology of China), Zhou Liao (University of Electronic Science and Technology of China), Hang Zhu (University of Electronic Science and Technology of China), Gang Chen (Chengdu Kongdi Technology Inc.), Zheyuan He (University of Electronic Science and Technology of China), Yuxing Tang (University of Electronic Science and Technology of China), Xiaodong Lin (University of Guelph), Xiaosong Zhang (University of Electronic Science and Technology of China). NDSS'20

  - Keyword: _`Smart Contracts`_, _`Formal Methods`_

- 🎓 [Anonymous Multi-Hop Locks for Blockchain Scalability and Interoperability](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_09-4_Malavolta_paper.pdf). Malavolta G, Moreno-Sanchez P, Schneidewind C, Kate A, Maffei M. NDSS'19.
  - Keyword: _`Payment Channels`_
  - Github: https://github.com/KZen-networks/multi-hop-locks

* 🎓 [SABRE: Protecting Bitcoin against Routing Attacks](https://arxiv.org/pdf/1808.06254.pdf). Maria Apostolaki, Gian Marti, Jan Müller, and Laurent Vanbever. NDSS'19.

  - Keyword: _`Network`_

* 🎓 [Seth: Protecting Existing Smart Contracts Against Re-Entrancy Attacks](https://arxiv.org/pdf/1812.05934.pdf). Michael Rodler, Wenting Li and Ghassan Karame, Lucas Davi. NDSS'19.

  - Keyword: _`Smart Contracts`_

* 🎓 [YODA: Enabling computationally intensive contracts on blockchains with Byzantine and Selfish nodes](https://arxiv.org/pdf/1811.03265.pdf). Sourav Das, Vinay Joseph Ribeiro, and Abhijeet Anand. NDSS'19.

  - Keyword: _`Smart Contracts`_

* 🎓 [Fine-Grained and Controlled Rewriting in Blockchains: Chameleon-Hashing Gone Attribute-Based](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_02A-3_Derler_paper.pdf). David Derler, Kai Samelin, Daniel Slamanig and Christoph Striecks. NDSS'19.

  - Keyword: _`Cryptograph`_

* 🎓 [Privacy-preserving Multi-hop Locks for Blockchain Scalability and Interoperability](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_09-4_Malavolta_paper.pdf). Giulio Malavolta, Pedro Moreno Sanchez, Clara Schneidewind and Matteo Maffei, Aniket Kate. NDSS'19.

  - Keyword: _`Scalability`_, _`Layer 2`_

* 🎓 ["Zeus": Analyzing Safety of Smart Contracts](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_09-1_Kalra_paper.pdf). Kalra S, Goel S, Dhawan M, Sharma S. NDSS'18.

  - Keyword: _`Economic`_, _`Smart Contracts`_

* 🎓 [Chainspace: A Sharded Smart Contracts Platform](https://sheharbano.com/assets/publications/ndss2018-chainspace.pdf). Mustafa Al-Bassam, Alberto Sonnino, Shehar Bano, Dave Hrycyszyn, and George Danezis. NDSS'18.

  - Keyword: _`System`_

* 🎓 [Settling Payments Fast and Private: Efficient Decentralized Routing for Path-Based Transactions](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_09-3_Roos_paper.pdf). Stefanie Roos, Pedro Moreno-Sanchez, Aniket Kate, and Ian Goldberg. NDSS'18.
  - Keyword: _`Scalability`_, _`Layer 2`_

- 🎓 [TumbleBit: An untrusted Bitcoin-compatible anonymous payment hub](https://pdfs.semanticscholar.org/a4ce/62a44770a33d1a19b5553f080d4f12e9e55d.pdf). Heilman E, Alshenibr L, Baldimtsi F, Scafuro A, Goldberg S. NDSS'17.

  - Keyword: _`Privacy`_

- 🎓 [Centrally banked cryptocurrencies](https://arxiv.org/pdf/1505.06895.pdf). Danezis G, Meiklejohn S. NDSS'16.
  - Keyword: _`Consensus`_, **RSCoin**

## CRYPTO (A)

- 🎓 [Order-Fairness for Byzantine Consensus](https://eprint.iacr.org/2020/269.pdf). Mahimna Kelkar, Fan Zhang, Steven Goldfeder, Ari Juels. CRYPTO'20

  - Keyword: _`Consensus`_

- 🎓 [Two-party ECDSA from hash proof systems and efficient instantiations](https://hal.archives-ouvertes.fr/hal-02281931/file/CRYPTO19_2pECDSA_extended.pdf). Castagnos G, Catalano D, Laguillaumie F, et al. CRYPTO'19.

  - Keyword: _`Wallets`_, _`Threshold Signature`_

- 🎓 [Threshold cryptosystems from threshold fully homomorphic encryption](https://pdfs.semanticscholar.org/5224/7b8f30a05bd8bd73b921f918af78c1ef015a.pdf). Boneh D, Gennaro R, Goldfeder S, et al. CRYPTO'18.

  - Keyword: _`Wallets`_, _`Threshold Signature`_

- 🎓 [Bitcoin as a Transaction Ledger: A Composable Treatment](https://eprint.iacr.org/2017/149.pdf). Badertscher C., Maurer U., Tschudi D., Zikas V. CRYPTO'17.
  - Keyword: _`Wallets`_

* 🎓 [Fast secure two-party ECDSA signing](https://pdfs.semanticscholar.org/59cb/bb6ccd07dc312d3d0c218d384f004396c370.pdf). Lindell Y. CRYPTO'17.

  - Keyword: _`Wallets`_, _`Threshold Signature`_

* 🎓 [The Bitcoin Backbone Protocol with Chains of Variable Difficulty](https://eprint.iacr.org/2016/1048). Juan A. Garay and Aggelos Kiayias and Nikos Leonardos. CRYPTO'17.
  - Keyword: _`Consensus`_, _`PoS`_

- 🎓 [Ouroboros: A provably secure proof-of-stake blockchain protocol](https://pdfs.semanticscholar.org/1c14/549f7ba7d6a000d79a7d12255eb11113e6fa.pdf). Kiayias A, Russell A, David B, Oliynykov R. CRYPTO'17.
  - Keyword: _`PoS`_

* 🎓 [Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake protocol](http://eprint.iacr.org/2017/573.pdf). Bernardo D, Gazi P, Kiayias A, Russell A. Crypto'17.
  - Keyword: _`Consensus`_, _`PoS`_

- 🎓 [How to Use Bitcoin to Design Fair Protocols](https://eprint.iacr.org/2014/129.pdf). Bentov I, Kumaresan R. CRYPTO'14.

  - Keyword: _`Economics`_

- 🎓 [Two-party generation of DSA signatures](https://link.springer.com/content/pdf/10.1007/3-540-45539-6_15.pdf). MacKenzie P, Reiter M K. CRYPTO'01

  - Keyword: _`Wallets`_, _`Threshold Signature`_

- 🎓 [Pricing via processing or combatting junk mail](https://web.cs.dal.ca/~abrodsky/7301/readings/DwNa93.pdf). Dwork C, Naor M. CRYPTO'92.

  - Keyword: _`Consensus`_, _`PoS`_, **Proof-of-Work**

- 🎓 [Blind signatures for untraceable payments](http://blog.koehntopp.de/uploads/Chaum.BlindSigForPayment.1982.PDF). Chaum D. CRYPTO'83.
  - Keyword: _`Privacy`_, _`Blind Signature`_

## EUROCRYPT (A)

> no papers directly related to blockchain in EUROCRYPTO'20

- 🎓 [Consensus through Herding](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_24.pdf). T-H. Hubert Chan Rafael Pass Elaine Shi. EUROCRYPT'19.

  - Keyword: _`Consensus`_

- 🎓 [Proof-of-Stake Protocols for Privacy-Aware Blockchains](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_23.pdf). Chaya Ganesh Claudio Orlandi Daniel Tschudi. EUROCRYPT'19.

  - Keyword: _`PoS`_

- 🎓 [Multi-Party Virtual State Channels](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_21.pdf). Stefan Dziembowski Lisa Eckey Sebastian Faust Julia Hesse Kristina Hostáková. EUROCRYPT'19.

  - Keyword: _`Payment Channel`_

- 🎓 [Aggregate Cash Systems: A Cryptographic Investigation of Mimblewimble](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_22.pdf). Georg Fuchsbauer Michele Orrù Yannick Seurin. EUROCRYPT'19.

  - Keyword: _`System`_

- 🎓 [Analysis of the Blockchain Protocol in Asynchronous Networks](https://eprint.iacr.org/2016/454.pdf). Pass R, Seeman L, shelat a. EUROCRYPT'17
  - Keyword: _`Consensus-PoW`_

* 🎓 [Fair and Robust Multi-Party Computation using a Global Transaction Ledger](https://eprint.iacr.org/2015/574.pdf). Kiayias A., Zhouh S., Zikas V. EUROCRYPT'16.

  - Keyword: _`Applications`_

* 🎓 **[The Bitcoin Backbone Protocol: Analysis and Applications](https://eprint.iacr.org/2014/765.pdf)**. Garay J, Kiayias A, Leonardos N. EUROCRYPT'15.

  - Keyword: _`Consensus`_, _`PoW`_

* 🎓 [Practical threshold signatures](https://link.springer.com/content/pdf/10.1007/3-540-45539-6_15.pdf). Shoup V. EUROCRYPT'00.

  - Keyword: _`Wallets`_, _`Threshold Signature`_

* 🎓 Secure distributed key generation for discrete-log based cryptosystems. Gennaro R, Jarecki S, Krawczyk H, et al. EUROCRYPT'99
  - Keyword: _`Wallets`_, _`Threshold Signature`_

## INFOCOM (A)

- 🎓 [Modeling the Impact of Network Connectivity on Consensus Security of Proof-of-Work Blockchain](https://arxiv.org/pdf/2002.08912.pdf).
  Yang Xiao (Virginia Tech, USA); Ning Zhang (Washington University in St. Louis, USA); Wenjing Lou and Thomas Hou (Virginia Tech, USA) + Keyword: _`Consensus-PoW`_, _`Security`_

- 🎓 [Secure Balance Planning of Off-blockchain Payment Channel Networks](https://www.u-aizu.ac.jp/~pengli/files/pcn_planning_infocom2020.pdf).
  Peng Li and Toshiaki Miyazaki (The University of Aizu, Japan); Wanlei Zhou (University of Technology Sydney, Australia) + Keyword: _`Payment Channel Networks`_

- 🎓 [Corking by Forking: Vulnerability Analysis of Blockchain](https://sci-hub.tw/https://ieeexplore.ieee.org/document/8737490). Shengling Wang and Chenyu Wang, Qin Hu. INFOCOM'19

  - Keyword: _`Security`_

- 🎓 [ACCEL: Accelerating the Bitcoin Blockchain for High-throughput, Low-latency Applications](https://sci-hub.tw/https://ieeexplore.ieee.org/document/8737556). Adiseshu Hari, Murali Kodialam, T. V Lakshman. INFOCOM'19

  - Keyword: _`Scalability`_

- 🎓 [A Blockchain based Witness Model for Trustworthy Cloud Service Level Agreement Enforcement](https://pure.uva.nl/ws/files/42160225/Blockchain_based_Witness_Model.pdf). Huan Zhou, Xue Ouyang, Zhijie Ren, Jinshu Su, Cees de Laat and Zhiming Zhao. INFOCOM'19

  - Keyword: _`Application`_

- 🎓 [Stochastic Models and Wide-Area Network Measurements for Blockchain Design and Analysis](https://www.researchgate.net/publication/321369565_Stochastic_Models_and_Wide-Area_Network_Measurements_for_Blockchain_Design_and_Analysis). Nikolaos Papadis, Sem Borst, Anwar Walid, Mohamed Grissa, Leandros Tassiulas. INFOCOM'18

  - Keyword: _`Network`_

- 🎓 [Understanding ethereum via graph analysis](https://www4.comp.polyu.edu.hk/~csxluo/EthereumGraphAnalysis.pdf). Ting Chen,Yuxiao Zhu, Zihao Li, Jiachi Chen, Xiaoqi Li, Xiapu Luo, Xiaodong Lin, Xiaodong Lin. INFOCOM'18
  - Keyword: _`Transaction`_

## SOSP (A)

- 🎓 [Teechain: A Secure Payment Network with Asynchronous Blockchain Access](https://arxiv.org/pdf/1707.05454.pdf). Joshua Lind, Oded Naor, Ittay Eyal, Florian Kelbert, Peter Pietzuch, Emin Gun Sirer. SOSP'19

  - Keyword: _`Payment Channel Networks`_

- 🎓 [Fast and Secure Global Payments with Stellar](https://www.scs.stanford.edu/~dm/home/papers/lokhava:stellar-core.pdf). Marta Lokhava, Giuliano Losa, David Mazières, Graydon Hoare, Nicolas Barry, Eliezer Gafni, Jonathan Jove, Rafał Malinowski, Jed McCaleb. SOSP'19

  - Keyword: _`Consensus`_

- 🎓 [Notary: A Device for Secure Transaction Approval](https://pdos.csail.mit.edu/papers/notary:sosp19.pdf). Anish Athalye, Adam Belay, Frans Kaashoek, Robert Morris, Nickolai Zeldovich. SOSP'19

  - Keyword: _`Consensus`_

- 🎓 [Algorand: Scaling Byzantine Agreements for Cryptocurrencies](https://people.csail.mit.edu/nickolai/papers/gilad-algorand.pdf). Yossi Gilad, Rotem Hemo, Silvio Micali, Georgios Vlachos, Nickolai Zeldovich. SOSP'17
  - Keyword: _`Consensus`_

## NSDI (A)

- 🎓 [High Throughput Cryptocurrency Routing in Payment Channel Networks](https://www.usenix.org/system/files/nsdi20-paper-sivaraman.pdf). Vibhaalakshmi Sivaraman, Massachusetts Institute of Technology; Shaileshh Bojja Venkatakrishnan, Ohio State University; Kathleen Ruan, Carnegie Mellon University; Parimarjan Negi and Lei Yang, Massachusetts Institute of Technology; Radhika Mittal, University of Illinois at Urbana-Champaign; Giulia Fanti, Carnegie Mellon University; Mohammad Alizadeh, Massachusetts Institute of Technology. NSDI'20

  - Keyword: _`Payment Channel Networks`_, **Spider**

- 🎓 [Monoxide: Scale Out Blockchain with Asynchronized Consensus Zones](https://www.usenix.org/system/files/nsdi19-wang-jiaping.pdf). Jiaping Wang, Hao Wang. NSDI'19

  - Keyword: _`System`_, **Zones**, **Eventual Atomicity**, **Chu-ko-nu Mining**

- 🎓 [zkLedger: Privacy-Preserving Auditing for Distributed Ledgers](https://www.usenix.org/system/files/conference/nsdi18/nsdi18-narula.pdf). Neha Narula and Willy Vasquez and Madars Virza. NSDI'18

  - Keyword: _`Privacy`_, **zkLedger**

- 🎓 [Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf). Eyal I, Gencer AE, Sirer EG, Van Renesse R. NSDI’16
  - Keyword: _`Consensus-PoW`_

## VLDB (A)

- 🎓 [Scalable, Resilient and Configurable Permissioned Blockchain Fabric](http://www.vldb.org/pvldb/vol13/p2893-rahnama.pdf), Sajjad Rahnama (University of California Davis); Suyash Gupta (University of California Davis); Thamir Qadah (Purdue University); Jelle Hellings (University of California Davis); Mohammad Sadoghi (University of California, Davis). VLDB'20

  - Type: _`Demo`_

- 🎓 [A Demonstration of Sterling: A Privacy-Preserving Data Marketplace](http://www.vldb.org/pvldb/vol11/p2086-hynes.pdf). Nick Hynes1, David Dao, David Yan, Raymond Cheng, Dawn Song. VLDB'19.

  - Keyword: _`Privacy`_

- 🎓 [CAPER: A Cross-Application Permissioned Blockchain](http://www.vldb.org/pvldb/vol12/p1385-amiri.pdf). Mohammad Javad Amiri, Divyakant Agrawal, Amr El Abbadi. VLDB'19.

  - Keyword: _`Application`_

- 🎓 [BlockchainDB - A Shared Database on Blockchains](http://www.vldb.org/pvldb/vol12/p1597-el-hindi.pdf). Muhammad El-Hindi,
  Carsten Binnig, Arvind Arasu, Donald Kossmann, Ravi Ramamurthy. VLDB'19. + Keyword: _`Application`_

- 🎓 [Fine-Grained, Secure and Efficient Data Provenance on Blockchain Systems](http://www.vldb.org/pvldb/vol12/p975-ruan.pdf). Pingcheng Ruan, Gang Chen, Tien Tuan Anh Dinh, Qian Lin, Beng Chin Ooi, Meihui Zhang. VLDB'19.

  - Keyword: _`Provenance`_

- 🎓 [ForkBase: An Efficient Storage Engine for Blockchain and Forkable Applications](http://www.vldb.org/pvldb/vol11/p1137-wang.pdf). Sheng Wang, Tien Tuan Anh Dinh, Qian Lin, Zhongle Xie, Meihui Zhang, Qingchao Cai, Gang Chen, Beng Chin Ooi, Pingcheng Rua. VLDB'18.
  - Keyword: _`Storage`_

## OSDI (A)

- 🎓 [Virtual Consensus in Delos](https://maheshba.bitbucket.io/papers/delos-osdi2020.pdf). Mahesh Balakrishnan, Jason Flinn, Chen Shen, Mihir Dharamshi, Ahmed Jafri, Xiao Shi, Santosh Ghosh, Hazem Hassan, Aaryaman Sagar, Rhed Shi, Jingming Liu, Filip Gruszczynski, Xianan Zhang, Huy Hoang, Ahmed Yossef, Francois Richard, and Yee Jiun Song, Facebook, Inc. OSDI'20

  - Keyword: _`Scalability`_, _`Consensus`_

- 🎓 [Byzantine Ordered Consensus without Byzantine Oligarchy](https://eprint.iacr.org/2020/1300.pdf). Yunhao Zhang, Cornell University; Srinath Setty, Qi Chen, and Lidong Zhou, Microsoft Research; Lorenzo Alvisi, Cornell University. OSDI'20

  - Keyword: _`Scalability`_, _`Consensus`_, **Byzantine Ordered Consensus**

- 🎓 [Microsecond Consensus for Microsecond Applications](https://arxiv.org/pdf/2010.06288.pdf). Marcos K. Aguilera and Naama Ben-David, VMware Research; Rachid Guerraoui, EPFL; Virendra J. Marathe, Oracle Labs; Athanasios Xygkis and Igor Zablotchi, EPFL. OSDI'20

  - Keyword: _`Scalability`_, _`Consensus`_

- 🎓 [Blockene: A High-throughput Blockchain Over Mobile Devices](https://www.usenix.org/conference/osdi20/presentation/satija). Sambhav Satija and Apurv Mehra, Microsoft Research India; Sudheesh Singanamalla, University of Washington; Karan Grover, Muthian Sivathanu, Nishanth Chandran, Divya Gupta, and Satya Lokam, Microsoft Research India. OSDI'20

  - Keyword: _`Scalability`_, _`Consensus`_

- 🎓 [Proving the correct execution of concurrent services in zero-knowledge](https://www.usenix.org/system/files/osdi18-setty.pdf). Srinath Setty, Sebastian Angel, Trinabh Gupta, Jonathan Lee. OSDI'18.

  - Keyword: _`Formal Methods`_, _`ZKP`_, **Spice**

- 🎓 [Practical Byzantine Fault Tolerance](http://pmg.csail.mit.edu/papers/osdi99.pdf). Castro M., Liskov B. OSDI'99.
  - Keyword: _`Consensus`_

## SIGMOD (A)

- 🎓 Confidentiality Support over Financial Grade Consortium Blockchain.
  Ying Yan (Ant Financial Services Group), Changzheng Wei (Ant Financial Services Group), Xuepeng Guo (Ant Financial Services Group), Xuming Lu (Ant Financial Services Group), Xiaofu Zheng (Ant Financial Services Group), Qi Liu (Ant Financial Services Group), Chenhui Zhou (Ant Financial Services Group), Xuyang Song (Ant Financial Services Group), Boran Zhao (Ant Financial Services Group), Hui Zhang (Ant Financial Services Group), Guofei Jiang (Ant Financial Services Group). SIGMOD'20

  - Keyword: _`Privacy`_, _`TEE`_
  - Type: _`Industrial`_

- 🎓 [FalconDB: Blockchain-based Collaborative Database](http://www.cs.utah.edu/~lifeifei/papers/falcondb.pdf). Yanqing Peng (University of Utah), Min Du (University of California, Berkeley), Feifei Li (University of Utah), Raymond Cheng (University of California, Berkeley), Dawn Song (University of California, Berkeley). SIGMOD'20

  - Keyword: _`Application`_

- 🎓 [A Transactional Perspective on Execute-order-validate Blockchains](https://arxiv.org/pdf/2003.10064.pdf). Pingcheng Ruan (National University of Singapore), Dumitrel Loghin (National University of Singapore), Quang-Trung Ta (National University of Singapore), Meihui Zhang (Beijing Institute of Technology), Gang Chen (Zhejiang University), Beng Chin Ooi (National University of Singapore). SIGMOD'20

## TOCS (A)

- 🎓 [The part-time parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf). Lamport L. TOCS '98.
  - Keyword: _`Consensus`_

## TOPLAS (A)

- 🎓 [The Byzantine Generals Problem](https://people.eecs.berkeley.edu/~luca/cs174/byzantine.pdf). Lamport L, Shostak R., Pease M. '82. TOPLAS '82.
  - Keyword: _`Consensus`_

## JACM (A)

- 🎓 [Consensus in the Presence of Partial Synchrony](https://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf). Dwork S., Lynch N. '88. JACM '88.
  - Keyword: _`Consensus`_

## ASE (A)

- 🎓 [Demystifying Loops in Smart Contracts](https://fredfeng.github.io/papers/ase20-consul.pdf).
  Benjamin Mariano (University of Texas at Austin), Yanju Chen (University of California, Santa Barbara), Yu Feng (University of California, Santa Barbara), Shuvendu K. Lahiri (Microsoft Research), and Isil Dillig (University of Texas at Austin). ASE'20

- 🎓 [Cross-Contract Static Analysis for Detecting Practical Reentrancy Vulnerabilities in Smart Contracts](https://yuleisui.github.io/publications/ase20.pdf). Yinxing Xue (University of Science and Technology of China), Mingliang Ma (University of Science and Technology of China), Yun Lin (National University of Singapore), Yulei Sui (University of Technology Sydney), Jiaming Ye (University of Science and Technology of China), and Tianyong Peng (University of Science and Technology of China). ASE'20

- 🎓 [Summary-Based Symbolic Evaluation for Smart Contracts](https://homes.cs.washington.edu/~emina/doc/solar.ase20.pdf). Yu Feng (University of California, Santa Barbara), Emina Torlak (University of Washington), and Rastislav Bodik (University of
  Washington). ASE'20

- 🎓 [SmartBugs: A Framework to Analyze Solidity Smart Contracts](https://www.inesc-id.pt/publications/15467/pdf/). João Ferreira (INESC-ID & IST, University of Lisbon, Portugal), Pedro Cruz (INESC-ID & IST, University of Lisbon, Portugal), Thomas Durieux (KTH Royal Institute of Technology, Sweden), and Rui Abreu (INESC-ID &
  IST, University of Lisbon, Portugal). ASE'20

  - Type: _`Tool`_

- 🎓 [EXPRESS: An Energy-Efficient and Secure Framework for Mobile Edge Computing and Blockchain based Smart Systems](https://drive.google.com/file/d/1VtUJY6IY4SOcLAz_690nTYgHxj3xCeQs/view). Jia Xu (Anhui University, China), Xiao Liu (Deakin University, Australia), Xuejun Li (Anhui University, China), Lei Zhang Antwork Robotics Co., Ltm.), and Yun Yang (Swinburne University of Technology, Australia). ASE'20
  - Type: _`Tool`_

## Journal of Cryptology (A)

## TDSC (A)

- 🎓 [Security and privacy in decentralized energy trading through multi-signatures, blockchain and anonymous messaging streams](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/7589035). Aitzhan N Z, Svetinovic D. TDSC'16
  - Keyword: _`Applications`_

## ASIACRYPT (B)

- 🎓 [Compact multi-signatures for smaller blockchains](https://eprint.iacr.org/2018/483.pdf). Boneh D, Drijvers M, Neven G. ASIACRYPT'18

  - Keyword: _`Wallets`_, _`Threshold Signature`_

- 🎓 [Short signatures from the Weil pairing](https://www.iacr.org/archive/asiacrypt2001/22480516.pdf). Boneh D, Lynn B, Shacham H. ASIACRYPT'01
  - Keyword: _`Wallets`_, _`Threshold Signature`_

## ESORICS (B)

- 🎓 [Anonymity Preserving Byzantine Vector Consensus](https://gramoli.redbellyblockchain.io/web/doc/pubs/anonymous-vote-ESORICS20.pdf). Christian Cachin, Daniel Collins, Tyler Crain, Vincent Gramoli. ESORICS'20

  - Keyword: _`Consensus`_

- 🎓 [LegIoT: Ledgered Trust Management Platform for IoT](https://se.informatik.uni-wuerzburg.de/secure-software-systems-group/staff0/alexandra-dmitrienko/?tx_extbibsonomycsl_publicationlist%5BuserName%5D=sssgroup&tx_extbibsonomycsl_publicationlist%5BintraHash%5D=74fa5167627be7d794d5ddd457ba1bbb&tx_extbibsonomycsl_publicationlist%5BfileName%5D=LegIoT_camera_ready-v4.pdf&tx_extbibsonomycsl_publicationlist%5Baction%5D=download&tx_extbibsonomycsl_publicationlist%5Bcontroller%5D=Document&cHash=d3e5fdff7d78ca4cb3b00d4bb92b70ee). Jens Neureither, Alexandra Dmitrienko, David Koisser, Ferdinand Brasser, Ahmad-Reza Sadeghi. ESORICS'20

- 🎓 [Distributed Detection of APTs: Consensus vs. Clustering](https://www.nics.uma.es/pub/papers/1846.pdf). Juan E. Rubio, Cristina Alcaraz, Ruben Rios, Rodrigo Roman, Javier Lopez. ESORICS'20

- 🎓 [How to Model the Bribery Attack: A Practical Quantification Method in Blockchain](https://link.springer.com/chapter/10.1007%2F978-3-030-59013-0_28). Hanyi Sun, Na Ruan, Chunhua Su. ESORICS'20

  - Keyword: _`Attacks`_

- 🎓 [Updatable Blockchains](https://eprint.iacr.org/2020/887.pdf). Michele Ciampi, Nikos Karayannidis, Aggelos Kiayias, Dionysis Zindros. ESORICS'20

- 🎓 [PrivacyGuard: Enforcing Private Data Usage Control with Blockchain and Attested Off-Chain Contract Execution](https://arxiv.org/pdf/1904.07275.pdf). Yang Xiao, Ning Zhang, Jin Li, Wenjing Lou, Y. Thomas Hou. ESORICS'20

- 🎓 [2-hop Blockchain: Combining Proof-of-Work and Proof-of-Stake Securely](https://eprint.iacr.org/2016/716.pdf). Tuyet Duong, Lei Fan, Jonathan Katz, Phuc Thai, Hong-Sheng Zhou. ESORICS'20

  - Keyword: _`Consensus`_, _`PoW`_(Proof of Work), _`PoS`_(Proof of Stake), _`Proof-of-X`_

- 🎓 [Generic Superlight Client for Permissionless Blockchains](https://arxiv.org/pdf/2003.06552.pdf). Yuan Lu, Qiang Tang, Guiling Wang. ESORICS'20

  - Keyword: _`Wallets`_

- 🎓 [LNBot: A Covert Hybrid Botnet on Bitcoin Lightning Network for Fun and Profit](https://arxiv.org/pdf/1912.10617.pdf). Ahmet Kurt, Enes Erdin, Mumin Cebe, Kemal Akkaya, A. Selcuk Uluagac. ESORICS'20

- 🎓 [PGC: Decentralized Confidential Payment System with Auditability](https://eprint.iacr.org/2019/319.pdf). Yu Chen, Xuecheng Ma, Cong Tang, Man Ho Au. ESORICS'20

- 🎓 [Incentives for Harvesting Attack in Proof of Work Mining Pools](https://link.springer.com/chapter/10.1007/978-3-030-29959-0_34). Zolotavkin Y, & Kuchta V. ESORICS'19

  - Keyword: _`Attacks`_

- 🎓 [PDFS: practical data feed service for smart contracts](https://arxiv.org/pdf/1808.06641.pdf). Guarnizo J, Szalachowski P. ESORICS'19

  - Keyword: _`Application`_, _`Smart Contracts`_

- 🎓 [Towards a Marketplace for Secure Outsourced Computations](https://arxiv.org/pdf/1808.09682.pdf). Dang H., Le Tien D., Chang E C. ESORICS'19

  - Keyword: _`Application`_, _`Payment Channels`_

- 🎓 [Annotary: A Concolic Execution System for Developing Secure Smart Contracts](https://arxiv.org/pdf/1907.03868.pdf). Weiss, K. Schütte, J. ESORICS'19

  - Keyword: _`Smart Contracts`_

- 🎓 [A Lattice-Based Linkable Ring Signature Supporting Stealth Addresses](https://books.google.com.hk/books?id=TqOvDwAAQBAJ&pg=PA745&lpg=PA745&dq=pdf+A+Lattice-Based+Linkable+Ring+Signature+Supporting+Stealth+Addresses&source=bl&ots=X8AWJqPEBj&sig=ACfU3U1-Ev8mg5y9G1X-GgTeRQN50MhWCQ&hl=zh-CN&sa=X&ved=2ahUKEwiM0IGL-5LlAhUsy4sBHYCuDEwQ6AEwBHoECAkQAQ#v=onepage&q=A%20Lattice-Based%20Linkable%20Ring%20Signature%20Supporting%20Stealth%20Addresses&f=false). Liu, Z., Nguyen, K., Yang, G., Wang, H., Wong, D. S. ESORICS'19

  - Keyword: _`Privacy`_, _`Ring Signature`_

- 🎓 [Coinshuffle: Practical decentralized coin mixing for bitcoin](http://crypsys.mmci.uni-saarland.de/projects/CoinShuffle/coinshuffle.pdf). Ruffing T, Moreno-Sanchez P, Kate A. ESORICS '14.
  - Keyword: _`Privacy`_

## ACSAC (B)

- 🎓 Policy-based Chameleon Hash for Blockchain Rewriting with Black-box Accountability. Yangguang Tian, Pawel Szalachowski, Jianying Zhou (Singapore University of Technology and Design), Yingjiu Li (University of Oregon), Nan Li (University of Newcastle). ACSAC'20

  - Keyword: _`System`_

## EuroSys (B)

> no papers directly related to blockchain in EUROSYS'20

- 🎓 [Hyperledger Fabric: A Distributed Operating System for Permissioned Blockchains](https://arxiv.org/pdf/1801.10228.pdf). Elli Androulaki, Artem Barger, Vita Bortnikov, Christian Cachin, Konstantinos Christidis, Angelo De Caro, David Enyeart, Christopher Ferris, Gennady Laventman, Yacov Manevich, Srinivasan Muralidharan, Chet Murthy, Binh Nguyen, Manish Sethi, Gari Singh, Keith Smith, Alessandro Sorniotti, Chrysoula Stathakopoulou, Marko Vukolić, Sharon Weed Cocco, Jason Yellick. EuroSys'18
  - Keyword: _`System`_

## ICDCS (B)

- 🎓 [Selfish Mining in Ethereum](https://arxiv.org/abs/1901.04620) Jianyu Niu and Chen Feng. ICDCS'19

  - Keyword: _`PoW`_

- 🎓 [Trust Mends Blockchains: Living up to Expectations](http://kth.diva-portal.org/smash/get/diva2:1316199/FULLTEXT01.pdf). Leila Bahri and Sarunas Girdzijauskas. ICDCS'19

  - Keyword: _`Consensus`_

- 🎓 [Hierarchical Edge-Cloud Computing for Mobile Blockchain Mining Game](https://pdfs.semanticscholar.org/cfe0/77c9b880c2a0dfb495448a068fdf1db07b6e.pdf). Suhan Jiang, Xinyi Li and Jie Wu. ICDCS'19

  - Keyword: _`Application`_

- 🎓 OptChain: Optimal Transactions Placement for Scalable Blockchain Sharding. Lan Nguyen, Truc Nguyen, Thang Dinh and My Thai. ICDCS'19

  - Keyword: _`Scalability`_

- 🎓 Jidar: A Jigsaw-like Data Reduction Approach without Trust Assumptions for Bitcoin System. Xiaohai Dai, Jiang Xiao, Wenhui Yang, Chaofan Wang and Hai Jin. ICDCS'19

  - Keyword:

- 🎓 [ParBlockchain: Leveraging Transaction Parallelism in Permissioned Blockchain Systems](https://arxiv.org/pdf/1902.01457.pdf). Mohammad Javad Amiri, Divyakant Agrawal and Amr El Abbadi. ICDCS'19

  - Keyword: _`Scalability`_

- 🎓 Optimal Admission Control For Secondary Users using Blockchain Technology In Cognitive Radio Networks. Wenlong Ni, Yuhong Zhang and Wei Li. ICDCS'19

  - Keyword: _`Application`_

- 🎓 B-IoT: Blockchain Driven Internet of Things with Credit-Based Consensus Mechanism. Junqin Huang, Linghe Kong, Guihai Chen, Long Chen, Kaishun Wu and Xue Liu. ICDCS'19

  - Keyword: _`Application`_

- 🎓 Resource Allocation and Consensus on Edge Blockchain in Pervasive Edge Computing Environments. Yaodong Huang, Jiarui Zhang, Jun Duan, Bin Xiao, Fan Ye and Yuanyuan Yang. ICDCS'19

  - Keyword: _`Application`_

- 🎓 Xyreum: A High-Performance and Scalable Blockchain for IIoT Security and Privacy. Abubakar Sadiq Sani, Dong Yuan, Wei Bao, Phee Lep Yeoh, Zhaoyang Dong, Branka Vucetic and Elisa Bertino. ICDCS'19

  - Keyword: _`Application`_

- 🎓 AI Blockchain Platform for Trusting News. Zonyin Shae and Jeffrey Tsai. ICDCS'19

  - Keyword: _`Vision`_

- 🎓 Dependable Public Ledger for Policy Compliance, a Blockchain Based Approach. Zhou Wu, Andrew Williams and Debbie Perouli. ICDCS'19

  - Keyword: _`Vision`_

- 🎓 [Please, do not decentralize the Internet with (permissionless) blockchains!](https://arxiv.org/pdf/1904.13093.pdf). Pedro Garcia Lopez, Alberto Montresor and Anwitaman Datta. ICDCS'19

  - Keyword: _`Vision`_

- 🎓 Transform Blockchain into Distributed Parallel Computing Architecture for Precision Medicine. Zonyin Shae, Jeffrey J.P. Tsai. ICDCS'18

  - Keyword: _`Application`_

- 🎓 Towards A Novel Architecture for Enabling Interoperability Amongst Multiple Blockchains. Hai Jin, Xiaohai Dai, and Jiang Xiao. ICDCS'18

  - Keyword: _`Interoperability`_

- 🎓 Towards Dependable, Scalable, and Pervasive Distributed Ledgers with Blockchains. Zhang Kaiwen, Jacobsen Hans-Arno.ICDCS'18

  - Keyword: _`Consensus`_
  - Type: _`Short`_

- 🎓 A Flexible Network Approach to Privacy of Blockchain Transactions. David M¨odinger, Henning Kopp, Frank Kargl and Franz J. Hauck. ICDCS'18
  - Keyword: _`Privacy`_
  - Type: _`Short`_

## PODC (B)

- 🎓 [Genuinely Distributed Byzantine Machine Learning](https://arxiv.org/pdf/1905.03853.pdf). El-Mahdi El-Mhamdi (EPFL), Rachid Guerraoui (EPFL), Arsany Guirguis (EPFL), Lê Nguyên Hoang (EPFL), Sébastien Rouault (EPFL). PODC'20

  - Keyword: _`Consensus`_

- 🎓 [Fault-Tolerance in Distributed Optimization: The Case of Redundancy](https://arxiv.org/pdf/2009.14763.pdf). Nirupam Gupta (Georgetown University), Nitin H. Vaidya (Georgetown University), Probably Approximately Knowing (video), Yoram Moses (Technion), Nitzan Zamir (Technion). PODC'20

  - Keyword: _`Consensus`_

- 🎓 [Positive Aging Admits Fast Asynchronous Plurality Consensus](). Gregor Bankhamer (University of Salzburg), Robert Elsässer (University of Salzburg), Dominik Kaaser (University of Hamburg), Matjaž Krnc (University of Primorska). PODC'20

  - Keyword: _`Consensus`_

- 🎓 [K set-agreement bounds in round-based models through combinatorial topology](). Adam Shimi (IRIT, University of Toulouse), Armando Castaneda (UNAM). PODC'20

  - Keyword: _`Consensus`_

- 🎓 [On Using Null Messages in a Byzantine Setting](). Guy Goren (Technion), Yoram Moses (Technion). PODC'20

  - Type: _`Short`_

- 🎓 [Dumbo-MVBA: Optimal Multi-Valued Validated Asynchronous Byzantine Agreement, Revisited](https://eprint.iacr.org/2020/842.pdf). Yuan Lu (New Jersey Institute of Technology), Zhenliang Lu, Qiang Tang (New Jersey Institute of Technology JDD-NJIT-ISCAS Joint Blockchain Lab), Guiling Wang (New Jersey Institute of Technology). PODC'20

  - Keyword: _`Consensus`_

- 🎓 [Revisiting Asynchronous Fault Tolerant Computation with Optimal Resilience](https://arxiv.org/pdf/2006.16686.pdf). Ittai Abraham (VMware Research), Danny Dolev (Hebrew University), Gilad Stern (Hebrew University). PODC'20

  - Keyword: _`Consensus`_

- 🎓 [Asynchronous Byzantine Approximate Consensus in Directed Networks](https://arxiv.org/pdf/2004.09054.pdf). Dimitris Sakavalas (Boston College), Lewis Tseng (Boston College), Nitin H. Vaidya (Georgetown University). PODC'20

  - Keyword: _`Consensus`_

- 🎓 [On the Subject of Non-Equivocation](https://itu.dk/people/debois/papers/podc20.pdf). Mads Frederik Madsen (IT University of Copenhagen), Søren Debois (IT University of Copenhagen). PODC'20

  - Keyword: _`Consensus`_

- 🎓 [Almost-surely Terminating Asynchronous Byzantine Agreement Protocols with a Constant Expected Running Time](https://eprint.iacr.org/2018/394.pdf). Ashish Choudhury (IIIT Bangalore). PODC'20

  - Keyword: _`Consensus`_, _`BFT`_
  - Type: _`Short`_

- 🎓 [On the Significance of Consecutive Ballots in Paxos](https://arxiv.org/pdf/2006.01885.pdf). Eli Goldweber (University of Michigan), Nuda Zhang (University of Michigan), Manos Kapritsos (University of Michigan). PODC'20

  - Keyword: _`Consensus`_
  - Type: _`Short`_

- 🎓 [Not a COINcidence: Sub-Quadratic Asynchronous Byzantine Agreement WHP](https://arxiv.org/pdf/2002.06545.pdf). Shir Cohen (Technion), Idit Keidar (Technion), Alexander Spiegelman (Novi). PODC'20

  - Keyword: _`Consensus`_, _`BFT`_
  - Type: _`Short`_

- 🎓 [Byzantine Agreement with Unknown Participants and Failures](https://dl.acm.org/doi/pdf/10.1145/3382734.3405740). Pankaj Khanchandani (ETH Zurich), Roger Wattenhofer (ETH Zurich). PODC'20

  - Keyword: _`Consensus`_
  - Type: _`Short`_

- 🎓 [Perigee: Efficient Peer-to-Peer Network Design for Blockchains](https://arxiv.org/pdf/2006.14186.pdf). Yifan Mao (The Ohio State University), Soubhik Deb (University of Washington Seattle), Shaileshh Bojja Venkatakrishnan (The Ohio State University), Sreeram Kannan (University of Washington Seattle), Kannan Srinivasan (The Ohio State University). PODC'20

  - Keyword: _`Network`_

- 🎓 [The Consensus Number of a Cryptocurrency](https://arxiv.org/pdf/1906.05574.pdf). R. Guerraoui, P. Kuznetsov, M. Monti, M. Pavlovic, D. Seredinschi. PODC'19

  - Keyword: _`Consensus`_

- 🎓 Communication Complexity of Byzantine Agreement, Revisited. I. Abraham, T. Chan, D. Dolev, K. Nayak, R. Pass, L. Ren, E. Shi. PODC'19

  - Keyword: _`Consensus`_, _`BFT`_

- 🎓 [Exact Byzantine Consensus on Undirected Graphs under Local Broadcast Model](https://arxiv.org/pdf/1903.11677.pdf). M. Khan, S. Naqvi, N. Vaidya. PODC'19

  - Keyword: _`Consensus`_, _`BFT`_

- 🎓 [Asymptotically Optimal Validated Asynchronous Byzantine Agreement](https://dl.acm.org/doi/pdf/10.1145/3293611.3331612). I. Abraham, D. Malkhi, A. Spiegelman. PODC'19

  - Keyword: _`Consensus`_, _`BFT`_

- 🎓 [HotStuff: BFT Consensus with Linearity and Responsiveness](https://www.cs.unc.edu/~reiter/papers/2019/PODC.pdf). M. Yin, I. Abraham, G. Gueta, D. Malkhi, M. Reiter. PODC'19

  - Keyword: _`Consensus`_, _`BFT`_

- 🎓 [Atomic Cross-Chain Swaps](https://arxiv.org/abs/1801.09515). Maurice Herlihy. PODC'18

  - Keyword: _`Sidechain`_

- 🎓 [Brief Announcement: Sustainable Blockchains through Proof of eXercise](https://haslab.uminho.pt/ashoker/files/pox-podc.pdf). Ali Shoker. PODC'18

  - Keyword: _`Consensus`_

- 🎓 [FruitChains: A Fair Blockchain](https://eprint.iacr.org/2016/916.pdf).Rafael Pass, Elaine Shi. PODC'17
  - Keyword: _`Consensus`_, _`PoW`_

## CoNEXT (B)

> no papers directly related to blockchain in CoNEXT'20

- 🎓 [On the Necessity of a Prescribed Block Validity Consensus: Analyzing Bitcoin Unlimited Mining Protocol](https://eprint.iacr.org/2017/686.pdf). Ren Zhang, Bart Preneel. CoNEXT '17
  - Keyword: _`Consensus`_, _`PoW`_

## ACNS (C)

- 🎓 [Threshold-optimal DSA/ECDSA signatures and an application to Bitcoin wallet security](https://eprint.iacr.org/2016/013.pdf). Gennaro R, Goldfeder S, Narayanan A. ACNS'16.
  - Keyword: _`Wallets`_, _`Threshold Signature`_

## FC (C)

- 🎓 [Leveraging Bitcoin Testnet for Bidirectional Botnet Command and Control Systems](http://fc20.ifca.ai/preproceedings/71.pdf). Federico Franzoni (Universitat Pompeu Fabra), Vanesa Daza (Universitat Pompeu Fabra), Iván Abellán (Universitat Pompeu Fabra). FC'20

  - Keyword: _`Attacks`_

- 🎓 [Security Analysis on dBFT protocol of NEO](http://fc20.ifca.ai/preproceedings/32.pdf). Qin Wang (Swinburne University of Technology), Jiangshan Yu (Monash University), Zhiniang Peng (Qihoo 360 Core Security), Vancuong Bui (Swinburne University of Technology), Shiping Chen (Csiro, Data61), Yong Ding (Cyberspace Security Research Center), Yang Xiang (Swinburne University of Technology). FC'20

  - Keyword: _`Attacks`_

- 🎓 [Breaking the encryption scheme of the Moscow internet voting system](http://fc20.ifca.ai/preproceedings/178.pdf). Pierrick Gaudry (CNRS, Inria, Université de Lorraine), Alexander Golovnev (Harvard University). FC'20

  - Keyword: _`Attacks`_

- 🎓 [Short Paper: XOR Arbiter PUFs have Systematic Response Bias](http://fc20.ifca.ai/preproceedings/58.pdf). Nils Wisiol (Technische Universität Berlin), Niklas Pirnay (Technische Universität Berlin). FC'20

  - Keyword: _`Attacks`_

- 🎓 [Selfish Mining Re-Examined](http://fc20.ifca.ai/preproceedings/4.pdf). Kevin Alarcón Negy (Cornell University), Peter R. Rizun (Bitcoin Unlimited), Emin Gün Sirer (Cornell University). FC'20

  - Keyword: _`Consensus`_, _`Mining`_

- 🎓 [Fairness and Efficiency in DAG-based Cryptocurrencies](http://fc20.ifca.ai/preproceedings/165.pdf). Georgios Birmpas (University of Oxford), Elias Koutsoupias (University of Oxford), Philip Lazos (Sapienza University of Rome), Francisco J. Marmolejo Cossío (University of Oxford). FC'20

  - Keyword: _`Consensus`_, _`DAG`_

- 🎓 [Stake Shift in Major Cryptocurrencies: An Empirical Study](http://fc20.ifca.ai/preproceedings/195.pdf). Rainer Stütz (Austrian Institute of Technology), Peter Gaži (IOHK), Bernhard Haslhofer (Austrian Institute of Technology), Jacob Illium (Chainalysis). FC'20

  - Keyword: _`Consensus`_
  - Type: _`Empirical`_

- 🎓 [Coded Merkle Tree: Solving Data Availability Attacks in Blockchains](http://fc20.ifca.ai/preproceedings/47.pdf). Mingchao Yu (University of Southern California), Saeid Sahraei (University of Southern California), Songze Li, Salman Avestimehr (University of Southern California), Sreeram Kannan (University of Washington), Pramod Viswanath (University of Illinois at Urbana-Champaign). FC'20

  - Keyword: _`Consensus`_

- 🎓 [Decentralized Privacy-Preserving Netting Protocol on Blockchain for Payment Systems](http://fc20.ifca.ai/preproceedings/27.pdf). Shengjiao Cao (Ant Financial), Yuan Yuan (Ant Financial), Angelo De Caro (IBM Research), Karthik Nandakumar (IBM Research), Kaoutar Elkhiyaoui (IBM Research), Yanyan Hu (IBM Research). FC'20

  - Keyword: _`Economics`_

- 🎓 [The Arwen Trading Protocols](http://fc20.ifca.ai/preproceedings/23.pdf). Ethan Heilman (Boston University/Arwen), Sebastien Lipmann (Arwen), Sharon Goldberg (Boston University/Arwen). FC'20

  - Keyword: _`Economics`_

- 🎓 [SoK: A Classification Framework for Stablecoin Designs](http://fc20.ifca.ai/preproceedings/119.pdf). Amani Moin (Cornell University), Kevin Sekniqi (Cornell University), Emin Gün Sirer (Cornell University). FC'20

  - Keyword: _`System`_
  - Type: _`SoK`_

- 🎓 [Zether: Towards Privacy in a Smart Contract World](http://fc20.ifca.ai/preproceedings/158.pdf). Benedikt Bünz (Stanford University), Shashank Agrawal (Visa Research), Mahdi Zamani (Visa Research), Dan Boneh (Stanford University). FC'20
  - Keyword: _`Privacy`_, _`Smart Contract`_
- 🎓 [An airdrop that preserves recipient privacy](http://fc20.ifca.ai/preproceedings/54.pdf). Riad S. Wahby (Stanford), Dan Boneh (Stanford), Christopher Jeffrey (Purse.io), Joseph Poon (Lightning Network). FC'20

  - Keyword: _`Privacy`_, _`Smart Contract`_

- 🎓 [SoK: Layer-Two Blockchain Protocols](http://fc20.ifca.ai/preproceedings/150.pdf). Lewis Gudgeon (Imperial College London), Pedro Moreno-Sanchez (TU Wein), Stefanie Roos (TU Delft), Patrick McCorry (PISA Research), Arthur Gervais (Imperial College London). FC'20

  - Keyword: _`Scalability`_, _`Layer 2`_
  - Type: _`SoK`_

- 🎓 [MicroCash: Practical Concurrent Processing of Micropayments](http://fc20.ifca.ai/preproceedings/38.pdf). Ghada Almashaqbeh (Columbia), Allison Bishop (Proof of Trading and Columbia), Justin Cappos (New York University). FC'20

  - Keyword: _`Scalability`_, _`Layer 2`_

- 🎓 [LockDown: Balance Availability Attack against Lightning Network Channels](http://fc20.ifca.ai/preproceedings/73.pdf). Cristina Pérez-Solà (Universitat Oberta de Catalunya), Alejandro Ranchal-Pedrosa (University of Sydney), Jordi Herrera-Joancomarti (Universitat Autònoma de Barcelona), Guillermo Navarro-Arribas (Universitat Autònoma de Barcelona), Joaquin Garcia-Alfaro (Institut Polytechnique de Paris). FC'20

  - Keyword: _`Scalability`_, _`Layer 2`_

- 🎓 [Ride the Lightning: The Game Theory of Payment Channels](http://fc20.ifca.ai/preproceedings/134.pdf). Zeta Avarikioti (ETH Zurich), Lioba Heimbach (ETH Zurich), Yuyi Wang (ETH Zurich), Roger Wattenhofer (ETH Zurich). FC'20

  - Keyword: _`Scalability`_, _`Layer 2`_

- 🎓 [How to profit from payments channels](http://fc20.ifca.ai/preproceedings/201.pdf). Oguzhan Ersoy (Delft University of Technology), Stefanie Roos (Delft University of Technology), Zekeriya Erkin (Delft University of Technology). FC'20

  - Keyword: _`Scalability`_, _`Layer 2`_

- 🎓 [Boomerang: Redundancy Improves Latency and Throughput in Payment Channel Networks](http://fc20.ifca.ai/preproceedings/12.pdf). Joachim Neu (Stanford University), Vivek Bagaria (Stanford University), David Tse (Stanford University). FC'20

  - Keyword: _`Scalability`_, _`Layer 2`_

- 🎓 [DLSAG: Non-Interactive Refund Transactions For Interoperable Payment Channels in Monero](http://fc20.ifca.ai/preproceedings/124.pdf). Pedro Moreno-Sanchez (TU Wien), Arthur Blue, Duc Le (Purdue University), Sarang Noether (Monero Research Lab), Brandon Goodell (Monero Research Lab), Aniket Kate (Purdue University). FC'20

  - Keyword: _`Scalability`_, _`Layer 2`_

- 🎓 [Cerberus Channels: Incentivizing Watchtowers for Bitcoin](http://fc20.ifca.ai/preproceedings/132.pdf). Zeta Avarikioti (ETH Zurich), Orfeas Stefanos Thyfronitis Litos (University of Edinburgh), Roger Wattenhofer (ETH Zurich). FC'20

  - Keyword: _`Scalability`_, _`Layer 2`_

- 🎓 [RingCT 3.0 for Blockchain Confidential Transaction](http://fc20.ifca.ai/preproceedings/52.pdf): Shorter Size and Stronger Security. Tsz Hon Yuen (The University of Hong Kong), Shi-feng Sun (Monash University), Joseph K. Liu (Monash University), Man Ho Au (Hong Kong Polytechnic University), Muhammed F. Esgin (Monash University), Qingzhao Zhang (Shanghai Jiao Tong University), Dawu Gu (Shanghai Jiao Tong University). FC'20

  - Keyword: _`Privacy`_, _`RingCT`_

- 🎓 [BLAZE: Practical Lattice-Based Blind Signatures for Privacy-Preserving Applications](http://fc20.ifca.ai/preproceedings/141.pdf). Nabil Alkeilani Alkadri (Technische Universität Darmstadt), Rachid El Bansarkhani (QuantiCor Security GmbH), Johannes Buchmann (Technische Universität Darmstadt). FC'20

  - Keyword: _`Privacy`_, _`Blind Signatures`_

- 🎓 [Two-Party State Channels with Assertions](https://fc19.ifca.ai/wtsc/StateAssertions.pdf). Buckland C, McCorry P. FC '19.

  - Keyword: _`Payment Channel Networks`_

- 🎓 [Snow White: Provably Secure Proofs of Stake.](https://fc19.ifca.ai/preproceedings/141-preproceedings.pdf). Bentov I, Pass R, Shi E. FC '19.

  - Keyword: _`PoS`_

- 🎓 [Proof-of-Work Sidechains](https://eprint.iacr.org/2018/1048.pdf). Kiayias A, Zindros D. FC WTSC'19.

  - Keyword: _`Sidechains`_, _`Scalability`_

- 🎓 [Hostile blockchain takeovers](https://fc18.ifca.ai/bitcoin/papers/bitcoin18-final17.pdf). Bonneau J. FC '18.

  - Keyword: _`Attacks`_

- 🎓 [Teechan: Payment Channels Using Trusted Execution Environments](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final21.pdf). Lind J, Eyal I, Pietzuch P, Sirer EG. FC BITCOIN '17.

  - Keyword: _`Payment Channel Networks`_

- 🎓 [A Proof-of-Stake protocol for consensus on Bitcoin subchains](http://eprint.iacr.org/2017/417.pdf). Bartoletti M, Lande S, & Podda A S. FC'17.

  - Keyword: _`PoS`_

- 🎓 [A Smart Contract for Boardroom Voting with Maximum Voter Privacy](http://fc17.ifca.ai/preproceedings/paper_80.pdf). McCorry P, Shahandashti SF, Hao F. FC'17.

  - Keyword: _`Smart Contracts`_

- 🎓 [Constant-deposit multiparty lotteries on Bitcoin](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final39.pdf). Bartoletti M, Zunino R. FC'17.

  - Keyword: _`Smart Contracts`_

- 🎓 [PieceWork: Generalized Outsourcing Control for Proofs of Work](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final24.pdf). Daian P, Eyal I, Juels A, Sirer EG. FC'17.

  - Keyword: _`Economic`_, _`PoW`_

- 🎓 [OpenTimestamps: Securing Software Updates using the Bitcoin Blockchain Financial Cryptography and Data Security](https://github.com/opentimestamps/). Todd P, Halpin H. (FC Poster'17)
  - Keyword: _`Application`_

* 🎓 [A Proof-of-Stake protocol for consensus on Bitcoin subchains](http://eprint.iacr.org/2017/417.pdf). Bartoletti M, Lande S, & Podda A S. FC'17.
  - Keyword: _`Consensus`_, _`PoW`_

- 🎓 [Improving Authenticated Dynamic Dictionaries, with Applications to Cryptocurrencies](http://fc17.ifca.ai/preproceedings/paper_34.pdf). Reyzin L, Meshkov D, Chepurnoy A, Ivanov S. FC'17.

  - Keyword: _`Scalability`_, _`Sidechains`_

- 🎓 [Service-Oriented Sharding for Blockchains](http://fc17.ifca.ai/preproceedings/paper_73.pdf). Gencer AE, Van Renesse R, Sirer EG. FC'17.

  - Keyword: _`Scalability`_, _`Sharding`_

- 🎓 [Could Network Information Facilitate Address Clustering in Bitcoin?](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final11.pdf). Neudecker T, Hartenstein H. FC'17.

  - Keyword: _`Privacy`_

- 🎓 [Exchange Pattern Mining in the Bitcoin Transaction Directed Hypergraph](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final17.pdf). Ranshous S, Joslyn A, Kreyling S, Nowak K, Samatova N, West C, Winters C. FC'17.

  - Keyword: _`Privacy`_

- 🎓 [Confidential Assets](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final41.pdf). Poelstra A, Back A, Friedenbach M, Maxwell G, Wuille P. FC'17.

  - Keyword: _`Privacy`_

- 🎓 [Mixing Confidential Transactions: Comprehensive Transaction Privacy for Bitcoin](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final6.pdf). Ruffing T, Moreno-Sanchez P. FC'17.

  - Keyword: _`Privacy`_

- 🎓 [Switch Commitments: A Safety Switch for Confidential Transactions](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final23.pdf). Ruffing T, Malavolta G. FC'17.

  - Keyword: _`Privacy`_

- 🎓 [Escrow protocols for cryptocurrencies: How to buy physical goods using Bitcoin](http://www.jbonneau.com/doc/GBGN17-FC-physical_escrow.pdf). Goldfeder S, Bonneau J, Gennaro R, Narayanan A. FC '17.

  - Keyword: _`Marketplaces`_

- 🎓 [Trust Is Risk: A Decentralized Financial Trust Platform](http://fc17.ifca.ai/preproceedings/paper_37.pdf). Thyfronitis Litos OS, Zindros D. FC '17.

  - Keyword: _`Marketplaces`_

- 🎓 [Incentivizing Blockchain Forks via Whale Transactions](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final26.pdf). Liao K, Katz J. FC '17.

  - Keyword: _`Economics`_

- 🎓 [Smart Contracts Make Bitcoin Mining Pools Vulnerable](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final38.pdf). Velner Y, Teutsch J, Luu L. FC '17.

  - Keyword: _`Economics`_

- 🎓 [Mixing Coins of Different Quality: A Game-Theoretic Approach](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final40.pdf). Abramova S, Schöttle P, Böhme R. FC '17.

  - Keyword: _`Economics`_

- 🎓 [Decentralized Prediction Market without Arbiters](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final29.pdf). Bentov I, Mizrahi A, Rosenfeld M. FC '17.

  - Keyword: _`Economics`_

- 🎓 [An analysis of Bitcoin OP_RETURN metadata](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final32.pdf). Bartoletti M, Pompianu L. FC'17.

  - Keyword: _`Survey`_, _`Sociological`_, _`Anthropological`_

- 🎓 [Enhancing Bitcoin Transactions with Covenants](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final28.pdf). O’Connor R, Piekarska M. FC'17.

  - Keyword: _`Wallets`_

- 🎓 [Bitcoin Covenants](http://fc16.ifca.ai/bitcoin/papers/MES16.pdf). Möser M, Eyal I, Sirer EG. FC'16.

  - Keyword: _`Wallets`_

- 🎓 [The Other Side of the Coin: User Experiences with Bitcoin Security and Privacy](http://fc16.ifca.ai/preproceedings/33_Krombholz.pdf). Krombholz K, Judmayer A, Gusenbauer M, Weippl E. FC'16.

  - Keyword: _`Survey`_, _`Sociological`_, _`Anthropological`_

- 🎓 [Why buy when you can rent? Bribery attacks on Bitcoin-style consensus](http://fc16.ifca.ai/bitcoin/papers/Bon16b.pdf). Bonneau J. FC '16.

  - Keyword: _`Economics`_

- 🎓 [Incentive Compatibility of Bitcoin Mining Pool Reward Functions](http://fc16.ifca.ai/preproceedings/28_Schrijvers.pdf). Schrijvers O, Bonneau J, Boneh D, Roughgarden T. FC '16.

  - Keyword: _`Economics`_

- 🎓 [When cryptocurrencies mine their own business](http://fc16.ifca.ai/preproceedings/29_Teutsch.pdf). Teutsch J, Jain S, Saxena P. FC '16.

  - Keyword: _`Economics`_

- 🎓 [Optimal Selfish Mining Strategies in Bitcoin](http://fc16.ifca.ai/preproceedings/30_Sapirshtein.pdf). Sapirshtein A, Sompolinsky Y, Zohar A. FC'16.

  - Keyword: _`Attacks`_

- 🎓 [Refund attacks on Bitcoin’s Payment Protocol](http://fc16.ifca.ai/preproceedings/34_McCorry.pdf). McCorry P, Shahandashti S, Hao F. FC'16.

  - Keyword: _`Attacks`_

- 🎓 [Cryptocurrencies without Proof of Work](http://fc16.ifca.ai/bitcoin/papers/BGM16.pdf). Bentov I, Gabizon A, Mizrahi A. FC'16.

  - Keyword: _`PoS`_

- 🎓 [Blindly Signed Contracts: Anonymous On-Blockchain and Off-Blockchain Bitcoin Transactions](http://fc16.ifca.ai/bitcoin/papers/HBG16.pdf). Heilman E, Baldimtsi F, Goldberg S. FC'16.

  - Keyword: _`Privacy`_

- 🎓 [Proofs of Proofs of Work with Sublinear Complexity](http://fc16.ifca.ai/bitcoin/papers/KLS16.pdf). Kiayias A, Lamprou N, Stouka AP. FC'16.

  - Keyword: _`Scalability`_

- 🎓 [On Scaling Decentralized Blockchains](http://fc16.ifca.ai/bitcoin/papers/CDE+16.pdf). Croman K, Decker C, Eyal I, Gencer AE, Juels A, Kosba A, Miller A, Saxena P, Shi E, Sirer EG, Song D. FC'16.

  - Keyword: _`Scalability`_

- 🎓 [Stressing Out: Bitcoin “Stress Testing”](http://fc16.ifca.ai/bitcoin/papers/BHMW16.pdf). Baqer K, Yuxing Huang D, McCoy D, Weaver N. FC'16.

  - Keyword: _`Network`_

- 🎓 [Step by Step Towards Creating a Safe Smart Contract: Lessons and Insights from a Cryptocurrency Lab](http://fc16.ifca.ai/bitcoin/papers/DAKMS16.pdf). Delmolino K, Arnett M, Kosba A, Miller A, Shi E. FC'16.

  - Keyword: _`Smart Contracts`_

- 🎓 [EthIKS: Using Ethereum to audit a CONIKS key transparency log](http://fc16.ifca.ai/bitcoin/papers/Bon16a.pdf). Bonneau J. FC'16.

  - Keyword: _`Smart Contracts`_

- 🎓 [Automated Verification of Electrum Wallet](http://fc16.ifca.ai/bitcoin/papers/TVR16.pdf). Turuani M, Voegtlin T, Rusinowitch M. FC'16.
  - Keyword: _`Formal Methods`_

* 🎓 [Cryptocurrencies without Proof of Work](http://fc16.ifca.ai/bitcoin/papers/BGM16.pdf). Bentov I, Gabizon A, Mizrahi A. FC'16.

  - Keyword: _`Consensus`_

* 🎓 [Optimal Selfish Mining Strategies in Bitcoin](http://fc16.ifca.ai/preproceedings/30_Sapirshtein.pdf). Sapirshtein A, Sompolinsky Y, Zohar A. FC'16.
  - Keyword: _`Economic-PoW`_

- 🎓 [Hierarchical deterministic Bitcoin wallets that tolerate key leakage](http://fc15.ifca.ai/preproceedings/paper_15.pdf). Gutoski G, Stebila D. FC'15.

  - Keyword: _`Wallets`_

- 🎓 [ZombieCoin: Powering Next-Generation Botnets with Bitcoin](http://fc15.ifca.ai/preproceedings/bitcoin/paper_15.pdf). Ali ST, McCorry P, Lee PH, Hao F. FC'15.

  - Keyword: _`Crime`_

- 🎓 [The Bitcoin Market Potential Index](http://fc15.ifca.ai/preproceedings/bitcoin/paper_14.pdf). Hileman G. FC'15.

  - Keyword: _`Survey`_, _`Sociological`_, _`Anthropological`_

- 🎓 [Cryptographic Currencies from a Tech-Policy Perspective: Policy Issues and Technical Direction](http://fc15.ifca.ai/preproceedings/bitcoin/paper_16.pdf). McReynolds E, Lerner A, Scott W, Roesner F, Kohno T. FC'15.

  - Keyword: _`Survey`_, _`Sociological`_, _`Anthropological`_

- 🎓 [On the Malleability of Bitcoin Transactions](http://fc15.ifca.ai/preproceedings/bitcoin/paper_9.pdf). Andrychowicz M, Dziembowski S, Malinowski D, Mazurek Ł. FC'15.

- 🎓 [Cuckoo Cycle: a memory bound graph-theoretic proof-of-work](http://fc15.ifca.ai/preproceedings/bitcoin/paper_12.pdf). Tromp J. FC'15.

  - Keyword: _`Economic`_, _`PoW`_

- 🎓 [Secure High-Rate Transaction Processing in Bitcoin](https://fc15.ifca.ai/preproceedings/paper_30.pdf). Sompolinsky Y, Zohar A. FC'15.

  - Keyword: _`Mining`_, **GHOST**

- 🎓 [Inclusive Block Chain Protocols](http://fc15.ifca.ai/preproceedings/paper_101.pdf). Lewenberg Y, Sompolinsky Y, Zohar A. FC '15.
  - Keyword: _`Mining`_, _`ChainStructure`_

* 🎓 [Secure High-Rate Transaction Processing in Bitcoin](http://www.cs.huji.ac.il/~avivz/pubs/15/btc_ghost_full.pdf). Sompolinsky Y, Zohar A. FC'15.
  - Keyword: _`Consensus`_, _`PoW`_

- 🎓 [Blindcoin Blinded, Accountable Mixes for Bitcoin](http://fc15.ifca.ai/preproceedings/bitcoin/paper_3.pdf). Valenta L, Rowan B. FC'15.

  - Keyword: _`Privacy`_

- 🎓 [Issues in Designing a Bitcoin-Like Community Currency](http://fc15.ifca.ai/preproceedings/bitcoin/paper_2.pdf). Vandervort D, Gaucas D, St Jacques R. FC'15.

  - Keyword: _`Survey`_, _`Sociological`_, _`Anthropological`_

- 🎓 [There’s No Free Lunch, Even Using Bitcoin: Tracking the Popularity and Profits of Virtual Currency Scams](http://fc15.ifca.ai/preproceedings/paper_75.pdf). Vasek M, Moore T. FC'15.

  - Keyword: _`Marketplaces`_

- 🎓 [When Bitcoin Mining Pools Run Dry A Game-Theoretic Analysis of the Long-Term Impact of Attacks Between Mining Pools](http://fc15.ifca.ai/preproceedings/bitcoin/paper_13.pdf). Laszka A, Johnson B, Grossklags J. FC '15.

  - Keyword: _`Economics`_

- 🎓 [Trends, Tips, Tolls: A Longitudinal Study of Bitcoin Transaction Fees](http://fc15.ifca.ai/preproceedings/bitcoin/paper_8.pdf). Möser M, Böhme R. FC '15.

  - Keyword: _`Economics`_

- 🎓 [Game-Theoretic Analysis of DDoS Attacks Against Bitcoin Mining Pools](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_16.pdf). Johnson B, Laszka A, Grossklags J, Vasek M, Moore T. FC '14.

  - Keyword: _`Economics`_

- 🎓 [Challenges and Opportunities Associated with a Bitcoin-based Transaction Rating System](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_5.pdf). Vandervort D. FC'14.

  - Keyword: _`Marketplaces`_

- 🎓 [Majority Is Not Enough: Bitcoin Mining Is Vulnerable](https://arxiv.org/pdf/1311.0243). Eyal I, Sirer EG. FC '14.

  - Keyword: _`Attacks`_, **"Selfish Mining"**

- 🎓 [Increasing Anonymity in Bitcoin](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_19.pdf). Saxena A, Misra J, Dhar A. FC '14.

  - Keyword: _`Privacy`_

- 🎓 [How Did Dread Pirate Roberts Acquire and Protect His Bitcoin Wealth?](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_2.pdf). Ron D, Shamir A. FC '14.

  - Keyword: _`Privacy`_

- 🎓 [The Bitcoin P2P network](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_3.pdf). Donet Donet JA, Perez-Sola C, Herrera-Joancomart J. FC '14.

  - Keyword: _`Network`_

- 🎓 [Empirical Analysis of Denial-of-Service Attacks in the Bitcoin Ecosystem](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_17.pdf). Vasek M, Thornton M, Moore T. FC '14.

  - Keyword: _`Network`_

- 🎓 [Mixcoin: Anonymity for bitcoin with accountable mixes](https://eprint.iacr.org/2014/077.pdf). Bonneau J, Narayanan A, Miller A, Clark J, Kroll JA, Felten EW. FC'14.

  - Keyword: _`Privacy`_

- 🎓 [Rational Zero: Economic Security for Zerocoin with Everlasting Anonymity](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_12.pdf). Garman C, Green M, Miers I, Rubin A. FC'14.

  - Keyword: _`Privacy`_

- 🎓 [Fair Two-Party Computations via Bitcoin Deposits](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_10.pdf). Andrychowicz M, Dziembowski S, Malinowski D, Mazurek Ł. FC'14.
  - Keyword: _`Smart Contracts`_

* 🎓 [Majority Is Not Enough: Bitcoin Mining Is Vulnerable](https://arxiv.org/pdf/1311.0243). Eyal I, Sirer EG. FC'14.
  - Keyword: _`Economic`_, _`PoW`_

- 🎓 [Quantitative analysis of the full bitcoin transaction graph](https://eprint.iacr.org/2012/584.pdf). Ron D, Shamir A. FC '13.
  - Keyword: _`Privacy`_

* 🎓 [Commitcoin: Carbon dating commitments with bitcoin](https://eprint.iacr.org/2011/677.pdf). Clark J, Essex A. FC'12.
  - Keyword: _`Application`_

## Others

- [ShareLock: Mixing for Cryptocurrencies from Multiparty ECDSA](https://eprint.iacr.org/2019/563.pdf). Omer Shlomovits and István András Seres. IACR'19.

  - Keyword: _`Privacy`_, _`Threshold Signature`_, _`Mixing`_

- [SoK: A Taxonomy for Layer-2 Scalability Related Protocols for Cryptocurrencies](https://eprint.iacr.org/2019/352.pdf). Jourenko M, Kurazumi K, Larangeira M, Tanaka K. '19.

  - Keyword: _`Payment Channel Networks`_, **SoK**

- [SoK: Off The Chain Transactions](https://eprint.iacr.org/2019/360.pdf). Gudgeon L, Moreno-Sanchez P, Roos S, McCorry P, Gervais A. '19.

  - Keyword: _`Payment Channel Networks`_

- [Sprites and State Channels: Payment Channel Networks that Go Faster than Lightning](https://arxiv.org/pdf/1702.05812.pdf) Miller A, Bentov I, Kumaresan R, Cordi C, McCorry P. FC'19.

  - Keyword: _`Payment Channel Networks`_

- [Nitro Protocol](https://eprint.iacr.org/2019/219.pdf). Close T. '19.

  - Keyword: _`Payment Channel Networks`_

- [NOCUST – A Non-Custodial 2nd-Layer Financial Intermediary](https://liquidity.network/NOCUST_Liquidity_Network_Paper.pdf). Khalil R, Gervais, A. ICAR'18.

  - Keyword: _`Payment Channel Networks`_

- [Counterfactual: Generalized state channels](https://l4.ventures/papers/statechannels.pdf). Coleman J, Horne L, Xuanji L. '18.

  - Keyword: _`Payment Channel Networks`_

- [Flare: An Approach to Routing in Lightning Network](https://bitfury.com/content/downloads/whitepaper_flare_an_approach_to_routing_in_lightning_network_7_7_2016.pdf). Prihodko P, Zhigulin S, Sahno M, Ostrovskiy A, Osuntokyn O. '16.

  - Keyword: _`Payment Channel Networks`_

- [The bitcoin lightning network: Scalable off-chain instant payments](https://www.weusecoins.com/assets/pdf/library/Lightning%20Network%20Whitepaper.pdf). Poon J, Dryja T. '15.

  - Keyword: _`Payment Channel Networks`_

- [Reaching The Ground With Lightning](https://github.com/ElementsProject/lightning/raw/master/doc/deployable-lightning.pdf). Russell R. '15.

  - Keyword: _`Payment Channel Networks`_, **Deployable Lightning**

- [FlyClient: Super-Light Clients for Cryptocurrencies](https://eprint.iacr.org/2019/226.pdf). B Bünz, L Kiffer, L Luu, M Zamani. IACR'19.

  - Keyword: _`Scalability`_

- [A Scalable BlockDAG protocol](https://eprint.iacr.org/2018/104.pdf). Sompolinsky Y, Zohar A. '18.

  - Keyword: _`Consensus`_, _`DAG`_, **PHANTOM**

- [Snowflake to Avalanche: A Novel Metastable Consensus Protocol Family for Cryptocurrencies](https://ipfs.io/ipfs/QmUy4jh5mGNZvLkjies1RWM4YuvJh5o2FYopNPVYwrRVGV). Team Rocket. '18.

  - Keyword: _`Consensus`_, _`DAG`_

- [Scaling Nakamoto Consensus to Thousands of Transactions per Second](https://arxiv.org/pdf/1805.03870.pdf). Li C, Li P, Zhou D, Xu W, Long F, Chi-Chih Yao A. '18.

  - Keyword: _`Consensus`_, _`DAG`_

- [PolyShard: Coded Sharding Achieves Linearly Scaling Efficiency and Security Simultaneously](https://arxiv.org/pdf/1809.10361.pdf). Li S, Yu M, Avestimehr S, Kannan S, Viswanath P. CoRR'18.

  - Keyword: _`Scalability`_, _`Sharding`_

- [Low-Resource Eclipse Attacks on Ethereum’s Peer-to-Peer Network](https://eprint.iacr.org/2018/236.pdf). Marcus Y, Heilman E, Goldberg S. IACR'18.
  - Keyword: _`Attacks`_

<!-- - [Scalable, transparent, and post-quantum secure computational integrity](https://eprint.iacr.org/2018/046.pdf). Ben-Sasson E, Bentov I, Horesh Y, Riabzev M. IACR'18.
    + Keyword: *`Cryptography`* -->

- 🎓[A systematic literature review of blockchain-based applications: Current status, classification and open issues](https://www.researchgate.net/profile/Thomas_Dasaklis/publication/329136952_A_systematic_literature_review_of_blockchain-based_applications_Current_status_classification_and_open_issues/links/5c4cab1ba6fdccd6b5cb7ea1/A-systematic-literature-review-of-blockchain-based-applications-Current-status-classification-and-open-issues.pdf). Casino F, Dasaklis T, Patsakis C. T&I'18.

  - Keyword: _`Applications`_
  - Type: _`Review`_

- [Storj A Peer-to-Peer Cloud Storage Network](https://storj.io/storjv3.pdf). Shawn W., Tome B., Josh B., James P., Gordon H., Patrick G., Philip H., Chris P. '18

  - Keyword: _`Applications`_, _`Storage`_

- [Blockstack Technical Whitepaper](https://blockstack.org/whitepaper.pdf). Muneeb A., Ryan S., Jude N, Michael F. '17

  - Keyword: _`Applications`_

- [BigchainDB: A Scalable Blockchain Database](https://www.bigchaindb.com/whitepaper/bigchaindb-whitepaper.pdf). McConaghy T, Marques R, Müller A, De Jonghe D, McConaghy T, McMullen G, Henderson R, Bellemare S, Granzotto A. '17

  - Keyword: _`Applications`_

- [Non-Interactive Proofs of Proof-of-Work](https://eprint.iacr.org/2017/963.pdf). Kiayias A, Miller A, Zindros D. IACR'17.

  - Keyword: _`Scalability`_

- [Bitcoin's Academic Pedigree](http://delivery.acm.org/10.1145/3140000/3132259/p36-narayanan.pdf?ip=88.197.32.177&id=3132259&acc=OPEN&key=5641A0C343C36AC1%2E4ABAF8470B13FB25%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1541082825_ead879dbf5b3644bfed2a09e11b47834). Narayanan A, Clark J. ACM Queue '17.

  - Keyword: _`SoK`_

- 🎓 [On Trees, Chains and Fast Transactions in the Blockchain](https://eprint.iacr.org/2016/545.pdf). Kiayias A, Panagiotakos G. LATINCRYPT '17.

  - Keyword: _`Consensus`_

- 🎓 [Transferable Anonymous Payments via TumbleBit in Permissioned Blockchains](http://ceur-ws.org/Vol-2334/DLTpaper5.pdf). Ferretti C, Leporati A, Mariot L, Nizzardo L. DLT '19.

  - Keyword: _`Privacy`_

- "MoneroLink": [An Empirical Analysis of Linkability in the Monero Blockchain](http://monerolink.com/monerolink.pdf). Miller A, Möser M, Lee K, Narayanan A. '17.

  - Keyword: _`Privacy`_

- 🎓 [ALGORAND: The Efficient and Democratic Ledger](https://arxiv.org/pdf/1607.01341.pdf). Micali S. CoRR'16.

  - Keyword: _`PoS`_

- [Bootstrapping the Blockchain - Directly](https://eprint.iacr.org/2016/991.pdf). Garay JA, Kiayias A, Leonardos N, Panagiotakos G. IACR'16.

  - Keyword: _`Mining`_

- [Blockchain-Free Cryptocurrencies: A Framework for Truly Decentralised Fast Transactions](https://eprint.iacr.org/2016/871.pdf) Boyen X, Carr C, Haines T. '16.

  - Keyword: _`Consensus`_, _`DAG`_

- [SPECTRE: A Fast and Scalable Cryptocurrency Protocol](https://eprint.iacr.org/2016/1159.pdf). Sompolinsky Y, Lewenberg Y, Zohar A. '16.

  - Keyword: _`Consensus`_, _`DAG`_

- [Byteball: A Decentralized System for Storage and Transfer of Value](https://byteball.org/Byteball.pdf) Churyumov A. '16.

  - Keyword: _`Consensus`_, _`DAG`_

- [DAGcoin Whitepaper](https://dagcoin.org/whitepaper.pdf) Ribero Y, Raissar D. '15.

  - Keyword: _`Consensus`_, _`DAG`_

- [Speed-Security Tradeoffs in Blockchain Protocols](https://pdfs.semanticscholar.org/7de8/ff6bb85a020aa96f62dd86233fe9416550f3.pdf). Kiayias A, Panagiotakos G. IACR'15.

  - Keyword: _`Mining`_

- 🎓 [CoinParty: Secure Multi-Party Mixing of Bitcoins](https://www.martinhenze.de/wp-content/papercite-data/pdf/zgh+15.pdf). Ziegeldorf, J.H., Grossmann, F., Henze, M., Inden, N. and Wehrle, K. CODASPY '15.

  - Keyword: _`Privacy`_

- [Data-Driven De-Anonymization in Bitcoin](http://e-collection.library.ethz.ch/eserv/eth:48205/eth-48205-01.pdf). Nick J. Diss. ETH-Zürich, '15.
  - Keyword: _`Privacy`_, _`Attacks`_
- [Trust in decentralized anonymous marketplaces](http://dspace.lib.ntua.gr/bitstream/handle/123456789/43147/pseudonymous-trust-2.pdf?sequence=1). Zindros D. '15.

  - Keyword: _`Marketplaces`_

- [The stellar consensus protocol: A federated model for internet-level consensus](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.696.93&amp=&rep=rep1&amp=&type=pdf). Mazières D. '15.

  - Keyword: _`Marketplaces`_

- 🎓 [A Fast and Scalable Payment Network with Bitcoin Duplex Micropayment Channels](https://pdfs.semanticscholar.org/c8d2/b0c1f9b1ca739c340e9dc4a2ff71b5bfbb2e.pdf). Decker C, Wattenhofer R. SSS'15.
  - Keyword: _`Payment Channel Networks`_

<!-- - [On Bitcoin as a public randomness source](https://pdfs.semanticscholar.org/ebae/9c7d91ea8b6a987642040a2142cc5ea67f7d.pdf). Bonneau J, Clark J, Goldfeder S. IACR'15.
    + Keyword: *`Cryptography`* -->

- [Decentralized trusted timestamping using the crypto currency bitcoin](https://arxiv.org/pdf/1502.04015.pdf). Gipp B., Meuschke N., Gernandt A. CoRR'15

  - Keyword: _`Applications`_

- [IPFS - Content Addressed, Versioned, P2P File System](https://github.com/ipfs/papers/raw/master/ipfs-cap2pfs/ipfs-p2p-file-system.pdf). Benet J. CoRR'14

  - Keyword: _`Applications`_, **IPFS**

- [A next-generation smart contract and decentralized application platform](https://www.weusecoins.com/assets/pdf/library/Ethereum_white_paper-a_next_generation_smart_contract_and_decentralized_application_platform-vitalik-buterin.pdf). Vitalik Buterin. '14.

  - Keyword: _`Smart Contracts`_, **Ethereum**

- [Ethereum: A secure decentralised generalised transaction ledger](http://gavwood.com/paper.pdf). Wood G. '14.

  - Keyword: _`Smart Contracts`_, **Ethereum**

- [Distributed Cryptography Based on the Proofs of Work](https://eprint.iacr.org/2014/796.pdf). Andrychowicz M, and Dziembowski S. IACR'14.

  - Keyword: _`Consensus`_, _`PoW`_

- [Anonymous Byzantine Consensus from Moderately-Hard Puzzles: A Model for Bitcoin](https://socrates1024.s3.amazonaws.com/consensus.pdf). Miller A, LaViola JJ Jr. '14.

  - Keyword: _`Consensus`_

- [Enabling Blockchain Innovations with Pegged Sidechains](https://blockstream.com/sidechains.pdf). Back A, Corallo M, Dashjr L, Friedenbach M, Maxwell G, Miller A, Poelstra A, Timón J, Wuille P. '14.

  - Keyword: _`Scalability`_, _`Sidechains`_

- [The Ripple protocol consensus algorithm](https://ripple.com/files/ripple_consensus_whitepaper.pdf). Schwartz D, Youngs N, Britto A. '14.

  - Keyword: _`Marketplaces`_

- [Information Propagation in the Bitcoin Network](http://www.tik.ee.ethz.ch/file/49318d3f56c1d525aabf7fda78b23fc0/P2P2013_041.pdf). Decker C., Wattenhofer R. P2P'13.

  - Keyword: _`Network`_

- [CryptoNote v2.0](https://cryptonote.org/whitepaper.pdf). Saberhagen N. '13

  - Keyword: _`Privacy`_, **Monero**

- **[Theoretical Bitcoin Attacks with less than Half of the Computational Power](https://arxiv.org/pdf/1312.7013.pdf)**. Bahack L. CoRR'13.

  - Keyword: _`Attacks`_

- 🎓 [The Economics of Bitcoin Mining or Bitcoin in the Presence of Adversaries](https://www.econinfosec.org/archive/weis2013/papers/KrollDaveyFeltenWEIS2013.pdf). Kroll J, Davey I, Felten E. WEIS '13.

  - Keyword: _`Economics`_

- 🎓 **[On Bitcoin and Red Balloons](https://arxiv.org/pdf/1111.2626.pdf)**. Babaioff M, Dobzinski S, Oren S, Zohar A. EC'12.

  - Keyword: _`Economics`_

- **[Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.com/bitcoin.pdf)**. Nakamoto S. '08.

  - Keyword: _`SoK`_, **Bitcoin**

- [Money as IOUs in social trust networks & a proposal for a decentralized currency network protocol](http://library.uniteddiversity.coop/Money_and_Economics/decentralizedcurrency.pdf). Fugger R. '04.

  - Keyword: _`Marketplaces`_

- [Hashcash - A Denial of Service Counter-Measure](http://www.hashcash.org/papers/hashcash.pdf). Back A. '02.

  - Keyword: _`PoW`_

- 🎓 [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf) Lamport L. '00, ACM SIGACT News '01.

  - Keyword: _`Consensus`_

- 🎓 [Accountability in a Permissioned Blockchain:Formal Analysis of Hyperledger Fabric](https://eprint.iacr.org/2020/386.pdf). Ralf Küsters, Daniel Rausch, and Mike Simon (University of Stuttgart). EuroS&P'20

  - Keyword: _`Formal Methods`_

- 🎓 [Revisiting Transactional Statistics of High-scalability Blockchain](https://arxiv.org/pdf/2003.02693.pdf). Daniel Perez (Imperial College London); Jiahua Xu (UCL); Benjamin Livshits (Imperial College London). IMC'20
  - Keyword: _`Scalability`_
  - Type: _`Empirical`_

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain.
