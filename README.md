# Augmented-Random-Search

**Find the paper here**: [Simple random search provides a competitive approach to reinforcement learning](https://arxiv.org/pdf/1803.07055.pdf)

### Overview

* ‘Simple random search provides a competitive approach to reinforcement learning’, by Horia Mania and Aurelia Guy, University of California, Berkeley in March 20, 2018.

* Two different directions proposed for simplifying RL: 
  - Evolution Strategies : derivative-free policy optimization method, to train policies faster
  - Training linear policies via natural policy gradients to solve the continuous control problems
* ARS combines best of both to obtain the simplest model-free RL method yet, a derivative-free optimization algorithm for training linear policies.
* Simple random search method can match or exceed state-of-the-art sample efficiency on MuJoCo locomotion benchmarks.
* 15 times more computationally efficient than Evolution Strategies, the fastest competing method, which employs several complicated algorithmic elements.
* Method learns static, linear policies that achieve high rewards on all MuJoCo tasks. No neural networks are used, and yet state-of-the-art performance is still uniformly achieved.
* Though ARS successfully trains policies for locomotion tasks when hyper-parameters and random seeds are varied, it exhibits a large variance, and learned policies do not uniformly yield high rewards.


### File Details

* Detailed explanation with presentation can be found in the file **_'Augmented Random Search(1).ppt'_**.
 
* The code is intricately elaborated with proper comments for easy understanding in the file **_'ARS- Half Cheetah.ipynb'_**.
 

### ARS Algorithm

![image](https://user-images.githubusercontent.com/26281528/52167728-a40c3180-2745-11e9-96fb-7c7d824d20a9.png)


## Output in MuJoCo environment - HalfCheetah v0

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/26281528/52167871-d454cf80-2747-11e9-89c4-e5a28df196d5.gif)
