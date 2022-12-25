# gpt_learnings
Just me playing around with the latests GPT zoo



# Papers
## Training language models to follow instructions with human feedback
https://arxiv.org/pdf/2203.02155.pdf

Explains three steps recipe:
1. Supervised modelling to fine-tune a "knowledge" model.. In this case GPT-3
2. "A Reward Model" to summarize human understand of what is considered "acceptable"
3. Policy trained using PPO and the reward model
## Deep reinforcement learning from human preferences
https://arxiv.org/abs/1706.03741
Uses pair-wise ranking score function to rank preferences

## Proximal Policy Optimization Algorithms
https://arxiv.org/pdf/1707.06347.pdf
Simplified TRPO
