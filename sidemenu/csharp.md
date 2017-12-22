---
layout: page
title: C# Application
---
## About
이번 카테고리는 C# 어플리케이션 개발에 유용한 정보를 공유할 예정입니다.

<!-- This loops through the paginated posts -->
{% for post in paginator.posts %}
  <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
  <p class="author">
    <span class="date">{{ post.date }}</span>
  </p>
  <div class="content">
    {{ post.content }}
  </div>
{% endfor %}


