---
title: Hexo常用总结
date: 2017-12-01 23:58:23
tags: [tools]
type: "categories"
categories: 总结
comments: true
---


# Hexo中一些常用总结

#### **1. 添加图片**
关于资源的加载最好是放置在云服务器上根据链接去访问。
例如用[七牛云](https://www.qiniu.com/)、阿里云等。
```javascript
![“图片描述”](图片地址)  
```

_ _ _

#### **2. 添加音视频**
生成外部链接后直接添加：
```javascript
<iframe   
    height=498 width=510   
    src="http://player.youku.com/embed/XNjcyMDU4Njg0"   
    frameborder=0 allowfullscreen>  
</iframe>  
```
_ _ _

#### **3. 关于博文中添加空格**
```javascript
半方大的空白&ensp;或&#8194;
全方大的空白&emsp;或&#8195;
不断行的空白格&nbsp;或&#160;
```
#### **4. 关于博文中字体和颜色字号**
```javascript
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=#0099ff size=12 face="黑体">黑体</font>
<font color=#00ffff size=3>null</font>
<font color=gray size=5>gray</font>

```
_ _ _
#### **5. 关于博文中背景色设置**
```javascript
<table><tr><td bgcolor=red>背景色是：red</td></tr></table>
```
_ _ _
#### **6. 添加algolia搜索**
algolia搜索感觉还是一款高逼格的检索,[algolia官网](https://www.algolia.com/)
```javascript
hexo algolia
```
_ _ _
#### **7. 关于博文中添加评论**
目前的评论还是liveRe展示的效果比较好些，[liveRe官网](https://livere.com/)

_ _ _
#### ***. 常用的命令**

```javascript
hexo new page categories
hexo new page tags
hexo g
hexo d
npm install hexo-server --save
npm install hexo-admin --save
npm install hexo-generator-archive --save
npm install hexo-generator-feed --save
npm install hexo-generator-search --save
npm install hexo-generator-tag --save
npm install hexo-deployer-git --save
npm install hexo-generator-sitemap --save

#字数统计
npm install hexo-wordcount --save
#检索
npm install hexo-algolia@0.2.0 --save
hexo algolia
```