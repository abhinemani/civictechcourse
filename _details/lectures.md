---
layout: page
title: Lectures
permalink: /lectures/
output: true
---
<p>
	Every lecture from the Civic Technology course is freely available for download as a pdf. Currently only the slides are posted; overtime, the lecture notes providing more context to the presentations will be published.
</p>

<ul>
{% for lecture in site.data.lectures %}
  <li>
    <a href="{{ lecture.link }}">
      {{ lecture.name }}:
    </a> {{ lecture.description }}
  </li>
{% endfor %}
</ul>