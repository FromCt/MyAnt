# ant源码阅读

## 提交阅读

c5e67da first commit   2015年5月7日周四 下午6:50

    使用 nico 搭建 静态资源模板

0693ae7 update

    nico 根据模板打包，和开启静态资源服务。 感觉会读取页面 a 标签url 输出连接是否存在。

8b32a33 add deploy command

    添加deploy 指令 （打包到提交）

08900df rm src

    删除 src 目录

97f8d04 update theme
a9ac2ec update README

    添加 gh-pages-cli 依赖
    应该是个部署上线的工具。

fc27af8 update README
27c322b Add js

    注入jquery 并在onReady 后 在window 上挂载了 getTransform 方法 和homeFunc对象

a9ab956 fix page

    删除 了js


301f6d6 update layout and cases
095ff4c add home page animation 

    添加home.js 主要是animation 图片中位置画画，然后加载图片
    animEndStr = 'webkitAnimationEnd mozAnimationEnd MSAnimationEnd oanimationend animationend';
    $("#main").one(animEndStr,callback) // 第一次动画 结束时执行

====> 12

70b0829 code style

    修改 home.js 绘制 背景线 的数据结构。更加清晰。

06a97ff update

    aside.html 模板修改
    layout.html 识别componet 时 显示侧边栏
    nico.json 修改为 nico.js (修改nico node-modules 不扫描打包)

72885bd update aside style
066a968 update style
38756ba update style

  添加aside 样式

1c25b1b fix header nav style
8442487 fix header nav style

    修改aside 样式。 修改layout中 component判读 aside 位置（侧边栏和 内容相邻）。

2d6285a fix pages
7271e95 update style  2015年5月11日周一 下午3:52

    style 样式修改。


77367b1 update nav current style
5f13503 aside with category
c7d3649 update style
041ee44 update style
4055f6f update footer
61992b4 update font family
47dd218 update style
35e9a4b update link
892432d add react
c4023c8 aside
706b657 code snipple
6ff3130 layout
a346311 Add loading text
d83608d read demo from demo folder
21810a7 filter name
fef257a tag iconfont
41f7a0e single page update
937a760 toggle code snipple
85e33fd update index page
3ffe2df tweak code
7e05877 Add another demo for example
96dc866 字体
bc90003 adjust slogan position
6c4e32f header nav margin-right
8fc8c7d logo and animation of entry
d69af90 tweak code
ad4bab4 Github -> GitHub
83227c3 use 360 fonts
daae848 update font weight
ace6cfb 调整距离
2d1187c update code template
9591702 update code box template
456f796 use nico-jsx, allow code type jsx
14a2a43 update disabled button
4c12160 Add datepicker style
d08d510 components name
3a2e703 zh-cn
084660e chinese name after components title
31ef99c debug mode
01e582d Add source map config
4fb6722 rm dependency react-tools
1fb01cd waterfall layout
5d79b81 waterfall js script
7a97c50 head上的搜索和导航动画。。。
f184d2c Merge branch 'dev' of https://github.com/ant-design/ant-design.github.io into dev
12a1436 rm timepick
078b0f1 Merge branch 'dev' of github.com:ant-design/ant-design.github.io into dev
8e400f3 修改内页后导行失效。。
dcf8ec1 code style
93ad7f4 merge
9c3dc4b update webpack dev config
9738455 update watch mode
3542848 fix nav bar
b07d10b fix nav bar
03e59b7 default value of datepicker
3c5086d datepicker onChange
17a14fa update
306d106 import rc-style
058bb0b Add iconfont for home page
006fe8b banner 动画
b88043f Merge branch 'dev' of https://github.com/ant-design/ant-design.github.io into dev