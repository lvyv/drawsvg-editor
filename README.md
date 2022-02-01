## 组态画面编辑器

 **SVG** 编辑器被用于组态建模，可以方便的构建基于WEB的自动化组态应用。


## 快速开始

需要预先安装Node.js，然后使用npm安装和运行。

```bash
$ git clone https://github.com/DRAWSVG/drawsvg-editor
$ cd drawsvg-editor
$ npm config set registry https://registry.npm.taobao.org --global
$ npm config set disturl https://npm.taobao.org/dist --global
$ set ELECTRON_MIRROR=http://npm.taobao.org/mirrors/electron/
$ npm install (or yarn install)
$ npm start (or yarn start)
```

或如下启动静态WEB服务，然后访问：http://127.0.0.1:8000/src/drawsvg/edrawsvg.html

```bash
$ python -m http.server
```

## 待完成任务

1）在nodered中如何利用SVG界面事件操控；

2）绘制动画svg，实现空调任务。



https://funprojects.blog/2020/04/15/animated-node-red-graphics-with-mqtt-and-svg/

https://www.opto22.com/support/resources-tools/demos/svg-image-library



