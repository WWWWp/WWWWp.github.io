---
layout: article 
title: "可视化笔记"
categories:  rwd
image:
    teaser: keshihua4.jpg
    feature: keshihua4.jpg
---




### 关于 github.io/posts/infovis/ 主页插入可视化图片的技巧

---
最简单的方法：
将 Markdown 中用插入图片和插入链接的方法结合。
- ####  选择插入图片

在tableau desktop选择：==‘工作表’→‘导出’==，导出png，之后复制粘贴到本地 github.io/images 中，再从github仓库里找到所需图片的链接，右键图片，复制图片链接地址，
![image](https://github.com/WWWWp/WWWWp.github.io/blob/master/images/1515327041(1).jpg?raw=true)

```
![image](https://github.com/WWWWp/WWWWp.github.io/blob/master/images/1515327041(1).jpg?raw=true)
```
- #### 插入链接

以下是Markdown插入链接的形式，只需将 link 改成以插入的图片的image代码，再将()中的链接换成自己想要的链接就ok。
```
[link](http://note.youdao.com/)
```
[![image](https://github.com/WWWWp/WWWWp.github.io/blob/master/images/1515327041(1).jpg?raw=true)](https://github.com/WWWWp/WWWWp.github.io/blob/master/images/1515327041(1).jpg)