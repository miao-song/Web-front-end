## CSS3 动画

### 全屏切换效果

> 通过鼠标的滚轮 切换全屏页面

- 使用fullpage来完成


## 动画

动画 （JavaScript实现动画，css3实现动画）

- 一个是帧动画  一个是补间动画，css3是补间动画
- 什么是帧动画：使用定时器 每隔一段时间 更改当前元素的状态 
- 什么是补间动画：过渡(加过渡只要状态发生改变产出动画) 动画（多个节点来控制动画） 性能会更好
- 在支持H5C3的的浏览器尽可能使用css3动画 （移动端开发）
- transition  animation
- transition  组合写法（transition: all 1s linear 1s）
  的拆分写法 transition-property  transition-duration transition-timing-function transition-delay

### 转换

- 缩放 scale
- 位移 translate
- 旋转 rotate
- 倾斜 skew
以上四种转换方式是比较特殊，其实他们都是由 matrix 矩阵而来

### 动画速度
- ease  先快后慢 最后非常慢
- linear 匀速
- ease-in 速度越来越快
- ease-out 速度越来越慢
- ease-in-out 速度先快后慢
以上五种动画速度是比较特殊，其实他们都是由 贝塞尔曲线 来的

### 3d转换 translate3d rotate3d
2d转换和3d转换区别：
1.除了多了一个参数表示3d
2.在移动端使用3d转换可以优化性能（如果设备有3d加速引擎 GPU 可以提高性能 ,2d转换是无法调用GPU的）
