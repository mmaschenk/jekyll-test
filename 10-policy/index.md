---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Policies
---

A number of policies is in place that are relevant to using Cloud4Research services

{% assign policypages = site.pages | where_exp: "p", "p.dir == page.dir" | where_exp: "p", "p.name != 'index.md'" %}

{% for page in policypages %}

--------------

[{{page.title}}]({{page.url | relative_url }})

{% endfor %}