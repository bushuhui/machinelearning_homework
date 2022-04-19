# Homework 08 - Deep Learning



## 1. GoogLeNet的实现

GoogLeNet 有很多后续的版本，阅读论文，并亲自实现各个版本的技术点，对比分析有什么不同
* v1：最早的版本；
* v2：加入 批标准化（BN）加快训练；
* v3：对 Inception 模块做了调整；
* v4：基于 ResNet 加入了 残差连接。



## 2. ResNet的实验

基于ResNet的实现，完成如下的实验：
*  尝试一下论文中提出的 Bottleneck 的结构；
* 尝试改变 Conv -> BN -> ReLU 的顺序为 BN -> ReLU -> Conv，看看精度会不会提高；
* 在Residual\_Block加入 $1 \times 1$ 卷积，并尝试结果的差别。



