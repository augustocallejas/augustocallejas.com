---
layout: default
---
You can find out more about me [here](/about).

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: '%B %d, %Y' }}
    </li>
  {% endfor %}
</ul>
