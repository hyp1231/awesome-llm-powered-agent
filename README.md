# Awesome LLM-Powered Agent

[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/hyp1231/awesome-llm-powered-agent/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Thanks to the impressive planning, reasoning, and tool-calling capabilities of Large Language Models (LLMs), people are actively studying and developing **LLM-powered agents.** These agents are possible to autonomously (and collaboratively) solve complex tasks, or simulate human interactions.

Our goal with this project is to build an exhaustive collection of awesome resources relevant to LLM-powered agents encompassing papers, repositories, and more. We strive to keep these updated regularly and continuously. **We greatly appreciate any contributions via PRs, issues, emails, or other methods.**

-----

<i style="color: red;">New!</i> **Call for Papers** until Aug 25, 2023 - [Personalized Generative AI](https://sites.google.com/view/pgai2023) @ CIKM'23 - Submissions relating to LLM-powered agents are highly welcomed and valued!

-----

- [Papers](#papers)
  - [Autonomous Task Solver](#autonomous-task-solver)
    - [General Single Agent](#general-single-agent)
    - [Multi-Agent Cooperation](#multi-agent-cooperation)
    - [Application](#application)
      - [Web Agents](#web-agents)
      - [RL Agents](#rl-agents)
      - [Robotics & Embodied AI](#robotics--embodied-ai)
      - [Gaming & Role-Playing](#gaming--role-playing)
      - [Other Applications](#other-applications)
  - [Human Interaction Simulation](#human-interaction-simulation)
  - [Agents-Powered LLMs](#agents-powered-llms)
  - [Survey](#survey)
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

#### General Single Agent

* [May 2023] **"SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks."** *Bill Yuchen Lin (AI2) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.17390)] [[code](https://github.com/yuchenlin/swiftsage)] [[project page](https://yuchenlin.xyz/swiftsage)]
* [May 2023] **"ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models."** *Zhipeng Chen (RUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.14323)] [[code](https://github.com/RUCAIBOX/ChatCoT)]
* 🔥 [Mar 2023] **"Reflexion: Language Agents with Verbal Reinforcement Learning."** *Noah Shinn (Northeastern) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.11366)] [[code](https://github.com/noahshinn024/reflexion)]
* 🔥📖 [Oct 2022] **"ReAct: Synergizing Reasoning and Acting in Language Models."** *Shunyu Yao (Princeton & Google Brain) et al.* ICLR 2023. [[paper](https://arxiv.org/abs/2210.03629)] [[code](https://github.com/ysymyth/ReAct)] [[project page](https://react-lm.github.io)]

#### Multi-Agent Cooperation

* [Jul 2023] **"Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration."** *Zhenhailong Wang (UIUC & MSRA) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.05300)] [[code](https://github.com/MikeWangWZHL/Solo-Performance-Prompting)]
* [Jul 2023] **"RoCo: Dialectic Multi-Robot Collaboration with Large Language Models."** *Mandi Zhao (Columbia) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.04738)] [[code](https://github.com/MandiZhao/robot-collab)] [[project page](https://project-roco.github.io)]
* [Jul 2023] **"Wireless Multi-Agent Generative AI: From Connected Intelligence to Collective Intelligence."** *Hang Zou (Technology Innovation Institute, UAE) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.02757)]
* [Jul 2023] **"Building Cooperative Embodied Agents Modularly with Large Language Models."** *Hongxin Zhang (UMass) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.02485)] [[code](https://github.com/UMass-Foundation-Model/Co-LLM-Agents)] [[project page](https://vis-www.cs.umass.edu/Co-LLM-Agents)]
* [Jun 2023] **"Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents."** *Yashar Talebirad (UAlberta) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.03314)]
* [May 2023] **"Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate."** *Tian Liang (THU & Tencent) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.19118)] [[code](https://github.com/Skytliang/Multi-Agents-Debate)]
* 🔥 [May 2023] **"Large Language Models as Tool Makers."** *Tianle Cai (Deepmind & Princeton) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.17126)] [[code](https://github.com/ctlllll/LLM-ToolMaker)]
* [May 2023] **"Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback."** *Yao Fu (U of Edinburgh) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.10142)] [[code](https://github.com/FranxYao/GPT-Bargaining)]

#### Application

##### Web Agents

* 🔥 [Jul 2023] **"WebArena: A Realistic Web Environment for Building Autonomous Agents."** *Shuyan Zhou (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.13854)] [[code](https://github.com/web-arena-x/webarena)] [[project page](https://webarena.dev)]
* [Jul 2023] **"A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis."** *Izzeddin Gur (DeepMind) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.12856)]
* 🔥 [Jun 2023] **"Mind2Web: Towards a Generalist Agent for the Web."** *Xiang Deng (OSU) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.06070)] [[code](https://github.com/OSU-NLP-Group/Mind2Web)] [[project page](https://osu-nlp-group.github.io/Mind2Web)]
* [May 2023] **"Augmenting Autotelic Agents with Large Language Models."** *Cédric Colas (MIT & Inria) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.12487)]
* [May 2023] **"Mobile-Env: An Evaluation Platform and Benchmark for Interactive Agents in LLM Era."** *Danyang Zhang (SJTU) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.08144)] [[code](https://github.com/X-LANCE/Mobile-Env)]
* 📖 [Apr 2023] **"Emergent autonomous scientific research capabilities of large language models."** *Daniil A. Boiko (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.05332)]
* [Mar 2023] **"Language Models can Solve Computer Tasks."** *Geunwoo Kim (UCI) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.17491)] [[code](https://github.com/posgnu/rci-agent)] [[project page](https://posgnu.github.io/rci-web)]
* 📖 [Jul 2022] **"WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents."** *Shunyu Yao (Princeton) et al.* NeurIPS 2022. [[paper](https://arxiv.org/abs/2207.01206)] [[code](https://github.com/princeton-nlp/WebShop)] [[project page](https://webshop-pnlp.github.io)]

##### RL Agents

* [Jul 2023] **"Towards A Unified Agent with Foundation Models."** *Norman Di Palo (ICL & DeepMind) et al.* Reincarnating RL @ ICLR 2023. [[paper](https://arxiv.org/abs/2307.09668)]
* [Jun 2023] **"Large Language Model Is Semi-Parametric Reinforcement Learning Agent."** *Danyang Zhang (SJTU) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.07929)]
* [May 2023] **"Semantically Aligned Task Decomposition in Multi-Agent Reinforcement Learning."** *Wenhao Li (CUHK) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.10865)]

##### Robotics & Embodied AI

* [Jul 2023] **"Embodied Task Planning with Large Language Models."** *Zhenyu Wu (BUPT) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.01848)] [[code](https://github.com/Gary3410/TaPA)] [[project page](https://gary3410.github.io/TaPA/)]
* [Jun 2023] **"Enabling Intelligent Interactions between an Agent and an LLM: A Reinforcement Learning Approach."** *Bin Hu (Zhejiang Lab) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.03604)] [[code](https://github.com/ZJLAB-AMMI/LLM4RL)]
* 🔥 [May 2023] **"Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory."** *Xizhou Zhu (THU & SenseTim) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.17144)] [[code](https://github.com/OpenGVLab/GITM)]
* 🔥 [May 2023] **"Voyager: An Open-Ended Embodied Agent with Large Language Models."** *Guanzhi Wang (NVIDIA & Caltech) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16291)] [[code](https://github.com/MineDojo/Voyager)] [[project page](https://voyager.minedojo.org)]
* [May 2023] **"Plan, Eliminate, and Track -- Language Models are Good Teachers for Embodied Agents."** *Yue Wu (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.02412)]
* [Feb 2023] **"Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents."** *Zihao Wang (PKU) et al.* arXiv. [[paper](https://arxiv.org/abs/2302.01560)] [[code](https://github.com/CraftJarvis/MC-Planner)]
* [Feb 2023] **"Collaborating with language models for embodied reasoning."** *Ishita Dasgupta (DeepMind) et al.* LaReL @ NeurIPS 2022. [[paper](https://arxiv.org/abs/2302.00763)]
* [Jan 2023] **"Do Embodied Agents Dream of Pixelated Sheep: Embodied Decision Making using Language Guided World Modelling."** *Kolby Nottingham (UCI) et al.* ICML 2023. [[paper](https://arxiv.org/abs/2301.12050)] [[code](https://github.com/DeckardAgent/deckard)] [[project page](https://deckardagent.github.io)]
* 📖 [Dec 2022] **"LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models."** *Chan Hee Song (OSU) et al.* ICCV 2023. [[paper](https://arxiv.org/abs/2212.04088)] [[project page](https://dki-lab.github.io/LLM-Planner)]

##### Gaming & Role-Playing

* [May 2023] **"Role-Play with Large Language Models."** *Murray Shanahan (DeepMind & ICL) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16367)]
* [May 2023] **"clembench: Using Game Play to Evaluate Chat-Optimized Language Models as Conversational Agents."** *Kranti Chalamalasetti (University of Potsdam) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.13455)] [[code](https://github.com/clp-research/clembench)]
* 🔥 [Mar 2023] **"CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society."** *Guohao Li (KAUST) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.17760)] [[code](https://github.com/camel-ai/camel)] [[project page](https://www.camel-ai.org)]

##### Other Applications

* [Jun 2023] **"Towards Autonomous Testing Agents via Conversational Large Language Models."** *Robert Feldt (Chalmers University of Technology) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.05152)]
* 🔥 [Mar 2023] **"HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face."** *Yongliang Shen (ZJU & MSRA) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.17580)] [[code](https://github.com/microsoft/JARVIS)]

### Human Interaction Simulation

* [Jul 2023] **"S^3: Social-network Simulation System with Large Language Model-Empowered Agents."** *Chen Gao (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.14984)]
* [Jul 2023] **"Are you in a Masquerade? Exploring the Behavior and Impact of Large Language Model Driven Social Bots in Online Social Networks."** *Siyu Li (SCU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.10337)] [[dataset](https://github.com/Litsay/Masquerade-23)]
* [Jul 2023] **"Communicative Agents for Software Development."** *Chen Qian (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.07924)]
* [Jul 2023] **"Epidemic Modeling with Generative Agents."** *Ross Williams (Virginia Tech) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.04986)] [[code](https://github.com/bear96/GABM-Epidemic)]
* [Jul 2023] **"To Infinity and Beyond: SHOW-1 and Showrunner Agents in Multi-Agent Simulations."** *Philipp Maas (Fable Studio) et al.* preprint. [[paper](https://fablestudio.github.io/showrunner-agents/static/pdfs/To_Infinity_and_Beyond_SHOW-1_And_Showrunner_Agents_in_Multi_Agent_Simulations_v2.pdf)] [[project page](https://fablestudio.github.io/showrunner-agents)]
* [Jun 2023] **"RecAgent: A Novel Simulation Paradigm for Recommender Systems."** *Lei Wang (RUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.02552)] [[code](https://github.com/RUC-GSAI/YuLan-Rec)]
* [May 2023] **"Playing repeated games with Large Language Models."** *Elif Akata (U of Tübingen) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16867)]
* [May 2023] **"The Role of Summarization in Generative Agents: A Preliminary Perspective."** *Xiachong Feng (HIT) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.01253)]
* [Apr 2023] **"Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models."** *Jimmy Wei (Cornell & Meta) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.13835)] [[dataset](https://github.com/facebookresearch/LIGHT/tree/main/light/modeling/tasks/multilight)] [[code](https://github.com/facebookresearch/LIGHT/tree/main/crowdsourcing/dialogues/multi_party_chat)]
* 🔥 [Apr 2023] **"Generative Agents: Interactive Simulacra of Human Behavior."** *Joon Sung Park (Stanford) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.03442)]

### Agents-Powered LLMs

* 🔥 [May 2023] **"Training Socially Aligned Language Models in Simulated Human Society."** *Ruibo Liu (Dartmouth) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16960)] [[code](https://github.com/agi-templar/Stable-Alignment)]
* [May 2023] **"Language Models Meet World Models: Embodied Experiences Enhance Language Models."** *Jiannan Xiang (UCSD) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.10626)] [[code](https://github.com/szxiangjn/world-model-for-language-model)]

### Survey

* 🔥 [Mar 2023] **"A Survey of Large Language Models** (Sec. 6.3 - Planning for Complex Task Solving)." *Wayne Xin Zhao (RUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.18223)] [[GitHub](https://github.com/RUCAIBox/LLMSurvey#planning-for-complex-task-solving)]

## Open-Source Projects

### Autonomous Task Solver Projects

* ![Auto-GPT Stars](https://img.shields.io/github/stars/Significant-Gravitas/Auto-GPT) [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) - An experimental open-source attempt to make GPT-4 fully autonomous.
* ![LangChain Stars](https://img.shields.io/github/stars/langchain-ai/langchain) [🦜️🔗 LangChain](https://github.com/langchain-ai/langchain) - Building applications with LLMs through composability.
* ![GPT Engineer Stars](https://img.shields.io/github/stars/AntonOsika/gpt-engineer) [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - Specify what you want it to build, the AI asks for clarification, and then builds it.
* ![BabyAGI Stars](https://img.shields.io/github/stars/yoheinakajima/babyagi) [BabyAGI](https://github.com/yoheinakajima/babyagi) - An AI-powered task management system.

### Multi-Agent Simulation Projects

* ![GPTeam Stars](https://img.shields.io/github/stars/101dotxyz/GPTeam) [GPTeam](https://github.com/101dotxyz/GPTeam) - An open-source multi-agent simulation.
* ![ChatArena Stars](https://img.shields.io/github/stars/chatarena/chatarena) [🏟 ChatArena](https://github.com/chatarena/chatarena) - Multi-agent language game environments for LLMs.
* ![AgentVerse Stars](https://img.shields.io/github/stars/OpenBMB/AgentVerse) [🤖 AgentVerse 🪐](https://github.com/OpenBMB/AgentVerse) - A flexible framework that simplifies the process of building custom multi-agent environments for large language models (LLMs).

## Perspectives

* [KokoMind: Can LLMs Understand Social Interactions?](https://chats-lab.github.io/KokoMind/) - Imagine an AI 🤖 at a cocktail party 🍻, Weiyan Shi (Columbia) et al., Jul 2023
* [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent) - Amazing blog by Lilian Weng, Jun 23 2023.

## Other Related Sources

* [Personalized Generative AI](https://sites.google.com/view/pgai2023) @ CIKM'23
* [LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers) - Must-read papers on multiagents of LLMs.
* [awesome-llm-agents](https://github.com/kaushikb11/awesome-llm-agents) - A curated list of awesome LLM agents.

## Acknowledgement

We greatly appreciate any contributions via PRs, issues, emails, or other methods. Thanks Tianle Cai ([@ctlllll](https://github.com/ctlllll)) and many others for their kind suggestions and contributions. ❤️

The repository is initially built and maintained by [Yupeng Hou](https://yupenghou.com/) ([yphou@ucsd.edu](mailto:yphou@ucsd.edu)).
