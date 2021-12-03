---
layout: page
title: Grupos
permalink: /grupos/
---

<div>
    {%- for group in site.data.groups -%}
        <p>
            {{ group.name }}
            <br>
            {{ group.location }} ({{ group.founded }})
        </p>
    {%- endfor -%}
</div>
