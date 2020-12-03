# PongAI
A pong agent built using Proximal Policy Optimization, a policy based Reinforcement Learning method

### Framework Used:
Pytorch

## Algorithm
PPO algorithm is a kind of policy gradient method for reinforcement learning, in which this kind of methods are an appealing approach because they directly optimize the cumulative reward and can straightforwardly be used with nonlinear function approximators such as neural networks. PPO alternates between sampling data through interaction with the environment, and optimizing a surrogate objective function using stochastic gradient ascendent. The algorithm shown in the picture below is a generic representation of a proximal policy optimization method. Whereas standard policy gradient methods perform one gradient update per data sample, it proposes a different objective function that enables multiple epochs of mini-batch updates.


