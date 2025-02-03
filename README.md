# Optimal training of variational quantum algorithm without barren plateaus

Example code to optimally train a variational quantum algorithm for learning quantum states. Uses the quantum Fisher information metric to calculate optimal adaptive learning rate for gradient ascent. 
Uses quantum natural gradient or generalized quantum natural gradient for optimal gradients.
Quantum natural gradient requires regularization (add small hyperparameter times identity to quantum Fisher information metric) to run stable, while generalized quantum natural gradient works without regularization.

Companion code for "Optimal training of variational quantum algorithm without barren plateaus" by T. Haug, M.S. Kim
http://arxiv.org/abs/2104.14543

Requirements: 
NOTE: Requires older version of qutip, namely <=4.7.5, which has dependencies on older versions of numyp and scipy.
To install, make clean python environment and install packages as:
- pip install numpy==1.26.4
- pip install scipy==1.12.0
- pip install qutip==4.7.5

@author: Tobias Haug, Imperial College London
