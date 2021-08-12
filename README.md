# Car-FasterRcnn

由于这一部分不是我写的，是我另一位队友写的，所以我只是做一些简单的介绍。



# 项目结构

```
flask_ocr/
├── checkpoints
├── detect
├── recognize
├── app.py
├── ocr.py
└── test.html
```



- checkpoints ：存放训练的网络模型
- detect ： 训练路径以及相关配置
- recognize：训练识别
- app.py：flask框架与前端交互的api
- ocr.py：识别接口
- test.html ： 测试网页



# Faster-RCNN网络简介


![Faster RCNN](https://user-images.githubusercontent.com/57799587/129231534-7e0976c6-219d-4896-a2cc-90857ecc80b0.png)



我自己不是这方面的，也不懂。具体百度把！







# 简单介绍

由于环境因素，我们先对照片进行二值化处理，再进行识别，有效提高了识别的正确率。



<img src="https://img-blog.csdnimg.cn/20210602004440282.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTMwNDUwMw==,size_16,color_FFFFFF,t_70" width="47%">

<img src="https://img-blog.csdnimg.cn/20210602004543510.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTMwNDUwMw==,size_16,color_FFFFFF,t_70" width="47%">



![在这里插入图片描述](https://img-blog.csdnimg.cn/20210602004622894.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTMwNDUwMw==,size_16,color_FFFFFF,t_70)







