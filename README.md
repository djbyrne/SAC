# Soft Actor Critic

An implementation of the SAC algorithm trained on the Roboschool HalfCheetah environment using pytorch. This repo implements the latest version of SAC using only Policy and Soft Q networks. The agent is built with pytorch and is based on Vitchyr Pong's [rlkit](https://github.com/vitchyr/rlkit/tree/master/rlkit/torch/sac) and OpenAI's [Spinning Up](https://github.com/openai/spinningup/tree/master/spinup/algos/sac) examples.


## Getting Started

These instructions will demonstrate how to setup a conda environment with all requirements for the project setup.

### Installing

```
conda env create -n rl_dev python=3.6

conda activate rl_dev

git clone https://github.com/djbyrne/SAC.git

cd SAC

python setup.py install 

jupyter notebook
```

## Acknowledgments

* Vitchyr Pong [rlkit](https://github.com/vitchyr/rlkit/tree/master/rlkit/torch/sac)
* OpenAI [Spinning Up](https://github.com/openai/spinningup)
* Dulat Yerzat [RL-Adventure-2](https://github.com/openai/baselines)
