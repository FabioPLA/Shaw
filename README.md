
中文 Python 笔记
版本：0.0.1
作者：李金
邮件：lijinwithyou@gmail.com
Github 加载 .ipynb 的速度较慢，建议在 Nbviewer 中查看该项目。

简介
大部分内容来自网络。
默认安装了 Python 2.7，以及相关的第三方包 ipython， numpy， scipy，pandas。
life is short. use python.
推荐使用 Anaconda，这个IDE集成了大部分常用的包。
笔记内容使用 ipython notebook 来展示。
安装好 Python 和相应的包之后，可以在命令行下输入：
$ ipython notebook
来进入 ipython notebook。

基本环境配置
安装 Anaconda 或者 Miniconda
更新环境
conda update conda
conda update anaconda

参考
Enthought Training on Demand
Computational Statistics in Python
Scipy.org
Deep Learning Tutorials
High Performance Scientific Computing
Scipy Lectures
Pandas.org

目录
可以在 Notebook 中打开 generate static files.ipynb，或者命令行中运行代码 generate_static_files.py 来生成静态的 HTML 文件。

01. Python 工具 
01.01 Python 简介
01.02 Ipython 解释器
01.03 Ipython notebook
01.04 使用 Anaconda
02. Python 基础 
02.01 Python 入门演示
02.02 Python 数据类型
02.03 数字
02.04 字符串
02.05 索引和分片
02.06 列表
02.07 可变和不可变类型
02.08 元组
02.09 列表与元组的速度比较
02.10 字典
02.11 集合
02.12 不可变集合
02.13 Python 赋值机制
02.14 判断语句
02.15 循环
02.16 列表推导式
02.17 函数
02.18 模块和包
02.19 异常
02.20 警告
02.21 文件读写
03. Numpy 
03.01 Numpy 简介
03.02 Matplotlib 基础
03.03 Numpy 数组及其索引
03.04 数组类型
03.05 数组方法
03.06 数组排序
03.07 数组形状
03.08 对角线
03.09 数组与字符串的转换
03.10 数组属性方法总结
03.11 生成数组的函数
03.12 矩阵
03.13 一般函数
03.14 向量化函数
03.15 二元运算
03.16 ufunc 对象
03.17 choose 函数实现条件筛选
03.18 数组广播机制
03.19 数组读写
03.20 结构化数组
03.21 记录数组
03.22 内存映射
03.23 从 Matlab 到 Numpy
04. Scipy 
04.01 SCIentific PYthon 简介
04.02 插值
04.03 概率统计方法
04.04 曲线拟合
04.05 最小化函数
04.06 积分
04.07 解微分方程
04.08 稀疏矩阵
04.09 线性代数
04.10 稀疏矩阵的线性代数
05. Python 进阶 
05.01 sys 模块简介
05.02 与操作系统进行交互：os 模块
05.03 CSV 文件和 csv 模块
05.04 正则表达式和 re 模块
05.05 datetime 模块
05.06 SQL 数据库
05.07 对象关系映射
05.08 函数进阶：参数传递，高阶函数，lambda 匿名函数，global 变量，递归
05.09 迭代器
05.10 生成器
05.11 with 语句和上下文管理器
05.12 修饰符
05.13 修饰符的使用
05.14 operator, functools, itertools, toolz, fn, funcy 模块
05.15 作用域
05.16 动态编译
06. Matplotlib 
06.01 Pyplot 教程
06.02 使用 style 来配置 pyplot 风格
06.03 处理文本（基础）
06.04 处理文本（数学表达式）
06.05 图像基础
06.06 注释
06.07 标签
06.08 figures, subplots, axes 和 ticks 对象
06.09 不要迷信默认设置
06.10 各种绘图实例
07. 使用其他语言进行扩展 
07.01 简介
07.02 Python 扩展模块
07.03 Cython：Cython 基础，将源代码转换成扩展模块
07.04 Cython：Cython 语法，调用其他C库
07.05 Cython：class 和 cdef class，使用 C++
07.06 Cython：Typed memoryviews
07.07 生成编译注释
07.08 ctypes
08. 面向对象编程 
08.01 简介
08.02 使用 OOP 对森林火灾建模
08.03 什么是对象？
08.04 定义 class
08.05 特殊方法
08.06 属性
08.07 森林火灾模拟
08.08 继承
08.09 super() 函数
08.10 重定义森林火灾模拟
08.11 接口
08.12 共有，私有和特殊方法和属性
08.13 多重继承
09. Theano 基础 
09.01 Theano 简介及其安装
09.02 Theano 基础
09.03 Theano 在 Windows 上的配置
09.04 Theano 符号图结构
09.05 Theano 配置和编译模式
09.06 Theano 条件语句
09.07 Theano 循环：scan（详解）
09.08 Theano 实例：线性回归
09.09 Theano 实例：Logistic 回归
09.10 Theano 实例：Softmax 回归
09.11 Theano 实例：人工神经网络
09.12 Theano 随机数流变量
09.13 Theano 实例：更复杂的网络
09.14 Theano 实例：卷积神经网络
09.15 Theano tensor 模块：基础
09.16 Theano tensor 模块：索引
09.17 Theano tensor 模块：操作符和逐元素操作
09.18 Theano tensor 模块：nnet 子模块
09.19 Theano tensor 模块：conv 子模块
10. 有趣的第三方模块 
10.01 使用 basemap 画地图
10.02 使用 cartopy 画地图
10.03 探索 NBA 数据
10.04 金庸的武侠世界
11. 有用的工具 
11.01 pprint 模块：打印 Python 对象
11.02 pickle, cPickle 模块：序列化 Python 对象
11.03 json 模块：处理 JSON 数据
11.04 glob 模块：文件模式匹配
11.05 shutil 模块：高级文件操作
11.06 gzip, zipfile, tarfile 模块：处理压缩文件
11.07 logging 模块：记录日志
11.08 string 模块：字符串处理
11.09 collections 模块：更多数据结构
11.10 requests 模块：HTTP for Human
12. Pandas 
12.01 十分钟上手 Pandas
12.02 一维数据结构：Series
12.03 二维数据结构：DataFrame
