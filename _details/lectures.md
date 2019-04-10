---
layout: page
title: Lectures
permalink: /lectures/
output: true
---
<p>
	Every lecture from the Civic Technology course is freely available for download as a pdf. <em>(Since they are hosted on Google Drive, even without the necessary software to open this proprietary data format, you should be able to view the slides freely online.)</em>
</p>


<ul>
{% for lecture in site.data.lectures %}
  <li>
    <a href="{{ lecture.link }}">
      {{ lecture.name }}:
    </a> &nbsp;
	<em>{{ lecture.description }}</em>
  </li>
{% endfor %}
</ul>

<p> 
	Currently only the slides are posted; overtime, the lecture notes providing more context to the presentations will be published.
</p>