#MarkDown 图片

MarkDown图片语法格式
- 开头一个感叹号
- 接着一个方括号，里面放上图片的替代文字
- 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的‘title’属性的文字。

![银装素裹](https://img0.baidu.com/it/u=1435639120,2241364006&fm=253&fmt=auto&app=138&f=JPEG?w=800&h=500)

![百度](https://www.baidu.com/img/fnj_96d95207b4a706738f1b8be3b41ea9f3.gif)

---

也可以像网址那样对图片网址使用变量

这个链接用1作为网址变量 [百度][1]

然后在文档的结尾为变量赋值（网址）。
[1]:https://www.baidu.com/img/fnj_96d95207b4a706738f1b8be3b41ea9f3.gif
# 问题

## 图片链接
- 基本文字链接
	- [百度][baidu]
	- ![基本图片](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo_top_ca79a146.png)
- 图片链接
	- [![基本图片](baidu_logo)][baidu]
	
	
[baidu]:https://www.baidu.com/
[baidu_logo]:https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo_top_ca79a146.png
