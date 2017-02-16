---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}


으하으하으하아아앍 기본 화면 고치자
이제 여기좀 고쳐서 템플릿을 만들어 봐야것구먼

## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do
