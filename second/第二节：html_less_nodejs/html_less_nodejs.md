# html_less_nodejs

## 学完本节课你能

1. 了解less是什么，用less代替css编写样式
2. 使用nodejs运行js代码，开发一个微型的web站点
3. 管理平台的布局重构，掌握html元素如何规划编程

## 内容大纲

1. html扩展思考

2. 使用nvm安装nodejs
3. less安装使用
4. 管理平台布局重构


## html扩展思考

​	我们已经知道了 html 是有一个一个标签组成元素的，这些标签，有`<div>,<a>,<input>...`，那么大家是否想过，是否可以自定义标签呢，譬如，我想让这个标签叫 `<abc>`；同理，每个标签都有 `class`属性，那么我们是否可以自定义一些属性，譬如，有个属性我们叫 `cde`。 将来，我们就可能遇到这样的元素 `<adc cde="fgh">呵呵</abc>`。

## 使用nvm安装nodejs

​	nodejs有很多下载安装方式，但是为什么选择nvm呢？

### 	nvm指令

1. `nvm alias default <版本号>` 指定版本
2. `nvm install <版本号>` 指定版本


### 	链接	

1. [nodejs官网下载](https://nodejs.org/en/download/)
2. [nvm-windows下载](https://github.com/coreybutler/nvm-windows/releases)
3. [nvm](https://github.com/creationix/nvm)


### 	初步使用

1. `node --version` 验证是否安装成功
2. `npm --version` 验证是否安装成功
3. `node test.js` nodejs运行js文件

## less安装使用

1. 安装less `npm install -g less`

2. 使用less `lessc styles.less`

3. 配置webstorm使用less-watch

   ### 相关资料

   1. [慕课网——less即学即用](http://www.imooc.com/learn/102)
   2. [less官方文档](http://less.bootcss.com/)

## 管理平台布局重构

​	我的项目地址：[地址](https://github.com/wwlweihai/html-css-js-base/tree/master)

## 本节作业

1. 配置webstorm，less环境，将第一节课程的作业中css,修改成less。
2. 安装好nodejs,启动运行测试文件。
3. 在chrome浏览器中运行console方法，定义变量，定义常量，调试循环等等…[阮一峰，es6](http://es6.ruanyifeng.com/)









