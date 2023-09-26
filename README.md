
# Jittor 计图挑战热身赛 


[![主要结果1](https://i.postimg.cc/d1S8fw6W/result.png)](https://postimg.cc/LYLYYdrf)
[![主要结果2](https://i.postimg.cc/mgyVwczR/result.png)](https://postimg.cc/zy3nDGFP)


## 简介
本赛道将在数字图片数据集 MNIST 上训练 Conditional GAN（Conditional generative adversarial nets）模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。

## 赛题内容
本赛题将会提供数字图片数据集MNIST，参赛选手需要训练一个将随机噪声和类别标签映射为数字图片的Conditiona1GAN模型，并生成下方给定用户随机ID对应的数字图片结果。

## 安装 

项目在NVIDIA A800 80G 上训练，训练时间花费15分钟。

#### 运行环境
- ubuntu 20.04
- python >= 3.8
- jittor >= 1.3.0
- CUDA 11.4
#### 安装依赖
pip install jittor

## 训练参数
batch_size = 64
lr = 0.0002
## 使用方法
填写自己的number,到CGAN.py里的number变量值
python CGAN.py
## 致谢
基于计图官方示例代码填充注释为TODO的部分完成
