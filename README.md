## A simple Blog Program Powered By NodeJS
###重新开始
玩`博客`的时间算起来有两三年了，也经历了`wordpress`的热潮。那时候满心欢喜的买下一个虚拟空间，安装上wordpress，从此自己也是一个有博客的人了。

接着就是不断的尝试一下wordpress的各种插件，自定义自己的风格样式。算起来玩wordpress的时间大大超过了实际写文章的时间。后来由于国人开始热捧Github，在`github`上写博客成为一种时尚，这样不仅有了免费的空间，而且备份也不成问题了.

前段时间我的`虚拟空间`到期了，正好这段时间在学习nodejs，所以产生了一个用`nodejs`自己写一个博客程序的念头,就这样一切推倒从来，以前的wordpress博客内容也不打算要了，毕竟以前写的文章也不是很多，倒是转载了不少，能力有限自己写不出什么东西。现如今买了一个`VPS`，装上Ndoejs，开始新的征程。

###博客程序的诞生
参照了网上一些文章，最后完成主要的技术点就是：

* 博客的文章发布使用`Git`更新文章所在文件夹的形式
* 博客功能的升级也是通过Git更新的形式进行
* 博客的文章采用`markdown`形式书写
* 使用Nodejs的Markdown包将文本转成html
* 前端JS模板使用了`handlerbar`
* 前端的样式使用了Github的`Markdown CSS Theme`
* 后端的Nodejs没有使用任何框架，纯自己堆码完成，虽然功能有限，但是一方面自定义性高啊，另一个就是保持轻量级
* 评论系统使用流行的`DISQUS`评论系统


###未来

在以后的使用过程中不断添加自己想要的功能，看着自己程序不断发展壮大还是挺有成就感的。
