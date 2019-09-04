---
layout: page
title: About
description: 志在指尖 用双手敲打未来
keywords: 志在指尖, Liu Hai Dong, 刘海东
comments: true
menu: 关于
permalink: /about/
---

我是刘海东，志在指尖，用双手敲打未来。

仰慕「优雅编码的艺术」。

坚信熟能生巧，努力改变人生。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
