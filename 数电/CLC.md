# 组合逻辑电路

## 分析

写和观察，注意到

## 设计思想和重要例子

### 二进制转格雷码

1. 卡诺图
2. G<sub>i</sub> = B<sub>i</sub>⊕B<sub>i+1</sub>
栗子：

|B<sub>2</sub>|B<sub>1</sub>|B<sub>0</sub>|<font color=red>G<sub>1</sub>|<font color=red>G<sub>0</sub>|
|:---:|:---:|:---:|:---:|:---:|
|0|0|0|0|0|
|0|0|1|0|1|
|0|1|0|1|1|
|0|1|1|1|0|

<br>

###  加法器

获取本位和进位数据即可<br>

### 数值比较器

没啥好记的

### 编码器

每种信号对应一个编号，利用约束项

- 二进制编码器 

- 二-十进制编码器

- 优先编码器

### 译码器

对应三种编码器

特殊：
- 显示译码器
<s>注意阴阳、有效输入电平是0还是1</s>看手册就行
利用门电路控制发光二极管是否发光

### 数据选择器与数据分配器


#### 数据选择器

- 多输入（地址码），单输出。与编码器有相似处
- 利用输入信号选择使用的通路


#### 数据分配器

- <s>与译码器有相似处</s>就是译码器
- 通过选择控制端的输入选择需要的唯一输出端
- 可获取原码和反码


### 函数发生器

- 二进制译码器实现

利用最小项得到芯片输出与函数的关系

- 数据选择器实现

一. 利用数据输入端的取值控制输出与函数真值表相同<br>

二. 令数据输入端的取值为第n个变量或0或1，使输出与函数真值表相同（更复杂，但对芯片要求更低）

降维卡诺图

