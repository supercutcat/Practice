# Practice

1. Type Effect
    初始化，flex justify-content和align-item居中并设置最小高度
    
    设置右侧竖线通过after创建伪元素，作为已选中元素的最后一个子元素，通常通过content属性为该元素添加装饰内容这个虚拟元素默认是行内元素。
    在此装饰内容为空，设置背景色，宽高，圆角，绝对定位来达到在末尾的竖线效果
    
    在js在h1 classList中天机ended后， 给h1的伪元素设置aimation 达到闪烁效果
    
    文字从左到右opacity从0到1
    通过js设置delay达到文字依次展开的效果
    
    选中h1，在h1中innerHTML 通过h1 textContent取到的元素内容，通过/S非空白(字母之间)和/s空白(单词之间)替换成span的$& 和 $nbsp半角不断行空格

    在遍历时通过这两个标志让单词之间间隔时间设置长度不一样通过style的setProperty添加delay长度
    
3. mouse-out transition
    初始化， html block-size和inline-size设置为100%
    影响块元素和行内元素的width和height，具体取决于writing-mode

    body设置min-block-size和min-inline-size为100%，
    并设置margin和box-sizing为border-box

    display为grid 
    place-content(justify-content和align-content)为center
    居中

    media查询 orientation 为landscape
    body grid-auto-flow为column ?

    设置h1 before伪元素
    设置成BFC
    top right bottom left都为0让无宽高的盒子填满整个父容器
    insets无阴影
    z-index：-1在后一层

    设置h1伪类hover时before伪元素
    transform scaleX在X轴伸展 两侧
    transform-origin bottom left从左下角开始伸展
