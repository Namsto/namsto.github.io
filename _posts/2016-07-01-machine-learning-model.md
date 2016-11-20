---
layout: post
title: How to Build Models
author: 黄承威
date: 2016-09-08 22:49:35 +0800
permalink: /:title.html
categories: MachineLearning
---


### 常用的库  
---

[numpy](www.numpy.org)  
[pandas](http://pandas.pydata.org/)  
[matplotlib](http://matplotlib.org/)  
[sklearn](http://scikit-learn.org/stable/)  


### [机器学习项目工作流程](/machine-learning-workflow.html)  
---

#### Step 1 抽象成数学问题  
* [一些常用的机器学习模型](/images/ml/Models.png)  
介绍了一些机器学习中常用的模型，如SVM、Decision Tree、Random Forest、K Nearest Nerghbors等。
*[How to Define Your Machine Learning Problem](http://machinelearningmastery.com/how-to-define-your-machine-learning-problem/)
* [模型的评估及模型的选择 -- Part 1](http://sebastianraschka.com/blog/2016/model-evaluation-selection-part1.html)
* [模型的评估及模型的选择 -- Part 2](http://sebastianraschka.com/blog/2016/model-evaluation-selection-part2.html)
* [模型的评估及模型的选择 -- Part 3](http://sebastianraschka.com/blog/2016/model-evaluation-selection-part3.html)
* [支持向量机（SVM）介绍](https://www.zybuluo.com/Duanxx/note/433281)

#### Step 2 获取数据  

#### Step 3 特征工程  
* [Overall Introduction of Feature Engineering](/machine-learning-feature-engineering.html)
* [特征选择与特征学习](http://blog.jasonding.top/2015/11/12/Feature%20Engineering/%E3%80%90%E7%89%B9%E5%BE%81%E5%B7%A5%E7%A8%8B%E3%80%91%E7%89%B9%E5%BE%81%E9%80%89%E6%8B%A9%E4%B8%8E%E7%89%B9%E5%BE%81%E5%AD%A6%E4%B9%A0/)
* [如何做特征选择](http://chuansong.me/n/932590347121)  
Relief算法是一种特征权重算法(Feature weighting algorithms), 根据各个特征和类别的相关性赋予特征不同的权重，权重小于某个阈值的特征将被移除。  
* [关于特征工程](http://www.voidcn.com/blog/a353833082/article/p-5043230.html)
* [How to Prepare Data For Machine Learning](http://machinelearningmastery.com/how-to-prepare-data-for-machine-learning/)
* [How to Engineer Features and How to Get Good at It](http://machinelearningmastery.com/discover-feature-engineering-how-to-engineer-features-and-how-to-get-good-at-it/)
* [An Introduction to Feature Selection](http://machinelearningmastery.com/an-introduction-to-feature-selection/)
* [主成分分析（PCA）原理详解](http://blog.csdn.net/zhongkelee/article/details/44064401)

#### Step 4 训练模型与调优  
* [什么是超参数](https://www.quora.com/What-are-hyperparameters-in-machine-learning)
* [Cross Validation Python实现](http://www.csuldw.com/2015/07/28/2015-07-28%20crossvalidation/)


#### Step 5 模型诊断  



#### Step 6 模型融合  
* [Model Ensemble](/images/ml/ModelEnsemble.png)
* [集成学习方法](http://www.cnblogs.com/wxquare/p/5440664.html)
* [快速理解bootstrap、bagging、boosting](http://www.xiutx.cn/archives/24)
* [决策树模型组合之随机森林与GBDT](http://www.cnblogs.com/LeftNotEasy/archive/2011/03/07/random-forest-and-gbdt.html)
*[为什么说bagging是减少variance, 而boosting是减少bias?](https://www.zhihu.com/question/26760839)

#### Step 7 上线运行  


### 扩展阅读    
---
* [使用sklearn进行数据挖掘](http://www.cnblogs.com/jasonfreak/p/5448462.html)
* [Machine Learning Tutorial by Jason](http://machinelearningmastery.com/start-here/)
* [机器学习(Machine Learning)&深度学习(Deep Learning)资料(Chapter 1)](https://github.com/ty4z2008/Qix/blob/master/dl.md)  
共500篇paper，涉及范围非常广。
* [机器学习(Machine Learning)&深度学习(Deep Learning)资料(Chapter 2)](https://github.com/ty4z2008/Qix/blob/master/dl2.md)  
同上。
* [Deep learning Reading List](http://jmozah.github.io/links/)
* [Deep Learning Tutorial](http://deeplearning.stanford.edu/tutorial/)  
Stanford University 深度学习教程。
* [28款GitHub最流行的开源机器学习项目](https://yq.aliyun.com/articles/30794)

### 视频教程
---
* [机器学习入门 - 优达学城](https://cn.udacity.com/course/intro-to-machine-learning--ud120)  
你将从这门课程中学到使用机器学习进行数据调查时的端到端过程，并将运用所学知识处理真实的数据集。
* [Machine Learning](https://www.coursera.org/learn/machine-learning)  
经典的机器学习教程。由Stanford University的教授、现百度研究院首席科学家Andrew Ng主讲。
* [机器学习 - 优达学城](https://cn.udacity.com/course/machine-learning--ud262)  
在这门课程中，你将学习如何运用监督学习、非监督学习和强化学习技术，来解决一系列的数据科学问题。



#### Reference:
---
[http://www.cnblogs.com/jasonfreak/p/5448385.html](http://www.cnblogs.com/jasonfreak/p/5448385.html)  
[http://www.cnblogs.com/jasonfreak/p/5448462.html](http://www.cnblogs.com/jasonfreak/p/5448462.html)  
