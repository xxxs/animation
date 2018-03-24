# animation
[animation](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Animations/Using_CSS_animations)

# 1. 配置动画 
## animation-delay (默认值 0 )
- 设置延时 元素加载完成到动画开始播放的时间
- 语法 :  animation-delay: time;
- js语法: object	object.style.animationDelay="2s"


## animation-direction   - 设置动画播放完后反向播放还是重新开始
- normal默认 |  reverse动画反向播放  | alternate 奇数次反向播放  | alternate-reverse 奇数次正向播放
- 语法: js	object.style.animationDirection="reverse" 

## animation-duration 设置动画播放时间

- 语法 :	object.style.animationDuration="3s"

## animation-iteration-count   设置动画重复次数
-  infinte重复播放  or  具体播放次数 
    
- 语法: object.style.animationIterationCount=3


- animation-name 
    指定由@keyframes 描述的关键帧的名称

- animation-play-state
    允许暂停和播放动画

- animation-timing-function 
    设置动画速度 即通过建立加速度曲线 设置动画在关键帧之间是如何变化

- animation-fill-mode
    指定动画执行前后如何为目标元素应用样式
  