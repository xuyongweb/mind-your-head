# MindYourHead
使用 ThreeJs 框架写的一款 3D 射击游戏

## 游戏介绍

首先选取一张包含人脸的图片，人脸尽可能以便于裁剪。裁剪框有三条提示线，分别对应人的双眼和嘴。通过调节图片的大小，使双眼和嘴尽量重合。裁剪的图片会被用做怪物的脸。如下所示：

![](images/demo/crop.png)

![](images/demo/game.png)

<br />

## 操作
游戏可以支持电脑和移动设备，对于电脑通过按键来控制移动和攻击，对于移动设备可以使用重力感应或者网页图标来移动。

### 电脑
* 上下左右 方向键 - 移动
* `空格` - 停止移动
* `S` - 发射子弹
* `W` - 发射冷冻弹（使怪物停止移动） 
* `A` - 发送炮弹（发送之后，需要通过 `S` 键引爆，否则不会爆炸）
* `D` - 使用激光

### 手机
如果开启重力感应，则通过重力感应移动，如果未开启重力感应，通过网页上的方向图标移动。