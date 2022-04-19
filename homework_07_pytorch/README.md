# Homework 07 - PyTorch



## 1. Tensor 操作


查阅PyTorch文档了解 Tensor 更多的 API函数，实现下面的要求：

创建一个数据类型为float32、大小$4 \times 4$ 且元素全为 1 的矩阵，将矩阵正中间 $2 \times 2$ 的矩阵，全部修改成 2。

参考输出为：

```
1, 1, 1, 1
1, 2, 2, 1
1, 2, 2, 1
1, 1, 1, 1
```



## 2. Tensor求导

尝试构建一个函数 $y = x^2$ ，然后求 $x=2$ 时的导数。




## 3. 矩阵变量求导


定义
$$
x=\left[ \begin{matrix} x_0\\ x_1 \end{matrix} \right]=\left[ \begin{matrix}2\\ 3 \end{matrix} \right]
$$

$$
k=(k_0,k_1)=(x^2_0+3x_1,2x_0+x^2_1)
$$

希望通过PyTorch求
$$
\left[ \begin{matrix}
\frac{\partial k_0}{\partial x_0}&
\frac{\partial k_0}{\partial x_1}\\ 
\frac{\partial k_1}{\partial x_0}&
\frac{\partial k_1}{\partial x_1}\\ 
\end{matrix} \right]
$$



## 4. 改变神经网络结构

参照前面的神经网络实现，改变网络的隐藏层神经元数目，试试定义一个 5 层甚至更深的模型，增加训练次数，改变学习率，看看结果会怎么样。



## 5. 模型参数初始化尝试

一种非常流行的初始化方式叫 Xavier，方法来源于 2010 年的一篇论文《Understanding the difficulty of training deep feed forward neural networks》，其通过数学的推导，证明了这种初始化方式可以使得每一层的输出方差是尽可能相等的，自己编程实现这个参数初始化方法。

初始化的公式为:
$$
w\sim Uniform[-\frac{\sqrt{6}}{\sqrt{n_j+n_{j+1}}},\frac{\sqrt{6}}{\sqrt{n_j+n_{j+1}}}]
$$
其中 $n_j$和$n_{j+1}$表示该层的输入和输出数目。

