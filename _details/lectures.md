---
layout: page
title: Lectures
permalink: /lectures/
output: true
---
<p>
	As the course progresses, slides from each class will be posted here for viewing or download, per a <a href="http://creativecommons.org/licenses/by-sa/4.0/">Free Culture license</a>. 
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
	<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</p>