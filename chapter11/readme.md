# CSS简介

CSS是层叠样式表。HTML用于控制网页的结构，CSS用于控制网页的外观，JavaScript控制的是网页的行为。

CSS历经CSS1.0、CSS2.0、CSS2.1、CSS3.0这几个版本。CSS2.1是CSS2.0的修订版，CSS3.0是CSS的最新版本。

# CSS的引入方式

* 外部样式表

* 内部样式表

* 行内样式表

## 外部样式表

外部样式表是把CSS单独放在一个文件里，然后在HTML文件里引入(head标签里使用link标签引入。)。

```<link rel="stylesheet" type="text/css" href="文件路径"/>```


## 内部样式表

将CSS内容放在head标签中的style标签中。

```<style type="text/css">css内容</style>```

## 行内样式表

把CSS内容放进HTML元素的style属性中。

```<div style="color:red;">绿叶，给你初恋般的感觉。</div>```

# 总结

一般使用外部样式表，内部和行内样式表的css内容分布过于琐碎。