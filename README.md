# Emotion recognition in conversation (ERC)

2016:

2017:

2018:

2019:

2020:

2021:

1. Towards Emotional  Support Dialog Systems   $\textcolor{Red}{(ACL, CCF-A)}$

   $\bullet Motivation :$

   在对话系统中能提供情绪支持是十分重要的，但是目前来说，之前的研究基本是关注如何对于该会话做出合理的回应，但是并不考虑该回应是否可以帮助到对方，而且，由于缺乏好的任务设计和有效的情绪支持对话语料库，现有研究依旧没有将情绪支持融入对话系统。

   $\bullet Method :$

   本文定义了情绪支持对话任务（ESC）和基于Hill的帮助技巧理论提出ESC框架，此外还构建了一个情绪支持对话数据集(ESConv)。以Hill理论为核心模拟人类与朋友，家人等的交互关系而不是直接采取专业咨询过程，这有利于普通情绪分析。其中包括三个状态：探索，安慰和行动；每一个状态又包含了多个支持策略，状态顺序可以根据个人对话需要而变化，而不是固定的探索，安慰然后行动。策略有9种，包括提问，重述，建议等，在不同状态，采用这些策略去达成目的，比如探索阶段，可以通过提问获取更多信息，或者重述对方问题以刺激对方真实想法等策略去明确对方的问题是什么，有利于后面的安慰和行为状态。最后还有情绪评估的方法，通过情绪强度值去判断我们的行为是否对help-seeker有帮助。

   $\bullet Experiment \  Result :$

   实验结果表示，对于数据集（ESConv):评估它能对经典生成式对话模型（以BlenderBot和DialoGPT作为预训练模型，Vanilla和Variants with strategy作为变体）提高多少性能，结果显示该数据集对于生成式对话性能提升帮助很大，此外这些模型能从ESConv数据集中学习到如何提供有效的情绪支持。**(Written by Wenhua Zhu)** [(BibTex)](https://aclanthology.org/2021.acl-long.269.pdf)
   

 
