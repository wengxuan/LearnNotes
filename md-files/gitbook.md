### 使用GitBook生成文档

1. 全局安装gitbook-cli； `npm install gitbook-cli -g`
2. 在某个目录向执行`gitbook init`，会生成`README.md`和`SUMMARY.md`两个文件，其中`SUMMARY.md`是目录结构文件；
3. `gitbook serve`本地启动服务器在线预览 或 `gitbook build`生成html静态界面，需要部署才能使各个html文档中的链接生效。`gitbook build`默认会在当前目录生成`_book`文件夹存放生成的html文件，也可以在后面带上参数，如`gitbook build ./ ../docs`，build后跟了两个路径参数，第一个参数指定生成文档的`README.md`和`SUMMARY.md`的路径，第二个参数指定html静态文件生成的目录。完整例子可以参考当前仓库。

### Refs
[https://www.npmjs.com/package/gitbook](https://www.npmjs.com/package/gitbook)

[https://gitbook.zhangjikai.com/settings.html](https://gitbook.zhangjikai.com/settings.html)