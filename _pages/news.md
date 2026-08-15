---
layout: page
title: news
permalink: /news/
description: News, announcements, and research updates.
nav: true
nav_order: 2
---

<div class="news">
  {% if site.news != blank %}
    {% assign news_size = site.news | size %}
    <div
      class="table-responsive"
      {% if site.announcements.scrollable and news_size > 3 %}
        style="max-height: 60vh"
      {% endif %}
    >
      <table class="table table-sm table-borderless">
        {% assign news = site.news | sort: 'date' | reverse %}
        {% for item in news %}
          <tr>
            <th scope="row" style="width: 20%">{{ item.date | date: '%b %d, %Y' }}</th>
            <td>
              {% if item.inline %}
                {{ item.content | remove: '<p>' | remove: '</p>' | strip }}
              {% else %}
                <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
              {% endif %}
            </td>
          </tr>
        {% endfor %}
      </table>
    </div>
  {% else %}
    <p>No news so far...</p>
  {% endif %}
</div>
