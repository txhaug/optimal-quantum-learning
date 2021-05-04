# Optimal training of variational quantum algorithm without barren plateaus

Example code to optimally train a variational quantum algorithm for learning quantum states. Uses the quantum Fisher information metric to calculate optimal adaptive learning rate for gradient ascent. 
Uses quantum natural gradient or generalized quantum natural gradient for optimal gradients.
Quantum natural gradient requires regularization (add small hyperparameter times identity to quantum Fisher information metric) to run stable, while generalized quantum natural gradient works without regularization.

Companion code for "Optimal training of variational quantum algorithm without barren plateaus" by T. Haug, M.S. Kim
http://arxiv.org/abs/2104.14543

Requirements: Numpy, Scipy, matplotlib, Qutip (http://qutip.org/, install via "pip qutip")

@author: Tobias Haug, Imperial College London
