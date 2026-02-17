---
layout: default
---

<article class="post">
    <p>
        {{ page.date | date: "%Y-%m-%d" }}
        {% if page.author %}
        von <i>{{ page.author }}</i>
        {% endif %}
    </p>

    {{ content }}

</article>
