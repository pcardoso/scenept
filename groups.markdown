---
layout: page
title: Groups
permalink: /groups/
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
