# Storage System Paper List
In this repo, it records some paper related to storage system, including **Data Deduplication** (aka, dedup), **Erasure Coding** (aka, EC), general **Distributed Storage System** (aka, DSS) and other related topics (i.e., Network Security.....), updating from time to time~

[TOC]

## A. Data Deduplication

### Summary
1. *99 Deduplication Problems*----HotStorage'16 ([link](https://pdfs.semanticscholar.org/bd54/6dda50541489ff23fbc1e154dea50d911a43.pdf)) ([summary](https://yzr95924.github.io/paper_summary/99DeduplicationProblem-HotStorage'16.html))
2. *A Comprehensive Study of the Past, Present, and Future on Data Deduplication*----Proceedings of the IEEE'16 ([link](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7529062))
3. *A Survey of Secure Data Deduplication Schemes for Cloud Storage Systems*----ACM Computing Surveys'17 ([link](https://dl.acm.org/citation.cfm?id=3017428))
4. *A Survey of Classification of Storage Deduplication Systems*----ACM Computing Surveys'14 ([link](https://dl.acm.org/citation.cfm?id=2611778))
5. *Understanding Data Deduplication Ratios*----SNIA'08 ([link](https://www.snia.org/sites/default/files/Understanding_Data_Deduplication_Ratios-20080718.pdf))

### Workload Analysis
1. *Characteristics of Backup Workloads in Production Systems*----FAST'12 ([link](http://www.usenix.net/legacy/events/fast12/tech/full_papers/Wallace2-9-12.pdf))
2. *A Study of Practical Deduplication*----FAST'11 ([link](https://www.usenix.org/legacy/event/fast11/tech/full_papers/Meyer.pdf)) [summary](https://yzr95924.github.io/paper_summary/PracticalDedup-FAST'11.html)
3. *A Long-Term User-Centric Analysis of Deduplication Patterns*----MSST'16 ([link](https://www.fsl.cs.sunysb.edu/docs/msst16dedup-study/data-set-analysis.pdf))
4. *Capacity Forecasting in a Backup Storage Environment*----LISA'11 ([link](https://www.usenix.org/legacy/events/lisa11/tech/full_papers/Chamness.pdf)) [summary](https://yzr95924.github.io/paper_summary/CapacityForecasting-LISA'11.html)
5. *Generating Realistic Datasets for Deduplication Analysis* ---- ATC'12 ([link](https://www.usenix.org/conference/atc12/technical-sessions/presentation/tarasov)) 


