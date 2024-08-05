# Bidirectional Human-AI Alignment - Reading List


This repository lists papers on **[Bidirectional Human-AI Alignment](https://arxiv.org/pdf/2406.09264)** [Paper](https://arxiv.org/pdf/2406.09264) research, primarily covering papers in Human-Computer Interaction (HCI), Natural Language Processing (NLP) and Machine Learng (ML) fields. 

<!-- Reference: https://github.com/zhijing-jin/Causality4NLP_Papers -->


**Contributor:** [Hua Shen](https://hua-shen.org/).
Welcome to be a collaborator, -- you can make an issue/pull request, and I can add you.


### Contents (Actively Updating)

- [1. Alignment Basics](#1-alignment-basics)
  - [1.1 Overview Papers](#11-overview-papers)
  - [1.2 Alignment Goals and Human Value Theories](#12-alignment-goals-and-human-value-theories)
- [2. Human Values and Specifications](#2-human-values-and-specifications)
  - [2.1 Human Value Category](#21-human-value-category)
    - [2.1.1 Source of Values](#211-source-of-values)
    - [2.1.2 Value Types](#212-value-types)
  - [2.2 Interaction Techniques to Specify AI Values](#22-interaction-techniques-to-specify-ai-values)
    - [2.2.1 Explicit Human Feedback](#221-explicit-human-feedback)
    - [2.2.2 Implicit Human Feedback](#222-implicit-human-feedback)
    - [2.2.3 Simulated Human Value Feedback](#223-simulated-human-value-feedback)
- [3. Integrating Human Specifications into AI](#3-integrating-human-specifications-into-ai)
  - [3.1 Develop AI with General Values](#31-develop-ai-with-general-values)
    - [3.1.1 Instruction Data](#311-instruction-data)
    - [3.1.2 Model Learning](#312-model-learning)
    - [3.1.3 Inference Stage](#313-inference-stage)
  - [3.2 Customizing AI for Individuals and Groups](#32-customizing-ai-for-individuals-and-groups)
    - [3.2.1 Customized Data](#321-customized-data)
    - [3.2.2 Adapt Model by Learning](#322-adapt-model-by-learning)
    - [3.2.3 Interactive Alignment](#323-interactive-alignment)
  - [3.3 Evaluating AI Systems](#33-evaluating-ai-systems)
    - [3.3.1 Human-In-The-Loop-Evaluation](#331-human-in-the-loop-evaluation)
    - [3.3.2 Automatic Evaluation](#332-automatic-evaluation)
  - [3.4 Ecosystem](#34-ecosystem)
    - [3.4.1 Platforms](#341-platforms)
- [4. Human Cognitive Adjustment to AI](#4-human-cognitive-adjustment-to-ai)
  - [4.1 Perceiving and Understanding of AI](#41-perceiving-and-understanding-of-ai)
    - [4.1.1 Education and Training Human](#411-education-and-training-human)
    - [4.1.2 AI Sensemaking and Explanations](#412-ai-sensemaking-and-explanations)
  - [4.2 Critical Thinking about AI](#42-critical-thinking-about-ai)
    - [4.2.1 Trust and Reliance on AI Decisions](#421-trust-and-reliance-on-ai-decisions)
    - [4.2.2 Ethical Concerns and AI Auditing](#422-ethical-concerns-and-ai-auditing)
    - [4.2.3 Calibrate Cognition to Align AI](#423-calibrate-cognition-to-align-ai)
- [5. Human Adaptive Behavior to AI](#5-human-adaptive-behavior-to-ai)
  - [5.1 Human Collaborating with Diverse AI Roles](#51-human-collaborating-with-diverse-ai-roles)
    - [5.1.1 Assistants](#511-assistants)
    - [5.1.2 Partners](#512-partners)
    - [5.1.3 Tutors](#513-tutors)
  - [5.2 AI Impacts on Human and Society](#52-ai-impacts-on-human-and-society)
    - [5.2.1 Impact on Individual Behavior](#521-impact-on-individual-behavior)
    - [5.2.2 Societal Concerns and AI Impacts](#522-societal-concerns-and-ai-impacts)
    - [5.2.3 Reaction to AI Advancements](#523-reaction-to-ai-advancements)
  - [5.3 Evaluation in Human Studies](#53-evaluation-in-human-studies)
    - [5.3.1 Evaluate Human-AI Collaboration](#531-evaluate-human-ai-collaboration)
    - [5.3.2 Evaluate Societal Impact](#532-evaluate-societal-impact)
- [6. Others](#6-others)


## 1. Alignment Basics

### 1.1 Overview Papers (Chronological)

1. **Open problems and fundamental limitations of reinforcement learning from human feedback.** *Casper, Stephen, Xander Davies, Claudia Shi, Thomas Krendl Gilbert, Jérémy Scheurer, Javier Rando, Rachel Freedman et al.*, Sep 2023. [[pdf]](https://arxiv.org/pdf/2307.15217)


2. **AI alignment in the design of interactive AI: Specification alignment, process alignment, and evaluation support.** *Terry, Michael, Chinmay Kulkarni, Martin Wattenberg, Lucas Dixon, and Meredith Ringel Morris.*, Oct 2023. [[pdf]](https://arxiv.org/pdf/2311.00710)


3. **A roadmap to pluralistic alignment.** *Sorensen, Taylor, Jared Moore, Jillian Fisher, Mitchell Gordon, Niloofar Mireshghallah, Christopher Michael Rytting, Andre Ye et al.*, Feb 2024. [[pdf]](https://arxiv.org/pdf/2402.05070)


4. **Foundational challenges in assuring alignment and safety of large language models.** *Anwar, Usman, Abulhair Saparov, Javier Rando, Daniel Paleka, Miles Turpin, Peter Hase, Ekdeep Singh Lubana et al.*, Apr 2024. [[pdf]](https://arxiv.org/pdf/2404.09932)


5. **Managing extreme AI risks amid rapid progress.** *Bengio, Yoshua, Geoffrey Hinton, Andrew Yao, Dawn Song, Pieter Abbeel, Trevor Darrell, Yuval Noah Harari et al.*, May 2024. [[pdf]](https://arxiv.org/pdf/2310.17688)


6. **Towards Bidirectional Human-AI Alignment: A Systematic Review for Clarifications, Framework, and Future Directions.** *Shen, Hua, Tiffany Knearem, Reshmi Ghosh, Kenan Alkiek, Kundan Krishna, Yachuan Liu, Ziqiao Ma et al.*, Jun 2024. [[pdf]](https://arxiv.org/pdf/2406.09264)


### 1.2 Alignment Goals and Human Value Theories

1. **Artificial intelligence, values, and alignment.** *Gabriel, Iason.*, 2020. [[pdf]](https://link.springer.com/content/pdf/10.1007/s11023-020-09539-2.pdf)

2. (Schwartz Theory of Basic Values) **Are there universal aspects in the structure and contents of human values?.** *Schwartz, Shalom H.*, 1994. [[pdf]](https://spssi.onlinelibrary.wiley.com/doi/pdfdirect/10.1111/j.1540-4560.1994.tb01196.x)


3. (Schwartz Theory of Basic Values) **An overview of the Schwartz theory of basic values.** *Schwartz, Shalom H.*, 2012. [[pdf]](https://scholarworks.gvsu.edu/cgi/viewcontent.cgi?article=1116&context=orpc)

4. (Moral Foundation Theory) **Moral foundations theory: The pragmatic validity of moral pluralism.** *Graham, Jesse, Jonathan Haidt, Sena Koleva, Matt Motyl, Ravi Iyer, Sean P. Wojcik, and Peter H. Ditto.*, 2013. [[pdf]](https://www.sciencedirect.com/science/article/pii/B9780124072367000024)




## 2. Human Values and Specifications

### 2.1 Human Value Category

#### 2.1.1 Source of Values

**Individuals:**


1. (2019 CHI) **Improving fairness in machine learning systems: What do industry practitioners need?.** *Holstein, Kenneth, Jennifer Wortman Vaughan, Hal Daumé III, Miro Dudik, and Hanna Wallach.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3290605.3300830)

3. (2022 Arxiv) **Red teaming language models to reduce harms: Methods, scaling behaviors, and lessons learned.** *Ganguli, Deep, Liane Lovitt, Jackson Kernion, Amanda Askell, Yuntao Bai, Saurav Kadavath, Ben Mann et al.*  arXiv preprint arXiv:2209.07858 (2022).

2. (2023 EMNLP) **Ethical reasoning over moral alignment: A case and framework for in-context ethical policies in LLMs.** *Rao, Abhinav, Aditi Khandelwal, Kumar Tanmay, Utkarsh Agarwal, and Monojit Choudhury.* [[pdf]](https://aclanthology.org/2023.findings-emnlp.892.pdf)



3. (2021 CHI) **Human perceptions on moral responsibility of AI: A case study in AI-assisted bail decision-making**. *Lima, Gabriel, Nina Grgić-Hlača, and Meeyoung Cha*. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3411764.3445260?casa_token=1f8C9397M5UAAAAA:axhwwncFHhzsQgRueN8OER4kJuAGVO61zL7ic3OJviG-8FYuPY3dbdzh77M05Ko0xXi3RhU6h9T4)
<!-- {:target="_blank"} -->


**Society:**


1. (2023 EMNLP) **Do llms understand social knowledge? evaluating the sociability of large language models with socket benchmark.** *Choi, Minje, Jiaxin Pei, Sagar Kumar, Chang Shu, and David Jurgens.* [[pdf]](https://arxiv.org/pdf/2305.14938)

2. (2023 CHI) **Competent but Rigid: Identifying the Gap in Empowering AI to Participate Equally in Group Decision-Making.** *Zheng, Chengbo, Yuheng Wu, Chuhan Shi, Shuai Ma, Jiehui Luo, and Xiaojuan Ma.*

2. (2023 ACL) **The ecological fallacy in annotation: Modelling human label variation goes beyond sociodemographics.** *Orlikowski, Matthias, Paul Röttger, Philipp Cimiano, and Dirk Hovy.* [[pdf]](https://aclanthology.org/2023.acl-short.88.pdf)


1. (2023 Arxiv) **TASRA: a taxonomy and analysis of societal-scale risks from AI.** *Critch, Andrew, and Stuart Russell.* arXiv preprint arXiv:2306.06924 (2023). [[pdf]](https://arxiv.org/pdf/2306.06924)


5. (2020 EMNLP) **Social chemistry 101: Learning to reason about social and moral norms.** *Forbes, Maxwell, Jena D. Hwang, Vered Shwartz, Maarten Sap, and Yejin Choi.*  [[pdf]](https://arxiv.org/pdf/2011.00620)


**Interaction:**


1. (2023 EMNLP) **FANToM: A benchmark for stress-testing machine theory of mind in interactions.** *Kim, Hyunwoo, Melanie Sclar, Xuhui Zhou, Ronan Le Bras, Gunhee Kim, Yejin Choi, and Maarten Sap.* [[pdf]](https://aclanthology.org/2023.emnlp-main.890.pdf)


2. (2024 NeurIPS) **Lima: Less is more for alignment.** *Zhou, Chunting, Pengfei Liu, Puxin Xu, Srinivasan Iyer, Jiao Sun, Yuning Mao, Xuezhe Ma et al.* [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/ac662d74829e4407ce1d126477f4a03a-Paper-Conference.pdf)




#### 2.1.2 Value Types


**Self-Enhancement:**

<!-- 1. (2024 CHI) **Rehearsal: Simulating conflict to teach conflict resolution.** *Shaikh, Omar, Valentino Emil Chai, Michele Gelfand, Diyi Yang, and Michael S. Bernstein.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3613904.3642159)


2. (2024 AIED) **How to Teach Programming in the AI Era? Using LLMs as a Teachable Agent for Debugging.** *Ma, Qianou, Hua Shen, Kenneth Koedinger, and Sherry Tongshuang Wu.* [[pdf]](https://www.cs.cmu.edu/~sherryw/assets/pubs/2024-hypocompass.pdf) -->


**Self-Transcendence:**

1. (2023 NeurIPS) **Auditing for human expertise.** *Alur, Rohan, Loren Laine, Darrick Li, Manish Raghavan, Devavrat Shah, and Dennis Shung.* [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/fb44a668c2d4bc984e9d6ca261262cbb-Paper-Conference.pdf)


2. (2022 Arxiv) **Training a helpful and harmless assistant with reinforcement learning from human feedback.** *Bai, Yuntao, Andy Jones, Kamal Ndousse, Amanda Askell, Anna Chen, Nova DasSarma, Dawn Drain et al.* [[pdf]](https://arxiv.org/pdf/2204.05862?spm=a2c6h.13046898.publish-article.36.6cd56ffaIPu4NQ&file=2204.05862)

**Conservation:**

1. (2022 Arxiv) **Constitutional ai: Harmlessness from ai feedback.** *Bai, Yuntao, Saurav Kadavath, Sandipan Kundu, Amanda Askell, Jackson Kernion, Andy Jones, Anna Chen et al.* [[pdf]](https://arxiv.org/pdf/2212.08073)

2. (2024, ICLR) **Fine-tuning aligned language models compromises safety, even when users do not intend to!.** *Qi, Xiangyu, Yi Zeng, Tinghao Xie, Pin-Yu Chen, Ruoxi Jia, Prateek Mittal, and Peter Henderson.* [[pdf]](https://openreview.net/pdf?id=hTEGyKf0dZ)


**Openness to Change:**

1. (2023 ACL) **Increasing diversity while maintaining accuracy: Text data generation with large language models and human interventions.** *Chung, John Joon Young, Ece Kamar, and Saleema Amershi.* [[pdf]](https://aclanthology.org/2023.acl-long.34.pdf)

2. (2024 ICLR) **Fine-tuning language models for factuality.** *Tian, Katherine, Eric Mitchell, Huaxiu Yao, Christopher D. Manning, and Chelsea Finn.* [[pdf]](https://arxiv.org/pdf/2311.08401)


**Desired Values from AI Tools:**

1. (2024 ICLR) **Generative judge for evaluating alignment.** *Li, Junlong, Shichao Sun, Weizhe Yuan, Run-Ze Fan, Hai Zhao, and Pengfei Liu.* [[pdf]](https://arxiv.org/pdf/2310.05470)

2. (2022 ACL) **Are shortest rationales the best explanations for human understanding?.** *Shen, Hua, Tongshuang Wu, Wenbo Guo, and Ting-Hao'Kenneth Huang.* [[pdf]](https://arxiv.org/pdf/2203.08788)


### 2.2 Interaction Techniques to Specify AI Values

#### 2.2.1 Explicit Human Feedback

1. (2022 NeurIPS) **Training language models to follow instructions with human feedback.** *Ouyang, Long, Jeffrey Wu, Xu Jiang, Diogo Almeida, Carroll Wainwright, Pamela Mishkin, Chong Zhang et al.*  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/file/b1efde53be364a73914f58805a001731-Paper-Conference.pdf)

2. (2023 ACL) **Rl4f: Generating natural language feedback with reinforcement learning for repairing model outputs.** Akyürek, Afra Feyza, Ekin Akyürek, Aman Madaan, Ashwin Kalyan, Peter Clark, Derry Wijaya, and Niket Tandon. [[pdf]](https://arxiv.org/pdf/2305.08844)

3. (2023 IUI) **Constitutionmaker: Interactively critiquing large language models by converting feedback into principles.** *Petridis, Savvas, Benjamin D. Wedin, James Wexler, Mahima Pushkarna, Aaron Donsbach, Nitesh Goyal, Carrie J. Cai, and Michael Terry.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3640543.3645144)


#### 2.2.2 Implicit Human Feedback

1. (2023 EMNLP) **Towards a holistic landscape of situated theory of mind in large language models.** *Ma, Ziqiao, Jacob Sansom, Run Peng, and Joyce Chai.*  [[pdf]](https://aclanthology.org/2023.findings-emnlp.72.pdf)

2. (2023 EMNLP) **Hi-tom: A benchmark for evaluating higher-order theory of mind reasoning in large language models.** *He, Yinghui, Yufan Wu, Yilin Jia, Rada Mihalcea, Yulong Chen, and Naihao Deng.* [[pdf]](https://arxiv.org/pdf/2310.16755)

3. (2021 EMNLP) **A scalable framework for learning from implicit user feedback to improve natural language understanding in large-scale conversational ai systems.** *Park, Sunghyun, Han Li, Ameen Patel, Sidharth Mudgal, Sungjin Lee, Young-Bum Kim, Spyros Matsoukas, and Ruhi Sarikaya.* [[pdf]](https://aclanthology.org/2021.emnlp-main.489.pdf)


#### 2.2.3 Simulated Human Value Feedback

1. (2024 ICLR) **Identifying the risks of lm agents with an lm-emulated sandbox.** *Ruan, Yangjun, Honghua Dong, Andrew Wang, Silviu Pitis, Yongchao Zhou, Jimmy Ba, Yann Dubois, Chris J. Maddison, and Tatsunori Hashimoto.* [[pdf]](https://openreview.net/pdf?id=GEcwtMk1uA)

2. (2023 EMNLP) **Aligning large language models through synthetic feedback.** *Kim, Sungdong, Sanghwan Bae, Jamin Shin, Soyoung Kang, Donghyun Kwak, Kang Min Yoo, and Minjoon Seo.* [[pdf]](https://aclanthology.org/2023.emnlp-main.844.pdf)


## 3. Integrating Human Specifications into AI

### 3.1 Develop AI with General Values

#### 3.1.1 Instruction Data

1. (2023 EMNLP) **Multiturncleanup: A benchmark for multi-turn spoken conversational transcript cleanup.**, *Shen, Hua, Vicky Zayats, Johann C. Rocholl, Daniel D. Walker, and Dirk Padfield.* [[pdf]](https://arxiv.org/pdf/2305.12029)


2. (2023 EMNLP) **Coannotating: Uncertainty-guided work allocation between human and large language models for data annotation.** *Li, Minzhi, Taiwei Shi, Caleb Ziems, Min-Yen Kan, Nancy F. Chen, Zhengyuan Liu, and Diyi Yang.* [[pdf]](https://aclanthology.org/2023.emnlp-main.92.pdf)

3. (2024 NeurIPS) **RRHF: Rank responses to align language models with human feedback.** *Yuan, Hongyi, Zheng Yuan, Chuanqi Tan, Wei Wang, Songfang Huang, and Fei Huang.* [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/23e6f78bdec844a9f7b6c957de2aae91-Paper-Conference.pdf)


#### 3.1.2 Model Learning

1. (2024 NeurIPS) **Direct preference optimization: Your language model is secretly a reward model.** *Rafailov, Rafael, Archit Sharma, Eric Mitchell, Christopher D. Manning, Stefano Ermon, and Chelsea Finn.* [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/a85b405ed65c6477a4fe8302b5e06ce7-Paper-Conference.pdf)


2. (2023 TMLR) **Raft: Reward ranked finetuning for generative foundation model alignment.** *Dong, Hanze, Wei Xiong, Deepanshu Goyal, Yihan Zhang, Winnie Chow, Rui Pan, Shizhe Diao, Jipeng Zhang, Kashun Shum, and Tong Zhang.* [[pdf]](https://arxiv.org/pdf/2304.06767)

#### 3.1.3 Inference Stage

1. (2023 EMNLP) **Humanoid agents: Platform for simulating human-like generative agents.** *Wang, Zhilin, Yu Ying Chiu, and Yu Cheung Chiu.* [[pdf]](https://arxiv.org/pdf/2310.05418)


2. (2023 ICLR) **Critic: Large language models can self-correct with tool-interactive critiquing.** *Gou, Zhibin, Zhihong Shao, Yeyun Gong, Yelong Shen, Yujiu Yang, Nan Duan, and Weizhu Chen.* [[pdf]](https://arxiv.org/pdf/2305.11738)

3. (2024 ICLR) **Quality-diversity through ai feedback**. *Bradley, Herbie, Andrew Dai, Hannah Teufel, Jenny Zhang, Koen Oostermeijer, Marco Bellagente, Jeff Clune, Kenneth Stanley, Grégory Schott, and Joel Lehman.* [[pdf]](https://openreview.net/pdf?id=owokKCrGYr)


### 3.2 Customizing AI for Individuals and Groups

#### 3.2.1 Customized Data

1. (2023 ACL) **Winoqueer: A community-in-the-loop benchmark for anti-lgbtq+ bias in large language models.** *Felkner, Virginia K., Ho-Chun Herbert Chang, Eugene Jang, and Jonathan May.* [[pdf]](https://arxiv.org/pdf/2306.15087)

#### 3.2.2 Adapt Model by Learning

1. (2024 ICLR) **Group preference optimization: Few-shot alignment of large language models.** *Zhao, Siyan, John Dang, and Aditya Grover.* [[pdf]](https://openreview.net/forum?id=DpFeMH4l8Q)

2. (2022 AAMAS) **MORAL: Aligning AI with human norms through multi-objective reinforced active learning.** *Peschl, Markus, Arkady Zgonnikov, Frans A. Oliehoek, and Luciano C. Siebert.* [[pdf]](https://arxiv.org/pdf/2201.00012)


3. (2022 EMNLP) **BERTScore is unfair: On social bias in language model-based metrics for text generation.** *Sun, Tianxiang, Junliang He, Xipeng Qiu, and Xuanjing Huang.* [[pdf]](https://arxiv.org/pdf/2210.07626)


4. (2022 ICASSP) **Improving fairness in speaker verification via group-adapted fusion network.** *Shen, Hua, Yuguang Yang, Guoli Sun, Ryan Langman, Eunjung Han, Jasha Droppo, and Andreas Stolcke.* [[pdf]](https://arxiv.org/pdf/2202.11323)

5. (2023 EMNLP) **LDM $^ 2$: A Large Decision Model Imitating Human Cognition with Dynamic Memory Enhancement.** *Wang, Xingjin, Linjing Li, and Daniel Zeng.* [[pdf]](https://arxiv.org/pdf/2312.08402)



#### 3.2.3 Interactive Alignment

1. (2023 ICLR)  **Personalized reward learning with interaction-grounded learning (IGL).** *Maghakian, Jessica, Paul Mineiro, Kishan Panaganti, Mark Rucker, Akanksha Saran, and Cheng Tan.* [[pdf]](https://arxiv.org/pdf/2211.15823)

2. (2023 EMNLP) **Improving diversity of demographic representation in large language models via collective-critiques and self-voting.** *Lahoti, Preethi, Nicholas Blumm, Xiao Ma, Raghavendra Kotikalapudi, Sahitya Potluri, Qijun Tan, Hansa Srinivasan et al.* [[pdf]](https://arxiv.org/pdf/2310.16523)

3. (2022 ACL) **Leveraging similar users for personalized language modeling with limited data.** *Welch, Charles, Chenxi Gu, Jonathan K. Kummerfeld, Verónica Pérez-Rosas, and Rada Mihalcea.* [[pdf]](https://aclanthology.org/2022.acl-long.122.pdf)


### 3.3 Evaluating AI Systems

#### 3.3.1 Human-In-The-Loop-Evaluation

1. (2022 NAACL) **Aligning generative language models with human values.** *Liu, Ruibo, Ge Zhang, Xinyu Feng, and Soroush Vosoughi.* [[pdf]](https://aclanthology.org/2022.findings-naacl.18.pdf)


2. (2023 ACL) **Finspector: A human-centered visual inspection tool for exploring and comparing biases among foundation models.** *Kwon, Bum Chul, and Nandana Mihindukulasooriya.* [[pdf]](https://aclanthology.org/2023.acl-demo.4.pdf)


#### 3.3.2 Automatic Evaluation

1. (2024 NeurIPS) **Principle-driven self-alignment of language models from scratch with minimal human supervision.** *Sun, Zhiqing, Yikang Shen, Qinhong Zhou, Hongxin Zhang, Zhenfang Chen, David Cox, Yiming Yang, and Chuang Gan.* [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/0764db1151b936aca59249e2c1386101-Paper-Conference.pdf)


2. (2023 EMNLP) **Can Large Language Models Capture Dissenting Human Voices?.** *Lee, Noah, Na Min An, and James Thorne.* [[pdf]](https://arxiv.org/pdf/2305.13788)



### 3.4 Ecosystem

#### 3.4.1 Platforms

1. (2023 NeurIPS) **Alpacafarm: A simulation framework for methods that learn from human feedback.** *Dubois, Yann, Chen Xuechen Li, Rohan Taori, Tianyi Zhang, Ishaan Gulrajani, Jimmy Ba, Carlos Guestrin, Percy S. Liang, and Tatsunori B. Hashimoto.* [[pdf]](https://openreview.net/pdf?id=4hturzLcKX)


2. (2023 EMNLP)  **Gentopia: A collaborative platform for tool-augmented llms.** *Xu, Binfeng, Xukun Liu, Hua Shen, Zeyu Han, Yuhan Li, Murong Yue, Zhiyuan Peng, Yuchen Liu, Ziyu Yao, and Dongkuan Xu.* [[pdf]](https://arxiv.org/pdf/2308.04030)


3. (2022 EMNLP) **Potato: The portable text annotation tool.** *Pei, Jiaxin, Aparna Ananthasubramaniam, Xingyao Wang, Naitian Zhou, Jackson Sargent, Apostolos Dedeloudis, and David Jurgens.* [[pdf]](https://aclanthology.org/2022.emnlp-demos.33.pdf)


4. (2024 ICLR) **Uni-RLHF: Universal Platform and Benchmark Suite for Reinforcement Learning with Diverse Human Feedback.** *Yuan, Yifu, Jianye Hao, Yi Ma, Zibin Dong, Hebin Liang, Jinyi Liu, Zhixin Feng, Kai Zhao, and Yan Zheng.* [[pdf]](https://arxiv.org/pdf/2402.02423)




## 4.Human Cognitive Adjustment to AI

### 4.1 Perceiving and Understanding of AI


#### 4.1.1 Education and Training Human

1. (2022 CHI) **What is AI literacy? Competencies and design considerations.** *Long, Duri, and Brian Magerko.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3313831.3376727?casa_token=MWvd1NHw0HEAAAAA:xtkNw2v4XHT_wofSw4W6mvuGoN8wVH7536AkVVNLwwqTVB7ANk4J7UM-BA-B4JUCT8pT2qywJXpR)


2. (2020 CSCW) **Intersectional AI: A study of how information science students think about ethics and their impact.** *McDonald, Nora, and Shimei Pan.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3415218?casa_token=kPImRsLtrCYAAAAA:YW_O_1MPsXHeJc0Tmi7TA8iu3dQaGaS_n86DAJc_0jSHBTWI6AbDqGwgNLeQ_VXbpCIz19RmZmMu)


#### 4.1.2 AI Sensemaking and Explanations

1. (2023 CHI) **Anglekindling: Supporting journalistic angle ideation with large language models.** *Petridis, Savvas, Nicholas Diakopoulos, Kevin Crowston, Mark Hansen, Keren Henderson, Stan Jastrzebski, Jeffrey V. Nickerson, and Lydia B. Chilton.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3544548.3580907?casa_token=G5q-owxcuakAAAAA:awS7rEcVc6pJ9GofC6azdkXEc5aI6MNcWdTdlcwKdoOGsI5aZzJAepEMT6FIS2jFERiconlMWe3N)

2. (2020 EMNLP) **The language interpretability tool: Extensible, interactive visualizations and analysis for NLP models.** *Tenney, Ian, James Wexler, Jasmijn Bastings, Tolga Bolukbasi, Andy Coenen, Sebastian Gehrmann, Ellen Jiang et al.*  [[pdf]](https://aclanthology.org/2020.emnlp-demos.15.pdf)

3. (2023 CSCW Demo) **ConvXAI: Delivering heterogeneous AI explanations via conversations to support human-AI scientific writing.** *Shen, Hua, Chieh-Yang Huang, Tongshuang Wu, and Ting-Hao Kenneth Huang.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3584931.3607492?casa_token=TEUv5IwwP9cAAAAA:9iQ9rwkkF7ShMYEHYsGxHGxZfVye-da5M6fwLF5GSSIsmswpdvd6F9JO2Rch0QMNBwvyqLKjKIMq)



### 4.2 Critical Thinking about AI

#### 4.2.1 Trust and Reliance on AI Decisions

1. (2019 CHI) **Understanding the effect of accuracy on trust in machine learning models.** *Yin, Ming, Jennifer Wortman Vaughan, and Hanna Wallach.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3290605.3300509?casa_token=OTKgPNLNKa0AAAAA:2d3J1UX48ji_-K-F5Maz-PHj_Ap5Yb2bLF6BBxJEgZdA6Cr1eAARJfRZd3eBO924QbLVSayW0QBQ)

2. (2023 IUI) **Appropriate reliance on AI advice: Conceptualization and the effect of explanations.** *Schemmer, Max, Niklas Kuehl, Carina Benz, Andrea Bartos, and Gerhard Satzger.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3581641.3584066?casa_token=M315CFR5-BwAAAAA:HQNa200ItS9rIkGSYb1ARq1XYAbO1hXXskk2QoBwgB-XLilo7A8Nh5NFr2AOJFE26aomZP9ivNyN)


3. (2024 CHI) **An AI-Resilient Text Rendering Technique for Reading and Skimming Documents.** *Gu, Ziwei, Ian Arawjo, Kenneth Li, Jonathan K. Kummerfeld, and Elena L. Glassman.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3613904.3642699?casa_token=NtY359Zv7JgAAAAA:SR-Y5kOnKe_3vfCc3i7Cg3oEpzI2pa4zhq8xnr0ASOLPP_tOyXmt7bzWT1NagW7pU350MvlxK591)



#### 4.2.2 Ethical Concerns and AI Auditing

1. (2020 CHI) **Co-designing checklists to understand organizational challenges and opportunities around fairness in AI.** *Madaio, Michael A., Luke Stark, Jennifer Wortman Vaughan, and Hanna Wallach.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3313831.3376445)

2. (2021 CSCW) **Problematic machine behavior: A systematic literature review of algorithm audits.** *Bandy, Jack.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3449148)



#### 4.2.3 Calibrate Cognition to Align AI

1. (2019 CHI) **Will you accept an imperfect ai? exploring designs for adjusting end-user expectations of ai systems.** *Kocielnik, Rafal, Saleema Amershi, and Paul N. Bennett.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3290605.3300641?casa_token=OLB1htBBaNkAAAAA:UniqTgSTY3ruCB_AFKMRye9MZcsILJx6f3w0qAfRA8Z_uVxHzvmzfxAoyNwukN1kwhBSw7xWp7PL)

2. (2023 CHI) **Measuring and understanding trust calibrations for automated systems: a survey of the state-of-the-art and future directions.** *Wischnewski, Magdalena, Nicole Krämer, and Emmanuel Müller.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3544548.3581197)


## 5. Human Adaptive Behavior to AI

### 5.1 Human Collaborating with Diverse AI Roles

#### 5.1.1 Assistants

1. (2022 CHI) **Ai chains: Transparent and controllable human-ai interaction by chaining large language model prompts.** *Wu, Tongshuang, Michael Terry, and Carrie Jun Cai.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3491102.3517582)


2. (2023 CHI) **Patat: Human-ai collaborative qualitative coding with explainable interactive rule synthesis.** *Gebreegziabher, Simret Araya, Zheng Zhang, Xiaohang Tang, Yihao Meng, Elena L. Glassman, and Toby Jia-Jun Li.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3544548.3581352?casa_token=u1rVwBlK6tsAAAAA:3-9xZ34ortz9P-JPWXBIBviwlG7au4IfhBYM3iJyFlJQW6CFzlPH1hh17YNVC_KGurMoYGemy9VV)


3. (2019 CHI) **Aila: Attentive interactive labeling assistant for document classification through attention-based deep neural networks.** *Choi, Minsuk, Cheonbok Park, Soyoung Yang, Yonggyu Kim, Jaegul Choo, and Sungsoo Ray Hong.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3290605.3300460?casa_token=aGfb-S-YMhEAAAAA:IWMBGBUvx0jAYpfUfWN6ObXUlpoHD9JrRsxZ7OvIfn1UEifvOWmWJM7YUbx8BE9O0XOP5al6h2pS)




#### 5.1.2 Partners

1. (2023 UIST) **Generative agents: Interactive simulacra of human behavior.** *Park, Joon Sung, Joseph O'Brien, Carrie Jun Cai, Meredith Ringel Morris, Percy Liang, and Michael S. Bernstein.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3586183.3606763)


2. (2021 CSCW) **The design of reciprocal learning between human and artificial intelligence.** *Zagalsky, Alexey, Dov Te'eni, Inbal Yahav, David G. Schwartz, Gahl Silverman, Daniel Cohen, Yossi Mann, and Dafna Lewinsky.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3479587?casa_token=YFcCEFP8bZ4AAAAA:xEPS4jm8HVqD2GeDZMhi5WeIRUaAIY9RQiOYuiwx35P3YSEc4a55UOQhI3uKqeRc4IqAOkW5pNfy)


3. (2023 CHI) **AI knowledge: Improving AI delegation through human enablement.** *Pinski, Marc, Martin Adam, and Alexander Benlian.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3544548.3580794?casa_token=y-0Fq9LMzGoAAAAA:F_-vQ8wBm8O0Kk3483UPFprKStj9obQQF5lvsWbnG0c_YiztTzw8-LK9M7Tfd7SmKAvqtJCk3lNi)


4. (2022 HCR) **Rethinking communication in the era of artificial intelligence.** *Sundar, S. Shyam, and Eun-Ju Lee.* [[pdf]](https://academic.oup.com/hcr/article-abstract/48/3/379/6620825?redirectedFrom=PDF&casa_token=WsZy3Xfn3_MAAAAA:_UQiLadxs5ABVFR3uB9EtuOy4l-qihiqsASITi2nxIXPSYNUMZOhNAm7m0w5JcjPA4GU9KICkGUGZQ)


5. (2022 CHI) **How experienced designers of enterprise applications engage AI as a design material.** *Yildirim, Nur, Alex Kass, Teresa Tung, Connor Upton, Donnacha Costello, Robert Giusti, Sinem Lacin et al.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3491102.3517491)


#### 5.1.3 Tutors

1. (2024 AIED) **How to Teach Programming in the AI Era? Using LLMs as a Teachable Agent for Debugging.** *Ma, Qianou, Hua Shen, Kenneth Koedinger, and Sherry Tongshuang Wu.* [[pdf]](https://www.cs.cmu.edu/~sherryw/assets/pubs/2024-hypocompass.pdf)


2. (2024 CHI) **Rehearsal: Simulating conflict to teach conflict resolution.** *Shaikh, Omar, Valentino Emil Chai, Michele Gelfand, Diyi Yang, and Michael S. Bernstein.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3613904.3642159)



### 5.2 AI Impacts on Human and Society

#### 5.2.1 Impact on Individual Behavior

1. (2020 HCOMP) **How useful are the machine-generated interpretations to general users? a human evaluation on guessing the incorrectly predicted labels.** *Shen, Hua, and Ting-Hao Huang.* [[pdf]](https://ojs.aaai.org/index.php/HCOMP/article/view/7477/7256)


2. () **How AI Ideas Affect the Creativity, Diversity, and Evolution of Human Ideas: Evidence From a Large, Dynamic Experiment.** *Ashkinaze, Joshua, Julia Mendelsohn, Li Qiwei, Ceren Budak, and Eric Gilbert.* [[pdf]](https://arxiv.org/pdf/2401.13481)



3. (2022 IUI) **Do people engage cognitively with AI? Impact of AI assistance on incidental learning.** *Gajos, Krzysztof Z., and Lena Mamykina.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3490099.3511138)


<!-- 3. Li, Tianshi, Sauvik Das, Hao-Ping Lee, Dakuo Wang, Bingsheng Yao, and Zhiping Zhang. "Human-Centered Privacy Research in the Age of Large Language Models." In Extended Abstracts of the CHI Conference on Human Factors in Computing Systems, pp. 1-4. 2024. [[pdf]]() -->




#### 5.2.2 Societal Concerns and AI Impacts

1. (2023 CSCW) *Atreja, Shubham, Libby Hemphill, and Paul Resnick.* **Remove, reduce, inform: what actions do people want Social Media platforms to take on potentially misleading content?.** Proceedings of the ACM on Human-Computer Interaction 7, no. CSCW2 (2023): 1-33. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3610082?casa_token=kcoT4SDky3QAAAAA:ChztFk1kxFBgnAciq1oJLi-Te9OTZnlKZFMnMfto6R3-rcIZj3AR3apM9sssMmHQbn7EbQ3yx8gO)

2. (2023 ICLR) **Towards interpretable deep reinforcement learning with human-friendly prototypes.** *Kenny, Eoin M., Mycal Tucker, and Julie Shah.* [[pdf]](https://openreview.net/pdf?id=hWwY_Jq0xsN)

3. **Human vs. AI: Understanding the impact of anthropomorphism on consumer response to chatbots from the perspective of trust and relationship norms.** *Cheng, Xusen, Xiaoping Zhang, Jason Cohen, and Jian Mou.* [[pdf]](https://www.sciencedirect.com/science/article/pii/S0306457322000620?casa_token=R_GDKLpW1KwAAAAA:vjF-C8qKfA5EyeWowZ9N43EA1XEpQlFryMQ_3bpTuvuWIJrQx8F-fBuepIgQxYhGgWgntfvQ)


4. (2021 CHI) **Human-AI interaction in human resource management: Understanding why employees resist algorithmic evaluation at workplaces and how to mitigate burdens.** *Park, Hyanghee, Daehwan Ahn, Kartik Hosanagar, and Joonhwan Lee.*  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3411764.3445304?casa_token=UGBhg1Z31nkAAAAA:AotPhsLc-w4LiubqgV5owW-TFs5S6w7oAQJaS5svJyVwlz9Kc8uAQpFMIo5tvWsQ6_qBqK7JEJpm)



#### 5.2.3 Reaction to AI Advancements

1. Hacker, Philipp, Andreas Engel, and Marco Mauer. "Regulating ChatGPT and other large generative AI models." In Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency, pp. 1112-1123. 2023. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3593013.3594067)


2. **Who Should Pay When Machines Cause Harm? Laypeople’s Expectations of Legal Damages for Machine-Caused Harm.** *Lima, Gabriel, Nina Grgic-Hlaca, Jin Keun Jeong, and Meeyoung Cha.*  In Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency, pp. 236-246. 2023. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3593013.3593992)


3. (2021 CHI) **Human-AI interaction in human resource management: Understanding why employees resist algorithmic evaluation at workplaces and how to mitigate burdens.** *Park, Hyanghee, Daehwan Ahn, Kartik Hosanagar, and Joonhwan Lee.*  [pdf]](https://dl.acm.org/doi/pdf/10.1145/3411764.3445304?casa_token=sg-aQUgoRBsAAAAA:tk6rNjv_8qude-IhhZrieLhmBHBig64imKvpGgZq_tMpZq_l9mXNhgTOmpGdRKWiCuRMbzzmVtly)


4. *Madaio, Michael A., Luke Stark, Jennifer Wortman Vaughan, and Hanna Wallach.* **Co-designing checklists to understand organizational challenges and opportunities around fairness in AI.** In Proceedings of the 2020 CHI conference on human factors in computing systems, pp. 1-14. 2020. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3313831.3376445)


### 5.3 Evaluation in Human Studies

#### 5.3.1 Evaluate Human-AI Collaboration


1. (2024 Arxiv) **The RealHumanEval: Evaluating Large Language Models' Abilities to Support Programmers.** *Mozannar, Hussein, Valerie Chen, Mohammed Alsobay, Subhro Das, Sebastian Zhao, Dennis Wei, Manish Nagireddy, Prasanna Sattigeri, Ameet Talwalkar, and David Sontag.* [[pdf]](https://arxiv.org/pdf/2404.02806)

2. **Harnessing the power of LLMs: Evaluating human-AI text co-creation through the lens of news headline generation.** *Ding, Zijian, Alison Smith-Renner, Wenjuan Zhang, Joel R. Tetreault, and Alejandro Jaimes. [[pdf]](https://arxiv.org/pdf/2310.10706)


3. (2023 CCS) **Do users write more insecure code with AI assistants?** *Neil Perry, Megha Srivastava, Deepak Kumar, and Dan Boneh.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3576915.3623157?casa_token=DOFKsd6BLDcAAAAA:nz3SyrTaFV3igBRRz-ftObi_gQT-VrARkwzTSCLtyuPzOA6U6UHm699v2fGuLLh-fsLCZcofnPvf)


4. (2023 CSCW) **Deliberating with AI: improving decision-making for the future through participatory AI design and stakeholder deliberation.** *Zhang, Angie, Olympia Walker, Kaci Nguyen, Jiajun Dai, Anqing Chen, and Min Kyung Lee.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3579601)



5. (2021 CHI) **Towards mutual theory of mind in human-ai interaction: How language reflects what students perceive about a virtual teaching assistant.** *Wang, Qiaosi, Koustuv Saha, Eric Gregori, David Joyner, and Ashok Goel.* [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3411764.3445645?casa_token=HbHpIfbqCBcAAAAA:pO8IredpTSBqhL8EBYzHS3MmM3Q_qKdEyBlyTmEXD04xbESNtPfbQexWpUtKorzd6Cvg_LgIm9rb)




#### 5.3.2 Evaluate Societal Impact


1. (2023 ICML) **Whose opinions do language models reflect?.** *Santurkar, Shibani, Esin Durmus, Faisal Ladhak, Cinoo Lee, Percy Liang, and Tatsunori Hashimoto.* [[pdf]](https://proceedings.mlr.press/v202/santurkar23a/santurkar23a.pdf)


2. (2024 PNAS) **Generative artificial intelligence, human creativity, and art.** *Zhou, Eric, and Dokyun Lee.* [[pdf]](https://watermark.silverchair.com/pgae052.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA18wggNbBgkqhkiG9w0BBwagggNMMIIDSAIBADCCA0EGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMmh4z8Te_EeV3HkiMAgEQgIIDEmvEvC_tvnFV5oo8_ZvmgKDMTfc9gZClw4LT9wc2z4D1OgsqBoHawPCLpd700Ph9REZ4pJsHflb-7flavdxU7OxBwKIP8GbCkGW6JKSG43AAXdPe-ZwOmrMwKwGLx4fiaaS7v4hZZOs69ELMNXX0imoF2ejV-OUg1tmjLsba463Wnf9SZPkO7sKzTLpx6sVSaRU4p_gjtkHqotwFkF2SV15W2da84W9-oWSmXWSpqMC6TGAzmlZ6sqcs4FXha2kW_GjHv3iTwEiHy_asJ0Pd1fp06qZBoIzt_wLoex_7XY5Fh1qfv8tC1lyWWjVx6rd8GhcL2lAjXkTx7LP1zvIWueI3Mjuv_suuA2D9mfQjvZ0FHiV_R7RG0JS_vHuZ93kG73Hq-zjdDpf-396YbxvtOxwR5pWH5JQWli8LXEFBYLLvZ5XwZTxQYFz3Sb9soNfLC2r6QzG68CGzVvy7gMeqN_OegL3_89rU-CVyexOX4nhE8fx_QMUom_3d0asSTpibGWj1GjQCaxInTRMzrbOflObXqbco6hBb9-fRXDyzGy8Tjy_Uh1Ruz6d9qB66SEnu0THYCwgXNz5U8VsXS4rfBOBwEjcdxhjYDca42Ikq9VJvzDk43EyVutSWh8ucHnUUZr4OO01hlnC50E2BOmqwQFb9C9r2GNORVg2K24zLsVmImRq4syuDnlBA5GsQeI65KLGIUnQ18pOgMyZdmK29MEByr9g2N8TpztLCREDq4Bbv8PRXZS9SKVRD9K9iRY1N5CheW-WRXAcJVgQueoBMK1ysstJlSZjEi5AuozeroOBGud5wRIB8y2iy92i_RPekF3GmgSsU_t1M2DcAHEXLSY0GPBGAJJvziPw-v2qmrLoeKNRgTkat5uuB8jDB8xa_zIv4LcjzwKVLduNJph2f9Y04SBJ0VHWnuVCa4odRtNhvYoIys4uodYAbASVHuqXxakTufNcv4LALjKiGFjFjqKFbJJKkOQLIOdW2E3MvOebmjVM1QJilx_1dUXCuB4pQHqNYNZtMYC3RHkpkLWbb9bkZmQ)







<!-- ## 1. Causality Basics

### 1.3 Toolboxes

#### Causal Discovery

1. (2021) **causal-learn (Python package for causal discovery).** _Carnegie Mellon University_. [[GitHub](https://github.com/cmu-phil/causal-learn)] [[documentation](https://causal-learn.readthedocs.io/en/latest/)] 
3. (2019) **Causal Discovery Toolbox in Python.** [[GitHub](https://github.com/FenTechSolutions/CausalDiscoveryToolbox)] [[pdf](https://arxiv.org/pdf/1903.02278.pdf)] 
4. **Causal discovery tools.** _University of Pittsburgh/Carnegie Mellon University Center for Causal Discovery_. [[link](https://www.ccd.pitt.edu/tools/)]
   <br>e.g., Tretrad, [py-causal](https://bd2kccd.github.io/docs/py-causal/)  -->








## How to Cite This Repo

If you find the repository helpful to your research and would like to cite it, please see the `bibtex` below:

```bibtex
@article{shen2024towards,
  title={Towards Bidirectional Human-AI Alignment: A Systematic Review for Clarifications, Framework, and Future Directions},
  author={Shen, Hua and Knearem, Tiffany and Ghosh, Reshmi and Alkiek, Kenan and Krishna, Kundan and Liu, Yachuan and Ma, Ziqiao and Petridis, Savvas and Peng, Yi-Hao and Qiwei, Li and Rakshit, Sushrita and Si, Chenglei and Xie, Yutong and Bigham, Jeffrey P. and Bentley, Frank and Chai, Joyce and Lipton, Zachary and Mei, Qiaozhu and Mihalcea, Rada and Terry, Michael and Yang, Diyi and Morris, Meredith Ringel and Resnick, Paul and Jurgens, David},
  journal={arXiv preprint arXiv:2406.09264},
  year={2024}
}
```






<!-- 
- [1. Causality Basics](#1-causality-basics)
  - [1.1 Talks/Tutorial/etc](#11-Talkstutorialetc)
  - [1.2 Overview Papers](#12-overview-papers)
  - [1.3 Toolboxes](#13-toolboxes)
   -->


<!-- 
- [1. Causality Basics](#1-causality-basics)
  - [1.1 Talks/Tutorial/etc](#11-Talkstutorialetc)
  - [1.2 Overview Papers](#12-overview-papers)
  - [1.3 Toolboxes](#13-toolboxes)
- [2. Causality Applied to General NLP](#2-causality-applied-to-general-nlp)
  - [2.1 Causality to Bring Insights to NLP Modeling (for Robustness, Domain Adaptation, etc)](#21-causality-to-bring-insights-to-nlp-modeling-for-robustness-domain-adaptation-etc)
  - [2.2 Language Model Analysis in a Causal Way (for Probing, Interpretability, etc.)](#22-language-model-analysis-in-a-causal-way-for-probing-interpretability-etc)
  - [2.3 Text Features in Causal Graphs (for Social Science, Psychology, etc.)](#23-text-features-in-causal-graphs-for-social-science-psychology-etc)
  - [2.4 Causal Relation Extraction](#24-causal-relation-extraction)
  - [2.5 Causal Commonsense Reasoning and Generation](#25-causal-commonsense-reasoning-and-generation)
- [3. Causality for Various Applications](#3-causality-for-various-applications)
  - [3.1 Persuasion](#31-persuation)
  - [3.2 Psychology and Behavior](#32-psychology-and-behavior)
  - [3.3 Economics](#33-economics)
  - [3.4 Healthcare](#34-healthcare)
  - [3.4 Judicial Decision](#35-judicial-decision)
  - [3.5 Marketing strategies and sales prediction](#36-marketing-strategies-and-sales-prediction)
- [4. More Resources](#4-more-resources)
  - [4.1 Causality Papers from Schoelkopf's Lab, MPI](#41-causality-papers-from-schoelkopfs-lab-mpi)
    - [4.1.0 Overview](#410-overview)
    - [4.1.1 Learning Causal "Units" and Mechanisms (i.e., Causal Representation Learning)](#411-learning-causal-units-and-mechanisms-ie-causal-representation-learning)
    - [4.1.2 Robustness and Invariance (incl. Semi-Supervised Learning, Covariate Shift, Transfer Learning)](#411-learning-causal-units-and-mechanisms-ie-causal-representation-learning)
    - [4.1.3 Causal Discovery](#411-learning-causal-units-and-mechanisms-ie-causal-representation-learning)
    - [4.1.4 Causal Effect Estimation](#414-causal-effect-estimation)
    - [4.1.5 Foundational work (theory, ICA, etc.)](#415-foundational-work-theory-ica-etc)
  - [4.2 Causality Papers from Bengio's Lab, MILA](#42-causality-papers-from-bengios-lab-mila)
    - [Motivational Position Papers](#motivational-position-papers)
    - [Applying Causality Knowledge for RL Interaction Design](#applying-causality-knowledge-for-rl-interaction-design)
    - [Applying causality to model design](#applying-causality-to-model-design)
    - [Causal induction from interventional data](#causal-induction-from-interventional-data)
    - [Grounded AI](#grounded-AI)
  - [4.3 Other Causality Papers (Potentially Applicable to NLP)](#43-other-causality-papers-potentially-applicable-to-nlp)
  - [4.4 Books (for Systematic Learning)](#44-books-for-systematic-learning)
  - [4.5 Online Courses](#45-online-courses)
  - [4.6 People Directory](#46-people-directory)
  - [4.7 Workshops](#47-workshops)
  - [4.8 Others](#48-others)
- [Contributions](#contributions)
- [How to Cite This Repo](#How-to-Cite-This-Repo)
 -->



