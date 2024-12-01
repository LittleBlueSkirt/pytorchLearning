# pytorchLearning
get start pytorch
[Pytorch-UNet项目地址](https://github.com/milesial/Pytorch-UNet))
### 运行前准备
1. 安装anaconda 和pychar 运行环境
2. 配置conda 环境 pytorchEnv39
```conda
conda create -n pytorchEnv39 python=3.9
# 进入环境
conda activate pytorchEnv39
```
3. 安装pytorch with cuda 

```conda
# CUDA 11.6
conda install pytorch==1.13.0 torchvision==0.14.0 torchaudio==0.13.0 pytorch-cuda=11.6 -c pytorch -c nvidia
```

4. 在新环境中安装jupyter
```
# python3.9以下的版本
conda install nb_conda
#python3.9的版本
conda install nb_conda_kernels
``` 