### Deduplication System Design
1. *Avoiding the Disk Bottleneck in the Data Domain Deduplication File System*----FAST'08 ([link](https://www.usenix.org/legacy/event/fast08/tech/full_papers/zhu/zhu.pdf)) [summary](https://yzr95924.github.io/paper_summary/DiskBottleneck-FAST'08.html)
2. *dedupv1: Improving Deduplication Throughput using Solid State Drives (SSD)*----MSST'10 ([link](https://ieeexplore.ieee.org/document/5496992)) [summary](https://yzr95924.github.io/paper_summary/dedupv1-MSST'10.html)
3. *Extreme Binning: Scalable, Parallel Deduplication for Chunk-based File Backup*----MASCOTS'09 ([link](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.467.1985&rep=rep1&type=pdf)) [summary](https://yzr95924.github.io/paper_summary/ExtremeBining-MASCOTS'09.html)
4. *Sparse Indexing: Large Scale, Inline Deduplication Using Sampling and Locality*----FAST'09 ([link](https://pdfs.semanticscholar.org/6585/e111960d2b170bb6677865b73b6d1f27d71a.pdf)) [summary](yzr95924.github.io/paper_summary/SparseIndex-FAST'09.html)
5. *Building a High-performance Deduplication System*----USENIX ATC'11([link](https://www.usenix.org/legacy/events/atc11/tech/final_files/GuoEfstathopoulos.pdf)) 
6. *Primary Data Deduplication - Large Scale Study and System Design*----USENIX ATC'12
7. *Storage Efficiency Opportunities and Analysis for Video Repositories*----HotStorage'15
8. *Venti: A New Approach to Archival Storage*----FAST'02 ([link](https://www.usenix.org/legacy/publications/library/proceedings/fast02/quinlan/quinlan.pdf))
9. *ChunkStash: Speeding up Inline Storage Deduplication using Flash Memory*----USENIX ATC'10 ([link](https://www.usenix.org/legacy/events/atc10/tech/full_papers/Debnath.pdf)) 
10. *Data Domain Cloud Tier: Backup here, Backup there, Deduplicated Everywhere!*----USENIX ATC'19 ([link](https://www.usenix.org/system/files/atc19-duggal.pdf))
11. *SmartDedup: Optimizing Deduplication for Resource-constrained Devices*----USENIX ATC'19 ([link](https://www.usenix.org/system/files/atc19-yang-qirui.pdf))
12. *Probabilistic Deduplication for Cluster-Based Storage Systems*----SoCC'12 ([link](https://dl.acm.org/citation.cfm?id=2391246))
13. Can't We All Get Along? Redesigning Protection Storage for Modern Workloads----USENIX ATC'18 ([link](https://www.usenix.org/system/files/conference/atc18/atc18-allu.pdf)) [summary](https://yzr95924.github.io/paper_summary/Redesigning-ATC'18.html)
14. *Deduplication in SSDs: Model and quantitative analysis*----MSST'12 ([link](https://ieeexplore.ieee.org/document/6232379))
15. *SiLo: A Similarity-Locality based Near-Exact Deduplication Scheme withLow RAM Overhead and High Throughput* ---- ATC'11 ([link](https://www.usenix.org/legacy/events/atc11/tech/final_files/Xia.pdf))
16. *Design Tradeoffs for Data Deduplication Performance in Backup Workloads* ----FAST'15 ([link](https://www.usenix.org/conference/fast15/technical-sessions/presentation/fu)) 
17. *The Dilemma between Deduplication and Locality: Can Both be Achieved?* ---- FAST'21 ([link](https://www.usenix.org/conference/fast21/presentation/zou))
18. *Remap-SSD: Safely and Efficiently Exploiting SSD Address Remapping to Eliminate Duplicate Writes* ----FAST'21 ([link](https://www.usenix.org/conference/fast21/presentation/zhou))

### Restore Performance
1. *RevDedup: A Reverse Deduplication Storage System Optimized for Reads to Latest Backups*----APSys'13 ([link](http://adslab.cse.cuhk.edu.hk/pubs/apsys13.pdf)) [summary](https://yzr95924.github.io/paper_summary/RevDedup-APSys'13.html)
2. *ALACC: Accelerating Restore Performance of Data Deduplication Systems Using Adaptive Look-Ahead Window Assisted Chunk Caching*----FAST'18 ([link](https://www.usenix.org/system/files/conference/fast18/fast18-cao.pdf)) [summary](https://yzr95924.github.io/paper_summary/ALACC-FAST'18.html)
3. *Reducing Impact of Data Fragmentation Caused by In-line Deduplication*----SYSTOR'12 ([link](http://9livesdata.com/wp-content/uploads/2017/04/AsPresentedOnSYSTOR-1.pdf))
4. *Assuring Demanded Read Performance of Data Deduplication Storage with Backup Datasets*----MASCOTS'12
5. *Accelerating Restore and Garbage Collection in Deduplication-based Backup System via Exploiting Historical Information*----USENIX ATC'14 ([link](https://pdfs.semanticscholar.org/9b8d/a007a6801c9f96784dc7bc839794cb0db3ad.pdf))
6. *Sliding Look-Back Window Assisted Data Chunk Rewriting for Improving Deduplication Restore Performance*----FAST'19
7. *Improving Restore Speed for Backup Systems that Use Inline Chunk-Based Deduplication*---FAST'13 ([link](https://www.usenix.org/system/files/conference/fast13/fast13-final124.pdf)) [summary](https://yzr95924.github.io/paper_summary/ImproveRestore-FAST'13.html)

