# Visual Dialogue Papers
A list of papers about creating visual dialogue papers **Please feel free to add an issue or pull request for missing papers**.

## Datasets
### Open Domain
* [Visual Dialogue](https://arxiv.org/abs/1611.08669), Abhishek Das et al., CVPR 2017 

* [Visual Reference Resolution using Attention Memory for Visual Dialog](https://arxiv.org/abs/1709.07992), Paul Hongsuck Seo et al., NIPS 2017

* [Image-Grounded Conversations: Multimodal Context for Natural Question and Response Generation](https://aclanthology.org/I17-1047/), Nasrin Mostafazadeh et al., IJCNLP 2017

* MMD, [MMD: Towards Building Large Scale Multimodal Domain-Aware Conversation Systems](https://arxiv.org/abs/1704.00200), Amrita Saha et al., AAAI 2018

* CLEVR-Dialog, [CLEVR-Dialog: A Diagnostic Dataset for Multi-Round Reasoning in Visual Dialog](https://arxiv.org/abs/1903.03166), Satwik Kottur et al., NAACL 2019

* AVSA, [Audio-Visual Scene-Aware Dialog](https://arxiv.org/abs/1901.09107), Huda Alamri et al., CVPR 2019

* Image-chat, [Image-Chat: Engaging Grounded Conversations](https://arxiv.org/abs/1811.00945), Kurt Shuster et al., ACL 2020, [HomePage](https://parl.ai/projects/image_chat/)

* [Multi-Modal Open-Domain Dialogue](https://arxiv.org/abs/2010.01082), Kurt Shuster et al., *arXiv* 2020, [HomePage](https://github.com/facebookresearch/ParlAI/tree/master/projects/multimodal_blenderbot)

* [Constructing Multi-Modal Dialogue Dataset by Replacing Text with Semantically Relevant Images](https://arxiv.org/abs/2107.08685), Nyoungwoo Lee et al., ACL 2021, [HomePage](https://github.com/shh1574/multi-modal-dialogue-dataset)

* MMChat, [MMChat: Multi-Modal Chat Dataset on Social Media](https://arxiv.org/abs/2108.07154), Yinhe Zheng et al., CVPR 2021

* OpenViDial, [OpenViDial: A Large-Scale, Open-Domain Dialogue Dataset with Visual Contexts](https://arxiv.org/abs/2012.15015), Yuxian Meng et al., *arXiv* 2021

* OpenViDial 2.0, [OpenViDial 2.0: A Larger-Scale, Open-Domain Dialogue Generation Dataset with Visual Contexts](https://arxiv.org/abs/2109.12761v2), Shuhe Wang et al., *arXiv* 2021

### Goal Oriented

* GuessWhat, [GuessWhat?! Visual object discovery through multi-modal dialogue](https://arxiv.org/abs/1611.08481), Harm de Vries et al., CVPR 2017

* SIMMC, [SIMMC: Situated Interactive Multi-Modal Conversational Data Collection And Evaluation Platform](), et al., DSTC9 2020, [HomePage](https://github.com/facebookresearch/simmc)

* SIMMC 2.0, [SIMMC 2.0: A Task-oriented Dialog Dataset for Immersive Multimodal Conversations](), et al., DSTC10 2021, [HomePage](https://github.com/facebookresearch/simmc2)

* The JDDC 2.0, [The JDDC 2.0 Corpus: A Large-Scale Multimodal Multi-Turn Chinese Dialogue Dataset for E-commerce Customer Service](https://arxiv.org/abs/2109.12913), et al., *arXiv* 2021, [HomePage](https://jddc.jd.com/)


## Challenge
* [visualdialog](https://visualdialog.org/), 2020

* [Audio Visual Scene-Aware Dialog (AVSD) Challenge](https://video-dialog.com/), Bing Liu, *arXiv*, 2016


# Open Domain
### Pretraining

* VisualBERT, [Large-scale Pretraining for Visual Dialog: A Simple State-of-the-Art Baseline](https://arxiv.org/abs/1912.02379), Vishvak Murahari et al., ECCV 2020, [HomePage](https://github.com/vmurahari3/visdial-bert)

* VDBERT, [VD-BERT: A Unified Vision and Dialog Transformer with BERT](https://arxiv.org/abs/2004.13278), Yue Wang et al., EMNLP 2020, [HomePage](https://github.com/salesforce/VD-BERT)


### Transformer

* [Bridging Text and Video: A Universal Multimodal Transformer for Video-Audio Scene-Aware Dialog](https://arxiv.org/abs/2002.00163), Zekang Li et al., AAAI2020 DSTC8 workshop

* MITVG, [Multimodal Incremental Transformer with Visual Grounding for Visual Dialogue Generation](https://arxiv.org/abs/2109.08478), Feilong Chen et al., ACL Fingdings 2021

* [](), et al., 2016


### Attention-based models

* HCIAE, [Best of Both Worlds: Transferring Knowledge from Discriminative Learning to a Generative Visual Dialog Model](https://arxiv.org/abs/1706.01554), Jiasen Lu et al., NIPS 2017

* Primary, [Image-Question-Answer Synergistic Network for Visual Dialog](https://arxiv.org/abs/1902.09774), Dalu Guo et al., CVPR 2019

* ReDAN, [Multi-step Reasoning via Recurrent Dual Attention for Visual Dialog](https://arxiv.org/abs/1902.00579), Zhe Gan et al., ACL 2019

* DVAN, [Dual Visual Attention Network for Visual Dialog](https://www.ijcai.org/Proceedings/2019/0693.pdf), Dan Guo et al., IJCAI 2019, [Code](https://github.com/gicheonkang/dan-visdial)

* RvA, [Recursive Visual Attention in Visual Dialog](https://arxiv.org/abs/1812.02664), Yulei Niu et al., CVPR 2019

* DMRM, [DMRM: A Dual-channel Multi-hop Reasoning Model for Visual Dialog](https://arxiv.org/abs/1912.08360), Feilong Chen et al., AAAI 2020


### Graph-based models

* GNN-EM, [Reasoning Visual Dialogs with Structural and Partial Observations](https://arxiv.org/abs/1904.05548), Zilong Zheng et al., CVPR 2019

* DualVD, [DualVD: An Adaptive Dual Encoding Model for Deep Visual Understanding in Visual Dialogue](https://arxiv.org/abs/1911.07251), Xiaoze Jiang et al., AAAI 2020

* FGA, [Factor Graph Attention](https://arxiv.org/abs/1904.05880), Idan Schwartz et al., CVPR 2019

* KBGN, [KBGN: Knowledge-Bridge Graph Network for Adaptive Vision-Text Reasoning in Visual Dialogue](https://arxiv.org/abs/2008.04858), Xiaoze Jiang et al., ACM MM 2020

* GoG, [GoG: Relation-aware Graph-over-Graph Network for Visual Dialog](https://arxiv.org/abs/2109.08475), Feilong Chen et al., ACL Findings 2021


### GAN

* CoAtt, [Are You Talking to Me? Reasoned Visual Dialog Generation through Adversarial Learning](https://arxiv.org/abs/1711.07613), Qi Wu et al., CVPR 2018


### General

* CorefNMN, [Visual Coreference Resolution in Visual Dialog using Neural Module Networks](https://arxiv.org/abs/1809.01816), Satwik Kottur et al., ECCV 2018

* [Making History Matter: History-Advantage Sequence Training for Visual Dialog](https://arxiv.org/abs/1902.09326), Tianhao Yang et al., ICCV 2019

* [Generative Visual Dialogue System via Adaptive Reasoning and Weighted Likelihood Estimation](https://arxiv.org/abs/1902.09818), Heming Zhang et al., IJCAI 2019

* [Granular Multimodal Attention Networks for Visual Dialog](https://arxiv.org/abs/1910.05728), Badri N. Patro et al., ICCV Workshop 2019

* [Modality-Balanced Models for Visual Dialogue](https://arxiv.org/abs/2001.06354), Hyounghun Kim et al., AAAI 2020

* LTMI, [Efficient Attention Mechanism for Visual Dialog that can Handle All the Interactions between Multiple Inputs](https://arxiv.org/abs/1911.11390), Van-Quang Nguyen et al., ECCV 2020

* [Multi-View Attention Network for Visual Dialog](https://arxiv.org/abs/2004.14025), Sungjin Park et al., ACL 2020, [[Code]](https://github.com/taesunwhang/MVAN-VisDial)

* MCA, [History for Visual Dialog: Do we really need it?](https://aclanthology.org/2020.acl-main.728/), Shubham Agarwal et al., ACL 2020

* CAG, [Iterative Context-Aware Graph Inference for Visual Dialog](https://arxiv.org/abs/2004.02194), Dan Guo et al., CVPR 2020

* DAM, [DAM: Deliberation, Abandon and Memory Networks for Generating Detailed and Non-repetitive Responses in Visual Dialogue](https://arxiv.org/abs/2007.03310), Xiaoze Jiang et al., IJCAI 2020, [Code](https://github.com/JXZe/DAM)

* [Learning to Ground Visual Objects for Visual Dialog](https://arxiv.org/abs/2109.06013), Feilong Chen et al., EMNLP 2021

![image](https://user-images.githubusercontent.com/1453642/138843697-fc1af98b-5cc9-4c6d-be94-a7e3f638ea13.png)


* [](), et al., 2016

* [](), et al., 2016

* [](), et al., 2016


## Goal Oriented

### Reinforcement Learning

* [](), et al., 2016

* [](), et al., 2016

* [](), et al., 2016



### General

* [DialogStitch: Synthetic Deeper and Multi-Context Task-Oriented Dialogs](https://aclanthology.org/2021.sigdial-1.3.pdf), Satwik Kottur et al., SIGDIAL 2021, [[code]](https://github.com/facebookresearch/DialogStitch)

* [An Analysis of State-of-the-Art Models for Situated Interactive MultiModal Conversations (SIMMC)](https://aclanthology.org/2021.sigdial-1.15/), Satwik Kottur et al., SIGDIAL 2021, [[video]](https://www.youtube.com/watch?v=VmdHZSno2MQ)

* [](), et al., 2016

* [](), et al., 2016

* [](), et al., 2016

* [](), et al., 2016

* [](), et al., 2016

* [](), et al., 2016

* [](), et al., 2016



## Pretraining in Vision and Language
* [UNITER: UNiversal Image-TExt Representation Learning](https://arxiv.org/abs/1909.11740), Bing Liu, *arXiv*, 2016

* [Kaleido-BERT: Vision-Language Pre-training on Fashion Domain](), et al., CVPR 2021

* [](), et al., 2016

![image](https://user-images.githubusercontent.com/1453642/138585957-2762d461-b75e-4ec6-9c32-7b45152a554b.png)



## Related Survey

* [Trends in Integration of Vision and Language Research: A Survey of Tasks, Datasets, and Methods](https://arxiv.org/abs/1907.09358), Aditya Mogadala et al., JAIR 2021

* [](), et al., 2016


## Visual Dialog Challenge Starter Code

* [Visual Dialog Challenge 2019](https://github.com/batra-mlp-lab/visdial-challenge-starter-pytorch)


## Researchers' Homepage
* Satwik Kottur, https://satwikkottur.github.io/

* 
