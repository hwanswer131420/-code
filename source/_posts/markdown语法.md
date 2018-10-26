---
title: markdown语法
date: 2018-10-25 09:45:39
tags:
---
# 标题
# 一级标题
## 二级标题
...
###### 六级标题

# 超链接
  [点我](http://www.baidu.com)跳转到百度
  [链接名字](链接地址)

# ![图片](表情包)
  ![图片](http://i0.hdslb.com/bfs/archive/59b70dcc0c9a425d2450bfed04b7f544dda5c8dc.png)
  [![表情包]((http://i0.hdslb.com/bfs/archive/59b70dcc0c9a425d2450bfed04b7f544dda5c8dc.png)](http://www.baidu.com)

# 文本修饰
  *文本倾斜*
  **文本加粗**
  ***文本加粗并倾斜***
  ~~删除线~~

# 引用
> 引用的内容

# 分割线
三个或者以上的"-"号或者"*";
 ---                     #会出现一条虚直线
 ***
 
 ## 有序列表
 1.张三
 2.李四
 3.王五

 ## 无序列表
以一个-或 +或 *
-列表1
-列表2
-列表3

# 表格
姓名|排行|特长
-|-|-
刘备|老大|哭
关羽|老二|打
张飞|老三|骂

# 代码块
```javascript
while(alive){
  code();
  eat();
  sleep();
}
```

```css
body{
    color:red;
    font-size:15px;
}
```
# 完整初始化博客
```bash
# 初始化博客
hexo init blog
# 进入博客
cd blog
# 安装依赖包
npm install
# 启动hexo服务
hexo server  <-->  (hexo s)
```