### Secure Deduplication
1. *Convergent Dispersal: Toward Storage-Efficient Security in a Cloud-of-Clouds*----HotStorage'14 ([link](https://www.cse.cuhk.edu.hk/~pclee/www/pubs/hotstorage14.pdf)) [summary](https://yzr95924.github.io/paper_summary/CAONT-RS-HotStorage'14.html)
2. *CDStore: Toward Reliable, Secure, and Cost-Efficient Cloud Storage via Convergent Dispersal*----USENIX ATC'15 ([link](https://www.usenix.org/system/files/conference/atc15/atc15-paper-li-mingqiang.pdf)) [summary](https://yzr95924.github.io/paper_summary/CDStore-ATC'15.html)
3. *Information Leakage in Encrypted Deduplication via Frequency Analysis*----DSN'17
4. *DupLESS: Server-Aided Encryption for Deduplicated Storage*----USENIX Security'13 ([link](https://eprint.iacr.org/2013/429.pdf)) [summary](https://yzr95924.github.io/paper_summary/DupLESS-Security'13.html)
5. *Side Channels in Cloud Services, the Case of Deduplication in Cloud Storage*----S&P'10 ([link](http://www.pinkas.net/PAPERS/hps.pdf)) [summary](https://yzr95924.github.io/paper_summary/SideChannel-S&P'10.html)
6. *Side Channels in Deduplication: Trade-offs between Leakage and Efficiency*----AsiaCCS'17
7. *On Information Leakage in Deduplication Storage Systems*----CCS Workshop'16 [summary](https://yzr95924.github.io/paper_summary/InformationLeakage-CCSW'16.html)
8. *SecDep: A User-Aware Efficient Fine-Grained Secure Deduplication Scheme with Multi-Level Key Management*----MSST'15 ([link](https://cswxia.github.io/SecDep-final-2015.pdf))
9. *Message-Locked Encryption and Secure Deduplication*----EuroCrypt'13
10. *Proofs of Ownership in Remote Storage System*----CCS'11
11. *Tapping the Potential: Secure Chunk-based Deduplication of Encrypted Data for Cloud Backup*----CNS'18 [summary](https://yzr95924.github.io/paper_summary/TappingPotential-CNS'18.html)
12. *A Bandwidth-Efficient Middleware for Encrypted Deduplication*----DSC'18 [summary](https://yzr95924.github.io/paper_summary/UWare-DSC'18.html)
13. *Bloom Filter Based Privacy Preserving Deduplication System*----Springer International Conference on Security & Privacy'19 ([link](https://link.springer.com/chapter/10.1007/978-981-13-7561-3_2)) [summary](https://yzr95924.github.io/paper_summary/BloomFilterDedup-ICSP'19.html)
14. *Enhanced Secure Thresholded Data Deduplication Scheme for Cloud Storage*----TDSC'16 ([link](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7553458)) [summary](https://yzr95924.github.io/paper_summary/EnhancedThreshold-TDSC'16.html)
15. *Transparent Data Deduplication in the Cloud*----CCS'15 ([link](http://www.ghassankarame.com/dedup.pdf)) [summary](https://yzr95924.github.io/paper_summary/ClearBox-CCS'15.html)
16. *Secure Deduplication of Encrypted Data without Additional Independent Servers*----CCS'15 ([link](https://eprint.iacr.org/2015/455.pdf)) [summary](https://yzr95924.github.io/paper_summary/IndependentServer-CCS'15.html)
17. *Fast and Secure Laptop Backups with Encrypted Deduplication*----LISA'10 ([link](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.368.3092&rep=rep1&type=pdf))
18. *Weak Leakage-Resilient Client-side Deduplication of Encrypted Data in Cloud Storage*----ASIA CCS'13 ([link](https://eprint.iacr.org/2011/538.pdf))
19. *Lamassu: Storage-Efficient Host-Side Encryption*----USENIX ATC'15 ([link](https://www.usenix.org/system/files/conference/atc15/atc15-paper-shah.pdf))
20. *Mitigating Traffic-based Side Channel Attacks in Bandwidth-efficient Cloud Storage*----IPDPS'18 ([link](https://csyhua.github.io/csyhua/hua-ipdps2018.pdf)) [summary](https://yzr95924.github.io/paper_summary/MitigatingSideChannel-IPDPS'18.html)
21. *RARE: Defeating Side Channels based on Data-Deduplication in Cloud Storage*----INFOCOM'18 ([link](https://ieeexplore.ieee.org/document/8406888))
22. *PerfectDedup: Secure Data Deduplication*----Data Privacy Management, and Security Assurance'15 ([link](http://www.eurecom.fr/fr/publication/4683/download/rs-publi-4683.pdf))

