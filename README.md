# Awesome LLM-Powered Agent

[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/hyp1231/awesome-llm-powered-agent/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Thanks to the impressive planning, reasoning, and tool-calling capabilities of Large Language Models (LLMs), people are actively studying and developing **LLM-powered agents.** These agents are possible to autonomously (and collaboratively) solve complex tasks, or simulate human interactions.

Our goal with this project is to build an exhaustive collection of awesome resources relevant to LLM-powered agents encompassing papers, repositories, and more. We strive to keep these updated regularly and continuously. **We greatly appreciate any contributions via PRs, issues, emails, or other methods.**

-----

<i>New!</i> **Call for Papers** until ~Aug 25~ Sep 10, 2023 - [Personalized Generative AI](https://sites.google.com/view/pgai2023) @ CIKM'23 - Submissions relating to LLM-powered agents are highly welcomed and valued!

-----

- [Papers](#papers)
  - [Autonomous Task Solver](#autonomous-task-solver)
    - [General Reasoning & Planning & Tool Using](#general-reasoning--planning--tool-using)
    - [Multi-Agent Cooperation](#multi-agent-cooperation)
    - [Framework & Open-Source](#framework--open-source)
    - [Application](#application)
      - [Web Agents](#web-agents)
      - [RL Agents](#rl-agents)
      - [Robotics & Embodied AI](#robotics--embodied-ai)
      - [Gaming & Role-Playing](#gaming--role-playing)
      - [Other Applications](#other-applications)
    - [Trustworthy](#trustworthy)
  - [Human Interaction Simulation](#human-interaction-simulation)
  - [Human-Agent Interaction](#human-agent-interaction)
  - [Agents-Powered LLMs](#agents-powered-llms)
  - [Benchmark](#benchmark)
  - [Survey & Tutorial](#survey--tutorial)
- [Open-Source Projects](#open-source-projects)
  - [Autonomous Task Solver Projects](#autonomous-task-solver-projects)
  - [Multi-Agent Simulation Projects](#multi-agent-simulation-projects)
- [Perspectives](#perspectives)
- [Other Related Sources](#other-related-sources)
- [Acknowledgement](#acknowledgement)

## Papers

> 🔥 for papers with >50 citations or repositories with >200 stars.\
> 📖 for papers accepted by reputed conferences/journals.

### Autonomous Task Solver

#### General Reasoning & Planning & Tool Using

* [Oct 2023] **"Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models."** *Andy Zhou (UIUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.04406)] [[code](https://github.com/andyz245/LanguageAgentTreeSearch)] [[project page](https://andyz245.github.io/LanguageAgentTreeSearch)]
* [Oct 2023] **"Adapting LLM Agents Through Communication."** *Kuan Wang (GaTech & Microsoft) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.01444)]
* 📖 [Sep 2023] **"AVIS: Autonomous Visual Information Seeking with Large Language Models."** *Ziniu Hu (Google) et al.* NeurIPS 2023.  [[paper](https://arxiv.org/pdf/2306.08129.pdf)]
* [Sep 2023] **"Reason for Future, Act for Now: A Principled Framework for Autonomous LLM Agents with Provable Sample Efficiency."** *Zhihan Liu (Northwestern) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.17382)] [[code](https://github.com/agentification/RAFA_code)] [[project page](https://agentification.github.io/RAFA)]
* [Sep 2023] **"Self-driven Grounding: Large Language Model Agents with Automatical Language-aligned Skill Learning."** *Shaohui Peng (CAS) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.01352)]
* [Aug 2023] **"ExpeL: LLM Agents Are Experiential Learners."** *Andrew Zhao (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.10144)]
* [Aug 2023] **"Synergistic Integration of Large Language Models and Cognitive Architectures for Robust AI: An Exploratory Analysis."** *Oscar J. Romero (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.09830)]
* [Aug 2023] **"Dynamic Planning with a LLM."** *Gautier Dagan (U of Edinburgh) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.06391)] [[code](https://github.com/itl-ed/llm-dp)]
* [Aug 2023] **"Retroformer: Retrospective Large Language Agents with Policy Gradient Optimization."** *Weiran Yao (Salesforce) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.02151)]
* 🔥 [May 2023] **"ReWOO: Decoupling Reasoning from Observations for Efficient Augmented Language Models."** *Binfeng Xu et al.* arXiv. [[paper](https://arxiv.org/abs/2305.18323)] [[code](https://github.com/billxbf/ReWOO)]
* 📖 [May 2023] **"SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks."** *Bill Yuchen Lin (AI2) et al.* NeurIPS 2023. [[paper](https://arxiv.org/abs/2305.17390)] [[code](https://github.com/yuchenlin/swiftsage)] [[project page](https://yuchenlin.xyz/swiftsage)]
* 🔥📖 [May 2022] **"Reasoning with Language Model is Planning with World Model."** *Shibo Hao (UCSD) et al.* EMNLP 2023. [[paper](https://arxiv.org/abs/2305.14992)] [[code](https://github.com/Ber666/llm-reasoners)] [[project page](https://www.llm-reasoners.net/)]
* 📖 [May 2023] **"ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models."** *Zhipeng Chen (RUC) et al.* EMNLP 2023 Findings. [[paper](https://arxiv.org/abs/2305.14323)] [[code](https://github.com/RUCAIBOX/ChatCoT)]
* [May 2023] **"CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing."** *Zhibin Gou (THU & Microsoft) et al.* arXiv. [[paper](https://arxiv.org/pdf/2305.11738.pdf)] [[code](https://github.com/microsoft/ProphetNet/tree/master/CRITIC)]
* 🔥 [Apr 2023] **"LLM+P: Empowering Large Language Models with Optimal Planning Proficiency."** *Bo Liu (UT Austin) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.11477)] [[code](https://github.com/Cranial-XIX/llm-pddl)]
* 🔥📖 [Mar 2023] **"Reflexion: Language Agents with Verbal Reinforcement Learning."** *Noah Shinn (Northeastern) et al.* NeurIPS 2023. [[paper](https://arxiv.org/abs/2303.11366)] [[code](https://github.com/noahshinn024/reflexion)]
* 📖 [Dec 2022] **"Don’t Generate, Discriminate: A Proposal for Grounding Language Models to Real-World Environments"** *Yu Gu (OSU) et al.* ACL 2023. [[paper](https://aclanthology.org/2023.acl-long.270/)] [[code](https://github.com/dki-lab/Pangu)]
* 🔥📖 [Oct 2022] **"ReAct: Synergizing Reasoning and Acting in Language Models."** *Shunyu Yao (Princeton & Google Brain) et al.* ICLR 2023. [[paper](https://arxiv.org/abs/2210.03629)] [[code](https://github.com/ysymyth/ReAct)] [[project page](https://react-lm.github.io)]

#### Multi-Agent Cooperation

* [Oct 2023] **"Evaluating Multi-Agent Coordination Abilities in Large Language Models."** *Saaket Agashe (UCSC) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.03903)]
* [Oct 2023] **"Dynamic LLM-Agent Network: An LLM-agent Collaboration Framework with Agent Team Optimization."** *Zijun Liu (THU & Stanford) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.02170)] [[code](https://github.com/SALT-NLP/DyLAN)]
* [Oct 2023] **"Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View."** *Jintian Zhang (ZJU) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.02124)] [[code](https://github.com/zjunlp/MachineSoM)]
* [Oct 2023] **"Corex: Pushing the Boundaries of Complex Reasoning through Multi-Model Collaboration."** *Qiushi Sun (Shanghai AI Lab & NUS) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.00280)] [[code](https://github.com/QiushiSun/Corex)]
* [Sep 2023] **"LLM-Deliberation: Evaluating LLMs with Interactive Multi-Agent Negotiation Games."** *Sahar Abdelnabi (CISPA) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.17234)] [[code](https://github.com/S-Abdelnabi/LLM-Deliberation)]
* [Sep 2023] **"Scalable Multi-Robot Collaboration with Large Language Models: Centralized or Decentralized Systems?"** *Yongchao Chen (MIT & Harvard) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.15943)] [[code](https://github.com/yongchao98/multi-agent-framework)] [[project page](https://yongchao98.github.io/MIT-REALM-Multi-Robot)]
* [Sep 2023] **"ReConcile: Round-Table Conference Improves Reasoning via Consensus among Diverse LLMs."** *Justin Chih-Yao Chen (UNC Chapel Hill) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.13007)] [[code](https://github.com/dinobby/ReConcile)]
* [Sep 2023] **"MindAgent: Emergent Gaming Interaction."** *Ran Gong (UCLA) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.09971)] [[code](https://github.com/mindagent/mindagent)] [[project page](https://mindagent.github.io)]
* [Aug 2023] **"ProAgent: Building Proactive Cooperative AI with Large Language Models."** *Ceyao Zhang (CUHK & PKU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.11339)] [[project page](https://pku-proagent.github.io)]
* 🔥 [Aug 2023] **"AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors in Agents."** *Weize Chen (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.10848)] [[code](https://github.com/OpenBMB/AgentVerse)]
* [Aug 2023] **"GPT-in-the-Loop: Adaptive Decision-Making for Multiagent Systems."** *Nathalia Nascimento (U of Waterloo) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.10435)]
* [Aug 2023] **"How susceptible are LLMs to Logical Fallacies?"** *Amirreza Payandeh (GMU & Vail Systems) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.09853)] [[code](https://github.com/Amir-pyh/LOGICOM)]
* [Aug 2023] **"ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate."** *Chi-Min Chan (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.07201)] [[code](https://github.com/chanchimin/ChatEval)]
* [Aug 2023] **"LLM As DBA."** *Xuanhe Zhou (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.05481)] [[code](https://github.com/TsinghuaDatabaseGroup/DB-GPT)]
* [Aug 2023] **"Gentopia: A Collaborative Platform for Tool-Augmented LLMs."** *Binfeng Xu et al.* arXiv. [[paper](https://arxiv.org/abs/2308.04030)] [[code](https://github.com/Gentopia-AI/Gentopia)] [[project page](https://gentopia-ai.github.io/Gentopia-AI-Homepage)]
* 🔥 [Aug 2023] **"MetaGPT: Meta Programming for Multi-Agent Collaborative Framework."** *Sirui Hong (DeepWisdom) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.00352)] [[code](https://github.com/geekan/MetaGPT)]
* [Jul 2023] **"PRD: Peer Rank and Discussion Improve Large Language Model based Evaluations."** *Ruosen Li (UT Dallas) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.02762)] [[project page](https://bcdnlp.github.io/PR_LLM_EVAL/)][[code](https://github.com/bcdnlp/PRD)]
* [Jul 2023] **"Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration."** *Zhenhailong Wang (UIUC & MSRA) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.05300)] [[code](https://github.com/MikeWangWZHL/Solo-Performance-Prompting)]
* [Jul 2023] **"RoCo: Dialectic Multi-Robot Collaboration with Large Language Models."** *Mandi Zhao (Columbia) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.04738)] [[code](https://github.com/MandiZhao/robot-collab)] [[project page](https://project-roco.github.io)]
* [Jul 2023] **"Wireless Multi-Agent Generative AI: From Connected Intelligence to Collective Intelligence."** *Hang Zou (Technology Innovation Institute, UAE) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.02757)]
* [Jul 2023] **"Building Cooperative Embodied Agents Modularly with Large Language Models."** *Hongxin Zhang (UMass) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.02485)] [[code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents)] [[project page](https://vis-www.cs.umass.edu/Co-LLM-Agents)]
* [Jun 2023] **"RestGPT: Connecting Large Language Models with Real-World Applications via RESTful APIs."** *Yifan Song (PKU) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.06624)] [[project page](https://restgpt.github.io)]
* [Jun 2023] **"Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents."** *Yashar Talebirad (UAlberta) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.03314)]
* [May 2023] **"Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate."** *Tian Liang (THU & Tencent) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.19118)] [[code](https://github.com/Skytliang/Multi-Agents-Debate)]
* 🔥 [May 2023] **"Large Language Models as Tool Makers."** *Tianle Cai (Deepmind & Princeton) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.17126)] [[code](https://github.com/ctlllll/LLM-ToolMaker)]
* [May 2023] **"Improving Factuality and Reasoning in Language Models through Multiagent Debate."** *Yilun Du (MIT) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.14325)] [[code](https://github.com/composable-models/llm_multiagent_debate)] [[project page](https://composable-models.github.io/llm_debate)]
* [May 2023] **"Agreement and Statistical Efficiency in Bayesian Perception Models."** *Yash Deshpande (MIT) et al.* arXiv. [[paper](https://arxiv.org/abs/2205.11561)]
* [May 2023] **"Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback."** *Yao Fu (U of Edinburgh) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.10142)] [[code](https://github.com/FranxYao/GPT-Bargaining)]

#### Framework & Open-Source

* 🔥 [Oct 2023] **"OpenAgents: An Open Platform for Language Agents in the Wild."** *Tianbao Xie (HKU & XLang Lab) et al.* arxiv. [[paper](https://arxiv.org/abs/2310.10634)] [[code](https://github.com/xlang-ai/OpenAgents)]
* 🔥 [Sep 2023] **"AutoAgents: A Framework for Automatic Agent Generation."** *Guangyao Chen (PKU) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.17288)] [[code](https://github.com/LinkSoul-AI/AutoAgents)]
* 🔥 [Sep 2023] **"Agents: An Open-source Framework for Autonomous Language Agents."** *Wangchunshu Zhou (AI Waves) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.07870)] [[code](https://github.com/aiwaves-cn/agents)] [[project page](http://www.aiwaves-agents.com)]
* 🔥 [Sep 2023] **"Cognitive Architectures for Language Agents."** *Theodore Sumers (Princeton) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.02427)] [[repo](https://github.com/ysymyth/awesome-language-agents)]
* 🔥 [Aug 2023] **"AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework."** *Qingyun Wu et al.* arXiv. [[paper](https://arxiv.org/abs/2308.08155)] [[code](https://github.com/microsoft/autogen)] [[project page](https://microsoft.github.io/autogen/)]

#### Application

##### Web Agents

* [Sep 2023] **"You Only Look at Screens: Multimodal Chain-of-Action Agents."** *Zhuosheng Zhang (SJTU) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.11436)] [[code](https://github.com/cooelf/Auto-UI)]
* [Sep 2023] **"LASER: LLM Agent with State-Space Exploration for Web Navigation."** *Kaixin Ma (Tencent) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.08172)] [[code](https://github.com/Mayer123/LASER)]
* 🔥 [Jul 2023] **"WebArena: A Realistic Web Environment for Building Autonomous Agents."** *Shuyan Zhou (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.13854)] [[code](https://github.com/web-arena-x/webarena)] [[project page](https://webarena.dev)]
* [Jul 2023] **"A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis."** *Izzeddin Gur (DeepMind) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.12856)]
* 🔥📖 [Jun 2023] **"Mind2Web: Towards a Generalist Agent for the Web."** *Xiang Deng (OSU) et al.* NeurIPS 2023. [[paper](https://arxiv.org/abs/2306.06070)] [[code](https://github.com/OSU-NLP-Group/Mind2Web)] [[project page](https://osu-nlp-group.github.io/Mind2Web)]
* [May 2023] **"Augmenting Autotelic Agents with Large Language Models."** *Cédric Colas (MIT & Inria) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.12487)]
* [May 2023] **"Mobile-Env: An Evaluation Platform and Benchmark for Interactive Agents in LLM Era."** *Danyang Zhang (SJTU) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.08144)] [[code](https://github.com/X-LANCE/Mobile-Env)]
* 📖 [Apr 2023] **"Emergent autonomous scientific research capabilities of large language models."** *Daniil A. Boiko (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.05332)]
* [Mar 2023] **"Language Models can Solve Computer Tasks."** *Geunwoo Kim (UCI) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.17491)] [[code](https://github.com/posgnu/rci-agent)] [[project page](https://posgnu.github.io/rci-web)]
* 📖 [Jul 2022] **"WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents."** *Shunyu Yao (Princeton) et al.* NeurIPS 2022. [[paper](https://arxiv.org/abs/2207.01206)] [[code](https://github.com/princeton-nlp/WebShop)] [[project page](https://webshop-pnlp.github.io)]

##### RL Agents

* [Oct 2023] **"Motif: Intrinsic Motivation from Artificial Intelligence Feedback."** *Martin Klissarov (Mila & Meta & McGill) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.00166)]
* [Sep 2023] **"RLAdapter: Bridging Large Language Models to Reinforcement Learning in Open Worlds."** *Wanpeng Zhang (PKU) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.17176)]
* [Aug 2023] **"LaGR-SEQ: Language-Guided Reinforcement Learning with Sample-Efficient Querying."** *Thommen George Karimpanal (Deakin University) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.13542)] [[code](https://github.com/GKthom/LaGRSEQ)]
* [Jul 2023] **"Dialogue Shaping: Empowering Agents through NPC Interaction."** *Wei Zhou (GaTech) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.15833)]
* [Jul 2023] **"Towards A Unified Agent with Foundation Models."** *Norman Di Palo (ICL & DeepMind) et al.* Reincarnating RL @ ICLR 2023. [[paper](https://arxiv.org/abs/2307.09668)]
* 📖 [Jun 2023] **"Large Language Model Is Semi-Parametric Reinforcement Learning Agent."** *Danyang Zhang (SJTU) et al.* NeurIPS 2023. [[paper](https://arxiv.org/abs/2306.07929)]
* [May 2023] **"Semantically Aligned Task Decomposition in Multi-Agent Reinforcement Learning."** *Wenhao Li (CUHK) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.10865)]

##### Robotics & Embodied AI

* [Oct 2023] **"Towards End-to-End Embodied Decision Making via Multi-modal Large Language Model: Explorations with GPT4-Vision and Beyond."** *Liang Chen (PKU) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.02071)] [[code](https://github.com/pkunlp-icler/PCA-EVAL)] [[project page](https://pca-eval.github.io)]
* [Oct 2023] **"LANCAR: Leveraging Language for Context-Aware Robot Locomotion in Unstructured Environments."** *Chak Lam Shek (UMD) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.00481)] [[project page](https://raaslab.org/projects/LLM_Context_Estimation)]
* [Sep 2023] **"LLM-Grounder: Open-Vocabulary 3D Visual Grounding with Large Language Model as an Agent."** *Jianing Yang (UMich) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.12311)] [[code](https://github.com/sled-group/chat-with-nerf)] [[project page](https://chat-with-nerf.github.io)]
* [Sep 2023] **"SMART-LLM: Smart Multi-Agent Robot Task Planning using Large Language Models."** *Shyam Sundar Kannan (Purdue) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.10062)] [[project page](https://sites.google.com/view/smart-llm)]
* [Sep 2023] **"Plug in the Safety Chip: Enforcing Constraints for LLM-driven Robot Agents."** *Ziyi Yang et al.* arXiv. [[paper](https://arxiv.org/abs/2309.09919)] [[code & video](https://drive.google.com/drive/folders/1s1Ba-VanY0YqL8hVpkN4Xvg3PdZlStBb)]
* [Sep 2023] **"SayNav: Grounding Large Language Models for Dynamic Planning to Navigation in New Environments."** *Abhinav Rajvanshi (SRI International) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.04077)]
* [Sep 2023] **"Developmental Scaffolding with Large Language Models."** *M. Batuhan Celik (Bogazici University) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.00904)]
* [Jul 2023] **"March in Chat: Interactive Prompting for Remote Embodied Referring Expression."** *Yanyuan Qiao (Adelaide University) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.10141)] [[code](https://github.com/YanyuanQiao/MiC)]
* [Aug 2023] **"A^2Nav: Action-Aware Zero-Shot Robot Navigation by Exploiting Vision-and-Language Ability of Foundation Models."** *Peihao Chen (SCUT) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.07997)]
* [Jul 2023] **"Embodied Task Planning with Large Language Models."** *Zhenyu Wu (BUPT) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.01848)] [[code](https://github.com/Gary3410/TaPA)] [[project page](https://gary3410.github.io/TaPA/)]
* [Jun 2023] **"Enabling Intelligent Interactions between an Agent and an LLM: A Reinforcement Learning Approach."** *Bin Hu (Zhejiang Lab) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.03604)] [[code](https://github.com/ZJLAB-AMMI/LLM4RL)]
* 🔥 [May 2023] **"Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory."** *Xizhou Zhu (THU & SenseTim) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.17144)] [[code](https://github.com/OpenGVLab/GITM)]
* 🔥 [May 2023] **"Voyager: An Open-Ended Embodied Agent with Large Language Models."** *Guanzhi Wang (NVIDIA & Caltech) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16291)] [[code](https://github.com/MineDojo/Voyager)] [[project page](https://voyager.minedojo.org)]
* [May 2023] **"Plan, Eliminate, and Track -- Language Models are Good Teachers for Embodied Agents."** *Yue Wu (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.02412)]
* 📖 [Feb 2023] **"Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents."** *Zihao Wang (PKU) et al.* NeurIPS 2023. [[paper](https://arxiv.org/abs/2302.01560)] [[code](https://github.com/CraftJarvis/MC-Planner)]
* [Feb 2023] **"Collaborating with language models for embodied reasoning."** *Ishita Dasgupta (DeepMind) et al.* LaReL @ NeurIPS 2022. [[paper](https://arxiv.org/abs/2302.00763)]
* [Jan 2023] **"Do Embodied Agents Dream of Pixelated Sheep: Embodied Decision Making using Language Guided World Modelling."** *Kolby Nottingham (UCI) et al.* ICML 2023. [[paper](https://arxiv.org/abs/2301.12050)] [[code](https://github.com/DeckardAgent/deckard)] [[project page](https://deckardagent.github.io)]
* 📖 [Dec 2022] **"LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models."** *Chan Hee Song (OSU) et al.* ICCV 2023. [[paper](https://arxiv.org/abs/2212.04088)] [[project page](https://dki-lab.github.io/LLM-Planner)]

##### Gaming & Role-Playing

* [Oct 2023] **"From Text to Tactic: Evaluating LLMs Playing the Game of Avalon."** *Jonathan Light (RPI) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.05036)] [[code](https://github.com/jonathanmli/Avalon-LLM)]
* [Oct 2023] **"Ruffle&Riley: Towards the Automated Induction of Conversational Tutoring Systems."** *Robin Schmucker (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.01420)]
* [Oct 2023] **"Avalon's Game of Thoughts: Battle Against Deception through Recursive Contemplation."** *Shenzhi Wang (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.01320)]
* [Sep 2023] **"Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4."** *Jiaxian Guo (U of Tokyo) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.17277)] [[code](https://github.com/CR-Gjx/Suspicion-Agent)]
* [Aug 2023] **"Ambient Adventures: Teaching ChatGPT on Developing Complex Stories."** *Zexin Chen (GaTech) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.01734)]
* [Jul 2023] **"Tachikuma: Understading Complex Interactions with Multi-Character and Novel Objects by Large Language Models."** *Yuanzhi Liang (UTS) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.12573)]
* [May 2023] **"Role-Play with Large Language Models."** *Murray Shanahan (DeepMind & ICL) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16367)]
* [May 2023] **"clembench: Using Game Play to Evaluate Chat-Optimized Language Models as Conversational Agents."** *Kranti Chalamalasetti (University of Potsdam) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.13455)] [[code](https://github.com/clp-research/clembench)]
* [Apr 2023] **"Towards autonomous system: flexible modular production system enhanced with large language model agents."** *Yuchen Xia (University of Stuttgart) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.14721)] [[code](https://github.com/YuchenXia/GPT4IndustrialAutomation)]
* 🔥📖 [Mar 2023] **"CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society."** *Guohao Li (KAUST) et al.* NeurIPS 2023. [[paper](https://arxiv.org/abs/2303.17760)] [[code](https://github.com/camel-ai/camel)] [[project page](https://www.camel-ai.org)]

##### Other Applications

* [Oct 2023] **"OptiMUS: Optimization Modeling Using mip Solvers and large language models."** *Ali AhmadiTeshnizi (Stanford) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.06116)] [[code](https://github.com/teshnizi/OptiMUS)]
* [Oct 2023] **"An evolutionary model of personality traits related to cooperative behavior using a large language model."** *Reiji Suzuki (Nagoya University) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.05976)]
* [Oct 2023] **"Large Language Model (LLM) as a System of Multiple Expert Agents: An Approach to solve the Abstraction and Reasoning Corpus (ARC) Challenge."** *John Chong Min Tan (NUS) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.05146)]
* [Oct 2023] **"A Language-Agent Approach to Formal Theorem-Proving."** *Amitayush Thakur (UT Austin) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.04353)]
* [Oct 2023] **"Conversational Health Agents: A Personalized LLM-Powered Agent Framework."** *Mahyar Abbasian (UCI) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.02374)]
* [Oct 2023] **"OceanGPT: A Large Language Model for Ocean Science Tasks."** *Zhen Bi (ZJU & Donghai Lab) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.02031)] [[project page](https://www.zjukg.org/project/OceanGPT)]
* [Oct 2023] **"Voice2Action: Language Models as Agent for Efficient Real-Time Interaction in Virtual Reality."** *Yang Su (Cornell Tech).* arXiv. [[paper](https://arxiv.org/abs/2310.00092)]
* 🔥 [Sep 2023] **"ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving."** *Zhibin Gou (THU & Microsoft) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.17452)] [[code](https://github.com/microsoft/ToRA)] [[project page](https://microsoft.github.io/ToRA)]
* [Sep 2023] **""Teach AI How to Code": Using Large Language Models as Teachable Agents for Programming Education."** *Hyoungwook Jin (KAIST) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.14534)]
* [Sep 2023] **"SurrealDriver: Designing Generative Driver Agent Simulation Framework in Urban Contexts based on Large Language Model."** *Ye Jin (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.13193)]
* [Sep 2023] **"Large Language Models as Agents in the Clinic."** *Nikita Mehandru (UC Berkeley) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.10895)]
* [Sep 2023] **"An Appraisal-Based Chain-Of-Emotion Architecture for Affective Language Model Game Agents."** *Maximilian Croissant (UOY) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.05076)]
* [Sep 2023] **"Unleashing the Power of Graph Learning through LLM-based Autonomous Agents."** *Lanning Wei (CAS & 4Paradigm) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.04565)]
* [Sep 2023] **"TradingGPT: Multi-Agent System with Layered Memory and Distinct Characters for Enhanced Financial Trading Performance."** *Yang Li (SIT) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.03736)]
* 🔥 [Sep 2023] **"ModelScope-Agent: Building Your Customizable Agent System with Open-source Large Language Models."** *Chenliang Li (Alibaba) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.00986)] [[code](https://github.com/modelscope/modelscope-agent)] [[demo](https://modelscope.cn/studios/damo/ModelScopeGPT/summary)]
* [Aug 2023] **"Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations."** *Xu Huang (USTC) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.16505)] [[code](https://github.com/AngusHuang17/LLM4CRS)]
* [Aug 2023] **"RecMind: Large Language Model Powered Agent For Recommendation."** *Yancheng Wang (ASU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.14296)]
* [Aug 2023] **"LLM Powered Sim-to-real Transfer for Traffic Signal Control."** *Longchao Da (ASU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.14284)]
* [Aug 2023] **"Out of the Cage: How Stochastic Parrots Win in Cyber Security Environments."** *Maria Rigaki (ČVUT) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.12086)] [[code](https://anonymous.4open.science/r/NetSecGame-3951)]
* [Aug 2023] **"Is There Any Social Principle for LLM-Based Agents?"** *Jitao Bai (TJU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.11136)]
* [Aug 2023] **"ChatEDA: A Large Language Model Powered
Autonomous Agent for EDA."** *Zhuolun He (CUHK & Shanghai AI Lab) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.10204)]
* [Aug 2023] **"The Hitchhiker's Guide to Program Analysis: A Journey with Large Language Models."** *Haonan Li (UCR) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.00245)]
* [Jun 2023] **"Towards Autonomous Testing Agents via Conversational Large Language Models."** *Robert Feldt (Chalmers University of Technology) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.05152)]
* [Apr 2023] **"GeneGPT: Augmenting Large Language Models with Domain Tools for Improved Access to Biomedical Information."** *Qiao Jin, Yifan Yang, Qingyu Chen, Zhiyong Lu* arXiv. [[paper](https://arxiv.org/abs/2304.09667)] [[code](https://github.com/ncbi/GeneGPT)]
* 🔥 [Mar 2023] **"HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face."** *Yongliang Shen (ZJU & MSRA) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.17580)] [[code](https://github.com/microsoft/JARVIS)]

#### Trustworthy

* [Sep 2023] **"Identifying the Risks of LM Agents with an LM-Emulated Sandbox"** *Yangjun Ruan (University of Toronto & Vector Institute) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.15817)] [[code](https://github.com/ryoungj/toolemu)] [[demo](https://demo.toolemu.com/)] [[project page](https://toolemu.com/)]
* [Aug 2023] **"Enhancing Trust in LLM-Based AI Automation Agents: New Considerations and Future Challenges."** *Sivan Schwartz (IBM Research) et al.* AutoMate @ IJCAI 2023. [[paper](https://arxiv.org/abs/2308.05391)]

### Human Interaction Simulation

* [Oct 2023] **"Simulating Social Media Using Large Language Models to Evaluate Alternative News Feed Algorithms."** *Petter Törnberg (U of Amsterdam) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.05984)]
* [Oct 2023] **"Put Your Money Where Your Mouth Is: Evaluating Strategic Planning and Execution of LLM Agents in an Auction Arena."** *Jiangjie Chen (FDU & AI2) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.05746)] [[code](https://github.com/jiangjiechen/auction-arena)] [[project page](https://auction-arena.github.io)]
* [Oct 2023] **"Lyfe Agents: Generative agents for low-cost real-time social interactions."** *Zhao Kaiya (MIT) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.02172)]
* [Sep 2023] **"Identifying the Risks of LM Agents with an LM-Emulated Sandbox"** *Yangjun Ruan (University of Toronto & Vector Institute) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.15817)] [[code](https://github.com/ryoungj/toolemu)] [[demo](https://demo.toolemu.com/)] [[project page](https://toolemu.com/)]
* [Sep 2023] **"Generative Agent-Based Modeling: Unveiling Social System Dynamics through Coupling Mechanistic Models with Generative Artificial Intelligence."** *Navid Ghaffarzadegan (Virginia Tech) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.11456)]
* [Aug 2023] **"CGMI: Configurable General Multi-Agent Interaction Framework."** *Jinxin Shi (ECNU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.12503)]
* [Aug 2023] **"Exploring the Intersection of Large Language Models and Agent-Based Modeling via Prompt Engineering."** *Edward Junprung (UC Berkeley) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.07411)] [[code](https://github.com/ejunprung/llm-agents)]
* 🔥 [Aug 2023] **"AgentSims: An Open-Source Sandbox for Large Language Model Evaluation."** *Jiaju Lin (PTA Studio & PSU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.04026)] [[code](https://github.com/py499372727/AgentSims)] [[project page](https://agentsims.com)]
* [Jul 2023] **"S^3: Social-network Simulation System with Large Language Model-Empowered Agents."** *Chen Gao (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.14984)]
* [Jul 2023] **"Are you in a Masquerade? Exploring the Behavior and Impact of Large Language Model Driven Social Bots in Online Social Networks."** *Siyu Li (SCU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.10337)] [[dataset](https://github.com/Litsay/Masquerade-23)]
* [Jul 2023] **"Communicative Agents for Software Development."** *Chen Qian (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.07924)]
* [Jul 2023] **"Epidemic Modeling with Generative Agents."** *Ross Williams (Virginia Tech) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.04986)] [[code](https://github.com/bear96/GABM-Epidemic)]
* [Jul 2023] **"To Infinity and Beyond: SHOW-1 and Showrunner Agents in Multi-Agent Simulations."** *Philipp Maas (Fable Studio) et al.* preprint. [[paper](https://fablestudio.github.io/showrunner-agents/static/pdfs/To_Infinity_and_Beyond_SHOW-1_And_Showrunner_Agents_in_Multi_Agent_Simulations_v2.pdf)] [[project page](https://fablestudio.github.io/showrunner-agents)]
* [Jun 2023] **"RecAgent: A Novel Simulation Paradigm for Recommender Systems."** *Lei Wang (RUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.02552)] [[code](https://github.com/RUC-GSAI/YuLan-Rec)]
* [May 2023] **"Playing repeated games with Large Language Models."** *Elif Akata (U of Tübingen) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16867)]
* [May 2023] **"The Role of Summarization in Generative Agents: A Preliminary Perspective."** *Xiachong Feng (HIT) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.01253)]
* [Apr 2023] **"Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models."** *Jimmy Wei (Cornell & Meta) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.13835)] [[dataset](https://github.com/facebookresearch/LIGHT/tree/main/light/modeling/tasks/multilight)] [[code](https://github.com/facebookresearch/LIGHT/tree/main/crowdsourcing/dialogues/multi_party_chat)]
* 🔥 [Apr 2023] **"Generative Agents: Interactive Simulacra of Human Behavior."** *Joon Sung Park (Stanford) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.03442)] [[code](https://github.com/joonspk-research/generative_agents)]

### Human-Agent Interaction

* [Oct 2023] **"How AI Processing Delays Foster Creativity: Exploring Research Question Co-Creation with an LLM-based Agent."** *Yiren Liu (UIUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.06155)]
* [Aug 2023] **"Quantifying the Impact of Large Language Models on Collective Opinion Dynamics."** *Chao Li (ZJU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.03313)]
* [Aug 2023] **"SAPIEN: Affective Virtual Agents Powered by Large Language Models."** *Masum Hasan (U of Rochester) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.03022)]
* [Jul 2023] **"Understanding the Benefits and Challenges of Using Large Language Model-based Conversational Agents for Mental Well-being Support."** *Zilin Ma (Harvard) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.15810)]

