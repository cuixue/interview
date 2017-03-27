
## interview
1.正则化的方法,样本不平衡怎么处理,

2.拟牛顿法,svrg,智力题,

3.防止过拟合的方法,激活函数,数据预处理降维的方法,参数初始化的方法,pooling的作用



## 编程
一面的算法题 是 ，有序数组，找到所有 a + b = c 的对

二面的编程题 是 打印出二叉树每一层最后一个节点的值

编写确定两棵二叉树是否相等最长递增子序列

## 经验
每个项目都好好想想。。。你想传达给  面试官什么。。。要是面试官没问，你就找机会自己说出来.我阿里一面的经验就是，，，如果面试官问你的东西，你很懂。那就要回答到自己满意，不要后悔。尽量把你懂得都传达给面试官
二面，就是 竟然还有智力题。。。  面试官的问题，你不会没关系不慌。。。不急着给面试官答案，的。 面试官不是要看你会不会，而是看你分析问题的能力。。。

## 网站
如何准备机器学习工程师的面试 ？ https://www.zhihu.com/question/23259302

怎么准备年后的软件 / 互联网公司实习？ https://www.zhihu.com/question/28328974

Linear SVM 和 LR 有什么异同？https://www.zhihu.com/question/26768865

l1 相比于 l2 为什么容易获得稀疏解？https://www.zhihu.com/question/37096933

请问学习 ensemble learning 要从哪里开始呢？ https://www.zhihu.com/question/29036379

谈谈你对大规模机器学习这个领域的理解和认识? https://www.zhihu.com/question/37057945

谈谈你对"GPU/CPU集群下做到Data/Model Parallelism的区别"的理解？https://www.zhihu.com/question/31999064

机器学习算法中GBDT和XGBOOST的区别有哪些？ https://www.zhihu.com/question/41354392

为什么说bagging是减少variance，而boosting是减少bias? https://www.zhihu.com/question/26760839

GBDT预测时每一棵树是否能并行?https://www.zhihu.com/question/41272145

机器学习有很多关于核函数的说法，核函数的定义和作用是什么？https://www.zhihu.com/question/24627666

如果你是面试官，你怎么去判断一个面试者的深度学习水平？https://www.zhihu.com/question/41233373

深度学习相关的职位面试时一般会问什么？会问一些传统的机器学习算法吗？ https://www.zhihu.com/question/54308150

## 参考
正则化的方法：early stopping、数据集扩增（Data augmentation）、正则化（Regularization）包括L1、L2（L2 regularization也叫weight decay），dropout,Bagging and Other Ensemble Methods.

pooling的作用:位移的不变性,减小下一层输入大小，减小计算量和参数个数,获得定长输出。（文本分类的时候输入是不定长的，可以通过池化获得定长输出）

参数初始化的方法:参数的初始化很重要，对于函数的优化. 均匀,正态和正交初始化,两种初始化，初始化的大小很重要.从优化的角度想让参数大,这样有信息传播;从正则的角度想让参数小,

激活函数:sigmoid,tanh,relu,leaky relu(给负半轴一个权重),参数化relu(负半轴的斜率是学出来的而不是预先设定好的),随机化Relu(负半轴被随机初始化一个值)

数据预处理(降维的方法): 中心化和归一化(减去均值除以方差,这种只适用于不同维度的特征需要不同的缩放), PCA(降维), 特征清洗(把空间中的数据除以每个维度的特征值,用以缩放,这种方法会极大的放大数据中的噪声)
