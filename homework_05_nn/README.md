# Neural Networks

自己编程实现两层或多层全连接神经网络，可以使用`moons` 或者`circles`数据集来测试、验证算法。



dataset_moons:

![dataset_moons](images/dataset_moon.png)



dataset_circles:

![dataset_circles](images/dataset_circle.png)

加载数据的方式是：
```python
# moon dataset
% matplotlib inline
import numpy as np
from sklearn import datasets
import matplotlib.pyplot as plt

# generate sample data
np.random.seed(0)
X, y = datasets.make_moons(200, noise=0.20)

# plot data
plt.scatter(X[:, 0], X[:, 1], c=y, cmap=plt.cm.Spectral)
plt.show()
```

dataset_circles的数据文件是`dataset_circles.csv`



要求：

1. 自己编程实现多层全连接神经网络的多分类。
2. 先用函数的方式实现网络的正向计算和反向误差传播，权值更新。
3. 构思并实现基于类的神经网络程序。
4. 学习`softmax`和`cross entropy`的方法，并实现类别所属概率的输出。
5. 对比自己实现与sklearn的方法的精度。
6. 如何将分类错误的样本可视化出来？