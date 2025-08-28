---
title: "学术软件"
# meta title
meta_title: ""
# meta description
description: "沈伟 课题组 生物信息学 软件"
# save as draft
draft: false
---

#### 生物信息学相关

软件：

- **[LexicMap](https://github.com/shenwei356/LexicMap)**, 快速、低内存、具有高扩展性的百万规模原核生物基因组序列比对
- **[KMCP](https://github.com/shenwei356/kmcp)**, 宏基因组物种组成分析，同时也是大规模序列/基因组索引与搜索软件
- **[SeqKit](https://github.com/shenwei356/seqkit)**, FASTA/Q数据操作的瑞士军刀（功能非常多）
- **[TaxonKit](https://github.com/shenwei356/taxonkit)**, NCBI分类学数据各种操作，也能从任意分类学数据创建
- **[unikmer](https://github.com/shenwei356/unikmer)**, 支持分类学数据的核酸k-mer分析，可寻找物种/菌株特异性序列

数据：

- [taxid-changelog](https://github.com/shenwei356/taxid-changelog), NCBI taxonomic identifier (taxid) changelog, including taxids deletion, new adding, merge, reuse, and rank/name changes.
- [gtdb-taxdump](https://github.com/shenwei356/gtdb-taxdump) and [ictv-taxdump](https://github.com/shenwei356/ictv-taxdump), GTDB and ICTV taxonomy taxdump files with trackable TaxIds

包/库：

- [bio](https://github.com/shenwei356/bio), A lightweight and high-performance bioinformatics package in Golang.
    - [FASTA/Q reading](https://github.com/shenwei356/bio/tree/master/seqio)
    - [Sketching algorithms](https://github.com/shenwei356/bio/tree/master/sketches), including Minimizer, Protein Minimizer, Scaled MinHash, Closed Syncmers
    - [Taxonomy data manipulation](https://github.com/shenwei356/bio/tree/master/taxdump)
- [kmers](https://github.com/shenwei356/kmers), Bit-packed k-mers methods for Golang
- [unik](https://github.com/shenwei356/unik), A k-mer serialization package for Golang
- [lexichash](https://github.com/shenwei356/lexichash), LexicHash in Golang
- [wfa](https://github.com/shenwei356/wfa), Wavefront alignment algorithm (WFA) in Golang
- [strobemers](https://github.com/shenwei356/strobemers), A Go implementation of the strobemers
- [bwt](https://github.com/shenwei356/bwt), Burrows-Wheeler Transform and FM-index in Golang
- [countminsketch](https://github.com/shenwei356/countminsketch), Count-Min Sketch in Golang

#### 通用工具 

软件：

- **[csvtk](https://github.com/shenwei356/csvtk)**, CSV/TSV数据操作（功能非常多）
- **[rush](https://github.com/shenwei356/rush)**, 批量运行任务，特性丰富
- **[brename](https://github.com/shenwei356/brename)**, 安全地批量重命名
- [cluster_files](https://github.com/shenwei356/cluster_files), 规范地组织测序数据，方便并行、分阶段分析。
- [dirsize](https://github.com/shenwei356/dirsize), 列出文件和文件夹的大小，比du简单，方便，支持多种操作系统。

库/包：

- [stable](https://github.com/shenwei356/stable), streaming pretty text table for Golang

#### 其他

- **[perfect-bioinformatic-tools](https://github.com/shenwei356/perfect-bioinformatic-tools)**, 提高生物信息学命令行软件准确性和易用性的建议

#### 不再维护

- **[FOMmiR](https://github.com/yanlilab/FOMmiR)**, MicroRNA Prediction Using a Fixed-Order Markov Model Based on the Secondary Structure Pattern
- **[Fastcov](https://github.com/yanlilab/fastcov)**, A novel algorithm for detecting multiple covariance and clustering of biological sequences