### Metadata Management
1. *Metadedup: Deduplicating Metadata in Encrypted Deduplication via Indirection*----MSST'19 ([link](https://ieeexplore.ieee.org/document/8890207))
2. *Rekeying for Encrypted Deduplication Storage*----DSN'16 ([link](http://adslab.cse.cuhk.edu.hk/pubs/dsn16reed.pdf)) [summary](https://yzr95924.github.io/paper_summary/REED-DSN'16.html)
3. *File Recipe Compression in Data Deduplication Systems*----FAST'13 ([link](https://www.usenix.org/system/files/conference/fast13/fast13-final54.pdf)) [summary](https://yzr95924.github.io/paper_summary/FileRecipeCompression-FAST'13.html)
4. *Metadata Considered Harmful ... to Deduplication*----HotStorage'15 ([link](https://www.usenix.org/system/files/conference/hotstorage15/hotstorage15-lin.pdf)) [summary](https://yzr95924.github.io/paper_summary/MetadataHarmful-HotStorage'15.html)
5. *GoSeed: Generating an Optimal Seeding Plan for Deduplicated Storage* ---- FAST'19 ([link](https://www.usenix.org/conference/fast20/presentation/nachman)) (* This paper is actually not for metadata management, it is for balancing data in data transfer between volumes)


### Indexing & Caching
1. *LIPA: A Learning-based Indexing and Prefetching Approach for Data Deduplication*----MSST'19 ([link](http://storageconference.us/2019/Research/LIPA.pdf)) [summary](https://yzr95924.github.io/paper_summary/LIPA-MSST'19.html)
2. *Lazy Exact Deduplication*----MSST'16 
3. *MAD2: A Scalable High-throughput Exact Deduplication Approach for Network Backup Services*----MSST'10
4. *Block Locality Caching for Data Deduplication*----SYSTOR'13 ([link](https://dl.acm.org/citation.cfm?id=2485748))
5. *HANDS: A Heuristically Arranged Non-Backup In-line Deduplication System*----ICDE'13 ([link](https://www.ssrc.ucsc.edu/Papers/ssrctr-12-03.pdf))
6. *Austere Flash Caching with Deduplication and Compression*---ATC'20 ([link](https://www.usenix.org/conference/atc20/presentation/wang-qiuping))

### Deduplication Estimation

1. *Estimating Unseen Deduplication - from Theory to Practice*----FAST'16 ([link](https://www.usenix.org/system/files/conference/fast16/fast16-papers-harnik.pdf)) [summary](https://yzr95924.github.io/paper_summary/HintsDeduplication-FAST'16.html)
2. *Estimation of Deduplication Ratios in Large Data Sets*----MSST'12 ([link](http://www.storageconference.us/2012/Papers/17.Deduplication.Estimation.pdf)) [summary](https://yzr95924.github.io/paper_summary/EstimateDedupRatio-MSST'12.html)
3. *Sketching Volume Capacities in Deduplicated Storage*----FAST'19 ([link](https://www.usenix.org/system/files/fast19-harnik.pdf)) [summary](https://yzr95924.github.io/paper_summary/SketchDeduplication-FAST'19.html)
4. *Estimating Duplication by Content-based Sampling*----USENIX ATC'13 [summary](https://yzr95924.github.io/paper_summary/ContentBasedSampling-ATC'13.html)
5. *Content-aware Load Balancing for Distributed Backup*----LISA'11 ([link](https://www.usenix.org/legacy/event/lisa11/tech/full_papers/Chamness.pdf))
6. *Rangoli: Space Management in Deduplication Environments*----SYSTOR'13 ([link](https://atg.netapp.com/wp-content/uploads/2013/07/Systor13-Rangoli.pdf))

### Post-Deduplication: Data Compression
1. *Finesse: Fine-Grained Feature Locality based Fast Resemblance Detection for Post-Deduplication Delta Compression*----FAST'19 ([link](https://www.usenix.org/system/files/fast19-zhang.pdf)) [summary](https://yzr95924.github.io/paper_summary/Finesse-FAST'19.html)
2. *The Design of a Similarity Based Deduplication System*----SYSTOR'09
3. *Ddelta: A deduplication-inspired fast delta compression approach* ---- Performance Evaluation ([link](https://www.sciencedirect.com/science/article/pii/S0166531614000790))
4. *Exploring the Potential of Fast Delta Encoding: Marching to a Higher Compression Ratio* ---- TOPDS'2020 ([link](https://ieeexplore.ieee.org/abstract/document/9229609))
5. *Odess: Speeding up Resemblance Detection for RedundancyElimination by Fast Content-Defined Sampling* ---- ICDE' 2021 ([link](https://www.researchgate.net/profile/Xiangyu-Zou-4/publication/351037342_Odess_Speeding_up_Resemblance_Detection_for_Redundancy_Elimination_by_Fast_Content-Defined_Sampling/links/60806985881fa114b41b6604/Odess-Speeding-up-Resemblance-Detection-for-Redundancy-Elimination-by-Fast-Content-Defined-Sampling.pdf))

### Memory && Block-Layer Deduplication
1. *UKSM: Swift Memory Deduplication via Hierarchical and Adaptive Memory Region Distilling*----FAST'18 [summary](https://yzr95924.github.io/paper_summary/UKSM-FAST'18.html)
2. *Using Hints to Improve Inline Block-Layer Deduplication*----FAST'16 [summary](https://yzr95924.github.io/paper_summary/HintsDeduplication-FAST'16.html*)
3. *XLM: More Effective Memory Deduplication Scanners through Cross-Layer Hints*----USENIX ATC'13

