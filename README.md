# Spikingformer: Spike-driven Residual Learning for Transformer-based Spiking Neural Network, [Arxiv 2023](https://arxiv.org/abs/2304.11954)
Spikingformer is a pure event-driven transformer-based spiking neural network (**75.85% top-1** accuracy on ImageNet-1K, **+ 1.04%** and **significantly reduces energy consumption by 57.34%** compared with Spikformer). To our best knowledge, this is the first time that **a pure event-driven transformer-based SNN** has been developed in in 2023/04.

In this project, we replicate the results from previous work Spikingformer: Spike-driven Residual Learning for Transformer-based Spiking Neural Network, [Arxiv 2023](https://arxiv.org/abs/2304.11954).

<p align="center">
<img src="https://github.com/zhouchenlin2096/Spikingformer/blob/master/imgs/Spikingformer-Architecture.png">
</p>

## Reference
If you find this repo useful, please consider citing:
```
@article{zhou2023spikingformer,
  title={Spikingformer: Spike-driven Residual Learning for Transformer-based Spiking Neural Network},
  author={Zhou, Chenlin and Yu, Liutao and Zhou, Zhaokun and Zhang, Han and Ma, Zhengyu and Zhou, Huihui and Tian, Yonghong},
  journal={arXiv preprint arXiv:2304.11954},
  year={2023},
  url={https://arxiv.org/abs/2304.11954}
}
```

## Requirements
timm==0.6.12; cupy==11.4.0; torch==1.12.1; spikingjelly==0.0.0.0.12; pyyaml; 

## Evaluation

### Training  on CIFAR10
Setting hyper-parameters in cifar10.yml
```
cd cifar10
python train.py
```

### Testing on CIFAR10
Setting hyper-parameters in cifar10.yml
```
cd cifar10
python test.py
```

For help or issues using this git, please submit a GitHub issue.

For other communications related to this git, please contact zhouchl@pcl.ac.cn or zhouchenlin19@mails.ucas.ac.cn.
