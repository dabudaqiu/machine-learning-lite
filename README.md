# machine-learning-lite
A quick and light check list for machine learning learning.

2018年春节假期，对2017年9月以来学习的Machine Learning知识点进行简要的总结，随手记录下来；
机器学习部分主要集中在第7章，参考学习资料包含周志华《机器学习》，李航《统计学习方法》，《PRML》，《Deep Learning》，Tensorflow Docs，
Python Docs以一些技术博客；
其他章节来源于仓库 https://github.com/taizilongxu/interview_python#1-python
对Python部分进行了整理和充实；
C/C++，Algorithm，OS，网络和数据库章节尚待完成；
本书初稿使用MS-word2010编写，公式使用内嵌工具编辑；
Python部分代码均调试通过：
  OS：Windows7
  python：3.5.2
  numpy: 1.13.1
  tensorflow: 1.4.0
  
联系我：hsingmin.lee@yahoo.com

目录
1.	C/C++	5
  1.1	const关键字	5
  1.2函数传值与传引用	10
  1.3 字符串转整型问题	11
  1.4 操作符重载	11
2.	Python	12
  2.1	可变类型与非可变类型	12
  2.2	静态方法，实例方法与类方法	12
  2.3	类变量与实例变量	13
  2.4	Python自省特性	15
  2.5	列表推导式与字典推导式	15
  2.6	深拷贝与浅拷贝	16
  2.7	类方法__new__( )与__init__( )	18
  2.8	字符串格式化:%与.format	18
  2.9	Python的*args和**kwargs	19
  2.10	常见的几种设计模式	20
  2.11	Python变量的作用域	21
  2.12	GIL线程全局锁及协程	22
  2.13	闭包	22
  2.14	Lambda与函数式表达式	23
  2.15	编码与解码(incode/decode)	23
  2.16	迭代器与生成器	24
  2.17	装饰器	25
  2.18	Python中的重载	26
  2.19	Python新式类与旧式类	27
  2.20	邮箱地址正则表达式	27
  2.21	Python内置类型list/dictionary/tuple/string	32
  2.22	Python中的is	33
  2.23	read/readline和readlines	34
  2.24	垃圾回收	34
3.	Algorithm	34
  3.1	时间复杂度计算	34
  3.2	二叉树	35
  3.2.1 二叉树的数据结构	35
  3.2.2 二叉树的生成	36
  3.2.3 二叉树的遍历算法	36
  3.3	最大堆	41
  3.4	红黑树	41
  3.5	B树	41
  3.6	线性结构-栈与队列	41
  3.7	线性结构-链表	41
  3.8	寻找链表倒数第k个节点	41
  3.9	快速排序	42
  3.10	堆排序	42
  3.11	无序数字列表寻找所有间隔为d的组合	42
  3.12	列表[a1, a2, a3, …, an]求其所有组合	42
  3.13	一行python代码实现1+2+3+…+10**8	43
  3.14	长度未知的单向链表求其是否有环	43
  3.15	单向链表应用快速排序	43
  3.16	长度为n的无序数字元素列表求其中位数	43
  3.17	遍历一个内部未知的文件夹	43
  3.18	台阶问题/斐波那契	43
  3.19	变态台阶问题	43
  3.20	矩形覆盖问题	44
4.	OS	45
  4.1	多线程与多进程的区别	45
  4.2	协程	45
  4.3	进程间通信方式	45
  4.4	虚拟存储系统中缺页计算	45
  4.5	并发进程不会引起死锁的资源数量计算	45
  4.6	常用的Linux/git命令和作用	45
  4.7	查看当前进程的命令	45
  4.8	45
5.	网络	46
  5.1	TCP/IP协议	46
  5.2	OSI五层协议	46
  5.3	Socket长连接	46
  5.4	Select与epoll	46
  5.5	TCP与UDP协议的区别	46
  5.6	TIME_WAIT过多的原因	46
  5.7	http一次连接的全过程描述	46
  5.8	http连接方式——get与post的区别	46
  5.9	restful	47
  5.10	http请求的状态码 200/403/404/504	47
6.	数据库	48
  6.1	MySQL锁的种类	48
  6.2	死锁的产生	48
  6.3	MySQL的char/varchar/text的区别	48
  6.4	Join的种类与区别	48
  6.5	A LEFT JOIN B的查询结果中，B缺少的部分如何显示	48
  6.6	索引类型的种类	48
  6.7	BTree索引与hash索引的区别	48
  6.8	如何对查询命令进行优化	48
  6.9	NoSQL与关系型数据库的区别	48
  6.10	Redis常用的存储类型	49
7.	机器学习	50
  7.1	模型评估方法	50
    7.1.1	数据集划分	50
    7.1.2	模型的性能度量	50
    7.1.3	偏差-误差分解	50
  7.2	LR与极大似然估计	51
  7.3	LDA	51
  7.4	类别不平衡问题	52
  7.5	判别/生成模型与先验/后验概率	52
  7.6	朴素贝叶斯分类器	53
  7.7	常用的损失函数	53
  7.8	决策树	54
  7.9	连续值与缺失值处理	55
  7.10	BP算法	55
  7.11	梯度下降法	57
  7.12	IIS与牛顿法/拟牛顿法	57
  7.13	局部最小与全局最小	58
  7.14	支持向量机与拉格朗日乘子法	59
  7.15	正则化	62
    7.15.1	LASSO与Ridge	62
    7.15.2	L1正则化求解	63
  7.16	EM算法	64
  7.17	Boosting与Bagging	64
    7.17.1	Boosting方法	64
    7.17.2	Bagging方法	68
  7.18	监督学习与无监督学习	68
  7.19	聚类	69
  7.20	特征选择与稀疏学习	70
    7.20.1	维度灾难	70
    7.20.2	特征选择	70
  7.21	PCA	71
    7.21.1	特征值分解	71
    7.21.2	奇异值分解	72
    7.21.3	主成分分析	73
  7.22	Apriori算法与FP-Growth	74
    7.22.1	关联规则	74
    7.22.2	Apriori算法	75
  7.23	词频-逆文本词频	75
  7.24	概率图模型	75
    7.24.1	隐马尔科夫模型	76
    7.24.2	马尔科夫随机场	78
    7.24.3	条件随机场	79
    7.24.4	隐狄利克雷分配模型	83
  7.25	从伯努利到狄利克雷分布	85
    7.25.1	伯努利分布	85
    7.25.2	二项分布	85
    7.25.3	Beta分布	86
    7.25.4	多项式分布	86
    7.25.5	Dirichlet分布	87
