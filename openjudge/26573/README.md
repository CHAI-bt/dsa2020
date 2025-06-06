# 25TF5:康托集的图像表示

------

总时间限制: 1000ms 内存限制: 65536kB

### 描述

在数学上具有重要意义的康托集(cantor set)是用如下方法构造的。考虑区间[0,1]，我们第一步要做的是，将区间三等分，然后删去中间的部分(1/3, 2/3)。在后面的每一步中，取出所有剩下的小区间，将每一个小区间都三等分后删去中间的部分，这样操作无穷次，最后剩下的点即为康托集。

在本题中，对于输入n，我们假设操作n步之后剩下的每个小区间为一个单位长度。请你用线段图表示出这些剩下的小区间。每个小区间使用一个字符‘*’表示，而[0,1]区间的其余位置按照其单位长度用相应个数的‘-’表示。

例如：对于输入n=3，最后剩下的小区间为1个单位长度，则整个[0,1]区间的单位长度为27，各步删去的区间如下表示：

第一步删去中间一段（一个区间，9个单位长度）：

---------*********---------

第二步删去左右区间的中间一段（两个区间，分别有3个单位长度）：

---***---------------***---

最后一步删去的小区间是（四个区间，分别有1个单位长度）：

-*-----*-----------*-----*-

剩下的没有删去的小区间是（8个区间，分别有一个单位长度）：

*-*---*-*---------*-*---*-*

注意：你的程序需要输出的只是上面示例中的最后一行，即操作n步之后剩余的小区间

### 输入

3

### 输出


*-*---*-*---------*-*---*-*

### 样例输入

```
3
```

### 样例输出

```
*-*---*-*---------*-*---*-*s
```
### 来源
lxp

