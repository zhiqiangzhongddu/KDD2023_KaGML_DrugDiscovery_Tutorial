# KDD 2023 KaGML for Drug Discovery Tutorial

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) ![Stars](https://img.shields.io/github/stars/zhiqiangzhongddu/KDD2023_KaGML_DrugDiscovery_Tutorial?color=yellow)  ![Forks](https://img.shields.io/github/forks/zhiqiangzhongddu/KDD2023_KaGML_DrugDiscovery_Tutorial?color=blue&label=Fork)

Materials for KDD2023 tutorial: Knowledge-augmented Graph Machine Learning for Drug Discovery: from Precision to Interpretability

## Time and Location

**1. Time: TBD.**

**2. Location: TBD.**

**3. Zoom: Click "join zoom room" at Underline.**

## Tutorial abstract
*Graph Machine Learning* (GML) has gained considerable attention for its exceptional ability to model graph-structured biomedical data and investigate their properties and functional relationships. 
Despite extensive efforts, GML methods still suffer from several deficiencies, such as the limited ability to handle supervision sparsity and provide interpretability in learning and inference processes and their ineffectiveness in utilising relevant domain knowledge. 
In response, recent studies have proposed integrating external biomedical knowledge into the GML pipeline to realise more precise and interpretable drug discovery with limited training instances. 
This tutorial presents a comprehensive overview of long-standing drug discovery principles, provides the foundational concepts and cutting-edge techniques for graph-structured data and knowledge databases, and formally summarises *Knowledge-augmented Graph Machine Learning* (KaGML) for drug discovery.
We have recently completed a survey of KaGML works that organises the outstanding approaches into four categories following a novel-defined taxonomy. 
This tutorial will present the result of this scholarly work.
To encourage audience participation and facilitate research in this promptly emerging field, we also share valuable practical resources for intelligent drug discovery and provide an in-depth discussion of the potential avenues for future advancements.

## Outline and Material

- Introduction and Motivation [[Slides]](https://github.com/zhiqiangzhongddu/KDD2023_KaGML_DrugDiscovery_Tutorial)
- Background of Drug Discovery [[Slides]](https://github.com/zhiqiangzhongddu/KDD2023_KaGML_DrugDiscovery_Tutorial)
- Graph Machine Learning (GML) and Knowledge Graph (KG) in Drug Discovery [[Slides]](https://github.com/zhiqiangzhongddu/KDD2023_KaGML_DrugDiscovery_Tutorial)
- Knowledge-augmented Graph Machine Learning (KaGML) for Drug Discovery [[Slides]](https://github.com/zhiqiangzhongddu/KDD2023_KaGML_DrugDiscovery_Tutorial)
  - Taxonomy of KaGML
  - Incorporating knowledge in *preprocessing*
  - Incorporating knowledge in *pretraining*
  - Incorporating knowledge in *training*
  - Incorporating knowledge in *interpretability*
- Practical Resources [[Slides]](https://github.com/zhiqiangzhongddu/KDD2023_KaGML_DrugDiscovery_Tutorial)
- Open Challenges and Future Directions [[Slides]](https://github.com/zhiqiangzhongddu/KDD2023_KaGML_DrugDiscovery_Tutorial)
- Q&A Session

## Additional Relevant Materials

- [Survey papers](#surveypapers)
- [Papers](#papers)
  - [Incorporating Knowledge in *Preprocessing*](#preprocessing)
    - [Feature augmentation](#feature-augmentation)
    - [Graph structure augmentation](#generative-sample-pretraining)
  - [Incorporating Knowledge in *Pretraining*](#pretraining)
    - [Knowledge transfer pretraining](#pretraining-knowledge-transfer)
    - [Generative-sample pretraining](#pretraining-generative-sample)
    - [Contrastive-sample pretraining](#pretraining-contrastive-sample)
  - [Incorporating Knowledge in *Training*](#training)
    - [Auxiliary task-enhanced training](#training-auxiliary-task-enhanced)
    - [Auxiliary knowledge-enhanced training](#training-auxiliary-knowledge-enhanced)
  - [Incorporating Knowledge in *Interpretability*](#interpretability)
    - [Attention summarisation](#interpretability-attenntion-summarisation)
    - [Pathway extraction](#interpretability-pathway-extraction)
- [Practical Resources](#resources)
  - [Knowledge Database](#knowledge-database)
  - [Knowledge Graph](#knowledge-graph)

<a name="surveypapers" />

### Survey papers

1. **Knowledge-augmented Graph Machine Learning for Drug Discovery: A Survey from Precision to Interpretability.** arxiv 2023. [[Paper]](http://arxiv.org/abs/2302.08261) 

    *Zhiqiang Zhong, Anastasia Barkova, Davide Mottin.*

<a name="surveypapers" />

### Papers

1. **Neural Message Passing for Quantum Chemistry.** ICML 2017. [[Paper]](https://arxiv.org/abs/1704.01212)

    *Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, and George E. Dahl.*

1. **Analyzing Learned Molecular Representations for Property Prediction.** JCIM 2019. [[Paper]](https://arxiv.org/abs/1904.01561)

    *Kevin Yang, Kyle Swanson, Wengong Jin, Connor Coley, Philipp Eiden, Hua Gao, Angel Guzman-Perez, Timothy Hopper, Brian Kelley, Miriam Mathea, Andrew Palmer, Volker Settels, Tommi Jaakkola, Klavs Jensen, Regina Barzilay.*

1. **Communicative representation learning on attributed molecular graphs.** IJCAI 2020. [[Paper]](https://dl.acm.org/doi/pdf/10.5555/3491440.3491832)

    *Ying Song, Shuangjia Zheng, Zhangming Niu, Zhang-Hua Fu, Yutong Lu, Yuedong Yang.*

1. **KGNN: Knowledge Graph Neural Network for Drug-Drug Interaction Prediction.** IJCAI 2020. [[Paper]](https://www.ijcai.org/proceedings/2020/380)

    *Xuan Lin, Zhe Quan, Zhi-Jie Wang, Tengfei Ma, Xiangxiang Zeng.*

1. **Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning.** Nat. Methods 2020. [[Paper]](https://www.nature.com/articles/s41592-019-0666-6)

    *P. Gainza, F. Sverrisson, F. Monti, E. Rodolà, D. Boscaini, M. M. Bronstein, B. E. Correia.*

1. **Knowledge-Embedded Message-Passing Neural Networks: Improving Molecular Property Prediction with Human Knowledge.** ACS Omega 2021. [[Paper]](https://pubs.acs.org/doi/10.1021/acsomega.1c03839)

    *Tatsuya Hasebe.*

1. **SumGNN: Multi-typed Drug Interaction Prediction via Efficient Knowledge Graph Summarization.** Bioinform. 2021. [[Paper]](https://arxiv.org/abs/2010.01450)

    *Yue Yu, Kexin Huang, Chao Zhang, Lucas M. Glass, Jimeng Sun, Cao Xiao.*

1. **FraGAT: a fragment-oriented multi-scale graph attention model for molecular property prediction.** Bioinform. 2021. [[Paper]](https://academic.oup.com/bioinformatics/article/37/18/2981/6189082)

    *Ziqiao Zhang, Jihong Guan, Shuigeng Zhou.*

1. **Equivariant message passing for the prediction of tensorial properties and molecular spectra.** ICML 2021. [[Paper]](https://arxiv.org/abs/2102.03150)

    *Kristof T. Schütt, Oliver T. Unke, Michael Gastegger.*

1. **MDNN: A Multimodal Deep Neural Network for Predicting Drug-Drug Interaction Events.** IJCAI 2021. [[Paper]](https://www.ijcai.org/proceedings/2021/487)

    *Tengfei Lyu, Jianliang Gao, Ling Tian, Zhao Li, Peng Zhang, Ji Zhang.*

1. **MoCL: Data-driven Molecular Fingerprint via Knowledge-aware Contrastive Learning from Molecular Graph.** KDD 2021. [[Paper]](https://arxiv.org/abs/2106.04509)

    *Mengying Sun, Jing Xing, Huijun Wang, Bin Chen, Jiayu Zhou.*

1. **Highly accurate protein structure prediction with AlphaFold.** Nature 2021. [[Paper]](https://www.nature.com/articles/s41586-021-03819-2)

    *John Jumper, Richard Evans, Alexander Pritzel, Tim Green, Michael Figurnov, Olaf Ronneberger, Kathryn Tunyasuvunakool, Russ Bates, Augustin Žídek, Anna Potapenko, Alex Bridgland, Clemens Meyer, Simon A. A. Kohl, Andrew J. Ballard, Andrew Cowie, Bernardino Romera-Paredes, Stanislav Nikolov, Rishub Jain, Jonas Adler, Trevor Back, Stig Petersen, David Reiman, Ellen Clancy, Michal Zielinski, Martin Steinegger, Michalina Pacholska, Tamas Berghammer, Sebastian Bodenstein, David Silver, Oriol Vinyals, Andrew W. Senior, Koray Kavukcuoglu, Pushmeet Kohli, Demis Hassabis.*

1. **A unified drug–target interaction prediction framework based on knowledge graph and recommendation system.** Nat. Commun. 2021. [[Paper]](https://www.nature.com/articles/s41467-021-27137-3)

    *Qing Ye, Chang-Yu Hsieh, Ziyi Yang, Yu Kang, Jiming Chen, Dongsheng Cao, Shibo He, Tingjun Hou.*

1. **scGCN is a graph convolutional networks algorithm for knowledge transfer in single cell omics.** Nat. Commun. 2021. [[Paper]](https://www.nature.com/articles/s41467-021-24172-y)

    *Qianqian Song, Jing Su, Wei Zhang.*

1. **Out-of-the-box deep learning prediction of pharmaceutical properties by broadly learned knowledge-based molecular representations.** Nat. Mach. Intell. 2021. [[Paper]](https://www.nature.com/articles/s42256-021-00301-6)

    *Wan Xiang Shen, Xian Zeng, Feng Zhu, Ya li Wang, Chu Qin, Ying Tan, Yu Yang Jiang, Yu Zong Chen.*

1. **GemNet: Universal Directional Graph Neural Networks for Molecules.** NeurIPS 2021. [[Paper]](https://arxiv.org/abs/2106.08903)

    *Johannes Gasteiger, Florian Becker, Stephan Günnemann.*

1. **Multi-Scale Representation Learning on Proteins.** NeurIPS 2021. [[Paper]](https://arxiv.org/abs/2204.02337)

    *Vignesh Ram Somnath, Charlotte Bunne, Andreas Krause.*

1. **Directional Message Passing on Molecular Graphs via Synthetic Coordinates.** NeurIPS 2021. [[Paper]](https://arxiv.org/abs/2111.04718)

    *Johannes Gasteiger, Chandan Yeshwanth, Stephan Günnemann.*

1. **Molecular Contrastive Learning with Chemical Element Knowledge Graph.** AAAI 2022. [[Paper]](https://arxiv.org/abs/2112.00544)

    *Yin Fang, Qiang Zhang, Haihong Yang, Xiang Zhuang, Shumin Deng, Wen Zhang, Ming Qin, Zhuo Chen, Xiaohui Fan, Huajun Chen.*

1. **Structured Multi-task Learning for Molecular Property Prediction.** AISTATS 2022. [[Paper]](https://arxiv.org/abs/2203.04695)

    *Shengchao Liu, Meng Qu, Zuobai Zhang, Huiyu Cai, Jian Tang.*

1. **scGraph: a graph neural network-based approach to automatically identify cell types.** Bioinform. 2022. [[Paper]](https://academic.oup.com/bioinformatics/article/38/11/2996/6565313)

    *Qijin Yin, Qiao Liu, Zhuoran Fu, Wanwen Zeng, Boheng Zhang, Xuegong Zhang, Rui Jiang, Hairong Lv.*

1. **DTI-HETA: prediction of drug–target interactions based on GCN and GAT on heterogeneous graph.** Brief. Bioinform. 2022. [[Paper]](https://academic.oup.com/bib/article-abstract/23/3/bbac109/6563180?redirectedFrom=fulltext)

    *Kanghao Shao, Yunhao Zhang, Yuqi Wen, Zhongnan Zhang, Song He, Xiaochen Bo.*

1. **PEMP: Leveraging Physics Properties to Enhance Molecular Property Prediction.** CIKM 2022. [[Paper]](https://arxiv.org/abs/2211.01978)

    *Yuancheng Sun, Yimeng Chen, Weizhi Ma, Wenhao Huang, Kang Liu, Zhiming Ma, Wei-Ying Ma, Yanyan Lan.*

1. **Graph Neural Networks Pretraining Through Inherent Supervision for Molecular Property Prediction.** CIKM 2022. [[Paper]](https://dl.acm.org/doi/10.1145/3511808.3557085)

    *Roy Benjamin, Uriel Singer, Kira Radinsky.*

1. **Pre-training Molecular Graph Representation with 3D Geometry.** ICLR 2022. [[Paper]](https://arxiv.org/abs/2110.07728)

    *Shengchao Liu, Hanchen Wang, Weiyang Liu, Joan Lasenby, Hongyu Guo, Jian Tang.*

1. **OntoProtein: Protein Pretraining With Gene Ontology Embedding.** ICLR 2022. [[Paper]](https://openreview.net/forum?id=yfe1VMYAXa4)

    *Ningyu Zhang, Zhen Bi, Xiaozhuan Liang, Siyuan Cheng, Haosen Hong, Shumin Deng, Qiang Zhang, Jiazhang Lian, Huajun Chen.*

1. **Spherical Message Passing for 3D Graph Networks.** ICLR 2022. [[Paper]](https://arxiv.org/abs/2102.05013)

    *Yi Liu, Limei Wang, Meng Liu, Xuan Zhang, Bora Oztekin, Shuiwang Ji.*

1. **3D Infomax improves GNNs for Molecular Property Prediction.** ICML 2022. [[Paper]](https://arxiv.org/abs/2110.04126)

    *Hannes Stärk, Dominique Beaini, Gabriele Corso, Prudencio Tossou, Christian Dallago, Stephan Günnemann, Pietro Liò.*

1. **DRPreter: Interpretable Anticancer Drug Response Prediction Using Knowledge-Guided Graph Neural Networks and Transformer.** Int. J. Mol. Sci. 2022. [[Paper]](https://www.mdpi.com/1422-0067/23/22/13919)

    *Jihye Shin, Yinhua Piao, Dongmin Bang, Sun Kim, Kyuri Jo.*

1. **DENVIS: Scalable and High-Throughput Virtual Screening Using Graph Neural Networks with Atomic and Surface Protein Pocket Features.** J. Chem. Inf. Model. 2022. [[Paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01057)

    *Agamemnon Krasoulis, Nick Antonopoulos, Vassilis Pitsikalis, Stavros Theodorakis.*

1. **ReLMole: Molecular Representation Learning Based on Two-Level Graph Similarities.** J. Chem. Inf. Model. 2022. [[Paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00798)

    *Zewei Ji, Runhan Shi, Jiarui Lu, Fang Li, and Yang Yang.*

1. **KPGT: Knowledge-Guided Pre-training of Graph Transformer for Molecular Property Prediction.** KDD 2022. [[Paper]](https://arxiv.org/abs/2206.03364)

    *Han Li, Dan Zhao, Jianyang Zeng.*

1. **E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials.** Nat. Commun. 2022. [[Paper]](https://www.nature.com/articles/s41467-022-29939-5)

    *Simon Batzner, Albert Musaelian, Lixin Sun, Mario Geiger, Jonathan P Mailoa, Mordechai Kornbluth, Nicola Molinari, Tess E Smidt, Boris Kozinsky..*

1. **Geometry-enhanced molecular representation learning for property prediction.** Nat. Mach. Intell. 2022. [[Paper]](https://www.nature.com/articles/s42256-021-00438-4)

    *Xiaomin Fang, Lihang Liu, Jieqiong Lei, Donglong He, Shanzhuo Zhang, Jingbo Zhou, Fan Wang, Hua Wu, Haifeng Wang.*

1. **ComENet: Towards Complete and Efficient Message Passing for 3D Molecular Graphs.** NeurIPS 2022. [[Paper]](https://arxiv.org/abs/2206.08515)

    *Limei Wang, Yi Liu, Yuchao Lin, Haoran Liu, Shuiwang Ji.*

1. **Knowledge-guided deep learning models of drug toxicity improve interpretation.** Patterns 2022. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36124309/)

    *Yun Hao, Joseph D Romano, Jason H Moore.*

1. **Robust deep learning–based protein sequence design using ProteinMPNN.** Science 2022. [[Paper]](https://www.science.org/doi/10.1126/science.add2187)

    *J. Dauparas, I. Anishchenko, N. Bennett, H. Bai, R. J. Ragotte, L. F. Milles, B. I. M. Wicky, A. Courbet, R. J. de Haas, N. Bethel, P. J. Y. Leung, T. F. Huddy, S. Pellock, D. Tischer, F. Chan, B. Koepnick, H. Nguyen, A. Kang, B. Sankaran, A. K. Bera, N. P. King, D. Baker.*

1. **A Knowledge-Enhanced Multi-View Framework for Drug-Target Interaction Prediction.** TKDE 2022. [[Paper]](https://ieeexplore.ieee.org/document/9324998)

    *Ying Shen, Yilin Zhang, Kaiqi Yuan, Dagang Li, Haitao Zheng.*

1. **KG-MTL: Knowledge Graph Enhanced Multi-Task Learning for Molecular Interaction.** TKDE 2022. [[Paper]](https://ieeexplore.ieee.org/document/9815157)

    *Tengfei Ma, Xuan Lin, Bosheng Song, Philip S. Yu, Xiangxiang Zeng.*

1. **Hierarchical graph learning for protein-protein interaction.** Nat. Commun. 2023. [[Paper]](https://www.nature.com/articles/s41467-023-36736-1)

    *Ziqi Gao, Chenran Jiang, Jiawen Zhang, Xiaosen Jiang, Lanqing Li, Peilin Zhao, Huanming Yang, Yong Huang, Jia Li.*

<a name="preprocessing" />

### Incorporating Knowledge in *Preprocessing*

<a name="preprocessing-feature-augmentation" />

#### Feature augmentation

1. **Neural Message Passing for Quantum Chemistry.** ICML 2017. [[Paper]](https://arxiv.org/abs/1704.01212)

    *Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, and George E. Dahl.*

1. **Analyzing Learned Molecular Representations for Property Prediction.** JCIM 2019. [[Paper]](https://arxiv.org/abs/1904.01561)

    *Kevin Yang, Kyle Swanson, Wengong Jin, Connor Coley, Philipp Eiden, Hua Gao, Angel Guzman-Perez, Timothy Hopper, Brian Kelley, Miriam Mathea, Andrew Palmer, Volker Settels, Tommi Jaakkola, Klavs Jensen, Regina Barzilay.*

1. **Communicative representation learning on attributed molecular graphs.** IJCAI 2020. [[Paper]](https://dl.acm.org/doi/pdf/10.5555/3491440.3491832)

    *Ying Song, Shuangjia Zheng, Zhangming Niu, Zhang-Hua Fu, Yutong Lu, Yuedong Yang.*

1. **SumGNN: Multi-typed Drug Interaction Prediction via Efficient Knowledge Graph Summarization.** Bioinform. 2021. [[Paper]](https://arxiv.org/abs/2010.01450)

    *Yue Yu, Kexin Huang, Chao Zhang, Lucas M. Glass, Jimeng Sun, Cao Xiao.*

1. **Equivariant message passing for the prediction of tensorial properties and molecular spectra.** ICML 2021. [[Paper]](https://arxiv.org/abs/2102.03150)

    *Kristof T. Schütt, Oliver T. Unke, Michael Gastegger.*

1. **MDNN: A Multimodal Deep Neural Network for Predicting Drug-Drug Interaction Events.** IJCAI 2021. [[Paper]](https://www.ijcai.org/proceedings/2021/487)

    *Tengfei Lyu, Jianliang Gao, Ling Tian, Zhao Li, Peng Zhang, Ji Zhang.*

1. **Highly accurate protein structure prediction with AlphaFold.** Nature 2021. [[Paper]](https://www.nature.com/articles/s41586-021-03819-2)

    *John Jumper, Richard Evans, Alexander Pritzel, Tim Green, Michael Figurnov, Olaf Ronneberger, Kathryn Tunyasuvunakool, Russ Bates, Augustin Žídek, Anna Potapenko, Alex Bridgland, Clemens Meyer, Simon A. A. Kohl, Andrew J. Ballard, Andrew Cowie, Bernardino Romera-Paredes, Stanislav Nikolov, Rishub Jain, Jonas Adler, Trevor Back, Stig Petersen, David Reiman, Ellen Clancy, Michal Zielinski, Martin Steinegger, Michalina Pacholska, Tamas Berghammer, Sebastian Bodenstein, David Silver, Oriol Vinyals, Andrew W. Senior, Koray Kavukcuoglu, Pushmeet Kohli, Demis Hassabis.*

1. **Out-of-the-box deep learning prediction of pharmaceutical properties by broadly learned knowledge-based molecular representations.** Nat. Mach. Intell. 2021. [[Paper]](https://www.nature.com/articles/s42256-021-00301-6)

    *Wan Xiang Shen, Xian Zeng, Feng Zhu, Ya li Wang, Chu Qin, Ying Tan, Yu Yang Jiang, Yu Zong Chen.*

1. **GemNet: Universal Directional Graph Neural Networks for Molecules.** NeurIPS 2021. [[Paper]](https://arxiv.org/abs/2106.08903)

    *Johannes Gasteiger, Florian Becker, Stephan Günnemann.*

1. **Spherical Message Passing for 3D Graph Networks.** ICLR 2022. [[Paper]](https://arxiv.org/abs/2102.05013)

    *Yi Liu, Limei Wang, Meng Liu, Xuan Zhang, Bora Oztekin, Shuiwang Ji.*

1. **DRPreter: Interpretable Anticancer Drug Response Prediction Using Knowledge-Guided Graph Neural Networks and Transformer.** Int. J. Mol. Sci. 2022. [[Paper]](https://www.mdpi.com/1422-0067/23/22/13919)

    *Jihye Shin, Yinhua Piao, Dongmin Bang, Sun Kim, Kyuri Jo.*

1. **DENVIS: Scalable and High-Throughput Virtual Screening Using Graph Neural Networks with Atomic and Surface Protein Pocket Features.** J. Chem. Inf. Model. 2022. [[Paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01057)

    *Agamemnon Krasoulis, Nick Antonopoulos, Vassilis Pitsikalis, Stavros Theodorakis.*

1. **E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials.** Nat. Commun. 2022. [[Paper]](https://www.nature.com/articles/s41467-022-29939-5)

    *Simon Batzner, Albert Musaelian, Lixin Sun, Mario Geiger, Jonathan P Mailoa, Mordechai Kornbluth, Nicola Molinari, Tess E Smidt, Boris Kozinsky..*

1. **Geometry-enhanced molecular representation learning for property prediction.** Nat. Mach. Intell. 2022. [[Paper]](https://www.nature.com/articles/s42256-021-00438-4)

    *Xiaomin Fang, Lihang Liu, Jieqiong Lei, Donglong He, Shanzhuo Zhang, Jingbo Zhou, Fan Wang, Hua Wu, Haifeng Wang.*

1. **Spherical Message Passing for 3D Graph Networks.** ICLR 2022. [[Paper]](https://arxiv.org/abs/2102.05013)

    *Yi Liu, Limei Wang, Meng Liu, Xuan Zhang, Bora Oztekin, Shuiwang Ji.*

1. **Robust deep learning–based protein sequence design using ProteinMPNN.** Science 2022. [[Paper]](https://www.science.org/doi/10.1126/science.add2187)

    *J. Dauparas, I. Anishchenko, N. Bennett, H. Bai, R. J. Ragotte, L. F. Milles, B. I. M. Wicky, A. Courbet, R. J. de Haas, N. Bethel, P. J. Y. Leung, T. F. Huddy, S. Pellock, D. Tischer, F. Chan, B. Koepnick, H. Nguyen, A. Kang, B. Sankaran, A. K. Bera, N. P. King, D. Baker.*

1. **A Knowledge-Enhanced Multi-View Framework for Drug-Target Interaction Prediction.** TKDE 2022. [[Paper]](https://ieeexplore.ieee.org/document/9324998)

    *Ying Shen, Yilin Zhang, Kaiqi Yuan, Dagang Li, Haitao Zheng.*

<a name="preprocessing-graph-structure-augmentation" />

#### Graph structure augmentation

1. **KGNN: Knowledge Graph Neural Network for Drug-Drug Interaction Prediction.** IJCAI 2020. [[Paper]](https://www.ijcai.org/proceedings/2020/380)

    *Xuan Lin, Zhe Quan, Zhi-Jie Wang, Tengfei Ma, Xiangxiang Zeng.*

1. **Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning.** Nat. Methods 2020. [[Paper]](https://www.nature.com/articles/s41592-019-0666-6)

    *P. Gainza, F. Sverrisson, F. Monti, E. Rodolà, D. Boscaini, M. M. Bronstein, B. E. Correia.*

1. **FraGAT: a fragment-oriented multi-scale graph attention model for molecular property prediction.** Bioinform. 2021. [[Paper]](https://academic.oup.com/bioinformatics/article/37/18/2981/6189082)

    *Ziqiao Zhang, Jihong Guan, Shuigeng Zhou.*

1. **MDNN: A Multimodal Deep Neural Network for Predicting Drug-Drug Interaction Events.** IJCAI 2021. [[Paper]](https://www.ijcai.org/proceedings/2021/487)

    *Tengfei Lyu, Jianliang Gao, Ling Tian, Zhao Li, Peng Zhang, Ji Zhang.*

1. **A unified drug–target interaction prediction framework based on knowledge graph and recommendation system.** Nat. Commun. 2021. [[Paper]](https://www.nature.com/articles/s41467-021-27137-3)

    *Qing Ye, Chang-Yu Hsieh, Ziyi Yang, Yu Kang, Jiming Chen, Dongsheng Cao, Shibo He, Tingjun Hou.*

1. **scGCN is a graph convolutional networks algorithm for knowledge transfer in single cell omics.** Nat. Commun. 2021. [[Paper]](https://www.nature.com/articles/s41467-021-24172-y)

    *Qianqian Song, Jing Su, Wei Zhang.*

1. **Multi-Scale Representation Learning on Proteins.** NeurIPS 2021. [[Paper]](https://arxiv.org/abs/2204.02337)

    *Vignesh Ram Somnath, Charlotte Bunne, Andreas Krause.*

1. **Structured Multi-task Learning for Molecular Property Prediction.** AISTATS 2022. [[Paper]](https://arxiv.org/abs/2203.04695)

    *Shengchao Liu, Meng Qu, Zuobai Zhang, Huiyu Cai, Jian Tang.*

1. **DTI-HETA: prediction of drug–target interactions based on GCN and GAT on heterogeneous graph.** Brief. Bioinform. 2022. [[Paper]](https://academic.oup.com/bib/article-abstract/23/3/bbac109/6563180?redirectedFrom=fulltext)

    *Kanghao Shao, Yunhao Zhang, Yuqi Wen, Zhongnan Zhang, Song He, Xiaochen Bo.*

1. **DRPreter: Interpretable Anticancer Drug Response Prediction Using Knowledge-Guided Graph Neural Networks and Transformer.** Int. J. Mol. Sci. 2022. [[Paper]](https://www.mdpi.com/1422-0067/23/22/13919)

    *Jihye Shin, Yinhua Piao, Dongmin Bang, Sun Kim, Kyuri Jo.*

1. **ReLMole: Molecular Representation Learning Based on Two-Level Graph Similarities.** J. Chem. Inf. Model. 2022. [[Paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00798)

    *Zewei Ji, Runhan Shi, Jiarui Lu, Fang Li, and Yang Yang.*

1. **Hierarchical graph learning for protein-protein interaction.** Nat. Commun. 2023. [[Paper]](https://www.nature.com/articles/s41467-023-36736-1)

    *Ziqi Gao, Chenran Jiang, Jiawen Zhang, Xiaosen Jiang, Lanqing Li, Peilin Zhao, Huanming Yang, Yong Huang, Jia Li.*

<a name="pretraining" />

### Incorporating Knowledge in *Pretraining*

<a name="pretraining-knowledge-transfer" />

#### Knowledge transfer pretraining

1. **Knowledge-Embedded Message-Passing Neural Networks: Improving Molecular Property Prediction with Human Knowledge.** ACS Omega 2021. [[Paper]](https://pubs.acs.org/doi/10.1021/acsomega.1c03839)

    *Tatsuya Hasebe.*

1. **PEMP: Leveraging Physics Properties to Enhance Molecular Property Prediction.** CIKM 2022. [[Paper]](https://arxiv.org/abs/2211.01978)

    *Yuancheng Sun, Yimeng Chen, Weizhi Ma, Wenhao Huang, Kang Liu, Zhiming Ma, Wei-Ying Ma, Yanyan Lan.*

1. **Pre-training Molecular Graph Representation with 3D Geometry.** ICLR 2022. [[Paper]](https://arxiv.org/abs/2110.07728)

    *Shengchao Liu, Hanchen Wang, Weiyang Liu, Joan Lasenby, Hongyu Guo, Jian Tang.*

1. **OntoProtein: Protein Pretraining With Gene Ontology Embedding.** ICLR 2022. [[Paper]](https://openreview.net/forum?id=yfe1VMYAXa4)

    *Ningyu Zhang, Zhen Bi, Xiaozhuan Liang, Siyuan Cheng, Haosen Hong, Shumin Deng, Qiang Zhang, Jiazhang Lian, Huajun Chen.*

1. **3D Infomax improves GNNs for Molecular Property Prediction.** ICML 2022. [[Paper]](https://arxiv.org/abs/2110.04126)

    *Hannes Stärk, Dominique Beaini, Gabriele Corso, Prudencio Tossou, Christian Dallago, Stephan Günnemann, Pietro Liò.*

1. **Geometry-enhanced molecular representation learning for property prediction.** Nat. Mach. Intell. 2022. [[Paper]](https://www.nature.com/articles/s42256-021-00438-4)

    *Xiaomin Fang, Lihang Liu, Jieqiong Lei, Donglong He, Shanzhuo Zhang, Jingbo Zhou, Fan Wang, Hua Wu, Haifeng Wang.*

<a name="pretraining-generative-sample" />

#### Generative sample pretraining

1. **Graph Neural Networks Pretraining Through Inherent Supervision for Molecular Property Prediction.** CIKM 2022. [[Paper]](https://dl.acm.org/doi/10.1145/3511808.3557085)

    *Roy Benjamin, Uriel Singer, Kira Radinsky.*

1. **KPGT: Knowledge-Guided Pre-training of Graph Transformer for Molecular Property Prediction.** KDD 2022. [[Paper]](https://arxiv.org/abs/2206.03364)

    *Han Li, Dan Zhao, Jianyang Zeng.*

<a name="pretraining-contrastive-sample" />

#### Contrastive-sample pretraining

1. **MoCL: Data-driven Molecular Fingerprint via Knowledge-aware Contrastive Learning from Molecular Graph.** KDD 2021. [[Paper]](https://arxiv.org/abs/2106.04509)

    *Mengying Sun, Jing Xing, Huijun Wang, Bin Chen, Jiayu Zhou.*

1. **Molecular Contrastive Learning with Chemical Element Knowledge Graph.** AAAI 2022. [[Paper]](https://arxiv.org/abs/2112.00544)

    *Yin Fang, Qiang Zhang, Haihong Yang, Xiang Zhuang, Shumin Deng, Wen Zhang, Ming Qin, Zhuo Chen, Xiaohui Fan, Huajun Chen.*

<a name="training" />

### Incorporating Knowledge in *Training*

<a name="training-auxiliary-task-enhanced" />

#### Auxiliary task-enhanced training

1. **Highly accurate protein structure prediction with AlphaFold.** Nature 2021. [[Paper]](https://www.nature.com/articles/s41586-021-03819-2)

    *John Jumper, Richard Evans, Alexander Pritzel, Tim Green, Michael Figurnov, Olaf Ronneberger, Kathryn Tunyasuvunakool, Russ Bates, Augustin Žídek, Anna Potapenko, Alex Bridgland, Clemens Meyer, Simon A. A. Kohl, Andrew J. Ballard, Andrew Cowie, Bernardino Romera-Paredes, Stanislav Nikolov, Rishub Jain, Jonas Adler, Trevor Back, Stig Petersen, David Reiman, Ellen Clancy, Michal Zielinski, Martin Steinegger, Michalina Pacholska, Tamas Berghammer, Sebastian Bodenstein, David Silver, Oriol Vinyals, Andrew W. Senior, Koray Kavukcuoglu, Pushmeet Kohli, Demis Hassabis.*

1. **PEMP: Leveraging Physics Properties to Enhance Molecular Property Prediction.** CIKM 2022. [[Paper]](https://arxiv.org/abs/2211.01978)

    *Yuancheng Sun, Yimeng Chen, Weizhi Ma, Wenhao Huang, Kang Liu, Zhiming Ma, Wei-Ying Ma, Yanyan Lan.*

1. **KG-MTL: Knowledge Graph Enhanced Multi-Task Learning for Molecular Interaction.** TKDE 2022. [[Paper]](https://ieeexplore.ieee.org/document/9815157)

    *Tengfei Ma, Xuan Lin, Bosheng Song, Philip S. Yu, Xiangxiang Zeng.*

<a name="training-auxiliary-knowledge-enhanced" />

#### Auxiliary knowledge-enhanced training

1. **Knowledge-Embedded Message-Passing Neural Networks: Improving Molecular Property Prediction with Human Knowledge.** ACS Omega 2021. [[Paper]](https://pubs.acs.org/doi/10.1021/acsomega.1c03839)

    *Tatsuya Hasebe.*

<a name="interpretability" />

### Incorporating Knowledge in *Interpretability*

<a name="interpretability-attenntion-summarisation" />

#### Attention summarisation

1. **SumGNN: Multi-typed Drug Interaction Prediction via Efficient Knowledge Graph Summarization.** Bioinform. 2021. [[Paper]](https://arxiv.org/abs/2010.01450)

    *Yue Yu, Kexin Huang, Chao Zhang, Lucas M. Glass, Jimeng Sun, Cao Xiao.*

<a name="interpretability-pathway-extraction" />

#### Pathway extraction

1. **DRPreter: Interpretable Anticancer Drug Response Prediction Using Knowledge-Guided Graph Neural Networks and Transformer.** Int. J. Mol. Sci. 2022. [[Paper]](https://www.mdpi.com/1422-0067/23/22/13919)

    *Jihye Shin, Yinhua Piao, Dongmin Bang, Sun Kim, Kyuri Jo.*

1. **Knowledge-guided deep learning models of drug toxicity improve interpretation.** Patterns 2022. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36124309/)

    *Yun Hao, Joseph D Romano, Jason H Moore.*

<a name="resources" />

### Practical Resources

<a name="knowledge-database" />

#### Knowledge Database

##### Molecular and Structural 

1. **logP.** *Type:* Type. [[Paper]](https://pubs.acs.org/doi/10.1021/ci990307l)

    *Measures of a molecule’s hydrophobicity, or its partition coefficient between a nonpolar and polar solvent, and is commonly used to predict drug absorption and distribution.*

1. **rotatable bond.** *Type:* Type. [[Paper]](https://pubs.acs.org/doi/10.1021/acsomega.1c03839)

    *Annotation of the (non)rotatable bond.*

1. **MolMap.** *Type:* Software. [[Paper]](https://www.nature.com/articles/s42256-021-00301-6)

    *A method to visualise molecular structures in 3D by mapping atomic properties onto a 3D grid, allowing for the exploration and analysis of molecular interactions and properties.*

1. **RDKit.** *Type:* Software. [[Paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00456-1)

    *An open-source package to generate chemical features.*

1. **UFF.** *Type:* Table. [[Paper]](https://pubs.acs.org/doi/10.1021/ja00051a040)

    *A molecular mechanics force field designed for the full periodic table.*

1. **Mordred.** *Type:* Software. [[Paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0258-y)

    *A tool for generating molecular descriptors, which are mathematical representations of molecular structures used for molecular property analysis.*

1. **OpenBabel.** *Type:* Software. [[Paper]](https://jcheminf.biomedcentral.com/articles/10.1186/1758-2946-3-33)

    *An open-source molecular modelling software that provides a comprehensive toolkit for molecular conversion, visualisation, and analysis.*

1. **MoleculeNet.** *Type:* Database. [[Paper]](https://pubs.rsc.org/en/content/articlelanding/2018/sc/c7sc02664a)

    *A benchmark for molecular machine learning, comparing models performances on various molecular property prediction tasks such as solubility, melting point, and binding affinity.*

1. **Ptable.** *Type:* Table. [Resource](https://ptable.com/)

    *A periodic table of chemical elements classified by atomic number, electron configurations, and chemical properties into groups and periods, providing a systematic overview of elements.*

##### Compounds 

1. **CheMBL.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/30398643/)

    *A database of bioactive molecules, assays, and potency information for drug discovery and pharmaceutical research, used to facilitate target identification and selection.*

1. **PubChem.** *Type:* Database. [[Paper]](link)

    *Open database of chemical substances that contains information on their 2D and 3D structures, identifiers, properties, biological activities and occurrence in nature.*

1. **ChEBI.** *Type:* Ontology, Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/26467479/)

    *An open-source resource for molecular biology and biochemistry, providing a systematic and standardised vocabulary of molecular entities focused on small chemical compounds.*

1. **KEGG Compound.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36300620/)

    *A database of small molecular compounds, including their structures, reactions, pathways, and functions, used to provide information on metabolic pathways and cellular processes.*

1. **DrugBank.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/29126136/)

    *A database includes small molecular compounds, biologics, and natural products, providing information on their properties, mechanisms, and interactions used in drug discovery.*

##### Drugs and Targets 

1. **DDinter.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/34634800/)

    *A database of protein-protein interactions, providing information on protein targets, their interactions, and related diseases, used to advance drug discovery and development.*

1. **TCRD.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/33156327/)

    *Database that aggregates information on proteins targeted by drugs and attributes them a development/druggability level.*

1. **OpenTargets.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36399499/)

    *A database that integrates diverse genomic and molecular data to provide a comprehensive view of the relationships between diseases, genes, and molecular targets.*

1. **TTD.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/34718717/)

    *A publicly available database that provides information on protein and nucleic acid targets, drugs that target them and related diseases, used to advance drug discovery and development.*

1. **PharmGKB.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/34216021/)

    *A resource that provides information on the impact of human genetic variation on drug response, used to advance precision and personalised drug therapy.*

1. **e-TSN.** *Type:* Web platform. [[Paper]](https://academic.oup.com/bib/article/23/6/bbac465/6809962)

    *A platform that integrates knowledge on disease-target associations used for target identification. These associations were extracted from literature by using NLP techniques.*

1. **nSIDES.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/35752163/)

    *Multiple resources made available by the Tatonetti lab on drug side effects, drug-drug interactions and pediatric drug safety.*

1. **SIDER.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/26481350/)

    *A database of marketed drugs and their side effects, providing information on the frequency, type, and severity of adverse events, used to advance drug safety and pharmacovigilance.*

##### Genes and Proteins

1. **GeneOntology.** *Type:* Ontology. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/33290552/)

    *A structured and standardised ontology of gene functions, used to describe and categorise genes and gene products function in a consistent and interoperable manner.*

1. **Entrez.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/21115458/)

    *A database that includes nucleotide and protein sequences, genomic maps, taxonomy, and chemical compounds by referencing other databases, used to query various biomedical data.*

1. **Ensembl.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/34791404/)

    *A database that provides information on annotated genes, multiple sequence alignments and disease for a variety of species, including humans.*

1. **KEGG Genes.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36300620/)

    *A database that provides information on genes for complete genomes, their associated pathways, and functions in various organisms.*

1. **BioGRID.** *Type:* Database. [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7737760/)

    *A database of protein and genetic interactions curated from high-throughput experimental data sources in a variety of organisms. It includes a tool to create graphs of interactions.*

1. **UniProt.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36408920/)

    *A database of protein information, including their sequences, structure, structure and post-translational modifications.*

1. **STRING.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/25352553/)

    *A database of protein-protein interactions and functional associations, integrating diverse data sources and evidence to provide a weighted network of functional relationships.*

1. **HumanNet.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/30418591/)

    *Network of protein-protein and functional gene interactions, constructed by integrating high-throughput datasets and literature, used to advance understanding of disease gene prediction.*

1. **STITCH.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/26590256/)

    *A database of known and predicted interactions between chemicals and proteins (physical and functional associations), used for the study of molecular interactions.*

1. **PDB.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/10592235/)

    *A database that provides information on the 3D structure of proteins, nucleic acids, and complex molecular assemblies, obtained experimentally or predicted.*

1. **RNAcentral.** *Type:* Database. [[Paper]](https://academic.oup.com/nar/article/49/D1/D212/5940500)

    *A repository that integrates information on non-coding RNA sequences for a variety of organisms and attributes them to a unique identifier.*


##### Pathways

1. **Reactome.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/34788843/)

    *A database that stores and curates information about the molecular pathways in humans, providing insights into cellular processes and disease mechanisms.*

1. **KEGG pathways.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36300620/)

    *A database of curated biological pathways and interconnections between them, manually represented  as pathway maps of molecular reactions and interactions.*

1. **WikiPathways.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/33211851/)

    *A database of biological pathways that integrates information from several databases, which aims to provide an overview of molecular interactions and reactions.*

##### Disease

1. **Disease Ontology.** *Type:* Ontology. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/34755882/)

    *Disease Ontology (DO) is an ontology of human disease that integrates MeSH, ICD, OMIM, NCI Thesaurus and SNOMED nomenclatures.*

1. **MonDO.** *Type:* Ontology. [[Paper]](https://www.medrxiv.org/content/10.1101/2022.04.13.22273750v1)

    *Semi-automatic unifying terminology between different disease ontologies.*

1. **Orphanet.** *Type:* Database. [Resource](https://www.orpha.net/consor/cgi-bin/index.php)

    *A database that maintains information on rare diseases and orphan drugs using cross-references to other commonly used ontologies.*

1. **OMIM.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/30445645/)

    *A comprehensive, searchable database of gene-disease associations for Mendelian disorders.*

1. **KEGG Disease.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36300620/)

    *A database of disease entries that are characterised by their perturbants (genetic or environmental factors, drugs, and pathogens).*

1. **ICD-11.** *Type:* Ontology. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/34753471/)

    *The 11th version of the international resource for recording health and clinical data in a standardised format that is constantly updated.*

1. **Disgenet.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/31680165/)

    *A database that integrates manually curated data from GWAS studies, animal models, and scientific literature to identify gene-disease associations. It can be used for target identification and prioritisation.*

1. **DISEASES.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/25484339/)

    *A database for disease-gene associations based on manually curated data, cancer mutation data, GWAS, and automatic text mining.*

1. **GWAS Catalog.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36350656/)

    *Repository of published Genome-Wide Association Studies (GWAS) for investigating the impact of genomic variants on complex diseases.*

1. **SemMedDB.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/23044550/)

    *A database that provides information on the relationships between genes and diseases, extracted from the biomedical literature.*

1. **OncoKB.** *Type:* Database. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/28890946/)

    *A knowledge precision database containing information on human genetic alterations detected in different cancer types.*

1. **HPO.** *Type:* Ontology. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/33264411/)

    *The Human Phenotype Ontology (HPO) is an ontology of human phenotypes and database of disease-phenotype associations with cross-references to other relevant databases.*

##### Medical Terms and Anatomy

1. **Uberon.** *Type:* Ontology. [[Paper]](https://jbiomedsem.biomedcentral.com/articles/10.1186/2041-1480-5-21)

    *A multi-species anatomy ontology. It covers various anatomical systems for organs and tissues.*

1. **BRENDA.** *Type:* Ontology. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/33211880/)

    *A tissue ontology for enzyme source comprising tissues, cell lines, cell types and cultures.*

1. **TISSUES.** *Type:* Database. [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5808782/)

    *A database for gene expression in tissues that contains manually curated knowledge, proteomics, transcriptomics, and automatic text mining. Annotated with BRENDA tissue ontology.*

1. **MeSH.** *Type:* Vocabulary. [[Paper]](https://jbiomedsem.biomedcentral.com/articles/10.1186/s13326-017-0128-y)

    *A comprehensive controlled vocabulary used for biomedical and health-related information.*

1. **UMLS.** *Type:* Ontology. [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC308795/)

    *A biomedical terminologies and ontologies database that integrates and harmonises data from a variety of sources to support clinical documentation and research in healthcare.*

<a name="knowledge-graph" />

#### Knowledge Graph

1. **Hetionet.** *Intended Usage:* Drug discovery, Drug repurposing, etc. [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4497619/)

    *An integrated KG of more than 12,000 nodes representing various biological, medical and social entities and their relationships. It is a valuable resource combining many different databases that can be used for drug discovery and repurposing.*

1. **PharmKG.** *Intended Usage:* Drug discovery. [[Paper]](https://academic.oup.com/bib/article/22/4/bbaa344/6042240)

    *A comprehensive biomedical KG integrating information from various databases, literature, and experiments. It is mainly centered around interactions between genes, diseases and drugs.*

1. **DRKG.** *Intended Usage:* Drug repurposing. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/33571675/)

    *A large-scale, cross-domain KG that integrates information about drugs, proteins, diseases, and chemical compounds. It is based on Hetionet, and it was used for drug repurposing for Covid-19.*

1. **CKG.** *Intended Usage:* Biomarker discovery, Drug prioritisation. [[Paper]](https://www.nature.com/articles/s41587-021-01145-6)

    *A KG developed for precision medicine that combines various databases and integrates clinical and omics data. It allows for automated upload and integration of new omics data with pre-existing knowledge.*

1. **OpenBioLink.** *Intended Usage:* Drug discovery. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/32339214/)

    *An open-source KG that integrates diverse biomedical data from various databases. It was developed to enable benchmarking of ML algorithms.*

1. **BioKG.** *Intended Usage:* Pathway discovery, Drug discovery. [[Paper]](https://dl.acm.org/doi/10.1145/3340531.3412776)

    *A KG that integrates information about genes, proteins, diseases, drugs, and other biological entities. It aims at providing a standardised KG in a unified format with stable IDs.*

1. **Bioteque.** *Intended Usage:* Broad usage. [[Paper]](https://www.nature.com/articles/s41467-022-33026-0)

    *A KG that enables the discovery of relationships between genes, proteins, diseases, drugs, and other entities, providing an overview of biological knowledge for use in biomedical research and personalised medicine.*

1. **Harmonizome.** *Intended Usage:* Drug discovery, Precision medicine. [[Paper]](https://pubmed.ncbi.nlm.nih.gov/27374120/)

    *A KG that focuses on gene- and protein-centric information and their interactions. It provides a unified view of biological knowledge and enables the discovery of new insights fin the biomedical field.*


[//]: # (## Cite)

[//]: # ()
[//]: # (Please cite our paper if it is helpful in your own work:)

[//]: # ()
[//]: # (```bibtex)

[//]: # (@article{ZBM23,)

[//]: # (  title={Knowledge-augmented Graph Machine Learning for Drug Discovery: A Survey from Precision to Interpretability},)

[//]: # (  author={Zhiqiang Zhong and Anastasia Barkova and Davide Mottin},)

[//]: # (  journal = {CoRR},)

[//]: # (  volume = {abs/2302.08261},)

[//]: # (  year={2023},)

[//]: # (})

[//]: # (```)
