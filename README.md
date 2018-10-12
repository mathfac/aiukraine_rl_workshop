# AI Ukraine Reinforcement Learning Workshop


Latest achievements of AI beating human performance on Go and Dota 2 games were powered by Reinforcement Learning (RL). 
We will touch the basics of RL such as RL problem definition, different value functions, policy. The brief overview of 
main RL algorithms including Q-learning, Actor-Critic Algorithm. We will dive deeper in implementation one of the 
algorithms and run it on OpenAI gym environment. Finish with a summary of practical and business applications of RL.

**Minimum requirements to the listener**: knowledge of Python, basics of probability theory and machine learning.

Advantage Actor-Critic algorithms were chosen for practical consideration as strong baselines that combine 
Policy and Value function learning. This repository contains most easy to understand implementation of Advantage 
Actor-Critic algorithms.
A neural network is trained to play discrete action [CartPole](https://gym.openai.com/envs/CartPole-v0/) and
continuous action [Pendulum](https://gym.openai.com/envs/Pendulum-v0/) games.


## Alogrithms implementations

* [a2c](/simple-a2c): Simple Advantage Actor Critic (A2C)
* [a3c](/simple-a3c): Simple [Asynchronous Advantage Actor-Critic (A3C)](https://arxiv.org/pdf/1602.01783.pdf)

## Dependencies

* Python 3
* Pytorch
* Install requirements ``pip install -e .``


## Credits

Special thanks to authors of initial code implementations. They are stated inside respective directories.