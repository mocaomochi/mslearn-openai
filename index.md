---
title: Azure OpenAI Exercises
permalink: index.html
layout: home
---

# Azure OpenAI 演習
この演習は、[Microsoft Learn](https://learn.microsoft.com/training/browse/?terms=OpenAI) のモジュールをサポートするために作成されました。

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Exercises'" %}
{% for activity in labs  %}
- [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }})
{% endfor %}
