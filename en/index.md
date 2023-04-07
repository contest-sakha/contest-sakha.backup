---
layout: default
lang: en
ref: index
title: Home
---

# Results

{% for contest_hash in site.data.contests %}
{% assign contest = contest_hash[1] %}
{% if contest.nickname %}
<p>{{ site.contest_nicknames[contest.nickname][page.lang] }}-{{contest.year}}</p>
{% else %}
<p>{{ contest.name }}</p>
{% endif %}
{% endfor %}