# 文献的阅读笔记上传规则
### Readme为索引文档,记录了论文阅读者阅读了哪篇论文,这篇论文标题是什么，以及这篇论文的简要介绍
### 文章后有(I)表示这篇文章(这个类目)非常重要,有(UI)表示这篇文章(这个类目)太水了
### 文章的解释前加1个'>'缩进
## 样例

### 0.AABBCC(I) (冯浩哲)
#### >这篇文章讲了我们要在文章名后打一个空格加括号谁看了

### 0.AABB这是一个总结 (冯浩哲)
#### 0.1 aabbcc(UI)
##### >我很有感想
#### 0.2 aaccdd(I)
##### >这篇文章很重要

# 正文部分

### 1.Deep 3D Convolutional Encoder Networks With Shortcuts (张天平)
### 2.几篇用CNN做的分类论文 创新点总结 (张天平)
### 3.候选检测所用到的几篇论文的总结 (冯浩哲)
#### 3.1 A large-scale evaluation of automatic pulmonary nodule detection in chest CT using local image features and k-nearest-neighbour classification 
##### >使用传统的机器学习手法去检测结节,主要使用了局部图像特征和k-nearest聚类。对于结节的预检测使用了ShapeIndex以及Curveness的方法进行聚类.
#### 3.2 Automatic detection of subsolid pulmonary nodules in thoracic computed tomography images
##### >对subsolid结节进行图像检测
#### 3.3 Automatic detection of large pulmonary solid nodules in thoracic CT images 
##### >这个比较简单，就是用CAD方法去检测大型的结节。不过它对于肺分割的方法使用了传统的边缘特征检测,就是说分割出的肺是有白边的。
### 4.Fast Convolutional Neural Network Training Using Selective Data Sampling: Application to Hemorrhage Detection in Color Fundus Images(I) (冯浩哲)
#### >提出了一个样本选取的手法，以及一个完整的鉴别眼球出血的网络
### 5.AggNet: Deep Learning From Crowds for Mitosis Detection in Breast Cancer Histology Images (冯浩哲)
#### >讲了我们如何使用基于众包的数据来作为训练样本(如何巧妙地获取数据)
### 6.Pulmonary Nodule Detection in CT Images: False Positive Reduction Using Multi-View Convolutional Networks(I) (冯浩哲)
#### >一个完善的方法+一个完善的CT图像识别流程,对数据预先做的候选检测部分和如何选取视图方面有详细的介绍
