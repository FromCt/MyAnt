# 笔记


## 样式 css3

### 贝塞尔曲线

http://cubic-bezier.com/#.17,.81,.89,.12

曲线运动

    -webkit-transition: margin .3s cubic-bezier(0.075, 0.82, 0.165, 1)

### input placeholder focus

    .search input::-webkit-input-placeholder {
        color: #CADCE3;
        }
    .search input::-moz-placeholder {
        color: #CADCE3;
        }
    .search input:-ms-input-placeholder {
        color: #CADCE3;
        }

    .search input:focus ~ button {
        left: 170px;
        }

### css 计算属性

     width: calc(100% - 240px);

### css animation

animation 属性是一个简写属性，用于设置六个动画属性：

    animation-name
    animation-duration
    animation-timing-function
    animation-delay
    animation-iteration-count  次数默认 1次
    animation-direction  是否反向播放

animation-fill-mode 属性规定动画在播放之前或之后，其动画效果是否可见。

    none	不改变默认行为。
    forwards	当动画完成后，保持最后一个属性值（在最后一个关键帧中定义）。
    backwards	在 animation-delay 所指定的一段时间内，在动画显示之前，应用开始属性值（在第一个关键帧中定义）。
    both	向前和向后填充模式都被应用。

animation-timing-function

    linear	动画从头到尾的速度是相同的。	测试
    ease	默认。动画以低速开始，然后加快，在结束前变慢。	测试
    ease-in	动画以低速开始。	测试
    ease-out	动画以低速结束。	测试
    ease-in-out	动画以低速开始和结束。	测试
    cubic-bezier(n,n,n,n)	在 cubic-bezier 函数中自己的值。可能的值是从 0 到 1 的数值。

案例

    -webkit-animation: xRightMatrix .5s ease-out .5s backwards;
    animation: xRightMatrix .5s ease-out .5s backwards;

    @keyframes xRightMatrix {
        0% {
            opacity: 0;
            transform: translateX(50px);
        }
        100% {
            opacity: 1;
            transform: translateX(0px);
        }
        }
    @-webkit-keyframes xRightMatrix {
        0% {
            opacity: 0;
            -webkit-transform: translateX(50px);
        }
        100% {
            opacity: 1;
            -webkit-transform: translateX(0px);
        }
    }