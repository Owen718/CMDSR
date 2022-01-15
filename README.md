# CMDSR
Conditional Meta-Network for Blind Super-Resolution with Multiple Degradations

## Introduction
CMDSR is a novel conditional meta-network framework which helps the SR framework learn how to adapt to changes in the degradation distribution of input. The ConditionNet of our framework first learns the degradation prior from a support set, which is composed of a series of degraded image patches from the same task. Then the adaptive BaseNet rapidly shifts its parameters according to the conditional features. A task contrastive loss is also proposed to shorten the inner-task distance and enlarge the crosstask distance between task-level features. Without predefining degradation maps, our blind framework can conduct one single parameter update to yield considerable improvement in SR results. More details can be found in our [paper](https://arxiv.org/abs/2104.03926)

## Architecture
Whole Architecture of CMDSR
<div align=center><img src="https://github.com/guanghaoyin/CMDSR/blob/main/figs/CMDSR.png" alt="CMDSR" width="640" height="240" align="middle" /></div>


## Citation
Please cite our [paper](https://arxiv.org/abs/2104.03926) if you use our code or data.

```
@article{yin2021conditional,
  title={Conditional Meta-Network for Blind Super-Resolution with Multiple Degradations},
  author={Yin, Guanghao and Wang, Wei and Yuan, Zehuan and Yu, Dongdong and Sun, Shouqian and Wang, Changhu},
  journal={arXiv preprint arXiv:2104.03926},
  year={2021}
}

```