### Data Chunking
1. *SS-CDC: A Two-stage Parallel Content-Defined Chunking for Deduplicating Backup Storage*----SYSTOR'19 [summary](https://yzr95924.github.io/paper_summary/SSCDC-SYSTOR'19.html)
2. *Frequency Based Chunking for Data De-Duplication*----MASCOTS'10 [summary](https://yzr95924.github.io/paper_summary/FrequencyBasedChunking-MASCOTS'10.html)
3. *Bimodal Content Defined Chunking for Backup Streams*----FAST'10
4. *Delta: a Deduplication-inspired Fast Delta Compression Approach*----IFIP Performance'14
5. *P-dedupe: Exploiting Parallelism in Data Deduplication System*----NAS'12
6. *MUCH: Multi-threaded Content-Based File Chunking*----TC'15
7. *Multi-Level Comparison of Data Deduplication in a Backup Scenario*----SYSTOR'09
8. *A Framework for Analyzing the Improving Content-Based Chunking Algorithms*----HP Technique Report'05
9. *FastCDC - The Design of Fast Content-Defined Chunking for Data Deduplication Based Storage Systems* ---- IEEE TOPDS' 2020 [link](https://ieeexplore.ieee.org/abstract/document/9055082) 


### Deduplication Reliability
1. *A Simulation Analysis of Redundancy and Reliability in Primary Storage Deduplication*----TC'18 ([link]()) [summary](https://yzr95924.github.io/paper_summary/SimRedundancy-TC'18.html)
2. *A Simulation Analysis of Reliability in Primary Storage Deduplication*----IISWC'16

### Cache Deduplication
1. *CDAC: Content-Driven Deduplication-Aware Storage Cache*----MSST'19 ([link](http://storageconference.us/2019/Research/CDAC.pdf))
2. *PLC-cache: Endurable SSD cache for deduplication-based primary storage*----MSST'14 ([link](https://ieeexplore.ieee.org/abstract/document/6855536))
3. *Nitro: A Capacity-Optimized SSD Cache for Primary Storage*----USENIX ATC'14 ([link](https://www.usenix.org/system/files/conference/atc14/atc14-paper-li_cheng_nitro.pdf))

### Benchmark
1. *SDGen: Mimicking Datasets for Content Generation in Storage Benchmarks*----FAST'15 ([link](https://www.usenix.org/system/files/conference/fast15/fast15-paper-gracia-tinedo.pdf))

### Garbage Collection
1. *Memory Efficient Sanitization of a Deduplicated Storage System*----FAST'13 ([link](https://www.usenix.org/system/files/conference/fast13/fast13-final100_0.pdf)) 
2. *The Logic of Physical Garbage Collection in Deduplicating Storage*----FAST'17 ([link](https://www.usenix.org/conference/fast17/technical-sessions/presentation/douglis))([summary](https://www.cnblogs.com/wAther/p/14291170.html))
3. *A scalable dedupliation and garbage collection engine for incremental backup*----SYSTOR'13 ([link](https://dl.acm.org/doi/abs/10.1145/2485732.2485753))
4. *Concurrent Deletion in a Distributed Content-AddressableStorage Systemwith Global Deduplication*----FAST'13 ([link](https://www.usenix.org/conference/fast13/technical-sessions/presentation/strzelczak))

## B. Erasure Coding

### Erasure Coding Basics
1. *Network Coding for Distributed Storage System*----TIT'09
2. *A Performance Evaluation and Examination of Open-Source Erasure Coding Libraries for Storage*----FAST'09
3. *Erasure Coding for Cloud Storage Systems: A Survey*----By Jun Li in 2013

