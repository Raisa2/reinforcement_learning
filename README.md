# Overview
This repository contains Google Colab notebooks that implement various model-free reinforcement learning algorithms, such as value-based, policy-based, and actor-critic methods. All implementations are done in Python 3 and tested in the CartPole environment (version 1.0) of [OpenAI's Gym](https://github.com/openai/gym). Furthermore, all results are logged and illustrated using [Weights & Biases](https://wandb.ai/site) or [matplotlib](https://matplotlib.org/). [Pytorch](https://pytorch.org/) (version 1.10) is utilized to implement the neural networks in this repository.

# List of implemented algorithms
## Value-based algorithms
   - [Deep Q-Network (DQN)](value_based/dqn.ipynb)
   - [Double Deep Q-Network (DDQN)](value_based/double_dqn.ipynb)
   - [Dueling Double Deep Q-Network (DDDQN)](value_based/dueling_double_dqn.ipynb)
   - [Double Q-Network with prioritized experience replay](value_based/prior_exp_double_dqn.ipynb)
## Policy-based algorithms
   - [REINFORCE](policy_based/reinforce.ipynb)
   - [REINFORCE with Baseline](policy_based/reinforce_baseline.ipynb)
## Actor-critic algorithms
   - [Asynchronous Advantage Actor-Critic (A3C)](actor_critic/a3c.ipynb)

# Results
## DQN
<img width="369" alt="image" src="https://github.com/Raisa2/reinforcement_learning/assets/66182361/2a10f2a5-37bf-4239-9c96-6b47703860fc">

## Improvements of DQN
<img width="359" alt="image" src="https://github.com/Raisa2/reinforcement_learning/assets/66182361/fce116c4-3baf-4484-9fa4-75ff30b4778d">

## REINFORCE
<img width="359" alt="image" src="https://github.com/Raisa2/reinforcement_learning/assets/66182361/bfa0e0db-5226-46d1-be63-77c078658f43">

## REINFORCE with baseline
<img width="358" alt="image" src="https://github.com/Raisa2/reinforcement_learning/assets/66182361/893c52a5-4035-4916-a591-137c025ee791">

## A3C
<img width="374" alt="image" src="https://github.com/Raisa2/reinforcement_learning/assets/66182361/da5cda9a-72a2-4c31-a068-021bb3c79c85">

# Papers
## Value-based algorithms
- [DQN](https://www.nature.com/articles/nature14236)
- [DDQN](https://arxiv.org/abs/1509.06461)
- [DDDQN](https://arxiv.org/abs/1511.06581)
- [Double Q-Network with prioritized experience replay](https://arxiv.org/abs/1511.05952)
## Policy-based algortihms
- [REINFORCE](https://link.springer.com/article/10.1007/BF00992696)
## Actor-critic algorithms
- [A3C](https://arxiv.org/abs/1602.01783)
