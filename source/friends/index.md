---
layout: friends
title: 我的朋友们
cover: true
top_meta: false
bottom_meta: false
sidebar: [blogger, category, tagcloud, lastupdate, webinfo]
comments: false

---

{% span center logo large::Hello Friends! %}
{% note info::如果你想要添加你自己的博客/网站，可以按照下方的提示提交申请。 %}

<!-- more -->

{% folding ::申请友链 %}
👏欢迎加入我的朋友圈！
你需要进行如下操作以在这个页面中添加你的博客/网站。
{% timeline %}

{% timenode 1/3 %}

请点击{% btn 这个按钮:: https://github.com/imoscarz/blog-files/edit/master/source/_data/friends.yml %} ，创建一个Fork。

{% endtimenode %}

{% timenode 2/3 %}

按如下格式（高亮部分）在`source/_data/friends.yml`文件添加你的网站信息：

{% note warning::请注意，将自己的信息按时间添加到对应的分组。如`2023`年添加，即对应分组为`group: 2023` %}

{% codeblock lang:yaml mark:4-9 %}
- group: ****
  description: ****
  items:
    - title: # 名称（必要）
      avatar: # 头像（必要）
      url: # 链接（必要）
      screenshot: # 截图（选填）
      keywords: # 关键词（选填）
      description: # 描述（选填）
{% endcodeblock %}

{% endtimenode %}

{% timenode 3/3 %}

提交一个PR，我会在看到以后尽快审核。

{% endtimenode %}

{% endtimeline %}

{% endfolding %}