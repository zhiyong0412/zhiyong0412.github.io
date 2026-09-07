---
layout: default
title: 首页
---

# 王志勇的思考笔记

这里记录我平时的一些思考与笔记。下面是全部文章，按时间倒序排列（最新在最上面），列表会自动更新——只要往 `_posts/` 目录里新增 Markdown 文件即可。

## 文章列表

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% else %}
_还没有文章。在 `_posts/` 里新建一个 `YYYY-MM-DD-标题.md` 文件试试。_
{% endfor %}

## 其他

- [关于我]({{ '/about/' | relative_url }})