### Agents-Powered LLMs

* [Oct 2023] **"Agent Instructs Large Language Models to be General Zero-Shot Reasoners."** *Nicholas Crispino (WashU) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.03710)] [[code](https://github.com/wang-research-lab/agentinstruct)]
* [Oct 2023] **"ß-Coder: Value-Based Deep Reinforcement Learning for Program Synthesis."** *Zishun Yu (UIC & ByteDance) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.03173)]
* 🔥 [May 2023] **"Training Socially Aligned Language Models in Simulated Human Society."** *Ruibo Liu (Dartmouth) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16960)] [[code](https://github.com/agi-templar/Stable-Alignment)]
* 📖 [May 2023] **"Language Models Meet World Models: Embodied Experiences Enhance Language Models."** *Jiannan Xiang (UCSD) et al.* NeurIPS 2023. [[paper](https://arxiv.org/abs/2305.10626)] [[code](https://github.com/szxiangjn/world-model-for-language-model)]

### Benchmark

* [Oct 2023] **"Balancing Autonomy and Alignment: A Multi-Dimensional Taxonomy for Autonomous LLM-powered Multi-Agent Architectures."** *Thorsten Händler (FERNFH) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.03659)]
* [Oct 2023] **"Benchmarking Large Language Models As AI Research Agents."** *Qian Huang (Stanford) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.03302)] [[code](https://github.com/snap-stanford/MLAgentBench)]
* [Oct 2023] **"MetaTool Benchmark for Large Language Models: Deciding Whether to Use Tools and Which to Use."** *Yue Huang (Lehigh University) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.03128)] [[dataset](https://atlas.nomic.ai/map/a43a6a84-4453-428a-8738-2534d7bf0b89/b2b8134b-a37e-45d2-a0d9-765911f27df6)]
* [Oct 2023] **"SmartPlay : A Benchmark for LLMs as Intelligent Agents."** *Yue Wu (CMU & Microsoft) et al.* arXiv. [[paper](https://arxiv.org/abs/2310.01557)] [[code](https://github.com/microsoft/SmartPlay)]
* [Sep 2023] **"Identifying the Risks of LM Agents with an LM-Emulated Sandbox"** *Yangjun Ruan (University of Toronto & Vector Institute) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.15817)] [[code](https://github.com/ryoungj/toolemu)] [[demo](https://demo.toolemu.com/)] [[project page](https://toolemu.com/)]
* [Aug 2023] **"BOLAA: Benchmarking and Orchestrating LLM-augmented Autonomous Agents."** *Zhiwei Liu (Salesforce) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.05960)] [[code](https://github.com/salesforce/BOLAA)]
* 🔥 [Aug 2023] **"AgentBench: Evaluating LLMs as Agents."** *Xiao Liu (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.03688)] [[code](https://github.com/THUDM/AgentBench)] [[project page](https://llmbench.ai/)]
* [Aug 2023] **"TPTU: Task Planning and Tool Usage of Large Language Model-based AI Agents."** *Jingqing Ruan (SenseTime) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.03427)]

### Survey & Tutorial

* [Sep 2023] **"Natural Language based Context Modeling and Reasoning with LLMs: A Tutorial."** *Haoyi Xiong (Baidu) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.15074)]
* [Sep 2023] **"An In-depth Survey of Large Language Model-based Artificial Intelligence Agents."** *Pengyu Zhao (BJTU) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.14365)]
* 🔥 [Sep 2023] **"The Rise and Potential of Large Language Model Based Agents: A Survey."** *Zhiheng Xi (FDU) et al.* arXiv. [[paper](https://arxiv.org/abs/2309.07864)] [[GitHub](https://github.com/WooooDyy/LLM-Agent-Paper-List)]
* 🔥 [Aug 2023] **"A Survey on Large Language Model based Autonomous Agents."** *Lei Wang (RUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2308.11432)] [[GitHub](https://github.com/Paitesanshi/LLM-Agent-Survey)]
* 🔥 [Mar 2023] **"A Survey of Large Language Models** (Sec. 6.3 - Planning for Complex Task Solving)." *Wayne Xin Zhao (RUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.18223)] [[GitHub](https://github.com/RUCAIBox/LLMSurvey#planning-for-complex-task-solving)]

## Open-Source Projects

### Autonomous Task Solver Projects

* ![Auto-GPT Stars](https://img.shields.io/github/stars/Significant-Gravitas/Auto-GPT) [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) - An experimental open-source attempt to make GPT-4 fully autonomous.
* ![LangChain Stars](https://img.shields.io/github/stars/langchain-ai/langchain) [🦜️🔗 LangChain](https://github.com/langchain-ai/langchain) - Building applications with LLMs through composability.
* ![GPT Engineer Stars](https://img.shields.io/github/stars/AntonOsika/gpt-engineer) [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - Specify what you want it to build, the AI asks for clarification, and then builds it.
* ![MetaGPT Stars](https://img.shields.io/github/stars/geekan/MetaGPT) [MetaGPT](https://github.com/geekan/MetaGPT) - 🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo.
* ![BabyAGI Stars](https://img.shields.io/github/stars/yoheinakajima/babyagi) [BabyAGI](https://github.com/yoheinakajima/babyagi) - An AI-powered task management system.

### Multi-Agent Simulation Projects

* ![AI Town Stars](https://img.shields.io/github/stars/a16z-infra/ai-town) [AI Town 🏠💻💌](https://github.com/a16z-infra/ai-town) - A deployable starter kit for building and customizing your own version of AI town - a virtual town where AI characters live, chat and socialize.
* ![GPTeam Stars](https://img.shields.io/github/stars/101dotxyz/GPTeam) [GPTeam](https://github.com/101dotxyz/GPTeam) - An open-source multi-agent simulation.
* ![ChatArena Stars](https://img.shields.io/github/stars/chatarena/chatarena) [🏟 ChatArena](https://github.com/chatarena/chatarena) - Multi-agent language game environments for LLMs.
* ![AgentVerse Stars](https://img.shields.io/github/stars/OpenBMB/AgentVerse) [🤖 AgentVerse 🪐](https://github.com/OpenBMB/AgentVerse) - A flexible framework that simplifies the process of building custom multi-agent environments for large language models (LLMs).

## Perspectives
* [Language agents: a critical evolutionary step of artificial intelligence](https://yusu.substack.com/p/language-agents) - Yu Su (OSU), Sep 5, 2023.
* [Introducing XLang: An Open-Source Framework for Building Language Model Agents via Executable Language Grounding](https://www.xlang.ai/blog/xlang-intro) - XLANG Lab, Aug 9, 2023.
* [What are GPT Agents? A deep dive into the AI interface of the future](https://logankilpatrick.medium.com/what-are-gpt-agents-a-deep-dive-into-the-ai-interface-of-the-future-3c376dcb0824) - Learn why Agents are a core part of the future of AI, Logan Kilpatrick (OpenAI), Jul 25, 2023.
* [Language Agents in the Digital World: Opportunities and Risks](https://princeton-nlp.github.io/language-agent-impact) - Shunyu Yao (Princeton) et al., Jul 24, 2023.
* [KokoMind: Can LLMs Understand Social Interactions?](https://chats-lab.github.io/KokoMind/) - Imagine an AI 🤖 at a cocktail party 🍻, Weiyan Shi (Columbia) et al., Jul, 2023
* [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent) - Amazing blog by Lilian Weng (OpenAI), Jun 23, 2023.

## Other Related Sources

* [Personalized Generative AI](https://sites.google.com/view/pgai2023) @ CIKM'23
* [LLM-Agents-Papers](https://github.com/AGI-Edgerunners/LLM-Agents-Papers) - A repo lists papers about LLM role playing, memory mechanism and LLM game playing.
* [LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers) - Must-read papers on multiagents of LLMs.
* [awesome-llm-agents](https://github.com/kaushikb11/awesome-llm-agents) - A curated list of awesome LLM agents.

## Acknowledgement

We greatly appreciate any contributions via PRs, issues, emails, or other methods. Thanks Tianle Cai ([@ctlllll](https://github.com/ctlllll)), Yifan Song ([@Yifan-Song793](https://github.com/Yifan-Song793)), Xinya Du ([@xinyadu](https://github.com/xinyadu)), Binfeng Xu ([@billxbf](https://github.com/billxbf)), Xuanhe Zhou ([@zhouxh19](https://github.com/zhouxh19)), Boyuan Zheng ([@boyuanzheng010](https://github.com/boyuanzheng010)), Qiao Jin ([@Andy-jqa](https://github.com/Andy-jqa)), Shenao Zhang ([@shenao-zhang](https://github.com/shenao-zhang)), Yu Gu ([@entslscheia](https://github.com/entslscheia)), Zhibin Gou ([@ZubinGou](https://github.com/ZubinGou)), Fan Zhou ([@koalazf99](https://github.com/koalazf99)), Ziniu Hu ([@acbull](https://github.com/acbull)), Yangjun Ruan ([@ryoungj](https://github.com/ryoungj)) and many others for their kind suggestions and contributions. ❤️

The repository is initially built and maintained by [Yupeng Hou](https://yupenghou.com/) ([yphou@ucsd.edu](mailto:yphou@ucsd.edu)).
