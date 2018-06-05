# FashionAI_Tianchi_2018
---
###### 天池大数据竞赛中的FashionAI全球挑战赛—服饰属性标签识别，记录一下在比赛过程中踩过的坑，比赛最终成绩为21名
---
### 环境
    *ubuntu16.04
    *python 3.6.2
    *keras 2.1.6
    *tensroflow 1.8.0
    *opencv-python 3.4
    *imgaug 0.2.5

### 使用
      *因为懒，代码写完就跑，没封装得多好
      *config.py配置了样本目录等信息
      *Multitask_train.py——训练脚本
      *Multitask_predict——预测脚本
      *dataset.py——数据预处理脚本
      *cal_std_mean.py——计算数据集的std与mean
      *inceptionv4.py——模型API
      