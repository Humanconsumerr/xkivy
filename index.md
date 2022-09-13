---
layout: default
---

<div align="center">

{% include_relative README.md %}
</div>

--------------
<h3 align=center> scrobbles </h3>

<p align="center">
  <a href="https://last.fm/user/xkiv">
    <img src="https://lastfm-recently-played.vercel.app/api?user=xkiv" />
  </a>
</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul

--------------