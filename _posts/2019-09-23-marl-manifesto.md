---
title: "Autocurricula and the Emergence of Innovation from Social Interaction: A Manifesto for Multi-Agent Intelligence Research"
date: 2019-09-23
categories: [MARL, reading]
tags: [social-sciences, game-theory]
---
[paper](https://arxiv.org/pdf/1903.00742.pdf) by Joel Z. Leibo, Edward Hughes, Marc Lanctot and Thore Graepel

## Why am I reading this
I listened to a [TalkRL](https://www.talkrl.com/episodes/natasha-jaques) podcast with Natasha Jacques, who was talking about how social sciences can help development of intelligent agents.  
Also I was fascinated with the work at OpenAI where they study self-play in context of multi-agent RL in the [hide-and-seek game](https://openai.com/blog/emergent-tool-use/).  

## Key ideas
Developing environments for RL agents is laborious. The amount of knowledge that the agents can acquire in these environments is bounded by the richness of the environment (i.e. Board Games, Dota). Real problems are far harder than these RL envs.  
"Life is multi-agent system where any species’s innovation determines the environment to which others must adapt".  
Exploration by exploitation is an idea that adaptive units are forced to explore because the true value of their policy is shifting over time.
Curriculum structures learning by providing challenges to the adaptive units. There are two types of challenges that can cause the policy to shift:
- Exogenous Challenge  
    External change in the environment. Self play is a prime example of an exogenous challenge (think AlphaZero algorithm).
    The problem of forgetting previous policies arises due to constant innovation.
    Malthusian reinforcement learning extends self-play to allow for variable numbers of players to appear in each episode. In this framework, population size grows proportionally to its success.
- Endogenous Challenge  
    An internal change due to discovery of a better sequence of actions to reach a goal. A change that happens on the other levels of the hierarchy of agents. 
    Social dilemma is an example of endogenous challenge to the adaptive unit. 
    Any innovation that resolves a social dilemma must involve changing the behaviour of a critical fraction of the participants.
    Once a social dilemma is resolved at one hierarchy, another dilemma appears on another level.
    A society may resolve a social dilemma by hiring watchmen, but then who watches the watchmen?
    These dynamics may generate a sequence of endogenous challenges growing steadily in scope and complexity, i.e. an auto-curriculum.
How to accumulate and preserve the knowledge acquired in the auto-curriculum process?

## Thoughts
I wonder whether current paradigm of a single agent RL is an appropriate setting in which AI could emerge.  
What are some environments out there that would allow for auto-curricula? Is Minecraft rich enough to allow for continuous improvement?

## Further research
Read about [Social Influence as Intrinsic Motivation for Multi-Agent Deep Reinforcement Learning](https://arxiv.org/abs/1810.08647).  
Observe agents playing [hide-and-seek](https://github.com/openai/mujoco-worldgen/).


