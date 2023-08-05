#  Unconditional Latent Diffusion Model

**目录**
- [Unconditional Latent Diffusion Model](#unconditional-latent-diffusion-model)
    - [简介](#简介)
    - [环境](#环境)
    - [数据集](#数据集)
    - [checkpoints](#checkpioits)
## 简介
此项目为2023年系科协暑培CV课程作业，训练一个 Unconditional Latent Diffusion Model。
此项目基于 [DiffusionFastForward](https://github.com/mikonvergence/DiffusionFastForward/tree/master) 开发，按照原作者指定的 LICENSE 使用，特此鸣谢。

## 环境
详见requirements.txt

## 数据集
[此项目采用 MNIST-M 数据集进行训练](https://www.kaggle.com/datasets/aquibiqbal/mnistm?resource=download)：在论文 [Domain-Adversarial Training of Neural Networks](https://www.ggle.com/datasets/aquibiqbal/mnistm?resource=download) 中首次使用的数据集，包含约 60000 张 28*28 的彩色手写数字图片。<p>
在[清华云盘](https://cloud.tsinghua.edu.cn/d/a747c0d1110d451099f9/)可以找到


## checkpioits
本项目训练得到epoch=26-step=200000.ckpt的checkpoint,已上传至[清华云盘](https://cloud.tsinghua.edu.cn/d/66853d4fc18241cb8e14/)
