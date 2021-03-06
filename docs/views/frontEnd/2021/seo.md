---
title: '前端SEO技巧'
  # 大标题
sidebarDepth: 2
sidebar: auto
categories: frontEnd
date: 2021-07-06
# 时间
tags:
- SEO
# 标签
---

::: tip 概述
SEO(Search English Optimization),搜索引擎优化。
:::

<!-- more -->


## 存在的意义
为了提升网页在搜索引擎自然搜索结果中的收录数量以及排序位置而做的优化行为。

**白帽SEO**：改良和规范网站设计的作用，使网站对搜索引擎和用户更加友好，并且网站也能从搜索引擎中获取合理的流量

**黑帽SEO**：利用和放大搜索引擎政策缺陷来获取更多用户的访问量，这类行为大多是欺骗搜索引擎，一般搜索引擎公司是不支持与鼓励的


## 优化点
### 网站结构布局优化：尽量简单、开门见山，提倡扁平化结构
一般而言，建立的网站结构层次越少，越容易被“蜘蛛”抓取，也就容易被收录。一般中小型网站目录结构超过三级，“蜘蛛”便不愿意往下爬，“万一天黑迷路了怎么办”。并且根据相关调查：访客如果经过跳转3次还没找到需要的信息，很可能离开。因此，三层目录结构也是体验的需要。为此我们需要做到：

1. 控制首页链接数量
网站首页是权重最高的地方，如果首页链接太少，没有“桥”，“蜘蛛”不能继续往下爬到内页，直接影响网站收录数量。但是首页链接也不能太多，一旦太多，没有实质性的链接，很容易影响用户体验，也会降低网站首页的权重，收录效果也不好。

因此对于中小型企业网站，建议首页链接在100个以内，链接的性质可以包含页面导航、底部导航、锚文字链接等等，注意链接要建立在用户的良好体验和引导用户获取信息的基础之上。

2. 扁平化的目录层次
尽量让“蜘蛛”只要跳转3次，就能到达网站内的任何一个内页。扁平化的目录结构，比如：“植物”--> "水果" --> "苹果"、“桔子”、“香蕉”，通过3级就能找到香蕉了。

3. 导航优化
导航应该尽量采用文字方式，也可以搭配图片导航，但是图片代码一定要进行优化，`<img>`标签必须添加“alt”和“title”属性，告诉搜索引擎导航的定位，做到即使图片未能正常显示时，用户也能看到提示文字。

其次，在每一个网页上应该加上面包屑导航，好处：从用户体验方面来说，可以让用户了解当前所处的位置以及当前页面在整个网站中的位置，帮助用户很快了解网站组织形式，从而形成更好的位置感，同时提供了返回各个页面的接口，方便用户操作；对“蜘蛛”而言，能够清楚的了解网站结构，同时还增加了大量的内部链接，方便抓取，降低跳出率。

4. 网站的结构布局--不可忽略的细节
页面头部：logo及主导航，以及用户的信息。

页面主体：左边正文，包括面包屑导航及正文；右边放热门文章及相关文章，好处：留住访客，让访客多停留，对“蜘蛛”而言，这些文章属于相关链接，增强了页面相关性，也能增强页面的权重。

页面底部：版权信息和友情链接。

特别注意：分页导航写法，推荐写法：“首页 1 2 3 4 5 6 7 8 9 下拉框”，这样“蜘蛛”能够根据相应页码直接跳转，下拉框直接选择页面跳转。而下面的写法是不推荐的，“首页 下一页 尾页”，特别是当分页数量特别多时，“蜘蛛”需要经过很多次往下爬，才能抓取，会很累、会容易放弃。

5. 控制页面的大小，减少http请求，提高网站的加载速度。
一个页面最好不要超过100k，太大，页面加载速度慢。当速度很慢时，用户体验不好，留不住访客，并且一旦超时，“蜘蛛”也会离开。

## 网页代码优化
```
1. <title>标题：只强调重点即可，尽量把重要的关键词放在前面，关键词不要重复出现，尽量做到每个页面的<title>标题中不要设置相同的内容。

2. <meta keywords>标签：关键词，列举出几个页面的重要关键字即可，切记过分堆砌。



3. <meta description>标签：网页描述，需要高度概括网页内容，切记不能太长，过分堆砌关键词，每个页面也要有所不同。



4. <body>中的标签：尽量让代码语义化，在适当的位置使用适当的标签，用正确的标签做正确的事。让阅读源码者和“蜘蛛”都一目了然。比如：h1-h6 是用于标题类的，<nav>标签是用来设置页面主导航的等。



5. <a>标签：页内链接，要加 “title” 属性加以说明，让访客和 “蜘蛛” 知道。而外部链接，链接到其他网站的，则需要加上 el="nofollow" 属性, 告诉 “蜘蛛” 不要爬，因为一旦“蜘蛛”爬了外部链接之后，就不会再回来了。


6. 正文标题要用<h1>标签：“蜘蛛” 认为它最重要，若不喜欢<h1>的默认样式可以通过CSS设置。尽量做到正文标题用<h1>标签，副标题用<h2>标签, 而其它地方不应该随便乱用 h 标题标签。

7. <br>标签：只用于文本内容的换行，比如:

8. 表格应该使用<caption>表格标题标签

9. <img>应使用 "alt" 属性加以说明

10. <strong>、<em>标签 : 需要强调时使用。<strong>标签在搜索引擎中能够得到高度的重视，它能突出关键词，表现重要的内容，<em>标签强调效果仅次于<strong>标签。

　　　  <b>、<i>标签: 只是用于显示效果时使用，在SEO中不会起任何效果。

11. 重要内容不要用JS输出，因为“蜘蛛”不认识

12. 尽量少使用iframe框架,因为“蜘蛛”一般不会读取其中的内容

13. 谨慎使用 display：none ：对于不想显示的文字内容，应当设置z-index或设置到浏览器显示器之外。因为搜索引擎会过滤掉display:none其中的内容。

14. js代码如果是操作DOM操作，应尽量放在body结束标签之前，html代码之后。

15. 使用SSR框架
```
