---
layout: template1
title: Archive
comments: false
---

## Miniblog

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url | prepend: site.baseurl }})
{% endfor %}
