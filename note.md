# ant源码阅读

## 提交阅读

c5e67da first commit

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

    添加home.js 主要是animation
    
70b0829 code style
06a97ff update