# BayesRL
`BayesRL` is a Python library for reinforcement learning using Bayesian
approaches. It stores both agents and environments under separate classes, where
an agent class is a learning algorithm and environments are tasks that the agent
must solve. We include agents and environments for solving and implementing both
Markov decision processes (MDPs) and partially observable Markov decision
processes (POMDPs).

Examples can be found in the directory `tests/`.

## Installation
To install from pip, run
```{bash}
pip install -e "git+https://github.com/OlehLuk/bayesrl.git#egg=bayesrl"
```

## Authors
* Dustin Tran \<dtran@g.harvard.edu\>
* Xiaomin Wang \<xiaominw@mit.edu\>
* Rodrigo Gomes \<rgomes@mit.edu\>

## Refactoring by
* Oleh Lukianykhin \<lukianykhin@ucu.edu.ua\>

Refactoring was done to enable proper imports in library files. First of all, \__init__ files were updated with proper imports.

## References
* Malcolm Strens. A bayesian framework for reinforcement learning. In _Proceedings of the 17th International Conference on Machine Learning (ICML)_, 2000.

