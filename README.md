# Blockchain Papers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of blockchain-related academic papers. Papers with 🎓 have been
peer-reviewed and presented in academic conferences.

Thanks to the excellent work of [decrypto-org/blockchain-papers](https://github.com/decrypto-org/blockchain-papers). This repository is forked from their repository, but continuously add great papers and makes a more reasonable organization based on the content and source of papers.

If you want to join with us, please feel free to contact me. Then, remember to read `CONTRIBUTING.md` before adding papers.

## Conference Information

### CCF A
> Conference
- [USENIX Security(Usenix Security Symposium)](#usenix-security-a) <= 2020 Summer
- [S&P(IEEE Security and Privacy)](#sp-a) <= 2020
- [CCS(ACM Conference on Computer and Communications Security)](#ccs-a) <= 2019
- [NDSS(Network and Distributed System Security)](#ndss-a) <= 2020
- [CRYPTO(International Cryptology Conference)](#crypto-a) <= 2019 (Calling for paper in 2020)
- [EUROCRYPT(European Cryptology Conference)](#eurocrypt-a) <= 2020
- [INFOCOM(IEEE International Conference on Computer Communications)](#infocom-a) <= 2020
- [SOSP(ACM Symposium on Operating Systems Principles)](#sosp-a) <= 2019 (No schedule in 2020)
- [NSDI(USENIX Symposium on Networked Systems Design and Implementation)](#nsdi-a) <= 2020
- [VLDB(International Conference on Very Large Data Bases)](#vldb-a) <= 2019 (Calling for paper in 2020)
- [OSDI(USENIX Symposium on Operating Systems Design and Implementations)](#osdi-a) <= 2019 (Calling for paper in 2020)
- [SIGMOD(ACM Conference on Management of Data)](#sigmod-a) <= 2020

> Journal
+ [TOCS(ACM Transactions on Computer Systems)](#tocs-a) <= 2019
+ [TOPLAS(ACM Transactions on Programming Languages & Systems)](#toplas-a) <= 2019
+ [JACM(Journal of the ACM)](#jacm-a) <= 2019
+ [Journal of Cryptology](#journal-of-cryptology-a) <= 2019
+ [TDSC(IEEE Transactions on Dependable and Secure Computing)](#tdsc-a) <= 2019

### CCF B
> Conference
- [ASIACRYPT(International Conference on the Theory and Application of Cryptology and Information Security)](#asiacrypt-b) <= 2019 (Calling for paper in 2020)
- [ESORICS(European Symposium on Research in Computer Security)](#esorics-b) <= 2019 (Calling for paper in 2020)
- [EuroSys(European Conference on Computer Systems)](#eurosys-b) <= 2020
- [ICDCS(IEEE International Conference on Distributed Computing Systems)](#icdcs-b) <= 2019
- [PODC(ACM Symposium on Principles of Distributed Computing)](#podc-b) <= 2019
- [CoNEXT(ACM Conference on Emerging Networking EXperiments and Technologies)](#conext-b) <= 2019

### CCF C
> Conference
- [ACNS(Applied Cryptography and Network Security)](#acns-c) <= 2019
- [FC(Financial Cryptography and Data Security)](#fc-c) <= 2020

### [Other](#others)
+ CoRR
+ T&I(Telematics and Informatics)
+ EC
+ IACR
+ EuroS&P <= 2020

## Content Labels
+ *`Composition`*
    + *`System`*
    + *`Network`*, *`Wallets`*, *`Mining`*, *`Smart Contracts`*
    + *`Consensus`*: 
        + BFT, *`PoW`*(Proof of Work), *`PoS`*(Proof of Stake), Proof-of-X, *`DAG`*
+ *`Privacy`*
    + *`Mixing`*,  *`Ring Signature`*, *`RingCT`*
    + *`ZKP`*(Zero-Knowledge Proof)
    + *`Blind Signature`*
    + *`sMPC`*, *`Threshold Signature`*
    + *`TEE`*
+ *`Scalability`*: 
    + *`Layer 2`*
        + *`Payment Channel`*, *`Payment Channel Networks`*
    + *`Sidechains`*, *`Programmability`*
+ *`Interoperability`*
+ *`Security`*
    + *`Multi-signature`*, *`Threshold Signature`*
    + *`Formal Methods`*
    + *`Post-quantum`*
+ *`Applications`*
    + *`Crime`*, *`Economics`*, *`Marketplaces`*, *`Sociological`*, *`Anthropological`*
+ *`Attacks`*

> + **Article Types**: 
>   + *`SoK`*(Systematization of Knowledge), *`Survey`*, *`Review`*
>   + *`Empirical Study`*
>   + *`Research Paper`*, *`Industrial Paper`*
>   + *`Short Paper`*, *`Workshop`*

---

## USENIX Security (A)

+ 🎓 [Pixel: Multi-signatures for Consensus](https://smeiklej.com/files/usenix19.pdf). Manu Drijvers, DFINITY; Sergey Gorbunov, Algorand and University of Waterloo; Gregory Neven, DFINITY; Hoeteck Wee, Algorand and CNRS, ENS, PSL. USENIX Security'20.
    + Keyword: **Pixel**, *`Multi-signature`*, *`PoS`*

+ 🎓 [Tracing Transactions Across Cryptocurrency Ledgers](https://smeiklej.com/files/usenix19.pdf). Haaroon Yousaf, George Kappos, and Sarah Meiklejohn. USENIX Security'19.
    + Keyword: *`Transaction Analysis`*

+ 🎓 [StrongChain: Transparent and Collaborative Proof-of-Work Consensus](https://arxiv.org/pdf/1905.09655.pdf). Pawel Szalachowski, Daniël Reijsbergen, and Ivan Homoliak, Siwei Sun. USENIX Security'19.
    + Keyword: *`Consensus`*

+ 🎓 [BITE: Bitcoin Lightweight Client Privacy using Trusted Execution](https://www.usenix.org/system/files/sec19fall_matetic_prepub.pdf). Sinisa Matetic, Karl Wüst, Moritz Schneider, and Kari Kostiainen, Ghassan Karame, Srdjan Capkun. USENIX Security'19.
    + Keyword: *`Privacy`*

+ 🎓 [FastKitten: Practical Smart Contracts on Bitcoin](https://www.usenix.org/system/files/sec19fall_das_prepub.pdf). Poulami Das, Lisa Eckey, Tommaso Frassetto, David Gens, Kristina Hostáková, Patrick Jauernig, Sebastian Faust, and Ahmad-Reza Sadeghi. USENIX Security'19.
    + Keyword: *`Smart Contracts`*

- 🎓 [teEther: Gnawing at Ethereum to Automatically Exploit Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-krupp.pdf). Johannes K, Christian R. USENIX Security'18.
    + Keyword: *`Smart Contracts`*

- 🎓 [Enter the Hydra: Towards Principled Bug Bounties and Exploit-Resistant Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-breidenbach.pdf). Lorenz B, Philip D, Florian T, Ari J. USENIX Security'18.
    + Keyword: *`Smart Contracts`*

- 🎓 [Arbitrum: Scalable, private smart contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kalodner.pdf). Harry K, Steven G, Xiaoqi C, S. Matthew W, Edward W. F. USENIX Security'18.
    + Keyword: *`Smart Contracts`*

- 🎓 [Erays: Reverse Engineering Ethereum's Opaque Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-zhou.pdf). Yi Z, Deepak K, Surya B, Joshua M, Andrew M, Michael B.  USENIX Security'18.
    + Keyword: *`Smart Contracts`*

+ 🎓 [An Empirical Analysis of Anonymity in Zcash](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kappos.pdf). George Kappos, Haaroon Yousaf, Mary Maller, and Sarah Meiklejohn. USENIX Security'18 Security Symposium.
    + Keyword: *`Anonymity Privacy`*

- 🎓 [Smartpool: Practical decentralized pooled mining](https://eprint.iacr.org/2017/019.pdf). Luu L, Velner Y, Teutsch J, Saxena P. USENIX Security'17.
    + Keyword: *`Mining`*

- 🎓 [REM: Resource-Efficient Mining for Blockchains](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-zhang.pdf). Fan Z, Ittay E, Robert E, Ari J, Robbert van R. USENIX Security'17.
    + Keyword: *`Mining`*

- 🎓 **[Enhancing Bitcoin Security and Performance with Strong Consistency via Collective Signing](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kokoris-kogias.pdf)**. Kogias EK, Jovanovic P, Gailly N, Khoffi I, Gasser L, Ford B. USENIX Security'16.
    + Keyword: **ByzCoin**, *`Consensus`*, *`PoS`*

- 🎓 [Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf). Eyal I, Gencer AE, Sirer EG, Van Renesse R. USENIX'16.
    + Keyword: *`Scalability`*

+ 🎓 [Eclipse Attacks on Bitcoin's Peer-to-Peer Network](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-heilman.pdf). Heilman E, Kendler A, Zohar A, Goldberg S. USENIX Security'15.
    + Keyword: *`Network`*

- 🎓 [Measuring the Longitudinal Evolution of the Online Anonymous Marketplace Ecosystem](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-soska-updated.pdf). Soska K, Christin N. USENIX Security'15.
    + Keyword: *`Marketplaces`*

## S&P (A)

+ 🎓 [OHIE: Blockchain Scaling Made Simple](https://www.comp.nus.edu.sg/~prateeks/papers/Ohie.pdf). Haifeng Yu (National University of Singapore);  Ivica Nikolic (National University of Singapore);  Ruomu Hou(National University of Singapore);  Prateek Saxena (National University of Singapore). S&P'20.
    + Keyword: **OHIE**, *`Scalaility`*, *`Consensus`*

+ 🎓 [A Stealthier Partitioning Attack against Bitcoin Peer-to-Peer Network](https://www.comp.nus.edu.sg/~kangms/papers/erebus-attack.pdf). Muoi Tran (National University of Singapore);  Inho Choi (National University of Singapore);  Gi Jun Moon (Korea University);  Anh V. Vu (Japan Advanced Institute of Science and Technology);  Min Suk Kang (National University of Singapore). S&P'20.
    + Keyword: **EREBUS**, *`Attacks`*

+ 🎓 [VERISMART: A Highly Precise Safety Verifier for Ethereum Smart Contracts](https://arxiv.org/pdf/1908.11227.pdf). Sunbeom So (Korea University);  Myungho Lee (Korea University);  Jisu Park (Korea University);  Heejo Lee (Korea University);  Hakjoo Oh (Korea University). S&P'20.
    + Keyword: **VERISMART**, *`Smart Contracts`*, *`Formal Methods`*

+ 🎓 [FlyClient: Super-Light Clients for Cryptocurrencies](https://eprint.iacr.org/2019/226.pdf). Benedikt Bünz (Stanford University);  Lucianna Kiffer (Northeastern University);  Loi Lu (Kyber Network);  Mahdi Zamani (Visa Research). S&P'20.
    + Keyword: **FlyClient**, *`Scalaility`*, *`Wallets`*

+ 🎓 [VerX: Safety Verification of Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/sp20-verx.pdf). Anton Permenev (ChainSecurity);  Dimitar Dimitrov (ETH Zurich);  Petar Tsankov (ChainSecurity);  Dana Drachsler-Cohen (ETH Zurich);  Martin Vechev (ETH Zurich). S&P'20.
    + Keyword: **VerX**, *`Smart Contracts`*, *`Formal Methods`*

+ 🎓 [Threshold ecdsa from ecdsa assumptions: The multiparty case](http://www.firstlight.cn/upload/plusfile/20195/21/201952184227868.pdf). Doerner J, Kondi Y, Lee E, et al. S&P'19.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

+ 🎓 [Flash Boys 2.0: Frontrunning in Decentralized Exchanges, Miner Extractable Value, and Consensus Instability](https://arxiv.org/pdf/1904.05234.pdf). Philip Daian (Cornell Tech, USA);  Steven Goldfeder (Cornell Tech, USA);  Tyler Kell (Cornell Tech, USA);  Yunqi Li (UIUC,  USA);  Xueyuan Zhao (Carnegie Mellon University, USA);  Iddo Bentov (Cornell Tech, USA);   Lorenz Breidenbach (ETH Zurich, Switzerland);  Ari Juels (Cornell Tech, USA)
    + Keyword: *`Attacks`*

+ 🎓 [Proof-of-Stake Sidechains](https://eprint.iacr.org/2018/1239.pdf). Peter Gaži, Aggelos Kiayias, Dionysis Zindros. IEEE S&P'19.  
    + Keyword: *`Sidechain`*

- 🎓 [Blind Certificate Authorities](https://shelat.ccis.neu.edu/dl/WAPRS-blindca.pdf). Liang W, Gilad A, Rafael P, Thomas R, Abhi S.  S&P '19.
    + Keyword: *`Privacy`*

- 🎓 [Bitcoin vs. Bitcoin Cash: Coexistence or Downfall of Bitcoin Cash?](https://arxiv.org/pdf/1902.11064.pdf). Yujin K, Hyoungshick K, Jinwoo S, Yongdae K. S&P '19.
    + Keyword: *`Mining`*

+ 🎓 [Perun: Virtual payment hubs over cryptocurrencies](https://eprint.iacr.org/2017/635.pdf) Dziembowski S, Eckey L, Faust S, Malinowski D. IEEE S&P'19.
    + Keyword: *`Payment Channel Networks`*

+ 🎓 [Lay Down the Common Metrics: Evaluating Proof-of-Work Consensus Protocols’ Security](https://www.esat.kuleuven.be/cosic/publications/article-3005.pdf) Ren Zhang, Bart Preneel. IEEE S&P'19.
    + Keyword: *`Consensus`*, *`PoW`*

+ 🎓 [Redactable Blockchain in the Permissionless Setting](https://arxiv.org/abs/1901.03206). Dominic Deuber, Bernardo Magri, Sri Aravinda Krishnan Thyagarajan. IEEE S&P'19.
    + Keyword: *`Consensus`*

+ 🎓 [Ouroboros Crypsinous: Privacy-Preserving Proof-of-Stake](https://eprint.iacr.org/2018/1132). Thomas Kerber and Markulf Kohlweiss and Aggelos Kiayias and Vassilis Zikas. IEEE S&P'19.
    + Keyword: *`Consensus`*, *`Privacy`*

+ 🎓 [XCLAIM: Decentralized, Interoperable, Cryptocurrency-Backed Assets](https://eprint.iacr.org/2018/643.pdf). 
Alexei Zamyatin, Dominik Harz, Joshua Lind, Panayiotis Panayiotou, Arthur Gervais, William J. Knottenbelt. IEEE S&P'19. 
    + Keyword: *`Scalaility`*

+ 🎓 OmniLedger: A Secure, Scale-Out, Decentralized Ledger via Sharding. E. Kokoris-Kogias and P. Jovanovic and L. Gasser and N. Gailly and E. Syta and B. Ford. S&P'18.
    + Keyword: *`System`*

+ 🎓 [Secure two-party threshold ECDSA from ECDSA assumptions](https://eprint.iacr.org/2018/499.pdf). Doerner J, Kondi Y, Lee E, et al. S&P'18.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

- 🎓 [Hijacking Bitcoin: Routing Attacks on Cryptocurrencies](https://arxiv.org/pdf/1605.07524v2). Apostolaki M, Zohar A, Vanbever L. S&P'17.
    + Keyword: *`Network`*

+ 🎓 [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](https://eprint.iacr.org/2015/675.pdf). Kosba A, Miller A, Shi E, Wen Z, Papamanthou C. S&P'16
    + Keyword: *`Privacy`*

+ 🎓 [The Miner's Dilemma](https://arxiv.org/abs/1411.7099). Ittay Eyal. S&P'15
    + Keyword: *`Consensus`*, *`PoW`*, *`Mining`*

+ 🎓 **[SoK: Research Perspectives and Challenges for Bitcoin and Cryptocurrencies](http://www.jbonneau.com/doc/BMCNKF15-IEEESP-bitcoin.pdf)**. Bonneau J, Miller A, Clark J, Narayanan A, Kroll JA, Felten EW. S&P'15
    + Keyword: *`SoK`*

+ 🎓 [Permacoin: Repurposing bitcoin work for data preservation](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956582.pdf). Miller A, Juels A, Shi E, Parno B, Katz J. Permacoin. S&P'14.
    + Keyword: *`Consensus`*, *`PoW`*

+ 🎓 [Zerocash: Decentralized anonymous payments from bitcoin](http://ieeexplore.ieee.org/iel7/6954656/6956545/06956581.pdf). Sasson EB, Chiesa A, Garman C, Green M, Miers I, Tromer E, Virza M. S&P'14.
    + Keyword: *`Privacy`*

- 🎓 [Zerocoin: Anonymous distributed e-cash from bitcoin](http://ieeexplore.ieee.org/iel7/6547086/6547088/06547123.pdf). Miers I, Garman C, Green M, Rubin AD. S&P'13.
    + Keyword: *`Privacy`*

## CCS (A)

+ 🎓 [Efficient Publicly Verifiable 2PC over a Blockchain with Applications to Financially-Secure Computations](http://homes.sice.indiana.edu/yh33/mypub/pvc.pdf). Ruiyu Zhu, Changchang Ding, Yan Huang. CCS'19.
    + Keyword: *`Consensus`*, *`sMPC`*

+ 🎓 [Erlay: Efficient Transaction Relay for Bitcoin](https://www.ece.ubc.ca/~sasha/papers/ccs19.pdf).	Gleb Naumenko, Gregory Maxwell, Pieter Wuille, Alexandra (Sasha) Fedorova, Ivan Beschastnikh. CCS'19.
    + Keyword: **Erlay**, *`Scalability`*, *`Network`*

+ 🎓 [HyperService: Interoperability and Programmability across Heterogeneous Blockchains](https://arxiv.org/pdf/1908.09343).	Zhuotao Liu, Yangxi Xiang,Jian Shi, Peng Gao, Haoyu Wang, Xusheng Xiao, Bihan Wen, Yih-Chun Hu. CCS'19.
    + Keyword: **HyperService**, *`Sidechain`*, *`Interoperability`*, *`Programmability`*

+ 🎓 [MatRiCT: Efficient, Scalable and Post-Quantum Blockchain Confidential Transactions Protocol](https://eprint.iacr.org/2019/1287.pdf).	Muhammed F. Esgin, Raymond K. Zhao, Ron Steinfeld, Joseph K. Liu, Dongxi Liu. CCS'19. 
    + Keyword: **MatRiCT**, *`Privacy`*, *`Wallets`*, *`RingCT`*, *`Post-quantum`*

+ 🎓 [Omniring: Scaling Up Private Payments Without Trusted Setup — Formal Foundations and a Construction of Ring Confidential Transactions with Log-size Proofs](https://eprint.iacr.org/2019/580.pdf). Russell W. F. Lai, Viktoria Ronge, Tim Ruffing, Dominique Schröder, Sri Aravinda Krishnan Thyagarajan, Jiafan Wang. CCS'19. 
    + Keyword: **Omniring**, *`Payment`*, *`RingCT`*

+ 🎓 [Prism: Deconstructing the Blockchain to Approach Physical Limits](https://arxiv.org/pdf/1810.08092). Vivek Bagaria, Sreeram Kannan, David Tse, Giulia Fanti, Pramod Viswanath. CCS'19. 
    + Keyword: **Prism**, *`Consensus`*, *`PoW`*

+ 🎓 [Learning to Fuzz from Symbolic Execution with Application to Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/ccs19-ilf.pdf).	Jingxuan He, Mislav Balunovic, Nodar Ambroladze, Petar Tsankov, Martin Vechev. CCS'19. 
    + Keyword: *`Smart Contracts`*

+ 🎓 [zkay: Specifying and Enforcing Data Privacy in Smart Contracts](https://files.sri.inf.ethz.ch/website/papers/ccs19-zkay.pdf).	Samuel Steffen, Benjamin Bichsel, Mario Gersbach, Noa Melchior, Petar Tsankov, Martin Vechev. CCS'19.
    + Keyword: **zkay**, *`Smart Contracts`*

+ 🎓 [SAMPL: Scalable Auditability of Monitoring Processes using Public Ledgers](https://www.cs.nmsu.edu/~roopa/sampl.pdf). Roopa Vishwanathan, Gaurav Panwar, Satyajayant Misra, Austin Bos. CCS'19. 
    + Keyword: **SAMPL**, *`Ledger`*

+ 🎓 [Atomic Multi-Channel Updates with Constant Collateral in Payment-Channel Networks](https://eprint.iacr.org/2019/583.pdf). Christoph Egger, Pedro Moreno-Sanchez, Matteo Maffei. CCS'19. 
    + Keyword: *`Payment Channel Networks`*

+ 🎓 [Fast multiparty threshold ecdsa with fast trustless setup](https://eprint.iacr.org/2019/114.pdf). Gennaro R, Goldfeder S. CCS'18.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

+ 🎓 [Fast secure multiparty ecdsa with practical distributed key generation and applications to cryptocurrency custody](https://eprint.iacr.org/2018/987.pdf). Lindell Y, Nof A. CCS'18.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

+ 🎓 [General State Channel Networks](https://eprint.iacr.org/2018/320.pdf) Dziembowski S, Faust S, Hostáková K. CCS'18.
    + Keyword: *`Payment Channel Networks`*

- 🎓 [Ouroboros Genesis: Composable Proof-of-Stake Blockchains with Dynamic Availability](https://eprint.iacr.org/2018/378.pdf). Badertscher C, Gazi P, Kiayias A, Russell A, Zikas V. CCS'18.
    + Keyword: *`PoS`*

+ 🎓 [FairSwap: How to fairly exchange digital goods](https://eprint.iacr.org/2018/740) Dziembowski S, Faust S, Eckey L. CCS'18.
    + Keyword: *`System Design`*

+ 🎓 [RapidChain: Scaling Blockchain via Full Sharding](https://dl.acm.org/ft_gateway.cfm?ftid=2008927&id=3243853). Mahdi Zamani, Mahnush Movahedi, Mariana Raykova. CCS'18.
    + Keyword: *`System`*

- 🎓 [The Gap Game](http://delivery.acm.org/10.1145/3250000/3243737/p713-tsabary.pdf). Tsabary I., Eyal I. CCS'18.
    + Keyword: *`Economics`*

- 🎓 [Concurrency and Privacy with Payment-Channel Networks](https://eprint.iacr.org/2017/820.pdf). Malavolta G, Moreno-Sanchez P, Kate A, Maffei M, Ravi S. CCS '17.
    + Keyword: *`Payment Channel Networks`*

+ 🎓 [Revive: Rebalancing Off-Blockchain Payment Channel Networks](https://eprint.iacr.org/2017/823.pdf). Khalil, R., & Gervais, A. CCS'17.
    + Keyword: *`Payment Channel Networks`*

- 🎓 [Bolt: Anonymous Payment Channels for Decentralized Currencies](https://eprint.iacr.org/2016/701.pdf) Green M, Miers I. CCS'16.
    + Keyword: *`Payment Channel Networks`*

+ 🎓 [The Honey Badger of BFT Protocols](https://infoscience.epfl.ch/record/222858/files/199.pdf). Miller A, Xia Y, Croman K, Shi E, Song D. CCS'16.
    + Keyword: *`System`*

- 🎓 [A secure sharding protocol for open blockchains](https://www.comp.nus.edu.sg/~prateeks/papers/Elastico.pdf). Luu L, Narayanan V, Zheng C, Baweja K, Gilbert S, Saxena P. CCS '16.
    + Keyword: **Elastico**, *`Sharding`*, *`Scalability`*

- 🎓 **[On the instability of Bitcoin without the block reward](http://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf)**. Carlsten M, Kalodner H, Weinberg SM, Narayanan A. CCS'16.
    + Keyword: *`Economics`*

- 🎓 [On the Security and Performance of Proof of Work Blockchains](https://eprint.iacr.org/2016/555.pdf). Gervais A, Karame GO, Wüst K, Glykantzis V, Ritzdorf H, Capkun S. CCS '16.
    + Keyword: *`Mining`*

+ 🎓 [Making Smart Contracts Smarter](https://www.comp.nus.edu.sg/~loiluu/papers/oyente.pdf). Luu L, Chu DH, Olickel H, Saxena P, Hobor A. CCS'16.
    + Keyword: *`Smart Contracts`*

- 🎓 [The Honey Badger of BFT Protocols](https://infoscience.epfl.ch/record/222858/files/199.pdf). Miller A, Xia Y, Croman K, Shi E, Song D. CCS'16.
    + Keyword: *`Network`*

+ 🎓 [On the instability of Bitcoin without the block reward](http://www.cs.princeton.edu/~smattw/CKWN-CCS16.pdf). Carlsten M, Kalodner H, Weinberg SM, Narayanan A. CCS'16.
    + Keyword: *`Economic`*

+ 🎓 [Town crier: An authenticated data feed for smart contracts](http://delivery.acm.org/10.1145/2980000/2978326/p270-zhang.pdf?ip=46.176.188.9&id=2978326&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E594C525CFFA2AFAF&CFID=923932938&CFTOKEN=56121949&__acm__=1492299159_38039f3afa858f241818fdcf190e0200). Zhang F, Cecchetti E, Croman K, Juels A, Shi E. CCS'16.
    + Keyword: *`Smart Contracts`*

- 🎓 **[Making Smart Contracts Smarter](https://www.comp.nus.edu.sg/~loiluu/papers/oyente.pdf)**. Luu L, Chu DH, Olickel H, Saxena P, Hobor A. CCS'16.
    + Keyword: **Oyente**, *`Smart Contracts`*

- 🎓 [The Ring of Gyges: Investigating the Future of Criminal Smart Contracts](http://www.initc3.org/files/Gyges.pdf). Juels A, Kosba A, Shi E. CCS'16.
    + Keyword: *`Smart Contracts`*

- 🎓 [Town crier: An authenticated data feed for smart contracts](https://eprint.iacr.org/2016/168.pdf). Zhang F, Cecchetti E, Croman K, Juels A, Shi E. CCS'16.
    + Keyword: *`Smart Contracts`*

+ 🎓 [On the Security and Performance of Proof of Work Blockchains](https://eprint.iacr.org/2016/555.pdf). Gervais A, Karame GO, Karl Wüst, Glykantzis V, Ritzdorf H, Capkun S. CCS'16.
    + Keyword: *`Privacy`*

+ 🎓 [A Secure Sharding Protocol For Open Blockchains](https://www.comp.nus.edu.sg/~loiluu/papers/elastico.pdf). Loi Luu, Viswesh Narayanan, Chaodong Zheng, Kunal Baweja, Seth Gilbert, Prateek Saxena. CCS'16.
    + Keyword: *`System`*

+ 🎓 [Demystifying incentives in the consensus computer](https://eprint.iacr.org/2015/702). Loi Luu, Jason Teutsch, Raghav Kulkarni and Prateek Saxena. CCS'15
    + Keyword: *`Economic`*

+ 🎓 [Tampering with the Delivery of Blocks and Transactions in Bitcoin](https://eprint.iacr.org/2015/578.pdf).Gervais, Arthur and Ritzdorf, Hubert and Karame, Ghassan O. and Capkun, Srdjan. CCS'15
    + Keyword: *`Network`*, *`Consensus`*, *`PoW`*

+ 🎓 [Non-outsourceable Scratch-Off Puzzles to Discourage Bitcoin Mining Coalitions](http://soc1024.ece.illinois.edu/nonoutsourceable_full.pdf). Andrew Miller, Elaine Shi, Ahmed Kosba, and Jonathan Katz. CCS'15
    + Keyword: *`Consensus`*, *`PoW`*, *`Mining`*

+ 🎓 [Provisions: Privacy-preserving proofs of solvency for Bitcoin exchanges](https://eprint.iacr.org/2015/1008.pdf). Dagher GG, Bünz B, Bonneau J, Clark J, Boneh D. CCS'15
    + Keyword: *`Privacy`*

+ 🎓 [Deanonymisation of Clients in Bitcoin P2P Network](https://arxiv.org/pdf/1405.7418.pdf). Biryukov A, Khovratovich D, Pustogarov I. CCS'14.
    + Keyword: *`Privacy`*

+ 🎓 [Double-Spending Fast Payments in Bitcoin](https://www.eecis.udel.edu/~ruizhang/CISC859/S17/Paper/p9.pdf). Karame, Ghassan O. and Androulaki, Elli and Capkun, Srdjan. CCS'12.
    + Keyword: *`Consensus`*, *`PoW`*, *`Mining`*

## NDSS (A)
- 🎓 [Bobtail: Improved Blockchain Security with Low-Variance Mining](https://www.ndss-symposium.org/wp-content/uploads/2020/02/23095.pdf). George Bissias (University of Massachusetts Amherst), Brian N. Levine (University of Massachusetts Amherst). NDSS'20
    + Keyword: *`Mining`*

- 🎓 [Snappy: Fast On-chain Payments with Practical Collaterals](https://arxiv.org/abs/2001.01278.pdf). Vasilios Mavroudis (University College London), Karl Wüst (ETH Zurich), Aritra Dhar (ETH Zurich), Kari Kostiainen (ETH Zurich), Srdjan Capkun (ETH Zurich). NDSS'20
    + Keyword: *`Scalability`*

- 🎓 [The Attack of the Clones Against Proof-of-Authority](https://arxiv.org/abs/1902.10244.pdf). Parinya Ekparinya (University of Sydney), Vincent Gramoli (University of Sydney and CSIRO-Data61), Guillaume Jourjon (CSIRO-Data61). NDSS'20
    + Keyword: *`Attacks`*

- 🎓 [Broken Metre: Attacking Resource Metering in EVM](https://arxiv.org/abs/1909.07220.pdf). 
Daniel Perez (Imperial College London), Benjamin Livshits (Imperial College London, UCL Centre for Blockchain Technologies, and Brave Software). NDSS'20
    + Keyword: *`Attacks`*

- 🎓 [SODA: A Generic Online Detection Framework for Smart Contracts](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24449.pdf). Ting Chen (University of Electronic Science and Technology of China), Rong Cao (University of Electronic Science and Technology of China), Ting Li (University of Electronic Science and Technology of China), Xiapu Luo (The Hong Kong Polytechnic University), Guofei Gu (Texas A&M University), Yufei Zhang (University of Electronic Science and Technology of China), Zhou Liao (University of Electronic Science and Technology of China), Hang Zhu (University of Electronic Science and Technology of China), Gang Chen (Chengdu Kongdi Technology Inc.), Zheyuan He (University of Electronic Science and Technology of China), Yuxing Tang (University of Electronic Science and Technology of China), Xiaodong Lin (University of Guelph), Xiaosong Zhang (University of Electronic Science and Technology of China). NDSS'20
    + Keyword: *`Smart Contracts`*, *`Formal Methods`*

- 🎓 [Anonymous Multi-Hop Locks for Blockchain Scalability and Interoperability](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_09-4_Malavolta_paper.pdf). Malavolta G, Moreno-Sanchez P, Schneidewind C, Kate A, Maffei M. NDSS'19.
    + Keyword: *`Payment Channels`*
    + Github: https://github.com/KZen-networks/multi-hop-locks

+ 🎓 [SABRE: Protecting Bitcoin against Routing Attacks](https://arxiv.org/pdf/1808.06254.pdf). Maria Apostolaki, Gian Marti, Jan Müller, and Laurent Vanbever. NDSS'19.
    + Keyword: *`Network`*

+ 🎓 [Seth: Protecting Existing Smart Contracts Against Re-Entrancy Attacks](https://arxiv.org/pdf/1812.05934.pdf). Michael Rodler, Wenting Li and Ghassan Karame, Lucas Davi. NDSS'19.
    + Keyword: *`Smart Contracts`*

+ 🎓 [YODA: Enabling computationally intensive contracts on blockchains with Byzantine and Selfish nodes](https://arxiv.org/pdf/1811.03265.pdf). Sourav Das, Vinay Joseph Ribeiro, and Abhijeet Anand. NDSS'19.
    + Keyword: *`Smart Contracts`*

+ 🎓 [Fine-Grained and Controlled Rewriting in Blockchains: Chameleon-Hashing Gone Attribute-Based](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_02A-3_Derler_paper.pdf). David Derler, Kai Samelin, Daniel Slamanig and Christoph Striecks. NDSS'19.
    + Keyword: *`Cryptograph`*

+ 🎓 [Privacy-preserving Multi-hop Locks for Blockchain Scalability and Interoperability](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_09-4_Malavolta_paper.pdf). Giulio Malavolta, Pedro Moreno Sanchez, Clara Schneidewind and Matteo Maffei, Aniket Kate. NDSS'19.
    + Keyword: *`Scalability`*, *`Layer 2`*

+ 🎓 ["Zeus": Analyzing Safety of Smart Contracts](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_09-1_Kalra_paper.pdf). Kalra S, Goel S, Dhawan M, Sharma S. NDSS'18.
    + Keyword: *`Economic`*, *`Smart Contracts`*

+ 🎓 [Chainspace: A Sharded Smart Contracts Platform](https://sheharbano.com/assets/publications/ndss2018-chainspace.pdf). Mustafa Al-Bassam, Alberto Sonnino, Shehar Bano, Dave Hrycyszyn, and George Danezis. NDSS'18.
    + Keyword: *`System Design`*

+ 🎓 [Settling Payments Fast and Private: Efficient Decentralized Routing for Path-Based Transactions](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_09-3_Roos_paper.pdf). Stefanie Roos, Pedro Moreno-Sanchez, Aniket Kate, and Ian Goldberg. NDSS'18.
    + Keyword: *`Scalability`*, *`Layer 2`*

- 🎓 [TumbleBit: An untrusted Bitcoin-compatible anonymous payment hub](https://pdfs.semanticscholar.org/a4ce/62a44770a33d1a19b5553f080d4f12e9e55d.pdf). Heilman E, Alshenibr L, Baldimtsi F, Scafuro A, Goldberg S. NDSS'17.
    + Keyword: *`Privacy`*

- 🎓 [Centrally banked cryptocurrencies](https://arxiv.org/pdf/1505.06895.pdf). Danezis G, Meiklejohn S. NDSS'16.
    + Keyword: *`Consensus`*, **RSCoin**

## CRYPTO (A)

- 🎓 [Two-party ECDSA from hash proof systems and efficient instantiations](https://hal.archives-ouvertes.fr/hal-02281931/file/CRYPTO19_2pECDSA_extended.pdf). Castagnos G, Catalano D, Laguillaumie F, et al. CRYPTO'19.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

- 🎓 [Threshold cryptosystems from threshold fully homomorphic encryption](https://pdfs.semanticscholar.org/5224/7b8f30a05bd8bd73b921f918af78c1ef015a.pdf). Boneh D, Gennaro R, Goldfeder S, et al. CRYPTO'18.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

- 🎓 [Bitcoin as a Transaction Ledger: A Composable Treatment](https://eprint.iacr.org/2017/149.pdf). Badertscher C., Maurer U., Tschudi D., Zikas V. CRYPTO'17.
    + Keyword: *`Wallets`*

+ 🎓 [Fast secure two-party ECDSA signing](https://pdfs.semanticscholar.org/59cb/bb6ccd07dc312d3d0c218d384f004396c370.pdf). Lindell Y. CRYPTO'17.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

+ 🎓 [The Bitcoin Backbone Protocol with Chains of Variable Difficulty](https://eprint.iacr.org/2016/1048). Juan A. Garay and Aggelos Kiayias and Nikos Leonardos. CRYPTO'17.
    + Keyword: *`Consensus`*, *`PoS`*

- 🎓 [Ouroboros: A provably secure proof-of-stake blockchain protocol](https://pdfs.semanticscholar.org/1c14/549f7ba7d6a000d79a7d12255eb11113e6fa.pdf). Kiayias A, Russell A, David B, Oliynykov R. CRYPTO'17.
    + Keyword: *`PoS`*

+ 🎓 [Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake protocol](http://eprint.iacr.org/2017/573.pdf). Bernardo D, Gazi P, Kiayias A, Russell A. Crypto'17.
    + Keyword: *`Consensus`*, *`PoS`*

- 🎓 [How to Use Bitcoin to Design Fair Protocols](https://eprint.iacr.org/2014/129.pdf). Bentov I, Kumaresan R. CRYPTO'14.
    + Keyword: *`Economics`*

- 🎓 [Two-party generation of DSA signatures](https://link.springer.com/content/pdf/10.1007/3-540-45539-6_15.pdf). MacKenzie P, Reiter M K. CRYPTO'01
    + Keyword: *`Wallets`*, *`Threshold Signature`*

- 🎓 [Pricing via processing or combatting junk mail](https://web.cs.dal.ca/~abrodsky/7301/readings/DwNa93.pdf). Dwork C, Naor M. CRYPTO'92.
    + Keyword: *`Consensus`*, *`PoS`*, **Proof-of-Work**

- 🎓 [Blind signatures for untraceable payments](http://blog.koehntopp.de/uploads/Chaum.BlindSigForPayment.1982.PDF). Chaum D. CRYPTO'83.
    + Keyword: *`Privacy`*, *`Blind Signature`*

## EUROCRYPT (A)

> no papers directly related to blockchain in EUROCRYPTO'20

+ 🎓 [Consensus through Herding](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_24.pdf). T-H. Hubert Chan Rafael Pass Elaine Shi. EUROCRYPT'19. 
    + Keyword: *`Consensus`*

+ 🎓 [Proof-of-Stake Protocols for Privacy-Aware Blockchains](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_23.pdf). Chaya Ganesh Claudio Orlandi Daniel Tschudi. EUROCRYPT'19. 
    + Keyword: *`PoS`*

+ 🎓 [Multi-Party Virtual State Channels](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_21.pdf). Stefan Dziembowski Lisa Eckey Sebastian Faust Julia Hesse Kristina Hostáková. EUROCRYPT'19. 
    + Keyword: *`Payment Channel`*

+ 🎓 [Aggregate Cash Systems: A Cryptographic Investigation of Mimblewimble](https://link.springer.com/content/pdf/10.1007%2F978-3-030-17653-2_22.pdf). Georg Fuchsbauer Michele Orrù Yannick Seurin. EUROCRYPT'19. 
    + Keyword: *`System Design`*

+ 🎓 [Analysis of the Blockchain Protocol in Asynchronous Networks](https://eprint.iacr.org/2016/454.pdf). Pass R, Seeman L, shelat a. EUROCRYPT'17
    + Keyword: *`Consensus-PoW`*

- 🎓 [Fair and Robust Multi-Party Computation using a Global Transaction Ledger](https://eprint.iacr.org/2015/574.pdf). Kiayias A., Zhouh S., Zikas V. EUROCRYPT'16.
    + Keyword: *`Applications`*

- 🎓 **[The Bitcoin Backbone Protocol: Analysis and Applications](https://eprint.iacr.org/2014/765.pdf)**. Garay J, Kiayias A, Leonardos N. EUROCRYPT'15.
    + Keyword: *`Consensus`*, *`PoW`*

- 🎓 [Practical threshold signatures](https://link.springer.com/content/pdf/10.1007/3-540-45539-6_15.pdf). Shoup V. EUROCRYPT'00.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

- 🎓 Secure distributed key generation for discrete-log based cryptosystems. Gennaro R, Jarecki S, Krawczyk H, et al. EUROCRYPT'99
    + Keyword: *`Wallets`*, *`Threshold Signature`*

## INFOCOM (A)

+ 🎓 [Modeling the Impact of Network Connectivity on Consensus Security of Proof-of-Work Blockchain](https://arxiv.org/pdf/2002.08912.pdf). 
Yang Xiao (Virginia Tech, USA); Ning Zhang (Washington University in St. Louis, USA); Wenjing Lou and Thomas Hou (Virginia Tech, USA)
    + Keyword: *`Consensus-PoW`*, *`Security`*

+ 🎓 [Secure Balance Planning of Off-blockchain Payment Channel Networks](https://www.u-aizu.ac.jp/~pengli/files/pcn_planning_infocom2020.pdf). 
Peng Li and Toshiaki Miyazaki (The University of Aizu, Japan); Wanlei Zhou (University of Technology Sydney, Australia)
    + Keyword: *`Payment Channel Networks`*

+ 🎓 [Corking by Forking: Vulnerability Analysis of Blockchain](https://sci-hub.tw/https://ieeexplore.ieee.org/document/8737490). Shengling Wang and Chenyu Wang, Qin Hu. INFOCOM'19
    + Keyword: *`Security`*

+ 🎓 [ACCEL: Accelerating the Bitcoin Blockchain for High-throughput, Low-latency Applications](https://sci-hub.tw/https://ieeexplore.ieee.org/document/8737556). Adiseshu Hari, Murali Kodialam, T. V Lakshman. INFOCOM'19
    + Keyword: *`Scalability`*

+ 🎓 [A Blockchain based Witness Model for Trustworthy Cloud Service Level Agreement Enforcement](https://pure.uva.nl/ws/files/42160225/Blockchain_based_Witness_Model.pdf). Huan Zhou, Xue Ouyang, Zhijie Ren, Jinshu Su, Cees de Laat and Zhiming Zhao. INFOCOM'19
    + Keyword: *`Application`*

+ 🎓 [Stochastic Models and Wide-Area Network Measurements for Blockchain Design and Analysis](https://www.researchgate.net/publication/321369565_Stochastic_Models_and_Wide-Area_Network_Measurements_for_Blockchain_Design_and_Analysis). Nikolaos Papadis, Sem Borst, Anwar Walid, Mohamed Grissa, Leandros Tassiulas. INFOCOM'18
    + Keyword: *`Network`*

+ 🎓 [Understanding ethereum via graph analysis](https://www4.comp.polyu.edu.hk/~csxluo/EthereumGraphAnalysis.pdf). Ting Chen,Yuxiao Zhu, Zihao Li, Jiachi Chen, Xiaoqi Li, Xiapu Luo, Xiaodong Lin, Xiaodong Lin. INFOCOM'18
    + Keyword: *`Transaction`*

## SOSP (A)

+ 🎓 [Teechain: A Secure Payment Network with Asynchronous Blockchain Access](https://arxiv.org/pdf/1707.05454.pdf). Joshua Lind, Oded Naor, Ittay Eyal, Florian Kelbert, Peter Pietzuch, Emin Gun Sirer. SOSP'19
    + Keyword: *`Payment Channel Networks`*

+ 🎓 [Fast and Secure Global Payments with Stellar](https://www.scs.stanford.edu/~dm/home/papers/lokhava:stellar-core.pdf). Marta Lokhava, Giuliano Losa, David Mazières, Graydon Hoare, Nicolas Barry, Eliezer Gafni, Jonathan Jove, Rafał Malinowski, Jed McCaleb. SOSP'19
    + Keyword: *`Consensus`*

+ 🎓 [Notary: A Device for Secure Transaction Approval](https://pdos.csail.mit.edu/papers/notary:sosp19.pdf). Anish Athalye, Adam Belay, Frans Kaashoek, Robert Morris, Nickolai Zeldovich. SOSP'19
    + Keyword: *`Consensus`*

+ 🎓 [Algorand: Scaling Byzantine Agreements for Cryptocurrencies](https://people.csail.mit.edu/nickolai/papers/gilad-algorand.pdf). Yossi Gilad, Rotem Hemo, Silvio Micali, Georgios Vlachos, Nickolai Zeldovich. SOSP'17
    + Keyword: *`Consensus`*

## NSDI (A)

+ 🎓 [High Throughput Cryptocurrency Routing in Payment Channel Networks](https://www.usenix.org/system/files/nsdi20-paper-sivaraman.pdf). Vibhaalakshmi Sivaraman, Massachusetts Institute of Technology; Shaileshh Bojja Venkatakrishnan, Ohio State University; Kathleen Ruan, Carnegie Mellon University; Parimarjan Negi and Lei Yang, Massachusetts Institute of Technology; Radhika Mittal, University of Illinois at Urbana-Champaign; Giulia Fanti, Carnegie Mellon University; Mohammad Alizadeh, Massachusetts Institute of Technology. NSDI'20
    + Keyword: *`Payment Channel Networks`*, **Spider**

+ 🎓 [Monoxide: Scale Out Blockchain with Asynchronized Consensus Zones](https://www.usenix.org/system/files/nsdi19-wang-jiaping.pdf). Jiaping Wang, Hao Wang. NSDI'19
    + Keyword: *`System`*, **Zones**, **Eventual Atomicity**, **Chu-ko-nu Mining**

+ 🎓 [zkLedger: Privacy-Preserving Auditing for Distributed Ledgers](https://www.usenix.org/system/files/conference/nsdi18/nsdi18-narula.pdf). Neha Narula and Willy Vasquez and Madars Virza. NSDI'18
    + Keyword: *`Privacy`*, **zkLedger**

+ 🎓 [Bitcoin-NG: A Scalable Blockchain Protocol](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf). Eyal I, Gencer AE, Sirer EG, Van Renesse R. NSDI’16
    + Keyword: *`Consensus-PoW`*

## VLDB (A)

+ 🎓 [A Demonstration of Sterling: A Privacy-Preserving Data Marketplace](http://www.vldb.org/pvldb/vol11/p2086-hynes.pdf). Nick Hynes1, David Dao, David Yan, Raymond Cheng, Dawn Song. VLDB'19. 
    + Keyword: *`Privacy`*

+ 🎓 [CAPER: A Cross-Application Permissioned Blockchain](http://www.vldb.org/pvldb/vol12/p1385-amiri.pdf). Mohammad Javad Amiri, Divyakant Agrawal, Amr El Abbadi. VLDB'19.
    + Keyword: *`Application`*

+ 🎓 [BlockchainDB - A Shared Database on Blockchains](http://www.vldb.org/pvldb/vol12/p1597-el-hindi.pdf). Muhammad El-Hindi,
Carsten Binnig, Arvind Arasu, Donald Kossmann, Ravi Ramamurthy. VLDB'19.
    + Keyword: *`Application`*

+ 🎓 [Fine-Grained, Secure and Efficient Data Provenance on Blockchain Systems](http://www.vldb.org/pvldb/vol12/p975-ruan.pdf). Pingcheng Ruan, Gang Chen, Tien Tuan Anh Dinh, Qian Lin, Beng Chin Ooi, Meihui Zhang. VLDB'19. 
    + Keyword: *`Provenance`*

+ 🎓 [ForkBase: An Efficient Storage Engine for Blockchain and Forkable Applications](http://www.vldb.org/pvldb/vol11/p1137-wang.pdf). Sheng Wang, Tien Tuan Anh Dinh, Qian Lin, Zhongle Xie, Meihui Zhang, Qingchao Cai, Gang Chen, Beng Chin Ooi, Pingcheng Rua. VLDB'18. 
    + Keyword: *`Storage`*

## OSDI (A)

- 🎓 [Proving the correct execution of concurrent services in zero-knowledge](https://www.usenix.org/system/files/osdi18-setty.pdf). Srinath Setty, Sebastian Angel, Trinabh Gupta, Jonathan Lee. OSDI'18.
    + Keyword: *`Formal Methods`*, *`ZKP`*, **Spice**

- 🎓 [Practical Byzantine Fault Tolerance](http://pmg.csail.mit.edu/papers/osdi99.pdf). Castro M., Liskov B. OSDI'99.
    + Keyword: *`Consensus`*

## SIGMOD (A)

- 🎓 Confidentiality Support over Financial Grade Consortium Blockchain. 
Ying Yan (Ant Financial Services Group), Changzheng Wei (Ant Financial Services Group), Xuepeng Guo (Ant Financial Services Group), Xuming Lu (Ant Financial Services Group), Xiaofu Zheng (Ant Financial Services Group), Qi Liu (Ant Financial Services Group), Chenhui Zhou (Ant Financial Services Group), Xuyang Song (Ant Financial Services Group), Boran Zhao (Ant Financial Services Group), Hui Zhang (Ant Financial Services Group), Guofei Jiang (Ant Financial Services Group). SIGMOD'20
    + Keyword: *`Privacy`*, *`TEE`*
    + Type: *`Industrial Paper`*

- 🎓 FalconDB: Blockchain-based Collaborative Database. 
Yanqing Peng (University of Utah), Min Du (University of California, Berkeley), Feifei Li (University of Utah), Raymond Cheng (University of California, Berkeley), Dawn Song (University of California, Berkeley). SIGMOD'20
    + Keyword: *`Application`*
    + Type: *`Research Paper`*

- 🎓 A Transactional Perspective on Execute-order-validate Blockchains. Pingcheng Ruan (National University of Singapore), Dumitrel Loghin (National University of Singapore), Quang-Trung Ta (National University of Singapore), Meihui Zhang (Beijing Institute of Technology), Gang Chen (Zhejiang University), Beng Chin Ooi (National University of Singapore). SIGMOD'20
    + Type: *`Research Paper`*

## TOCS (A)

- 🎓 [The part-time parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf). Lamport L. TOCS '98.
    + Keyword: *`Consensus`*

## TOPLAS (A)

- 🎓 [The Byzantine Generals Problem](https://people.eecs.berkeley.edu/~luca/cs174/byzantine.pdf). Lamport L, Shostak R., Pease M. '82. TOPLAS '82.
    + Keyword: *`Consensus`*

## JACM (A)

- 🎓 [Consensus in the Presence of Partial Synchrony](https://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf). Dwork S., Lynch N. '88. JACM '88.
    + Keyword: *`Consensus`*

## Journal of Cryptology (A)

## TDSC (A)

- 🎓 [Security and privacy in decentralized energy trading through multi-signatures, blockchain and anonymous messaging streams](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/7589035). Aitzhan N Z, Svetinovic D. TDSC'16
    + Keyword: *`Applications`*

## ASIACRYPT (B)

- 🎓 [Compact multi-signatures for smaller blockchains](https://eprint.iacr.org/2018/483.pdf). Boneh D, Drijvers M, Neven G. ASIACRYPT'18
    + Keyword: *`Wallets`*, *`Threshold Signature`*

- 🎓 [Short signatures from the Weil pairing](https://www.iacr.org/archive/asiacrypt2001/22480516.pdf). Boneh D, Lynn B, Shacham H. ASIACRYPT'01
    + Keyword: *`Wallets`*, *`Threshold Signature`*

## ESORICS (B)

- 🎓 [Incentives for Harvesting Attack in Proof of Work Mining Pools](https://link.springer.com/chapter/10.1007/978-3-030-29959-0_34). Zolotavkin Y, & Kuchta V. ESORICS'19.
    + Keyword: *`Attacks`*

- 🎓 [PDFS: practical data feed service for smart contracts](https://arxiv.org/pdf/1808.06641.pdf). Guarnizo J, Szalachowski P. ESORICS'19
    + Keyword: *`Application`*, *`Smart Contracts`*

- 🎓 [Towards a Marketplace for Secure Outsourced Computations](https://arxiv.org/pdf/1808.09682.pdf). Dang H., Le Tien D., Chang E C. ESORICS'19
    + Keyword: *`Application`*, *`Payment Channels`*

- 🎓 [Annotary: A Concolic Execution System for Developing Secure Smart Contracts](https://arxiv.org/pdf/1907.03868.pdf). Weiss, K. Schütte, J. ESORICS'19
    + Keyword: *`Smart Contracts`*

- 🎓 [A Lattice-Based Linkable Ring Signature Supporting Stealth Addresses](https://books.google.com.hk/books?id=TqOvDwAAQBAJ&pg=PA745&lpg=PA745&dq=pdf+A+Lattice-Based+Linkable+Ring+Signature+Supporting+Stealth+Addresses&source=bl&ots=X8AWJqPEBj&sig=ACfU3U1-Ev8mg5y9G1X-GgTeRQN50MhWCQ&hl=zh-CN&sa=X&ved=2ahUKEwiM0IGL-5LlAhUsy4sBHYCuDEwQ6AEwBHoECAkQAQ#v=onepage&q=A%20Lattice-Based%20Linkable%20Ring%20Signature%20Supporting%20Stealth%20Addresses&f=false). Liu, Z., Nguyen, K., Yang, G., Wang, H., Wong, D. S. ESORICS'19
    + Keyword: *`Privacy`*, *`Ring Signature`*

- 🎓 [Coinshuffle: Practical decentralized coin mixing for bitcoin](http://crypsys.mmci.uni-saarland.de/projects/CoinShuffle/coinshuffle.pdf). Ruffing T, Moreno-Sanchez P, Kate A. ESORICS '14.
    + Keyword: *`Privacy`*

## EuroSys (B)

> no papers directly related to blockchain in EUROSYS'20

+ 🎓 [Hyperledger Fabric: A Distributed Operating System for Permissioned Blockchains](https://arxiv.org/pdf/1801.10228.pdf). Elli Androulaki, Artem Barger, Vita Bortnikov, Christian Cachin, Konstantinos Christidis, Angelo De Caro, David Enyeart, Christopher Ferris, Gennady Laventman, Yacov Manevich, Srinivasan Muralidharan, Chet Murthy, Binh Nguyen, Manish Sethi, Gari Singh, Keith Smith, Alessandro Sorniotti, Chrysoula Stathakopoulou, Marko Vukolić, Sharon Weed Cocco, Jason Yellick. EuroSys'18
    + Keyword: *`System Design`*

## ICDCS (B)

+ 🎓 [Selfish Mining in Ethereum](https://arxiv.org/abs/1901.04620) Jianyu Niu and Chen Feng. ICDCS'19
    + Keyword: *`PoW`*

+ 🎓 [Trust Mends Blockchains: Living up to Expectations](http://kth.diva-portal.org/smash/get/diva2:1316199/FULLTEXT01.pdf). Leila Bahri and Sarunas Girdzijauskas. ICDCS'19
    + Keyword: *`Consensus`*

+ 🎓 [Hierarchical Edge-Cloud Computing for Mobile Blockchain Mining Game](https://pdfs.semanticscholar.org/cfe0/77c9b880c2a0dfb495448a068fdf1db07b6e.pdf). Suhan Jiang, Xinyi Li and Jie Wu. ICDCS'19
    + Keyword: *`Application`*

+ 🎓 OptChain: Optimal Transactions Placement for Scalable Blockchain Sharding. Lan Nguyen, Truc Nguyen, Thang Dinh and My Thai. ICDCS'19
    + Keyword: *`Scalability`*

+ 🎓 Jidar: A Jigsaw-like Data Reduction Approach without Trust Assumptions for Bitcoin System. Xiaohai Dai, Jiang Xiao, Wenhui Yang, Chaofan Wang and Hai Jin. ICDCS'19
    + Keyword:

+ 🎓 [ParBlockchain: Leveraging Transaction Parallelism in Permissioned Blockchain Systems](https://arxiv.org/pdf/1902.01457.pdf). Mohammad Javad Amiri, Divyakant Agrawal and Amr El Abbadi. ICDCS'19
    + Keyword: *`Scalability`*

+ 🎓 Optimal Admission Control For Secondary Users using Blockchain Technology In Cognitive Radio Networks. Wenlong Ni, Yuhong Zhang and Wei Li. ICDCS'19
    + Keyword: *`Application`*

+ 🎓 B-IoT: Blockchain Driven Internet of Things with Credit-Based Consensus Mechanism. Junqin Huang, Linghe Kong, Guihai Chen, Long Chen, Kaishun Wu and Xue Liu. ICDCS'19
    + Keyword: *`Application`*

+ 🎓 Resource Allocation and Consensus on Edge Blockchain in Pervasive Edge Computing Environments. Yaodong Huang, Jiarui Zhang, Jun Duan, Bin Xiao, Fan Ye and Yuanyuan Yang. ICDCS'19
    + Keyword: *`Application`*

+ 🎓 Xyreum: A High-Performance and Scalable Blockchain for IIoT Security and Privacy. Abubakar Sadiq Sani, Dong Yuan, Wei Bao, Phee Lep Yeoh, Zhaoyang Dong, Branka Vucetic and Elisa Bertino. ICDCS'19
    + Keyword: *`Application`*

+ 🎓 AI Blockchain Platform for Trusting News. Zonyin Shae and Jeffrey Tsai. ICDCS'19
    + Keyword: *`Vision`*

+ 🎓 Dependable Public Ledger for Policy Compliance, a Blockchain Based Approach. Zhou Wu, Andrew Williams and Debbie Perouli. ICDCS'19
    + Keyword: *`Vision`*

+ 🎓 [Please, do not decentralize the Internet with (permissionless) blockchains!](https://arxiv.org/pdf/1904.13093.pdf). Pedro Garcia Lopez, Alberto Montresor and Anwitaman Datta. ICDCS'19
    + Keyword: *`Vision`*

+ 🎓 Transform Blockchain into Distributed Parallel Computing Architecture for Precision Medicine. Zonyin Shae, Jeffrey J.P. Tsai. ICDCS'18
    + Keyword: *`Application`*

+ 🎓 Towards A Novel Architecture for Enabling Interoperability Amongst Multiple Blockchains. Hai Jin, Xiaohai Dai, and Jiang Xiao. ICDCS'18
    + Keyword: *`Interoperability`*

+ 🎓 Towards Dependable, Scalable, and Pervasive Distributed Ledgers with Blockchains. Zhang Kaiwen, Jacobsen Hans-Arno.ICDCS'18
    + Keyword: *`Consensus`*
    + Type: *`Short Paper`*

+ 🎓 A Flexible Network Approach to Privacy of Blockchain Transactions. David M¨odinger, Henning Kopp, Frank Kargl and Franz J. Hauck. ICDCS'18
    + Keyword: *`Privacy`*
    + Type: *`Short Paper`*

## PODC (B)

+ 🎓 [The Consensus Number of a Cryptocurrency](https://arxiv.org/pdf/1906.05574.pdf). R. Guerraoui, P. Kuznetsov, M. Monti, M. Pavlovic, D. Seredinschi. PODC'19
    + Keyword: *`Consensus`*

+ 🎓 Communication Complexity of Byzantine Agreement, Revisited. I. Abraham, T. Chan, D. Dolev, K. Nayak, R. Pass, L. Ren, E. Shi. PODC'19
    + Keyword: *`Consensus`*, *`BFT`*

+ 🎓 [Exact Byzantine Consensus on Undirected Graphs under Local Broadcast Model](https://arxiv.org/pdf/1903.11677.pdf). M. Khan, S. Naqvi, N. Vaidya. PODC'19
    + Keyword: *`Consensus`*, *`BFT`*

+ 🎓 [Asymptotically Optimal Validated Asynchronous Byzantine Agreement](https://dl.acm.org/doi/pdf/10.1145/3293611.3331612). I. Abraham, D. Malkhi, A. Spiegelman. PODC'19
    + Keyword: *`Consensus`*, *`BFT`*

+ 🎓 [HotStuff: BFT Consensus with Linearity and Responsiveness](https://www.cs.unc.edu/~reiter/papers/2019/PODC.pdf). M. Yin, I. Abraham, G. Gueta, D. Malkhi, M. Reiter. PODC'19
    + Keyword: *`Consensus`*, *`BFT`*

+ 🎓 [Atomic Cross-Chain Swaps](https://arxiv.org/abs/1801.09515). Maurice Herlihy. PODC'18
    + Keyword: *`Sidechain`*

+ 🎓 [Brief Announcement: Sustainable Blockchains through Proof of eXercise](https://haslab.uminho.pt/ashoker/files/pox-podc.pdf). Ali Shoker. PODC'18
    + Keyword: *`Consensus`*

+ 🎓 [FruitChains: A Fair Blockchain](https://eprint.iacr.org/2016/916.pdf).Rafael Pass, Elaine Shi. PODC'17
    + Keyword: *`Consensus`*, *`PoW`*

## CoNEXT (B)
+ 🎓 [On the Necessity of a Prescribed Block Validity Consensus: Analyzing Bitcoin Unlimited Mining Protocol](https://eprint.iacr.org/2017/686.pdf). Ren Zhang, Bart Preneel. CoNEXT '17
    + Keyword: *`Consensus`*, *`PoW`*

## ACNS (C)

+ 🎓 [Threshold-optimal DSA/ECDSA signatures and an application to Bitcoin wallet security](https://eprint.iacr.org/2016/013.pdf). Gennaro R, Goldfeder S, Narayanan A. ACNS'16.
    + Keyword: *`Wallets`*, *`Threshold Signature`*

## FC (C)

- 🎓 [Leveraging Bitcoin Testnet for Bidirectional Botnet Command and Control Systems](http://fc20.ifca.ai/preproceedings/71.pdf). Federico Franzoni (Universitat Pompeu Fabra), Vanesa Daza (Universitat Pompeu Fabra), Iván Abellán (Universitat Pompeu Fabra). FC'20
    + Keyword: *`Attacks`*

- 🎓 [Security Analysis on dBFT protocol of NEO](http://fc20.ifca.ai/preproceedings/32.pdf). Qin Wang (Swinburne University of Technology), Jiangshan Yu (Monash University), Zhiniang Peng (Qihoo 360 Core Security), Vancuong Bui (Swinburne University of Technology), Shiping Chen (Csiro, Data61), Yong Ding (Cyberspace Security Research Center), Yang Xiang (Swinburne University of Technology). FC'20
    + Keyword: *`Attacks`*

- 🎓 [Breaking the encryption scheme of the Moscow internet voting system](http://fc20.ifca.ai/preproceedings/178.pdf). Pierrick Gaudry (CNRS, Inria, Université de Lorraine), Alexander Golovnev (Harvard University). FC'20
    + Keyword: *`Attacks`*

- 🎓 [Short Paper: XOR Arbiter PUFs have Systematic Response Bias](http://fc20.ifca.ai/preproceedings/58.pdf). Nils Wisiol (Technische Universität Berlin), Niklas Pirnay (Technische Universität Berlin). FC'20
    + Keyword: *`Attacks`*

- 🎓 [Selfish Mining Re-Examined](http://fc20.ifca.ai/preproceedings/4.pdf). Kevin Alarcón Negy (Cornell University), Peter R. Rizun (Bitcoin Unlimited), Emin Gün Sirer (Cornell University). FC'20
    + Keyword: *`Consensus`*, *`Mining`*

- 🎓 [Fairness and Efficiency in DAG-based Cryptocurrencies](http://fc20.ifca.ai/preproceedings/165.pdf). Georgios Birmpas (University of Oxford), Elias Koutsoupias (University of Oxford), Philip Lazos (Sapienza University of Rome), Francisco J. Marmolejo Cossío (University of Oxford). FC'20
    + Keyword: *`Consensus`*, *`DAG`*

- 🎓 [Stake Shift in Major Cryptocurrencies: An Empirical Study](http://fc20.ifca.ai/preproceedings/195.pdf). Rainer Stütz (Austrian Institute of Technology), Peter Gaži (IOHK), Bernhard Haslhofer (Austrian Institute of Technology), Jacob Illium (Chainalysis). FC'20
    + Keyword: *`Consensus`*
    + Type: *`Empirical Study`*

- 🎓 [Coded Merkle Tree: Solving Data Availability Attacks in Blockchains](http://fc20.ifca.ai/preproceedings/47.pdf). Mingchao Yu (University of Southern California), Saeid Sahraei (University of Southern California), Songze Li, Salman Avestimehr (University of Southern California), Sreeram Kannan (University of Washington), Pramod Viswanath (University of Illinois at Urbana-Champaign). FC'20
    + Keyword: *`Consensus`*

- 🎓 [Decentralized Privacy-Preserving Netting Protocol on Blockchain for Payment Systems](http://fc20.ifca.ai/preproceedings/27.pdf). Shengjiao Cao (Ant Financial), Yuan Yuan (Ant Financial), Angelo De Caro (IBM Research), Karthik Nandakumar (IBM Research), Kaoutar Elkhiyaoui (IBM Research), Yanyan Hu (IBM Research). FC'20
    + Keyword: *`Economics`*

- 🎓 [The Arwen Trading Protocols](http://fc20.ifca.ai/preproceedings/23.pdf). Ethan Heilman (Boston University/Arwen), Sebastien Lipmann (Arwen), Sharon Goldberg (Boston University/Arwen). FC'20
    + Keyword: *`Economics`*

- 🎓 [SoK: A Classification Framework for Stablecoin Designs](http://fc20.ifca.ai/preproceedings/119.pdf). Amani Moin (Cornell University), Kevin Sekniqi (Cornell University), Emin Gün Sirer (Cornell University). FC'20
    + Keyword: *`System`*
    + Type: *`SoK`*

- 🎓 [Zether: Towards Privacy in a Smart Contract World](http://fc20.ifca.ai/preproceedings/158.pdf). Benedikt Bünz (Stanford University), Shashank Agrawal (Visa Research), Mahdi Zamani (Visa Research), Dan Boneh (Stanford University). FC'20
    + Keyword: *`Privacy`*, *`Smart Contract`*
    
- 🎓 [An airdrop that preserves recipient privacy](http://fc20.ifca.ai/preproceedings/54.pdf). Riad S. Wahby (Stanford), Dan Boneh (Stanford), Christopher Jeffrey (Purse.io), Joseph Poon (Lightning Network). FC'20
    + Keyword: *`Privacy`*, *`Smart Contract`*

- 🎓 [SoK: Layer-Two Blockchain Protocols](http://fc20.ifca.ai/preproceedings/150.pdf). Lewis Gudgeon (Imperial College London), Pedro Moreno-Sanchez (TU Wein), Stefanie Roos (TU Delft), Patrick McCorry (PISA Research), Arthur Gervais (Imperial College London). FC'20
    + Keyword: *`Scalability`*, *`Layer 2`*
    + Type: *`SoK`*

- 🎓 [MicroCash: Practical Concurrent Processing of Micropayments](http://fc20.ifca.ai/preproceedings/38.pdf). Ghada Almashaqbeh (Columbia), Allison Bishop (Proof of Trading and Columbia), Justin Cappos (New York University). FC'20
    + Keyword: *`Scalability`*, *`Layer 2`*

- 🎓 [LockDown: Balance Availability Attack against Lightning Network Channels](http://fc20.ifca.ai/preproceedings/73.pdf). Cristina Pérez-Solà (Universitat Oberta de Catalunya), Alejandro Ranchal-Pedrosa (University of Sydney), Jordi Herrera-Joancomarti (Universitat Autònoma de Barcelona), Guillermo Navarro-Arribas (Universitat Autònoma de Barcelona), Joaquin Garcia-Alfaro (Institut Polytechnique de Paris). FC'20
    + Keyword: *`Scalability`*, *`Layer 2`*

- 🎓 [Ride the Lightning: The Game Theory of Payment Channels](http://fc20.ifca.ai/preproceedings/134.pdf). Zeta Avarikioti (ETH Zurich), Lioba Heimbach (ETH Zurich), Yuyi Wang (ETH Zurich), Roger Wattenhofer (ETH Zurich). FC'20
    + Keyword: *`Scalability`*, *`Layer 2`*

- 🎓 [How to profit from payments channels](http://fc20.ifca.ai/preproceedings/201.pdf). Oguzhan Ersoy (Delft University of Technology), Stefanie Roos (Delft University of Technology), Zekeriya Erkin (Delft University of Technology). FC'20
    + Keyword: *`Scalability`*, *`Layer 2`*

- 🎓 [Boomerang: Redundancy Improves Latency and Throughput in Payment Channel Networks](http://fc20.ifca.ai/preproceedings/12.pdf). Joachim Neu (Stanford University), Vivek Bagaria (Stanford University), David Tse (Stanford University). FC'20
    + Keyword: *`Scalability`*, *`Layer 2`*

- 🎓 [DLSAG: Non-Interactive Refund Transactions For Interoperable Payment Channels in Monero](http://fc20.ifca.ai/preproceedings/124.pdf). Pedro Moreno-Sanchez (TU Wien), Arthur Blue, Duc Le (Purdue University), Sarang Noether (Monero Research Lab), Brandon Goodell (Monero Research Lab), Aniket Kate (Purdue University). FC'20
    + Keyword: *`Scalability`*, *`Layer 2`*

- 🎓 [Cerberus Channels: Incentivizing Watchtowers for Bitcoin](http://fc20.ifca.ai/preproceedings/132.pdf). Zeta Avarikioti (ETH Zurich), Orfeas Stefanos Thyfronitis Litos (University of Edinburgh), Roger Wattenhofer (ETH Zurich). FC'20
    + Keyword: *`Scalability`*, *`Layer 2`*

- 🎓 [RingCT 3.0 for Blockchain Confidential Transaction](http://fc20.ifca.ai/preproceedings/52.pdf): Shorter Size and Stronger Security. Tsz Hon Yuen (The University of Hong Kong), Shi-feng Sun (Monash University), Joseph K. Liu (Monash University), Man Ho Au (Hong Kong Polytechnic University), Muhammed F. Esgin (Monash University), Qingzhao Zhang (Shanghai Jiao Tong University), Dawu Gu (Shanghai Jiao Tong University). FC'20
    + Keyword: *`Privacy`*, *`RingCT`*

- 🎓 [BLAZE: Practical Lattice-Based Blind Signatures for Privacy-Preserving Applications](http://fc20.ifca.ai/preproceedings/141.pdf). Nabil Alkeilani Alkadri (Technische Universität Darmstadt), Rachid El Bansarkhani (QuantiCor Security GmbH), Johannes Buchmann (Technische Universität Darmstadt). FC'20
    + Keyword: *`Privacy`*, *`Blind Signatures`*

- 🎓 [Two-Party State Channels with Assertions](https://fc19.ifca.ai/wtsc/StateAssertions.pdf). Buckland C, McCorry P. FC '19.
    + Keyword: *`Payment Channel Networks`*

- 🎓 [Snow White: Provably Secure Proofs of Stake.](https://fc19.ifca.ai/preproceedings/141-preproceedings.pdf). Bentov I, Pass R, Shi E. FC '19.
    + Keyword: *`PoS`*

- 🎓 [Proof-of-Work Sidechains](https://eprint.iacr.org/2018/1048.pdf). Kiayias A, Zindros D. FC WTSC'19.
    + Keyword: *`Sidechains`*, *`Scalability`*

- 🎓 [Hostile blockchain takeovers](https://fc18.ifca.ai/bitcoin/papers/bitcoin18-final17.pdf). Bonneau J. FC '18.
    + Keyword: *`Attacks`*

- 🎓 [Teechan: Payment Channels Using Trusted Execution Environments](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final21.pdf). Lind J, Eyal I, Pietzuch P, Sirer EG. FC BITCOIN '17.
    + Keyword: *`Payment Channel Networks`*

- 🎓 [A Proof-of-Stake protocol for consensus on Bitcoin subchains](http://eprint.iacr.org/2017/417.pdf). Bartoletti M, Lande S, & Podda A S. FC'17.
    + Keyword: *`PoS`*

- 🎓 [A Smart Contract for Boardroom Voting with Maximum Voter Privacy](http://fc17.ifca.ai/preproceedings/paper_80.pdf). McCorry P, Shahandashti SF, Hao F. FC'17.
    + Keyword: *`Smart Contracts`*

- 🎓 [Constant-deposit multiparty lotteries on Bitcoin](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final39.pdf). Bartoletti M, Zunino R. FC'17.
    + Keyword: *`Smart Contracts`*

- 🎓 [PieceWork: Generalized Outsourcing Control for Proofs of Work](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final24.pdf). Daian P, Eyal I, Juels A, Sirer EG. FC'17.
    + Keyword: *`Economic`*, *`PoW`*

- 🎓 [OpenTimestamps: Securing Software Updates using the Bitcoin Blockchain Financial Cryptography and Data Security](https://github.com/opentimestamps/). Todd P, Halpin H. (FC Poster'17)
    + Keyword: *`Application`*

+ 🎓 [A Proof-of-Stake protocol for consensus on Bitcoin subchains](http://eprint.iacr.org/2017/417.pdf). Bartoletti M, Lande S, & Podda A S. FC'17.
    + Keyword: *`Consensus`*, *`PoW`*

- 🎓 [Improving Authenticated Dynamic Dictionaries, with Applications to Cryptocurrencies](http://fc17.ifca.ai/preproceedings/paper_34.pdf). Reyzin L, Meshkov D, Chepurnoy A, Ivanov S. FC'17.
    + Keyword: *`Scalability`*, *`Sidechains`*

- 🎓 [Service-Oriented Sharding for Blockchains](http://fc17.ifca.ai/preproceedings/paper_73.pdf). Gencer AE, Van Renesse R, Sirer EG. FC'17.
    + Keyword: *`Scalability`*, *`Sharding`*

- 🎓 [Could Network Information Facilitate Address Clustering in Bitcoin?](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final11.pdf). Neudecker T, Hartenstein H. FC'17.
    + Keyword: *`Privacy`*

- 🎓 [Exchange Pattern Mining in the Bitcoin Transaction Directed Hypergraph](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final17.pdf). Ranshous S, Joslyn A, Kreyling S, Nowak K, Samatova N, West C, Winters C. FC'17.
    + Keyword: *`Privacy`*

- 🎓 [Confidential Assets](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final41.pdf). Poelstra A, Back A, Friedenbach M, Maxwell G, Wuille P. FC'17.
    + Keyword: *`Privacy`*

- 🎓 [Mixing Confidential Transactions: Comprehensive Transaction Privacy for Bitcoin](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final6.pdf). Ruffing T, Moreno-Sanchez P. FC'17.
    + Keyword: *`Privacy`*

- 🎓 [Switch Commitments: A Safety Switch for Confidential Transactions](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final23.pdf). Ruffing T, Malavolta G. FC'17.
    + Keyword: *`Privacy`*

- 🎓 [Escrow protocols for cryptocurrencies: How to buy physical goods using Bitcoin](http://www.jbonneau.com/doc/GBGN17-FC-physical_escrow.pdf). Goldfeder S, Bonneau J, Gennaro R, Narayanan A. FC '17.
    + Keyword: *`Marketplaces`*

- 🎓 [Trust Is Risk: A Decentralized Financial Trust Platform](http://fc17.ifca.ai/preproceedings/paper_37.pdf). Thyfronitis Litos OS, Zindros D. FC '17.
    + Keyword: *`Marketplaces`*

- 🎓 [Incentivizing Blockchain Forks via Whale Transactions](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final26.pdf). Liao K, Katz J. FC '17.
    + Keyword: *`Economics`*

- 🎓 [Smart Contracts Make Bitcoin Mining Pools Vulnerable](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final38.pdf). Velner Y, Teutsch J, Luu L. FC '17.
    + Keyword: *`Economics`*

- 🎓 [Mixing Coins of Different Quality: A Game-Theoretic Approach](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final40.pdf). Abramova S, Schöttle P, Böhme R. FC '17.
    + Keyword: *`Economics`*

- 🎓 [Decentralized Prediction Market without Arbiters](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final29.pdf). Bentov I, Mizrahi A, Rosenfeld M. FC '17.
    + Keyword: *`Economics`*

- 🎓 [An analysis of Bitcoin OP_RETURN metadata](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final32.pdf). Bartoletti M, Pompianu L. FC'17.
    + Keyword: *`Survey`*, *`Sociological`*, *`Anthropological`*

- 🎓 [Enhancing Bitcoin Transactions with Covenants](http://fc17.ifca.ai/bitcoin/papers/bitcoin17-final28.pdf). O’Connor R, Piekarska M. FC'17.
    + Keyword: *`Wallets`*

- 🎓 [Bitcoin Covenants](http://fc16.ifca.ai/bitcoin/papers/MES16.pdf). Möser M, Eyal I, Sirer EG. FC'16.
    + Keyword: *`Wallets`*

- 🎓 [The Other Side of the Coin: User Experiences with Bitcoin Security and Privacy](http://fc16.ifca.ai/preproceedings/33_Krombholz.pdf). Krombholz K, Judmayer A, Gusenbauer M, Weippl E. FC'16.
    + Keyword: *`Survey`*, *`Sociological`*, *`Anthropological`*

- 🎓 [Why buy when you can rent? Bribery attacks on Bitcoin-style consensus](http://fc16.ifca.ai/bitcoin/papers/Bon16b.pdf). Bonneau J. FC '16.
    + Keyword: *`Economics`*

- 🎓 [Incentive Compatibility of Bitcoin Mining Pool Reward Functions](http://fc16.ifca.ai/preproceedings/28_Schrijvers.pdf). Schrijvers O, Bonneau J, Boneh D, Roughgarden T. FC '16.
    + Keyword: *`Economics`*

- 🎓 [When cryptocurrencies mine their own business](http://fc16.ifca.ai/preproceedings/29_Teutsch.pdf). Teutsch J, Jain S, Saxena P. FC '16.
    + Keyword: *`Economics`*

- 🎓 [Optimal Selfish Mining Strategies in Bitcoin](http://fc16.ifca.ai/preproceedings/30_Sapirshtein.pdf). Sapirshtein A, Sompolinsky Y, Zohar A. FC'16.
    + Keyword: *`Attacks`*

- 🎓 [Refund attacks on Bitcoin’s Payment Protocol](http://fc16.ifca.ai/preproceedings/34_McCorry.pdf). McCorry P, Shahandashti S, Hao F. FC'16.
    + Keyword: *`Attacks`*

- 🎓 [Cryptocurrencies without Proof of Work](http://fc16.ifca.ai/bitcoin/papers/BGM16.pdf). Bentov I, Gabizon A, Mizrahi A. FC'16.
    + Keyword: *`PoS`*

- 🎓 [Blindly Signed Contracts: Anonymous On-Blockchain and Off-Blockchain Bitcoin Transactions](http://fc16.ifca.ai/bitcoin/papers/HBG16.pdf). Heilman E, Baldimtsi F, Goldberg S. FC'16.
    + Keyword: *`Privacy`*

- 🎓 [Proofs of Proofs of Work with Sublinear Complexity](http://fc16.ifca.ai/bitcoin/papers/KLS16.pdf). Kiayias A, Lamprou N, Stouka AP. FC'16.
    + Keyword: *`Scalability`*

- 🎓 [On Scaling Decentralized Blockchains](http://fc16.ifca.ai/bitcoin/papers/CDE+16.pdf). Croman K, Decker C, Eyal I, Gencer AE, Juels A, Kosba A, Miller A, Saxena P, Shi E, Sirer EG, Song D. FC'16.
    + Keyword: *`Scalability`*

- 🎓 [Stressing Out: Bitcoin “Stress Testing”](http://fc16.ifca.ai/bitcoin/papers/BHMW16.pdf). Baqer K, Yuxing Huang D, McCoy D, Weaver N. FC'16.
    + Keyword: *`Network`*

- 🎓 [Step by Step Towards Creating a Safe Smart Contract: Lessons and Insights from a Cryptocurrency Lab](http://fc16.ifca.ai/bitcoin/papers/DAKMS16.pdf). Delmolino K, Arnett M, Kosba A, Miller A, Shi E. FC'16.
    + Keyword: *`Smart Contracts`*

- 🎓 [EthIKS: Using Ethereum to audit a CONIKS key transparency log](http://fc16.ifca.ai/bitcoin/papers/Bon16a.pdf). Bonneau J. FC'16.
    + Keyword: *`Smart Contracts`*

- 🎓 [Automated Verification of Electrum Wallet](http://fc16.ifca.ai/bitcoin/papers/TVR16.pdf). Turuani M, Voegtlin T, Rusinowitch M. FC'16.
    + Keyword: *`Formal Methods`*

+ 🎓 [Cryptocurrencies without Proof of Work](http://fc16.ifca.ai/bitcoin/papers/BGM16.pdf). Bentov I, Gabizon A, Mizrahi A. FC'16.
    + Keyword: *`Consensus`*

+ 🎓 [Optimal Selfish Mining Strategies in Bitcoin](http://fc16.ifca.ai/preproceedings/30_Sapirshtein.pdf). Sapirshtein A, Sompolinsky Y, Zohar A. FC'16.
    + Keyword: *`Economic-PoW`*

- 🎓 [Hierarchical deterministic Bitcoin wallets that tolerate key leakage](http://fc15.ifca.ai/preproceedings/paper_15.pdf). Gutoski G, Stebila D. FC'15.
    + Keyword: *`Wallets`*

- 🎓 [ZombieCoin: Powering Next-Generation Botnets with Bitcoin](http://fc15.ifca.ai/preproceedings/bitcoin/paper_15.pdf). Ali ST, McCorry P, Lee PH, Hao F. FC'15.
    + Keyword: *`Crime`*

- 🎓 [The Bitcoin Market Potential Index](http://fc15.ifca.ai/preproceedings/bitcoin/paper_14.pdf). Hileman G. FC'15.
    + Keyword: *`Survey`*, *`Sociological`*, *`Anthropological`*

- 🎓 [Cryptographic Currencies from a Tech-Policy Perspective: Policy Issues and Technical Direction](http://fc15.ifca.ai/preproceedings/bitcoin/paper_16.pdf). McReynolds E, Lerner A, Scott W, Roesner F, Kohno T. FC'15.
    + Keyword: *`Survey`*, *`Sociological`*, *`Anthropological`*

- 🎓 [On the Malleability of Bitcoin Transactions](http://fc15.ifca.ai/preproceedings/bitcoin/paper_9.pdf). Andrychowicz M, Dziembowski S, Malinowski D, Mazurek Ł. FC'15.

- 🎓 [Cuckoo Cycle: a memory bound graph-theoretic proof-of-work](http://fc15.ifca.ai/preproceedings/bitcoin/paper_12.pdf). Tromp J. FC'15.
    + Keyword: *`Economic`*, *`PoW`*

- 🎓 [Secure High-Rate Transaction Processing in Bitcoin](https://fc15.ifca.ai/preproceedings/paper_30.pdf). Sompolinsky Y, Zohar A. FC'15.
    + Keyword: *`Mining`*, **GHOST**

- 🎓 [Inclusive Block Chain Protocols](http://fc15.ifca.ai/preproceedings/paper_101.pdf). Lewenberg Y, Sompolinsky Y, Zohar A. FC '15.
    + Keyword: *`Mining`*, *`ChainStructure`*

+ 🎓 [Secure High-Rate Transaction Processing in Bitcoin](http://www.cs.huji.ac.il/~avivz/pubs/15/btc_ghost_full.pdf). Sompolinsky Y, Zohar A. FC'15.
    + Keyword: *`Consensus`*, *`PoW`*

- 🎓 [Blindcoin Blinded, Accountable Mixes for Bitcoin](http://fc15.ifca.ai/preproceedings/bitcoin/paper_3.pdf). Valenta L, Rowan B. FC'15.
    + Keyword: *`Privacy`*

- 🎓 [Issues in Designing a Bitcoin-Like Community Currency](http://fc15.ifca.ai/preproceedings/bitcoin/paper_2.pdf). Vandervort D, Gaucas D, St Jacques R. FC'15.
    + Keyword: *`Survey`*, *`Sociological`*, *`Anthropological`*

- 🎓 [There’s No Free Lunch, Even Using Bitcoin: Tracking the Popularity and Profits of Virtual Currency Scams](http://fc15.ifca.ai/preproceedings/paper_75.pdf). Vasek M, Moore T. FC'15.
    + Keyword: *`Marketplaces`*

- 🎓 [When Bitcoin Mining Pools Run Dry A Game-Theoretic Analysis of the Long-Term Impact of Attacks Between Mining Pools](http://fc15.ifca.ai/preproceedings/bitcoin/paper_13.pdf). Laszka A, Johnson B, Grossklags J. FC '15.
    + Keyword: *`Economics`*

- 🎓 [Trends, Tips, Tolls: A Longitudinal Study of Bitcoin Transaction Fees](http://fc15.ifca.ai/preproceedings/bitcoin/paper_8.pdf). Möser M, Böhme R. FC '15.
    + Keyword: *`Economics`*

- 🎓 [Game-Theoretic Analysis of DDoS Attacks Against Bitcoin Mining Pools](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_16.pdf). Johnson B, Laszka A, Grossklags J, Vasek M, Moore T. FC '14.
    + Keyword: *`Economics`*

- 🎓 [Challenges and Opportunities Associated with a Bitcoin-based Transaction Rating System](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_5.pdf). Vandervort D. FC'14.
    + Keyword: *`Marketplaces`*

- 🎓 [Majority Is Not Enough: Bitcoin Mining Is Vulnerable](https://arxiv.org/pdf/1311.0243). Eyal I, Sirer EG. FC '14.
    + Keyword: *`Attacks`*, **"Selfish Mining"**

- 🎓 [Increasing Anonymity in Bitcoin](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_19.pdf). Saxena A, Misra J, Dhar A. FC '14.
    + Keyword: *`Privacy`*

- 🎓 [How Did Dread Pirate Roberts Acquire and Protect His Bitcoin Wealth?](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_2.pdf). Ron D, Shamir A. FC '14.
    + Keyword: *`Privacy`*

- 🎓 [The Bitcoin P2P network](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_3.pdf). Donet Donet JA, Perez-Sola C, Herrera-Joancomart J. FC '14.
    + Keyword: *`Network`*

- 🎓 [Empirical Analysis of Denial-of-Service Attacks in the Bitcoin Ecosystem](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_17.pdf). Vasek M, Thornton M, Moore T. FC '14.
    + Keyword: *`Network`*

- 🎓 [Mixcoin: Anonymity for bitcoin with accountable mixes](https://eprint.iacr.org/2014/077.pdf). Bonneau J, Narayanan A, Miller A, Clark J, Kroll JA, Felten EW. FC'14.
    + Keyword: *`Privacy`*

- 🎓 [Rational Zero: Economic Security for Zerocoin with Everlasting Anonymity](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_12.pdf). Garman C, Green M, Miers I, Rubin A. FC'14.
    + Keyword: *`Privacy`*

- 🎓 [Fair Two-Party Computations via Bitcoin Deposits](http://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_10.pdf). Andrychowicz M, Dziembowski S, Malinowski D, Mazurek Ł. FC'14.
    + Keyword: *`Smart Contracts`*

+ 🎓 [Majority Is Not Enough: Bitcoin Mining Is Vulnerable](https://arxiv.org/pdf/1311.0243). Eyal I, Sirer EG. FC'14.
    + Keyword: *`Economic`*, *`PoW`*

- 🎓 [Quantitative analysis of the full bitcoin transaction graph](https://eprint.iacr.org/2012/584.pdf). Ron D, Shamir A. FC '13.
    + Keyword: *`Privacy`*

+ 🎓 [Commitcoin: Carbon dating commitments with bitcoin](https://eprint.iacr.org/2011/677.pdf). Clark J, Essex A. FC'12.
    + Keyword: *`Application`*



## Others

- [ShareLock: Mixing for Cryptocurrencies from Multiparty ECDSA](https://eprint.iacr.org/2019/563.pdf). Omer Shlomovits and István András Seres. IACR'19.
    + Keyword: *`Privacy`*, *`Threshold Signature`*, *`Mixing`*

- [SoK: A Taxonomy for Layer-2 Scalability Related Protocols for Cryptocurrencies](https://eprint.iacr.org/2019/352.pdf). Jourenko M, Kurazumi K, Larangeira M, Tanaka K. '19.
    + Keyword: *`Payment Channel Networks`*, **SoK**

- [SoK: Off The Chain Transactions](https://eprint.iacr.org/2019/360.pdf). Gudgeon L, Moreno-Sanchez P, Roos S, McCorry P, Gervais A. '19.
    + Keyword: *`Payment Channel Networks`*

- [Sprites and State Channels: Payment Channel Networks that Go Faster than Lightning](https://arxiv.org/pdf/1702.05812.pdf) Miller A, Bentov I, Kumaresan R, Cordi C, McCorry P. FC'19.
    + Keyword: *`Payment Channel Networks`*

- [Nitro Protocol](https://eprint.iacr.org/2019/219.pdf). Close T. '19.
    + Keyword: *`Payment Channel Networks`*

- [NOCUST – A Non-Custodial 2nd-Layer Financial Intermediary](https://liquidity.network/NOCUST_Liquidity_Network_Paper.pdf). Khalil R, Gervais, A. ICAR'18.
    + Keyword: *`Payment Channel Networks`*

- [Counterfactual: Generalized state channels](https://l4.ventures/papers/statechannels.pdf). Coleman J, Horne L, Xuanji L. '18.
    + Keyword: *`Payment Channel Networks`*

- [Flare: An Approach to Routing in Lightning Network](https://bitfury.com/content/downloads/whitepaper_flare_an_approach_to_routing_in_lightning_network_7_7_2016.pdf). Prihodko P, Zhigulin S, Sahno M, Ostrovskiy A, Osuntokyn O. '16.
    + Keyword: *`Payment Channel Networks`*

- [The bitcoin lightning network: Scalable off-chain instant payments](https://www.weusecoins.com/assets/pdf/library/Lightning%20Network%20Whitepaper.pdf). Poon J, Dryja T. '15.
    + Keyword: *`Payment Channel Networks`*

- [Reaching The Ground With Lightning](https://github.com/ElementsProject/lightning/raw/master/doc/deployable-lightning.pdf). Russell R. '15.
    + Keyword: *`Payment Channel Networks`*, **Deployable Lightning**

- [FlyClient: Super-Light Clients for Cryptocurrencies](https://eprint.iacr.org/2019/226.pdf). B Bünz, L Kiffer, L Luu, M Zamani. IACR'19.
    + Keyword: *`Scalability`*

- [A Scalable BlockDAG protocol](https://eprint.iacr.org/2018/104.pdf). Sompolinsky Y, Zohar A. '18.
    + Keyword: *`Consensus`*, *`DAG`*, **PHANTOM**

- [Snowflake to Avalanche: A Novel Metastable Consensus Protocol Family for Cryptocurrencies](https://ipfs.io/ipfs/QmUy4jh5mGNZvLkjies1RWM4YuvJh5o2FYopNPVYwrRVGV). Team Rocket. '18.
    + Keyword: *`Consensus`*, *`DAG`*

- [Scaling Nakamoto Consensus to Thousands of Transactions per Second](https://arxiv.org/pdf/1805.03870.pdf). Li C, Li P, Zhou D, Xu W, Long F, Chi-Chih Yao A. '18.
    + Keyword: *`Consensus`*, *`DAG`*

- [PolyShard: Coded Sharding Achieves Linearly Scaling Efficiency and Security Simultaneously](https://arxiv.org/pdf/1809.10361.pdf). Li S, Yu M, Avestimehr S, Kannan S, Viswanath P. CoRR'18.
    + Keyword: *`Scalability`*, *`Sharding`*

- [Low-Resource Eclipse Attacks on Ethereum’s Peer-to-Peer Network](https://eprint.iacr.org/2018/236.pdf). Marcus Y, Heilman E, Goldberg S. IACR'18.
    + Keyword: *`Attacks`*
    
<!-- - [Scalable, transparent, and post-quantum secure computational integrity](https://eprint.iacr.org/2018/046.pdf). Ben-Sasson E, Bentov I, Horesh Y, Riabzev M. IACR'18.
    + Keyword: *`Cryptography`* -->

- 🎓[A systematic literature review of blockchain-based applications: Current status, classification and open issues](https://www.researchgate.net/profile/Thomas_Dasaklis/publication/329136952_A_systematic_literature_review_of_blockchain-based_applications_Current_status_classification_and_open_issues/links/5c4cab1ba6fdccd6b5cb7ea1/A-systematic-literature-review-of-blockchain-based-applications-Current-status-classification-and-open-issues.pdf). Casino F, Dasaklis T, Patsakis C. T&I'18.
    + Keyword: *`Applications`*
    + Type: *`Review`*

- [Storj A Peer-to-Peer Cloud Storage Network](https://storj.io/storjv3.pdf). Shawn W., Tome B., Josh B., James P., Gordon H., Patrick G., Philip H., Chris P. '18
    + Keyword: *`Applications`*, *`Storage`*

- [Blockstack Technical Whitepaper](https://blockstack.org/whitepaper.pdf). Muneeb A., Ryan S., Jude N, Michael F. '17
    + Keyword: *`Applications`*

- [BigchainDB: A Scalable Blockchain Database](https://www.bigchaindb.com/whitepaper/bigchaindb-whitepaper.pdf). McConaghy T, Marques R, Müller A, De Jonghe D, McConaghy T, McMullen G, Henderson R, Bellemare S, Granzotto A. '17
    + Keyword: *`Applications`*

- [Non-Interactive Proofs of Proof-of-Work](https://eprint.iacr.org/2017/963.pdf). Kiayias A, Miller A, Zindros D. IACR'17.
    + Keyword: *`Scalability`*

- [Bitcoin's Academic Pedigree](http://delivery.acm.org/10.1145/3140000/3132259/p36-narayanan.pdf?ip=88.197.32.177&id=3132259&acc=OPEN&key=5641A0C343C36AC1%2E4ABAF8470B13FB25%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1541082825_ead879dbf5b3644bfed2a09e11b47834). Narayanan A, Clark J. ACM Queue '17.
    + Keyword: *`SoK`*

- 🎓 [On Trees, Chains and Fast Transactions in the Blockchain](https://eprint.iacr.org/2016/545.pdf). Kiayias A, Panagiotakos G. LATINCRYPT '17.
    + Keyword: *`Consensus`*

- 🎓 [Transferable Anonymous Payments via TumbleBit in Permissioned Blockchains](http://ceur-ws.org/Vol-2334/DLTpaper5.pdf). Ferretti C, Leporati A, Mariot L, Nizzardo L. DLT '19.
    + Keyword: *`Privacy`*

- "MoneroLink": [An Empirical Analysis of Linkability in the Monero Blockchain](http://monerolink.com/monerolink.pdf). Miller A, Möser M, Lee K, Narayanan A. '17.
    + Keyword: *`Privacy`*

- 🎓 [ALGORAND: The Efficient and Democratic Ledger](https://arxiv.org/pdf/1607.01341.pdf). Micali S. CoRR'16.
    + Keyword: *`PoS`*

- [Bootstrapping the Blockchain - Directly](https://eprint.iacr.org/2016/991.pdf). Garay JA, Kiayias A, Leonardos N, Panagiotakos G. IACR'16.
    + Keyword: *`Mining`*

- [Blockchain-Free Cryptocurrencies: A Framework for Truly Decentralised Fast Transactions](https://eprint.iacr.org/2016/871.pdf) Boyen X, Carr C, Haines T. '16.
    + Keyword: *`Consensus`*, *`DAG`*

- [SPECTRE: A Fast and Scalable Cryptocurrency Protocol](https://eprint.iacr.org/2016/1159.pdf). Sompolinsky Y, Lewenberg Y, Zohar A. '16.
    + Keyword: *`Consensus`*, *`DAG`*

- [Byteball: A Decentralized System for Storage and Transfer of Value](https://byteball.org/Byteball.pdf) Churyumov A. '16.
    + Keyword: *`Consensus`*, *`DAG`*

- [DAGcoin Whitepaper](https://dagcoin.org/whitepaper.pdf) Ribero Y, Raissar D. '15.
    + Keyword: *`Consensus`*, *`DAG`*

- [Speed-Security Tradeoffs in Blockchain Protocols](https://pdfs.semanticscholar.org/7de8/ff6bb85a020aa96f62dd86233fe9416550f3.pdf). Kiayias A, Panagiotakos G. IACR'15.
    + Keyword: *`Mining`*

- 🎓 [CoinParty: Secure Multi-Party Mixing of Bitcoins](https://www.martinhenze.de/wp-content/papercite-data/pdf/zgh+15.pdf). Ziegeldorf, J.H., Grossmann, F., Henze, M., Inden, N. and Wehrle, K. CODASPY '15.
    + Keyword: *`Privacy`*

- [Data-Driven De-Anonymization in Bitcoin](http://e-collection.library.ethz.ch/eserv/eth:48205/eth-48205-01.pdf). Nick J. Diss. ETH-Zürich, '15.
    + Keyword: *`Privacy`*, *`Attacks`*
    
- [Trust in decentralized anonymous marketplaces](http://dspace.lib.ntua.gr/bitstream/handle/123456789/43147/pseudonymous-trust-2.pdf?sequence=1). Zindros D. '15.
    + Keyword: *`Marketplaces`*

- [The stellar consensus protocol: A federated model for internet-level consensus](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.696.93&amp=&rep=rep1&amp=&type=pdf). Mazières D. '15.
    + Keyword: *`Marketplaces`*

- 🎓 [A Fast and Scalable Payment Network with Bitcoin Duplex Micropayment Channels](https://pdfs.semanticscholar.org/c8d2/b0c1f9b1ca739c340e9dc4a2ff71b5bfbb2e.pdf). Decker C, Wattenhofer R. SSS'15.
    + Keyword: *`Payment Channel Networks`*
    
<!-- - [On Bitcoin as a public randomness source](https://pdfs.semanticscholar.org/ebae/9c7d91ea8b6a987642040a2142cc5ea67f7d.pdf). Bonneau J, Clark J, Goldfeder S. IACR'15.
    + Keyword: *`Cryptography`* -->

- [Decentralized trusted timestamping using the crypto currency bitcoin](https://arxiv.org/pdf/1502.04015.pdf). Gipp B., Meuschke N., Gernandt A. CoRR'15
    + Keyword: *`Applications`*

- [IPFS - Content Addressed, Versioned, P2P File System](https://github.com/ipfs/papers/raw/master/ipfs-cap2pfs/ipfs-p2p-file-system.pdf). Benet J. CoRR'14
    + Keyword: *`Applications`*, **IPFS**

- [A next-generation smart contract and decentralized application platform](https://www.weusecoins.com/assets/pdf/library/Ethereum_white_paper-a_next_generation_smart_contract_and_decentralized_application_platform-vitalik-buterin.pdf). Vitalik Buterin. '14.
    + Keyword: *`Smart Contracts`*, **Ethereum**

- [Ethereum: A secure decentralised generalised transaction ledger](http://gavwood.com/paper.pdf). Wood G. '14.
    + Keyword: *`Smart Contracts`*, **Ethereum**

- [Distributed Cryptography Based on the Proofs of Work](https://eprint.iacr.org/2014/796.pdf). Andrychowicz M, and Dziembowski S. IACR'14.
    + Keyword: *`Consensus`*, *`PoW`*
    
- [Anonymous Byzantine Consensus from Moderately-Hard Puzzles: A Model for Bitcoin](https://socrates1024.s3.amazonaws.com/consensus.pdf). Miller A, LaViola JJ Jr. '14.
    + Keyword: *`Consensus`*

- [Enabling Blockchain Innovations with Pegged Sidechains](https://blockstream.com/sidechains.pdf). Back A, Corallo M, Dashjr L, Friedenbach M, Maxwell G, Miller A, Poelstra A, Timón J, Wuille P. '14.
    + Keyword: *`Scalability`*, *`Sidechains`*

- [The Ripple protocol consensus algorithm](https://ripple.com/files/ripple_consensus_whitepaper.pdf). Schwartz D, Youngs N, Britto A. '14.
    + Keyword: *`Marketplaces`*

- [Information Propagation in the Bitcoin Network](http://www.tik.ee.ethz.ch/file/49318d3f56c1d525aabf7fda78b23fc0/P2P2013_041.pdf). Decker C., Wattenhofer R. P2P'13.
    + Keyword: *`Network`*

- [CryptoNote v2.0](https://cryptonote.org/whitepaper.pdf). Saberhagen N. '13
    + Keyword: *`Privacy`*, **Monero**

- **[Theoretical Bitcoin Attacks with less than Half of the Computational Power](https://arxiv.org/pdf/1312.7013.pdf)**. Bahack L. CoRR'13.
    + Keyword: *`Attacks`*

- 🎓 [The Economics of Bitcoin Mining or Bitcoin in the Presence of Adversaries](https://www.econinfosec.org/archive/weis2013/papers/KrollDaveyFeltenWEIS2013.pdf). Kroll J, Davey I, Felten E. WEIS '13.
    + Keyword: *`Economics`*

- 🎓 **[On Bitcoin and Red Balloons](https://arxiv.org/pdf/1111.2626.pdf)**. Babaioff M, Dobzinski S, Oren S, Zohar A. EC'12.
    + Keyword: *`Economics`*

- **[Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.com/bitcoin.pdf)**. Nakamoto S. '08.
    + Keyword: *`SoK`*, **Bitcoin**

- [Money as IOUs in social trust networks & a proposal for a decentralized currency network protocol](http://library.uniteddiversity.coop/Money_and_Economics/decentralizedcurrency.pdf). Fugger R. '04.
    + Keyword: *`Marketplaces`*

- [Hashcash - A Denial of Service Counter-Measure](http://www.hashcash.org/papers/hashcash.pdf). Back A. '02.
    + Keyword: *`PoW`*

- 🎓 [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf) Lamport L. '00, ACM SIGACT News '01.
    + Keyword: *`Consensus`*

- 🎓 [Accountability in a Permissioned Blockchain:Formal Analysis of Hyperledger Fabric](https://eprint.iacr.org/2020/386.pdf). Ralf Küsters, Daniel Rausch, and Mike Simon (University of Stuttgart). EuroS&P'20
    + Keyword: *`Formal Methods`*

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)


This list is released into the public domain.