### Improve Data Recovery
1. *CORE: Augmenting Regenerating-Coding-Based Recovery for Single and Concurrent Failures in Distributed Storage Systems*----MSST'13
2. *Degraded-First Scheduling for MapReduce in Erasure-Coded Storage Clusters*----DSN'14
3. *Repair Pipelining for Erasure-Coded Storage*----USENIX ATC'17
4. *A Tale of Two Erasure Codes in HDFS*----FAST'15
5. *On the Speedup of Single-Disk Failure Recovery in XOR-Coded Storage Systems: Theory and Prantice*----MSST'12
6. *Rethinking Erasure Codes for Cloud File Systems: Minimizing I/O for Recovery and Degraded Reads*----FAST'12
7. *Lazy Means Smart: Reducing Repair Bandwidth Costs in Erasure-coded Distributed Storage*----SYSTOR'14
8. *Enabling Efficient and Reliable Transition from Replication to Erasure Coding for Clustered File System*----DSN'15
9. *Reconsidering Single Failure Recovery in Clustered File Systems*----DSN'16 [summary](https://yzr95924.github.io/paper_summary/CAR-DSN'16.html)
10. *RAFI: Risk-Aware Failure Identification to Improve the RAS in Erasure-coded Data Center*----USENIX ATC'18
11. *Partial-Parallel-Repair (PPR): A Distributed Technique for Repairing Erasure Coded Storage*----EuroSys'16

### EC Update Issue
1. *Cross-Rack-Aware Updates in Erasure-Coded Data Centers*----ICPP'18
2. *PARIX: Speculative Partial Writes in Erasure-Coded Systems*----USENIX ATC'17

### EC Framework
1. *OpenEC: Toward Unified and Configurable Erasure Coding Management in Distributed Storage Systems*----FAST'19

### New EC code
1. *CodePlugin: Plugging Deduplication into Erasure Coding for Cloud Storage*----HotCloud'15
2. *Double Regenerating Codes for Hierarchical Data Centers*----ISIT'16
3. *Pyramid codes: Flexible schemes to trade space for access efficiency in reliable data storage systems*----ToS'13
4. *Having Your Cake and Eating It Too: Jointly Optimal Erasure Codes for I/O, Storage and Network-bandwidth*----FAST'15
5. *Opening the Chrysalis: On the Real Repair Performance of MSR Codes*----FAST'16
6. *NCCloud: A Network-Coding-Based Storage System in a Cloud-of-Clouds*----FAST'12
7. *Erasure Coding in Windows Azure Storage*----USENIX ATC'12
8. *XORing Elephants: Novel Erasure Codes for Big Data*----VLDB'13
9. *Clay Codes: Moulding MDS Codes to Yield an MSR Code*----FAST'18
10. *Alpha Entanglement Codes: Practical Erasure Codes to Archive Data in Unreliable Environments*----DSN'18 [summary](https://yzr95924.github.io/paper_summary/Alpha-Entanglement-Codes-DSN'18.html)
11. *On Fault Tolerance, Locality, and Optimality in Locally Repairable Codes*----USENIX ATC'18
12. *Parallelism-Aware Locally Repairable Code for Distributed Storage Systems*----ICDCS'18
13. *Beehive: Erasure Codes for Fixing Multiple Failures in Distributed Storage Systems*----HotStorage'15
14. *Pipelined regeneration with Regenerating Codes for Distributed Storage Systems*----NetCod'11
15. *Cooperative Pipelined Regeneration in Distribution Storage Systems*----INFOCOM'14
16. *Zebra: Demand-aware Erasure Coding for Distributed Storage Systems*----IWQoS'16
17. *On Data Parallelism of Erasure Coding in Distributed Storage Systems*----ICDCS'17

### EC System
1. *Giza: Erasure Coding Objects across Global Data Centers*----USENIX ATC'17
2. *EC-Store: Bridging the Gap Between Storage and Latency in Distributed Erasure Coded Systems*----ICDCS'18
3. *Latency Reduction and Load Balancing in Coded Storage Systems*----SoCC'17

## C. Security
### Survey
1. *A Survey on Systems Security Metrics*----ACM Computing Surveys'16

