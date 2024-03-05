# MyYOLOX
使用自己的训练数据集训练模型
#VOC数据集：以SAR-AIRcraft-1.0为例：数据集包含
  ① JPEGImages文件夹：数据集图片
  ② Annotations文件夹：与图片对应的xml文件
  ③ ImageSets/Main文件夹：将数据集分为训练集和验证集，因此产生的train.txt和val.txt。
#训练准备：修改训练配置参数：
###（1）修改exps/example/yolox_voc/yolox_voc_s.py
![image](https://github.com/2000YWQ/MyYOLOX/assets/162338249/0737b4b3-b55f-4bce-9f9f-c419176779ba)
![image](https://github.com/2000YWQ/MyYOLOX/assets/162338249/19bc5cf7-a63e-4be6-83a9-aa5a1d4ef44a)
此外max_labels，表示图片最多的目标数量也可视自己的数据集修改
###（2）修改exps/example/yolox_voc/yolox_voc_s.py
   修改yolox/data/datasets/voc.py中，VOCDection函数中的读取txt文件。
![image](https://github.com/2000YWQ/MyYOLOX/assets/162338249/855fb04e-ed42-42ee-b669-066ed111f97f)




     
