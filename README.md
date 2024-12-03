# pytorchLearning

get start pytorch

[Pytorch-UNet项目地址](https://github.com/milesial/Pytorch-UNet)

**由于该项目的数据集是kaggle上面的，你需要先注册一个kaggle账户，并申请一个api key**

### 运行前准备
1. 安装anaconda 和pycharm 运行环境
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

5.[电脑上安装git](https://github.com/LittleBlueSkirt/how-to-install-git)
### Windows

1. **下载Git**：
   - 访问Git的官方网站：[https://git-scm.com/](https://git-scm.com/)
   - 点击“Download for Windows”按钮。

2. **安装Git**：
   - 运行下载的安装程序。
   - 按照安装向导的步骤进行安装。在安装过程中，你可以选择默认的安装选项，或者根据需要自定义安装选项。
   - 在安装过程中，确保勾选“Add Git to PATH”（将Git添加到PATH环境变量）的选项，这样你就可以在命令行中直接使用Git命令。

3. **配置Git**：
   - 安装完成后，你可以打开命令提示符（CMD）或PowerShell，输入`git --version`来检查Git是否安装成功。
   - 配置你的Git用户名和邮箱，这将用于记录你的提交信息：
     ```
     git config --global user.name "Your Name"
     git config --global user.email "youremail@example.com"
     ```
### 正式开始




