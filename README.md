# SpatialTranscriptomicsTutorials
Tutorials of spatial transcriptomics data loading, including 10X Visium and Old ST.
目前，大多数的公开空转数据集，在这两个空间转录组数据集收集网站上可以找到**(.h5ad)**为文件后缀：

1. [STOmics DB](https://db.cngb.org/stomics/)：中国国家基因库数据库
2. [SODB](https://gene.ai.tencent.com/SpatialOmics/)：复旦大学与腾讯智能医学院的联合项目。

Spatial Domain Identification Methods可大致分为三类：

1. Non-spatial: 

   (1) [SCANPY](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-017-1382-0) (Genome Biology 2018.02)

   (2) [Seurat](https://satijalab.org/seurat/) (Nature Biotechnology 2015.04 (V1),  Nature Biotechnology 2018.04 (V2), Cell 2019.06 (V3), Cell 2021.05 (V4), bioRxiv 2022.02(V5))

2. Spatial but no morphology: 

   (1) [Giotto](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02286-2) (Genome Biology 2021.03)

   (2) [BayesSpace](https://www.nature.com/articles/s41587-021-00935-2) (Nature Biotechnology 2021.06)

   (3) [DR-SC](https://academic.oup.com/nar/article/50/12/e72/6555431) (NAR 2022.07)

   (4) [STAGATE](https://www.nature.com/articles/s41467-022-29439-6) (Nature Communication 2022.04)

   (5) [BASS](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02734-7) (Genome Biology 2022.08)

   (6) [BANKSY](https://www.biorxiv.org/content/10.1101/2022.04.14.488259v1.full) (bioRxiv 2022.04)

   (7) [SpatialPCA ](https://www.nature.com/articles/s41467-022-34879-1) (Nature Communication 2022.11)

   (8) [SEDR](https://www.biorxiv.org/content/10.1101/2021.06.15.448542v2) (bioRxiv, 2021.06)

   (9) [SOTIP](https://www.nature.com/articles/s41467-022-34867-5) (Nature Communication 2022.11)

   (10) [GraphST](https://www.nature.com/articles/s41467-023-36796-3) (Nature Communication 2023.03)

3. Spatial and morphology:

   (1) [stLearn](https://stlearn.readthedocs.io/en/latest/tutorials.html) (bioRxiv 2020.05)

   (2) [SpaGCN](https://www.nature.com/articles/s41592-021-01255-8) (Nature Methods 2021.10)

   (3) [DeepST](https://academic.oup.com/nar/article/50/22/e131/6761985) (NAR 2022.10)

   (4) [ConST](https://github.com/ys-zong/conST) (bioRxiv 2022.01)

此外，还有比较奇葩的，比如用了形态学和转录信息，但是没有用到空间信息的：

1. [ConGI](https://academic.oup.com/bib/article-abstract/24/2/bbad048/7035112) (BIB 2023.02)
1. [MUSE](https://www.nature.com/articles/s41587-022-01251-z) (Biotechnology 2022.05)
