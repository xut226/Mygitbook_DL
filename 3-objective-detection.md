## 1.传统目标检测

传统的目标检测与识别方法主要可以表示为：目标特征提取-&gt;目标识别-&gt;目标定位。

这里所用到的特征都是人为设计的，

SIFT \(尺度不变特征变换匹配算法Scale Invariant Feature Transform\),

HOG\(方向梯度直方图特征Histogram of Oriented Gradient\),

SURF\( 加速稳健特征Speeded Up Robust Features\)

通过这些特征对目标进行识别，然后再结合相应的策略对目标进行定位。

1.1 HOG + SVM

## 2.基于深度学习的目标检测

2.1基于区域的（two-stage）：

RCNN，SPPnet，fast-R-CNN，faster-R-CNN

2.2基于回归的（one-stage）：

YOLO，SDD，Mask-RCNN

2.3基于搜索的：

基于视觉注意的AttentionNet，基于强化学习的算法



### 参考

https://blog.csdn.net/amusi1994/article/details/81042923

