---
layout: default
title: 首页
---

# 欢迎来到我的博客！

这是我的个人博客，使用 GitHub Pages 和 Jekyll 构建。

## 关于我

我是 fyhbauyg，一个喜欢分享技术知识和学习心得的人。

## 博客特色

- 🚀 完全免费托管在 GitHub Pages
- 📝 使用 Markdown 编写文章
- 🎨 简洁的 Minimal 主题
- 🔄 自动构建和部署

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y年%m月%d日" }}
{% endfor %}

## 联系我

- GitHub: [fyhbauyg](https://github.com/fyhbauyg)
- 博客地址: [https://fyhbauyg.github.io](https://fyhbauyg.github.io)
