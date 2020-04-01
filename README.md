# css
learn css


flex布局：

1.两个重要概念：
(1)开启了flex布局的元素叫做Flex container
(2)Flex container里面的直接子元素叫做flex items
Tip：display:flex/inline-flex
Inline-flex: 行内元素
Flex：块级元素

2.felx布局模型：
main axis主轴 cross axis交叉轴 开始位置为start 结束位置为end

3.Flex container属性：
（1）flex-direction：决定了main axis（主轴）的方向
flex-direction有4个值：
row（默认）：左到右
row-reverse：右到左
column：上到下
column-reverse：下到上
Flex items默认是沿着main axis（主轴）的方向从start到end方向排布 
（items不管是块级元素还是行内元素）
（2）justify-content：决定了flex items在main axis上的对齐方式
flex-start（默认值）:与main start对齐
flex-end：与main end对齐
center：居中对齐
space-between：与main start和main end对齐，中间距离相等
space-evenly：从main start到main end中间距离相等
space-around：中间距离是两边的一倍

（3）align-items：决定了flex items在cross axis上的对齐方式
normal（默认值）：在弹性布局中，效果和stretch一样
stretch：没指定height，则进行拉伸，height为container高度
flex-start：与cross start对齐
flex-end：与cross end对齐
center：居中对齐
baseline：与基准线对齐
（4）flex-warp：决定了flex container是单行还是多行
nowarp：单行（宽度不够会进行压缩）
warp：多行
warp-reverse（很少用）：多行（warp的反转）
（5）felx-flow：是flex-direction||flex-warp的简写
可以省略，顺序任意
