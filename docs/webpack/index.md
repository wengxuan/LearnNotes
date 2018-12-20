# webpack

![webpack](https://webpack.github.io/assets/what-is-webpack.png)

> webpack让具有依赖关联关系的各个模块打包成一个压缩文件。

> 本质上，webpack 是一个现代 JavaScript 应用程序的静态模块打包器(module bundler)。当 webpack 处理应用程序时，它会递归地构建一个*依赖关系图*(dependency graph)，其中包含应用程序需要的每个[模块](../js/ecamascript/module.md)，然后将所有这些模块打包成一个或多个 bundle。

webpack的具体介绍还是看[官方文档](https://www.webpackjs.com/concepts/)，这里不做赘述了，下面还是讲些体会之类的。

四个核心概念：

* 入口(entry)
* 输出(output)
* loader： 将所有类型文件转化为webpack能处理的有效模块
* 插件(plugins)： 功能很强大，从打包优化压缩到重新定义环境中的变量

## 一、入口