### Secret Sharing
1. *How to Best Share a Big Secret*----SYSTOR'18
2. *AONT-RS: Blending Security and Performance in Dispersed Storage Systems*----FAST'11
3. *Secure Deletion for a Versioning File System*----FAST'05 

### Data Encryption
1. *Differentially Private Access Patterns for Searchable Symmetric Encryption*----INFOCOM'18 [summary](https://yzr95924.github.io/paper_summary/DifferentialPrivacy-INFOCOM'18.html)
2. *Frequency-Hiding Order-Preserving Encryption*----CCS'15
3. *RAPPOR: Randomized Aggregatable Privacy-Preserving Ordinal Response*----CCS'14
4. *Privacy at Scale: Local Differential Privacy in Practice*----SIGMOD'18
5. *Frequency-smoothing Encryption: Preventing Snapshot Attacks on Deterministically Encrypted Data*----IACR'17 [summary](https://yzr95924.github.io/paper_summary/FrequencySmoothing-ICAR'17.html)
6. *Efficient Homophonic Coding*----TIT'99
7. *A Note on the Optimality of Frequency Analysis vs. lp-Optimization*----IACR'15
8. *Inference Attacks on Property-Preserving Encrypted Databases*----CCS'15
9. *How Far Can we Go Beyond Linear Cryptanalysis?*----AsiaCRYPTO'04
10. *CryptDB: Protecting Confidentiality with Encrypted Query Processing*----SOSP'11 ([link](https://dspace.mit.edu/bitstream/handle/1721.1/74107/cryptdb-sosp11.pdf?sequence=1&isAllowed=y))
11. *Secure Deletion for a Versioning File System*----FAST'05
12. *Dark Clouds on the Horizon: Using Cloud Storage as Attack Vector and Online Slack Space*----USENIX Security'11 ([link](https://www.usenix.org/legacy/event/sec11/tech/full_papers/Mulazzani.pdf))

### Differential Privacy
1. *Differential Privacy*----ICALP'06 ([link](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/dwork.pdf))
2. *Calibrating Noise to Sensitivity in Private Data Analysis*----TCC'06 ([link](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/03/dmns06.pdf))

### SGX

1. *NEXUS: Practical and Secure Access Control on Untrusted Storage Platforms using Client-side SGX*----DSN'19 ([link](https://people.cs.pitt.edu/~adamlee/pubs/2019/djoko2019dsn-nexus.pdf))

## D. Others
### Multi-Cloud System
1. *Kurma: Secure Geo-Distributed Multi-Cloud Storage Gateways*----SYSTOR'19 [summary](https://yzr95924.github.io/paper_summary/Kurma-SYSTOR'19.html)
2. *SPANStore: Cost-Effective Geo-Replicated Storage Spanning Multiple Cloud Services*----SOSP'13 [summary](https://yzr95924.github.io/paper_summary/SPANStore-SOSP'13.html)
3. *CosTLO: Cost-Effective Redundancy for Lower Latency Variance on Cloud Storage Service*----NSDI'15
4. *A Day Late and a Dollar Short: The Case for Research on Cloud Billing Systems*----HotCloud'14

### New PAXOS 
1. *In Search of an Understandable Consensus Algorithm*----USENIX ATC'14

### Distributed File System
1. *Ceph: A Salable, High-Performance Distributed File System*----OSDI'06 
2. *The Hadoop Distributed File System*----MSST'10 ([link](http://storageconference.us/2010/Papers/MSST/Shvachko.pdf)) [summary](https://yzr95924.github.io/paper_summary/HDFS-MSST'10.html)
3. *RADOS: A Scalable, Reliable Storage Service for Petabyte-scale Storage Clusters*----PDSW'07
4. *CRUSH: Controlled, Scalable, Decentralized Placement of Replicated Data*----SC'06

### Hash
1. *Compare-by-Hash: A Reasoned Analysis*----USENIX ATC'06 ([link](https://www.usenix.org/legacy/event/usenix06/tech/full_papers/black/black.pdf)) [summary](https://yzr95924.github.io/paper_summary/CompareByHash-ATC'06.html)
2. *An Analysis of Compare-by-Hash*----HotOS'03 ([link](http://www.cs.utah.edu/~shanth/stuff/research/dup_elim/hash_cmp.pdf))

### Streaming Process
1. *A Lock-Free, Cache-Efficient Multi-Core Synchronization Mechanism for Line-Rate Network Traffic Monitoring*----IPDPS'10

