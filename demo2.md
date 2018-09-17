# Demo2

## 链接 Demo
### 内嵌式链接
- 外部链接: [百度](http://www.baidu.com)
- 内部链接: 链接仓库的其它文件: [demo1](demo1.md)
- 内部链接: 链接本文档的其它部分: [代码块 demo](demo2.md#代码块-Demo)
### 引用式链接
- 外部链接: [百度][baidu]
- 内部链接: 链接仓库的其它文件: [demo1]
- 内部链接: 链接本文档的其它部分: [代码块 demo](demo2.md#代码块 Demo)

## 图片 Demo

- 图片的markdown语法
![alt当图片不能正常显示的时候显示这里](https://www.baidu.com/img/superlogo_c4d7df0a003d3db9b65e9ef0fe6da1ec.png?qua=high&where=super "放在图片上显示的内容")

- 仓库内的图片
![nihao](test.jpg "nihao")

- 图片的引用式链接
![alt当图片不能正常显示的时候显示这里][百度log]

## 引用 Demo

> 这是一个引文
>> 这是多重引文

## 代码块 Demo

- 行式代码
这个代码中用来声明的变量是`var a=10`.打印的内容为`cat log`，这就是行内代码

- 块式代码
```javascript
a="nihao"
如果上面标记了语言，那么会高亮显示代码
```

```
a="你好"
```

    a="你好"


<!--- 下面是本文档中用到的链接 --->
[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[demo1]: demo1.md
[代码块 demo]: demo2.md#代码块-Demo
[百度log]: https://www.baidu.com/img/superlogo_c4d7df0a003d3db9b65e9ef0fe6da1ec.png?qua=high&where=super
