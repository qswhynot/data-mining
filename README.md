#### 简介：

通过Kaggle比赛开源或者爬虫搜集到的数据集进行一些数据挖掘算法实战。

整个数据挖掘过程包括：数据采集，数据清理，数据可视化，数据分析，设计模型，模型评价。

python版本：3.6

文件夹结构包括models和data两部分

data是收集到的数据集

models是选择对应的数据挖掘算法模型

目前练习实战的算法包括：

1.通过训练kaggle上的Titanic数据集，用决策树算法预测乘客生存

2.朴素贝叶斯算法用于文本分类，数据集爬虫得到

3.通过训练kaggle上的乳腺癌数据集，用SVM算法分类预测

4.KNN对MINIST手写数字数据集进行识别分类（对比以上三种分类器）

5.K-Means算法对微信登录图片像素进行聚类，实现简单的图像分割

6.EM算法中高斯混合模型对王者荣耀英雄分类

7.爬取豆瓣网宁财神导演电影的演员表，Apriori算法挖掘选择演员的规则

8.信用卡违约分析，数据集来自kaggle

   选择实战过的多个算法分别训练，包括：

   SVM，决策树，随机森林，KNN，AdaBoost

   使用 GridSearchCV 工具对模型参数进行调优

