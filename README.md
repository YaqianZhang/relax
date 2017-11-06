# relaxed-rebar
A repository for exploring ways to generalize the REBAR gradient estimator.

Backpropagation through the Void:
Optimizing control variates for black-box gradient estimation

by Will Grathwohl, Dami Choi, Yuhuai Wu, Geoff Roeder, David Duvenaud

We introduce a general framework for learning low-variance, unbiased gradient estimators for black-box functions of random variables, based on gradients of a learned function.
These estimators can be jointly trained with model parameters or policies, and are applicable in both discrete and continuous settings.
We give unbiased, adaptive analogs of state-of-the-art reinforcement learning methods such as advantage actor-critic.
We also demonstrate this framework for training discrete latent-variable models.


Code for VAE Experiments lives here. The Discrete RL experiments can be found at: https://github.com/wgrathwohl/relax_a2c 
