---
layout: page
title: Lectures
permalink: /lectures/
output: true
---
<p>
	Every lecture from the Civic Technology course is embedded below and also freely available for download as a pdf. 
</p>


{% for lecture in site.data.lectures %}
<h3>
	<a href="https://drive.google.com/uc?id={{ lecture.id }}&export=download">
	 <strong>{{ lecture.name }}:</strong> 	{{ lecture.description }}</a>
</h3>
<div class="resp-container">
   <iframe class="resp-iframe" 
   src="https://drive.google.com/file/d/{{ lecture.id }}/preview"></iframe>
</div>
{% endfor %}


<p> 
	Currently only the slides are posted; overtime, the lecture notes providing more context to the presentations will be published.
</p>