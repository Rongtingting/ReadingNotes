# [高通量测序技术-知乎专栏](https://zhuanlan.zhihu.com/ngs-learning)
Rongting Huang

build date: 2019-10-10

update date: 2019-10-10

## 生物信息学100个基础问题-答案汇总

[生物信息学100个基础问题：问题及答案目录-待更新](https://zhuanlan.zhihu.com/p/36279463)

[生物信息学100个基础问题——第1~ 5题 答案公布](https://zhuanlan.zhihu.com/p/34957915)

[生物信息学100个基础问题——第6~ 10题 答案公布](https://zhuanlan.zhihu.com/p/35262911)

[生物信息学100个基础问题——第11~15题 答案公布](https://zhuanlan.zhihu.com/p/35875081)

[生物信息学100个基础问题——第16~20题 答案公布](https://zhuanlan.zhihu.com/p/36591134)

[生物信息学100个基础问题——第21~25题 答案公布](https://zhuanlan.zhihu.com/p/44859871)

[生物信息学100个基础问题 —— 番外1： 不学Linux做什么生信？](https://zhuanlan.zhihu.com/p/34935771)

[生物信息学100个基础问题 —— 番外2: 用Anaconda快速搭建生物信息学分析平台](https://zhuanlan.zhihu.com/p/35711429)

[生物信息学100个基础问题 —— 番外3: R与Bioconductor的入门教学](https://zhuanlan.zhihu.com/p/37651960)

[生物信息学100个基础问题 —— 番外5：使用Snakemake快速搭建生信分析流程](https://zhuanlan.zhihu.com/p/58812856)


## 生物信息学100个基础问题
### 第1题，与FASTQ与FASTA格式有关

1.1 掌握FASTQ格式

- 格式有什么特点？
- 第1行什么开头，主要内容都有哪些？
- 第2行是什么？
- 第3行是什么？
- 第4行是什么？
- 什么是phred值，怎么计算？
- phred33 与 phred64是什么意思？

1.2 FASTA格式的构成是怎样的，有什么样的规律？

1.3 什么序列适合用FASTA保存，什么序列适合用FASTQ保存？

###  第2题 测序技术初探
现在我们实验室或者公司常用第1代测序与第2代测序，那么：

1. 第1代测序 sanger 测序法的原理是什么？通量比较低的核心原因是什么？

2. 作为2006年正式发布的illumina测序技术，或者称为第2代测序技术的代表性技术，其最大的特点是什么？

3. Illumina测序技术的核心是什么？

4. Illumina测序技术为什么不能像第1代测序技术一样测500bp以上？

### 第3题 Illumina测序技术细节探究
目前我们最常使用的就是Illumina公司的测序技术，Illumina公司的测序技术最明显的几个特点是：价格低，通量高，测序读长短。那么我们今天的问题，就是围绕Illumina测序技术的细节来提问的。

1. 什么是Illumina测序adapter？同一批上机的adapter序列一样吗？它的作用是什么？

2. 一个完整的Illumina测序过程是那几步？

3. 什么是桥式PCR技术？为什么要进行桥式PCR？

4. 我们都说，测序结果会包含index，那么index是什么？有什么作用？

5. 我们所说的flowcell，lane，tile都是什么意思？

6. Illumina测序结果质量表示方法采用的是Phred33还是Phred64？

### 第4题 Illumina测序技术细节探究 II
我们接着第2个问题，第3个问题接着问。既然我们已经知道的Illumina测序的基本概念，基本过程；也知道了Illumina测序的主要特点。那么还是要有个细节的探索。

1. Illumina目前主流的测序仪都有哪几种型号？各自大概的通量是多少？（也就是1个run能跑出多少数据）

2. Illumina目前的测序技术，最核心的就是边合成边测序，即我们常说的 Sequencing by synthesis （SBS），那么为什么能够实现SBS？

3. 我们在第1问中，问了大家一个问题“Illumina测序技术为什么不能像第1代测序技术一样测500bp以上？”，这里面主要涉及到两种错误，一种叫phasing，一种叫pre-phasing，分别是什么意思？

### 第5题 测序建库的adapter
围绕着测序后续的质控与建库细节来进行。

今天我们提出的问题是Illumina目前常用的双端测序建库办法中，会在打断的序列前后加上adapter，请问：

1.adapter是什么意思？adapter与primer有什么区别？

2.比如最终的测序结果是 AATTCCGGATCGATCG...，那么adapter的序列可能出现在哪一端，还是两端都有可能出现？为什么？






