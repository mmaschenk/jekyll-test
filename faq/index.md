---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: FAQ
---
### Frequently asked questions

This page holds the frequently asked question with regards to Cloud4Research.

**Is your question not answered here?** Please e-mail to <xxxx@tudelft.nl>

{% assign faqpages = site.pages | where_exp: "p", "p.dir == '/faq/'" | where_exp: "p", "p.name != 'index.md'" %}

{% for page in faqpages %}

--------------

[{{page.title}}]({{page.url | relative_url }})

{% endfor %}