---
layout: default
lang: ru
ref: index
title: Главная
---

# Результаты

{% for contest_hash in site.data.contests %}
{% assign contest = contest_hash[1] %}
{% if contest.nickname %}
<p>{{ site.contest_nicknames[contest.nickname][page.lang] }}-{{contest.year}}</p>
{% else %}
<p>{{ contest.name }}</p>
{% endif %}
{% endfor %}