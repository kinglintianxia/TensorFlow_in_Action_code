# TensorFlow in Action code 

## Anaconda3 install
```shell
$ conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
$ conda config --set show_channel_urls yes

### 安装python kernel for Tensroflow
```shell
ipython kernelspec install-self --user
```
## start tensorflow
```shell
$ source activate tensorflow
$ python
$ import tensorflow as tf
$ tf.__version__
```
## [CSDN blog](https://blog.csdn.net/zj360202/article/details/78590285)

* 3.2_HelloWorld.py
> TensorFlow 识别MINIST手写数字

* 4.2_AutoEncoer.py
> TensorFlow 实现自编码器

* 4.4_MLP.py
> TensorFlow 实现多层感知机

* 5.2_CNN_MNIST.py
> TensorFlow 实现简单卷积网络

* 5.3_CNN_CIFAR10.py
> TensorFlow 实现进阶卷积网络

* 6.1_AlexNet.py
> TensorFlow 实现AlexNet

* 6.2_VGG.py
> TensorFlow 实现VGGNet

* 6.3_InceptionNet.py
> TensorFlow 实现GoogLeNet

* 6.4_ResNet.py
> TensorFlow 实现ResNet
