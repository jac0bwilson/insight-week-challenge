---
layout: page
title: Solutions
permalink: /solutions/
---

On this page you will find solutions for all of the challenges that we created!

---

## Easy:

<div class="item-container">
  {% for challenge in site.data.challenges %}
    {% if challenge.difficulty == 1 %}
      <div class="challenge-container">
        <br><a class="challenge-button" href="{{ challenge.link }}">{{ challenge.name }}</a>
      </div>
    {% endif %}
  {% endfor %}
</div>

## Medium:

<div class="item-container">
  {% for challenge in site.data.challenges %}
    {% if challenge.difficulty == 2 %}
      <div class="challenge-container">
        <br><a class="challenge-button" href="{{ challenge.link }}">{{ challenge.name }}</a>
      </div>
    {% endif %}
  {% endfor %}
</div>

## Hard:

<div class="item-container">
  {% for challenge in site.data.challenges %}
    {% if challenge.difficulty == 3 %}
      <div class="challenge-container">
        <br><a class="challenge-button" href="{{ challenge.link }}">{{ challenge.name }}</a>
      </div>
    {% endif %}
  {% endfor %}
</div>