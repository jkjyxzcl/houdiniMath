# 产生的需求
在不同的情况下我们使用不同的坐标系能更方便的实现效果。
比如在天文学中的日心说，地心说。就可以把他们理解为不同的坐标系。
在合适的情况下选在最优的情况就可以了。
# 常用坐标系
## 1.世界坐标系
也就是我们视图的坐标
## 2.物体坐标系
模型自己的坐标系（物体自身坐标）
## 3.相机坐标系
就是相机的可视区域（常见于我们的材质模块）
![图片](https://images-cdn.shimo.im/HIcX4wy1B5MpqbuP/image.png!thumbnail)
# 坐标系转换
vex中的transform节点可以实现这个功能
![图片](https://images-cdn.shimo.im/qxccRjosvZUyFpY7/image.png!thumbnail)

