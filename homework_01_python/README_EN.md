# Homework 1 - Python


## Python

### (1) String
Given a short article, please find the occurance number of each word. You can use the following sentences to test your program.

```
One is always on a strange road, watching strange scenery and listening to strange music. Then one day, you will find that the things you try hard to forget are already gone. 
```

**Deep Thinking:**
* After finished the first version, please consider the how to resolve the problem that there are two blank between two words, or `\t` between words. If the input paragraph has the situation, how to improve the robustness of the program?
* If `?` or `/` punctuation marks appears after words, how to resolve the case?


### (2) Combination
Given number 1, 2, 3, 4, how many three-digit numbers can be formed that are different from each other and have no duplicate numbers? What are they?


**Deep Thinking:**
* Please consider the algorithm complexity.


### (3) Judgement
企业发放的奖金根据利润提成。利润(I)： 
* 低于或等于 10 万元时，奖金可提 10%； 
* 高于 10 万元，低于 20 万元时，低于 10 万元的部分按 10%提成，高于 10 万元的部分，可提成 7.5%； 
* 20 万到 40 万之间时，高于 20 万元的部分，可提成 5%； 
* 40 万到 60 万之间时，高于 40 万元的部分，可提成 3%； 
* 60 万到 100 万之间时，高于 60 万元的部分，可提成 1.5%， 
* 高于 100 万元时， 超过 100 万元的部分按 1%提成， 
从键盘输入当月利润 I，求应发放奖金总数？

**深入思考：**
* 除了用`if`手写，能否用其他方式（例如用list，然后自动实现所有的判断）来实现？


### （4）循环
输出9x9的乘法口诀表

**深入思考：**
* 如何对齐，看着更清楚？

### （5）使用while循环实现输出2-3+4-5+6.....+100的和

**深入思考：**
* 除了直接的方法，能否用一句话写完？


### （6）算法
给一个数字列表，将其按照由大到小的顺序排列

例如
```
1, 10, 4, 2, 9, 2, 34, 5, 9, 8, 5, 0
```

### (7)  算法2
编写一个高效的算法来搜索 m x n 矩阵 matrix 中的一个目标值 target。该矩阵具有以下特性：
* 每行的元素从左到右升序排列。
* 每列的元素从上到下升序排列。

示例:
现有矩阵 matrix 如下：
```
[
[1, 4, 7, 11, 15],
[2, 5, 8, 12, 19],
[3, 6, 9, 16, 22],
[10, 13, 14, 17, 24],
[18, 21, 23, 26, 30]
]
```

* 给定 target = 5，返回 true。
* 给定 target = 20，返回 false。


### （8）应用1
做为 Apple Store App 独立开发者，你要搞限时促销，为你的应用生成激活码（或者优惠券），使用 Python 如何生成 200 个激活码（或者优惠券）？

需要考虑什么是激活码？有什么特性？例如`KR603guyVvR`是一个激活码

### （9）应用2
需要把某个目录下面所有的某种类型的文件找到。
例如把`c:`下面所有的`.dll`文件找到。*需要注意的是，需要递归到每一个目录去查找。*

### （10）应用3
你有个目录，里面是程序（假如是C或者是Python），统计一下你写过多少行代码。包括空行和注释，但是要分别（例如C程序多少行，Python程序多少行，等等）列出来。



## References
上面的程序只是简单的练练手，仅仅通过上面的程序练习还是不够的，大家需要更多的程序练习才能把Python学好，下面是一些参考的练习题，大家可以挑选一些去做做。

* [Python 练习册，每天一个小程序](https://github.com/Yixiaohan/show-me-the-code)
* [70个python练手项目](practice_projects.md)
* [PythonExercises](https://github.com/greyli/PythonExercises)
* [Python Challenge](http://www.pythonchallenge.com)
* [Python 100例](http://www.runoob.com/python/python-100-examples.html)
* [Python练习题](https://blog.csdn.net/qq_28356833/article/details/54963342)
* [python实现 66道算法题](https://blog.csdn.net/u012193416/article/details/79253398)

