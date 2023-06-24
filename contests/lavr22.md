---
layout: default
ref: lavr-2022
lang: ru
title: Лаврентьевские чтения 2022
---
# Лаврентьевские чтения 2022

## Личный зачёт

{% assign problems = "A B C D E" | split: " " %}
{% include lavr_pers.html results=site.data.lavr.pers22.results problems=problems %}

## Командный зачёт

<div style="overflow-x: auto">
  <table>
    <thead>
      <tr>
        <th>Команда</th>
        <th>Комментарий</th>
        <th>Всего</th>
      </tr>
    </thead>
    <tbody>
      {% for res in site.data.lavr.team22.results -%}
      <tr>
        <td>{{ res.team }}</td>
        <td>{{ res.comment }}</td>
        <td class="center">{{ res.total }}</td>
      </tr>
      {%- endfor %}
    </tbody>
  </table>
</div>
