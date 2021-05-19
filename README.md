# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2

# For students from SJTU
Please read [HEAR](EE369.md).

# 作业提交
Name： 曹嘉航

ID： 519030910347

# Q1（逻辑回归）
Training accuracy: 97.33%

Testing accuracy: 88.80%

注：模型未收敛

# Q2（朴素贝叶斯）
Training accuracy: 81.55%

Testing accuracy: 82.20%

# Q3（线性支持向量机）
Training accuracy: 97.85%

Testing accuracy: 86.80%

注：模型未收敛
# Q4（线性支持向量机，调整超参数）
Training accuracy: 95.05%

Testing accuracy: 89.40%

注：更改的参数：

loss='hinge'

C=0.5

intercept_scaling=0.2

# Q5（神经网络，选用Pytorch实现）

Epoch 1, Loss: 0.0088, Training accuracy: 94.44%, Testing accuracy: 94.41%

Epoch 2, Loss: 0.0010, Training accuracy: 96.95%, Testing accuracy: 96.88%

Epoch 3, Loss: 0.0006, Training accuracy: 97.53%, Testing accuracy: 97.35%

Epoch 4, Loss: 0.0005, Training accuracy: 98.51%, Testing accuracy: 98.29%

Epoch 5, Loss: 0.0004, Training accuracy: 98.67%, Testing accuracy: 98.49%

Epoch 6, Loss: 0.0003, Training accuracy: 99.05%, Testing accuracy: 98.57%

Epoch 7, Loss: 0.0003, Training accuracy: 99.05%, Testing accuracy: 98.62%

Epoch 8, Loss: 0.0003, Training accuracy: 99.20%, Testing accuracy: 98.87%

Epoch 9, Loss: 0.0002, Training accuracy: 99.31%, Testing accuracy: 98.69%

Epoch 10, Loss: 0.0002, Training accuracy: 99.40%, Testing accuracy: 98.82%

使用经典的LeNet结构进行分类任务

损失函数：对数交叉熵

优化器：随机梯度下降，一阶动量权重为0.1

初始化方式：xavier uniform初始化

注：主要超参数：

学习率learning rate=0.9
