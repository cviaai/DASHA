# Decentralized Autofocusing System with Hierarchical Agents

[![License](https://img.shields.io/github/license/analysiscenter/pydens.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Python](https://img.shields.io/badge/python-3.7-blue.svg)](https://python.org)
[![Python](https://img.shields.io/badge/pytorch-1.6.0-red)](https://pytorch.org)
[![arXiv](https://img.shields.io/badge/arXiv-2108.12842-b31b1b.svg)](https://arxiv.org/abs/2108.12842)



## Requirements

Ray RLlib is required to run the training scripts:

```setup
pip install 'ray[rllib]'
```
## Training

To train the models used in the paper, run this command:

```train
basler_camera/RL/RL_corning_basler_ver5.ipynb
```

## Citing
If you use this package in your publications or in other work, please cite it as follows:
```
@misc{anikina2021decentralized,
      title={Decentralized Autofocusing System with Hierarchical Agents}, 
      author={Anna Anikina and Oleg Y. Rogov and Dmitry V. Dylov},
      year={2021},
      eprint={2108.12842},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
## Maintainers
Anna S. Anikina (Main contributor) @annshorn

Oleg Y. Rogov @olegrgv
