# XDroidAnimation
简单创建属性动画
#Provide
	 1.渐变Alpha动画（AlphaAnimation），支持多值
	 2.旋转Rotate动画（RotateAnimation），支持设置轴点
	 3.缩放Scale动画（ScaleAnimation），支持多值，,支持设置轴点
	 4.全屏滑动Slide动画（SlideAnimation）,支持上下左右四个方向移入与移出
	 5.自身控件范围内滑动动画（SlideUnderneathAnimation）,支持上下左右四个方向移入与移出
	 6.抖动Shake动画（ShakeAnimation）,支持垂直与水平抖动
	 7.视图位移Transfer动画（TransferAnimation）
	 8.窗帘动画（BlindAnimation），支持上下左右四个方向移入与移出，支持设置轴点
	 9.翻转动画（FlipAnimation），支持垂直与水平翻转，支持设置轴点
	 10.View转换翻转动画（FlipToAnimation），一个View翻转成另一个View,支持垂直与水平翻转，支持设置轴点
	 11.膨胀动画（PuffAnimation）, 支持进入，淡出，支持设置轴点
	 12.组合动画（CombinationAnimation）将一系列动画组合到一起，同时执行
	 13.颜色动画（ColorAnimation），支持 多属性、多值 设定
	 14.伸缩动画（TelescopicAnimation），支持 进入与移出、高度与宽度伸缩
	 15.路径动画（PathAnimation）
	 16.多种自定义的Interpolate插值器
	 17.SVG动画（SVGAnimationView）
#Here is the sample
[Download demo.apk](https://github.com/robinxdroid/XDroidAnimation/blob/master/XDroidAnimationExample.apk?raw=true)
#Screenshot
![](https://github.com/robinxdroid/XDroidAnimation/blob/master/XDroidAnimation.gif) 
![](https://github.com/robinxdroid/XDroidAnimation/blob/master/XDroidAnimation2.gif) 

# Usage
以下为一个片段
```java
AnimationKit.createSlideUnderneathAnimation(button).setDuration(1000)
            .setInterpolator(new DecelerateInterpolator())
            .setDirection(Direction.DIRECTION_RIGHT)
	    .setSlideMode(SlideMode.OUT)
	    .animate();
```
具体请见Demo中MainActivity.java
#Thanks
[EasyAndroidAnimations](https://github.com/2359media/EasyAndroidAnimations)<br>
[EaseInterpolator](https://github.com/cimi-chen/EaseInterpolator)
#About me
Email:735506404@robinx.net<br>
Blog:[www.robinx.net](http://www.robinx.net)

