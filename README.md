# 我的一些想法：关于皮肤颜色的分类

1. 图像分割得到人脸区域
2. 提取人脸皮肤部分, 即扣除嘴和眼睛区域
3. 采用机器学习聚类算法对其进行具体分类学习


keras save issue: https://github.com/keras-team/keras/issues/9342


调研:  1. 颜色分类器依据

			2. 不同分类器比如svm rf 人工神经网络比较
   			3. 评估方法 曲线、指标、5-折交叉实验