---
layout: sidebar-page
title: Actions
permalink: /reference/action/
script: /js/search.js
---

Work In Progress

This is a list of the actions that plugins can respond to.

It's a long list, and most haven't been documented yet, but we're providing it now to allow people to experiment whilst the documentation catches up.


## List of actions
<table>
  <tbody>
  {% assign actions = site.actions | sort: 'title' %}
  {% for action in actions %}
    <tr>
      <td><a href="{{action.url}}">{{action.title}}</a></td>
      <td>{{action.summary}}</td>
    <tr>
  {% endfor %}
  </tbody>
</table>
