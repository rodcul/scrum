---
layout: page
title: SCRUM for Startups
tagline: The no bullshit approach to shipping product
---
{% include JB/setup %}

# Pomodoro app

Download Pomodoro App by Ugo Landini: [http://rodcul.github.io/scrum/app/Pomodoro.app.zip](http://rodcul.github.io/scrum/app/Pomodoro.app.zip)

Source: [https://github.com/ugol/pomodoro](https://github.com/ugol/pomodoro)

    
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



