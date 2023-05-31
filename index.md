---
layout: default
title: Home
---

All these tests and not a meaningful fail. :/ 

[about](/about)


Let's see if I can get a list of posts...

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>