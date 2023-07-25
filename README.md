# Awesome LLM-Powered Agent

[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/hyp1231/awesome-llm-powered-agent/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Thanks to the impressive planning, reasoning, and tool-calling capabilities of Large Language Models (LLMs), people are actively studying and developing **LLM-powered agents.** These agents are possible to autonomously (and collaboratively) solve complex tasks, or simulate human interactions.

Our goal with this project is to build an exhaustive collection of awesome resources relevant to LLM-powered agents encompassing papers, repositories, and more. We strive to keep these updated regularly and continuously. **We greatly appreciate any contributions via PRs, issues, emails, or other methods.**

- [Papers](#papers)
  - [Autonomous Task Solver](#autonomous-task-solver)
    - [General](#general)
    - [Web Agents](#web-agents)
    - [Robotics & Embodied AI](#robotics--embodied-ai)
    - [Multi-Agent Cooperation](#multi-agent-cooperation)
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

### Autonomous Task Solver

#### General

* [May 2023] **"SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks."** *Bill Yuchen Lin (AI2) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.17390)] [[code](https://github.com/yuchenlin/swiftsage/)] [[project page](https://yuchenlin.xyz/swiftsage/)]
* [Mar 2023] **"HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face."** *Yongliang Shen (ZJU & MSRA) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.17580)] [[code](https://github.com/microsoft/JARVIS)]
* [Mar 2023] **"Reflexion: Language Agents with Verbal Reinforcement Learning."** *Noah Shinn (Northeastern) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.11366)] [[code](https://github.com/noahshinn024/reflexion)]
* [Oct 2022] **"ReAct: Synergizing Reasoning and Acting in Language Models."** *Shunyu Yao (Princeton & Google Brain) et al.* ICLR 2023. [[paper](https://arxiv.org/abs/2210.03629)] [[code](https://github.com/ysymyth/ReAct)] [[project page](https://react-lm.github.io/)]

#### Web Agents

* [Jul 2023] **"A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis."** *Izzeddin Gur (DeepMind) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.12856)]
* [Apr 2023] **"Emergent autonomous scientific research capabilities of large language models."** *Daniil A. Boiko (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.05332)]
* [Jul 2022] **"WebShop: Towards Scalable Real-World Web
Interaction with Grounded Language Agents."** *Shunyu Yao (Princeton) et al.* NeurIPS 2022. [[paper](https://arxiv.org/abs/2207.01206)] [[code](https://github.com/princeton-nlp/WebShop)] [[project page](https://webshop-pnlp.github.io/)]

#### Robotics & Embodied AI

* [Jul 2023] **"Towards A Unified Agent with Foundation Models."** *Norman Di Palo (ICL & DeepMind) et al.* Reincarnating RL @ ICLR 2023. [[paper](https://arxiv.org/abs/2307.09668)]
* [May 2023] **"Voyager: An Open-Ended Embodied Agent with Large Language Models."** *Guanzhi Wang (NVIDIA & Caltech) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16291)] [[code](https://github.com/MineDojo/Voyager)] [[project page](https://voyager.minedojo.org/)]
* [May 2023] **"Plan, Eliminate, and Track -- Language Models are Good Teachers for Embodied Agents."** *Yue Wu (CMU) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.02412)]
* [Feb 2023] **"Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents."** *Zihao Wang (PKU) et al.* arXiv. [[paper](https://arxiv.org/abs/2302.01560)] [[code](https://github.com/CraftJarvis/MC-Planner)]
* [Feb 2023] **"Collaborating with language models for embodied reasoning."** *Ishita Dasgupta (DeepMind) et al.* LaReL @ NeurIPS 2022. [[paper](https://arxiv.org/abs/2302.00763)]
* [Jan 2023] **"Do Embodied Agents Dream of Pixelated Sheep: Embodied Decision Making using Language Guided World Modelling."** *Kolby Nottingham (UCI) et al.* ICML 2023. [[paper](https://arxiv.org/abs/2301.12050)] [[code](https://github.com/DeckardAgent/deckard)] [[project page](https://deckardagent.github.io/)]
* [Dec 2022] **"LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models."** *Chan Hee Song (OSU) et al.* ICCV 2023. [[paper](https://arxiv.org/abs/2212.04088)] [[project page](https://dki-lab.github.io/LLM-Planner/)]

#### Multi-Agent Cooperation

* [Jul 2023] **"Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration."** *Zhenhailong Wang (UIUC & MSRA) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.05300)] [[code](https://github.com/MikeWangWZHL/Solo-Performance-Prompting)]
* [May 2023] **"Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate."** *Tian Liang (THU & Tencent) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.19118)] [[code](https://github.com/Skytliang/Multi-Agents-Debate)]
* [May 2023] **"Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback."** *Yao Fu (U of Edinburgh) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.10142)] [[code](https://github.com/FranxYao/GPT-Bargaining)]
* [Mar 2023] **"CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society."** *Guohao Li (KAUST) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.17760)] [[code](https://github.com/camel-ai/camel)] [[project page](https://www.camel-ai.org/)]

### Human Interaction Simulation

* [Jul 2023] **"Are you in a Masquerade? Exploring the Behavior and Impact of Large Language Model Driven Social Bots in Online Social Networks."** *Siyu Li (SCU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.10337)] [[dataset](https://github.com/Litsay/Masquerade-23)]
* [Jul 2023] **"To Infinity and Beyond: SHOW-1 and Showrunner
Agents in Multi-Agent Simulations."** *Philipp Maas (Fable Studio) et al.* preprint. [[paper](https://fablestudio.github.io/showrunner-agents/static/pdfs/To_Infinity_and_Beyond_SHOW-1_And_Showrunner_Agents_in_Multi_Agent_Simulations_v2.pdf)] [[project page](https://fablestudio.github.io/showrunner-agents/)]
* [Jul 2023] **"Communicative Agents for Software Development."** *Chen Qian (THU) et al.* arXiv. [[paper](https://arxiv.org/abs/2307.07924)]
* [Jun 2023] **"RecAgent: A Novel Simulation Paradigm for Recommender Systems."** *Lei Wang (RUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2306.02552)] [[code](https://github.com/RUC-GSAI/YuLan-Rec)]
* [May 2023] **"Playing repeated games with Large Language Models."** *Elif Akata (U of Tübingen) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16867)]
* [Apr 2023] **"Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models."** *Jimmy Wei (Cornell & Meta) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.13835)] [[dataset](https://github.com/facebookresearch/LIGHT/tree/main/light/modeling/tasks/multilight)] [[code](https://github.com/facebookresearch/LIGHT/tree/main/crowdsourcing/dialogues/multi_party_chat)]
* [Apr 2023] **"Generative Agents: Interactive Simulacra of Human Behavior."** *Joon Sung Park (Stanford) et al.* arXiv. [[paper](https://arxiv.org/abs/2304.03442)]

### Agents-Powered LLMs

* [May 2023] **"Training Socially Aligned Language Models in Simulated Human Society."** *Ruibo Liu (Dartmouth) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.16960)] [[code](https://github.com/agi-templar/Stable-Alignment)]
* [May 2023] **"Language Models Meet World Models: Embodied Experiences Enhance Language Models."** *Jiannan Xiang (UCSD) et al.* arXiv. [[paper](https://arxiv.org/abs/2305.10626)] [[code](https://github.com/szxiangjn/world-model-for-language-model)]

### Survey

* [Mar 2023] **"A Survey of Large Language Models** (Sec. 6.3 - Planning for Complex Task Solving)." *Wayne Xin Zhao (RUC) et al.* arXiv. [[paper](https://arxiv.org/abs/2303.18223)] [[GitHub](https://github.com/RUCAIBox/LLMSurvey#planning-for-complex-task-solving)]

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

* [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) - Amazing blog by Lilian Weng, June 23, 2023.

## Other Related Sources

* [LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers) - Must-read papers on multiagents of LLMs.
* [awesome-llm-agents](https://github.com/kaushikb11/awesome-llm-agents) - A curated list of awesome LLM agents.

## Acknowledgement

We greatly appreciate any contributions via PRs, issues, emails, or other methods.

The repository is initially built and maintained by Yupeng Hou ([yphou@ucsd.edu](mailto:yphou@ucsd.edu)).
