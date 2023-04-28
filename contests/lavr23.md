---
layout: default
ref: lavr-2023
lang: ru
title: Лаврентьевские чтения 2023
---
# Лаврентьевские чтения 2023

## Личный зачёт

<div style="overflow-x: auto">
    <table>
    <thead>
        <tr>
        <th>Участник</th>
        <th>Команда</th>
        <th>Статус</th>
        <th>A</th>
        <th>B</th>
        <th>C</th>
        <th>D</th>
        <th>E</th>
        <th>F</th>
        <th>Всего</th>
        <th>Место</th>
        <th>Диплом</th>
        </tr>
    </thead>
    <tbody>
        {% for res in site.data.lavr.pers23.results -%}
        <tr>
        <td>{{ res.surname }} {{ res.name }} {{ res.patronymic }}</td>
        <td>{{ res.team }}</td>
        <td>{{ res.status }}</td>
        <td class="right">{{ res.problems[0] }}</td>
        <td class="right">{{ res.problems[1] }}</td>
        <td class="right">{{ res.problems[2] }}</td>
        <td class="right">{{ res.problems[3] }}</td>
        <td class="right">{{ res.problems[4] }}</td>
        <td class="right">{{ res.problems[5] }}</td>
        <td class="center">{{ res.total }}</td>
        <td class="center">{{ res.place }}</td>
        <td class="center">{{ res.award }}</td>
        </tr>
        {%- endfor %}
    </tbody>
    </table>
</div>

## Командный зачёт

<div style="overflow-x: auto">
    <table>
    <thead>
        <tr>
        <th>Команда</th>
        <th>Комментарий</th>
        <th>A</th>
        <th>B</th>
        <th>C</th>
        <th>D</th>
        <th>E</th>
        <th>F</th>
        <th>Всего</th>
        <th>Место</th>
        <th>Диплом</th>
        </tr>
    </thead>
    <tbody>
        {% for res in site.data.lavr.team23.results -%}
        <tr>
        <td>{{ res.name }}</td>
        <td>{{ res.comment }}</td>
        <td class="right">{{ res.problems[0] }}</td>
        <td class="right">{{ res.problems[1] }}</td>
        <td class="right">{{ res.problems[2] }}</td>
        <td class="right">{{ res.problems[3] }}</td>
        <td class="right">{{ res.problems[4] }}</td>
        <td class="right">{{ res.problems[5] }}</td>
        <td class="center">{{ res.total }}</td>
        <td class="center">{{ res.place }}</td>
        <td class="center">{{ res.award }}</td>
        </tr>
        {%- endfor %}
    </tbody>
    </table>
</div>

## Фото

<img alt="photo1" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaUgdeANaefnK7pq0HJYHATgvb-0aYG9I5x6gVbSL6ZmEAZ5pG_Y9j6QLOjujRVqZW71jP1EzYfjEc5n10CsaCap6Y6-vFHpU-6L86o8UUJ4rWKLPlQ8Z-FrqTBhkA226aqhqd_M6Lth--uUXA5G7LE=s960">

<img alt="photo2" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaXhEuvK2t1PlM8kYKomUuytxwoKKmItGzfvdk1TRRbfGGNYV4sFqKDNRLMHsgO9rurbiVqNJcFgQ2huJNPxN9WMqCbeGGsYLZTswNJx0wMBAXg5Nin_S7Ky6zdtQZpYZ8lTTEpwirHols5lDT_2xqo=s960">

<img alt="photo3" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaWaHI8W-bwmiDTQOiLkwZUYJMDwFZvq4ygAFO3OwReUu_rG7aYWzhZfec2N3VwZpLY0uGTo3UMBNTgpPAeWyy8PAEGzgRA-1KeBAtiH9hA6qRyK0D9dQxFPhjD69TfD8nu1Vh-JfkhEYEzseYTSN0o=s960">

<img alt="photo4" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaVMLfhvD1xYKUcI2WJHgC6WBMeeLX_7B7wA1GVSzjhPksDKiGJy0cFBNvGNaGKfaIMn7nsm-GbX0G7N262ItQlFMJU3JNrok-GhRlOOhu-iMny026T75QWpraDnHDs6lXWLMT_-gnp92-V7Y6-VvdM=s960">

<img alt="photo5" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaVPN4Y4mSkWNj83AtRu2erLS-GupAk25XBUSKgjz5TSid81Dp6iD6ksZCulbtTxqClE4RvdyNgVga6o2CZwAxD6vsYkQ3hKrPB7fji-W-8-riTH3P28NRXaltQNCniQekQTp1kb5W6WVCfnbHYX9vU=s960">

<img alt="photo6" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaXmNMFp7SsKKGniDnqZYdo_4Mb89rXBMhPaWamVIdcBtnZp8RXJ5dGeU_ZC4-Ow9yOJeX8Nf1uYYQ7TfMETz7MbMrNPAZTT3T7OrWCyRuFgxkZH0NjmRdZg1G_timwO-AR-0H9KqFnS219MWVXqebU=s960">

<img alt="photo7" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaWha3CxpZLAWSd1rb1kypxa0b3-RJHgWatLI64elTLjJZFPQ-hcF4b8J-skPtoMOUEFPq_0_fKkV6AajW_8f85nSOM_z56LCxJfvNRtLxIkVAxclTo7qVpAgcmqhZ3HfKbu3ved94GursgQNUerpgs=s960">

<img alt="photo8" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaX-49ijbAA68ErGiGRY7mcwl66qY4ttbVUR-3xlvlAsr8ypuK-J4e23KvgSiLONuv-9FHBnLGnXwJ4-g13hpPevcC-YmypTdg4OlEC6OBrIjYTXb5OAa5obIiESHceK8gpgzRMGYM0UahNBGr2HL3g=s960">

<img alt="photo9" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaWAs_9WGOfdu3Vx8Rs4JVh0dPI2G0KtAqJQUSDtqVkKliJsL8wLo9DK5LW4fwF_U_f9JuV_F72yji_V_sw4su6i1kay1G5v_iyzB6b4Hr7WRRvUwhAcdmY4vMma1conaivT5iQG9WWon6qkoINLu-U=s960">

<img alt="photo10" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaUuL57xFV7kf31CQatRrKhn4bN-5OjgySNmNgNw-8EEddd0iSuBj0d5ijQ0b7jhQgwQmw56B-C2_3vZ5MSQccgqaEpGXvIWioE4fXw3eTKAEQi6hxaJJKhsTDp5s-NuDquICaTprFJKqOV4FNttJF8=s960">

<img alt="photo11" style="width: 100%" src="https://lh3.googleusercontent.com/pw/AJFCJaWmCGXqO_1pIx2PNofu0f055rgjQ1BfTALjwFpyGBUULiz-oMpqpxngCSljS-eW-kMFxozIRPvWCMzg3aekFF-Te8o6_9ktEb9KOqLkSi3daQqtxinIL8nm9bbONHuZuJfzRVTj3HqiN8-_SucQ2ZE=s960">
