---
layout: page
title: Lectures
permalink: /lectures/
output: true
---
<p>
	As the Civic Tech course progresses &#8212; there will be 20 lectures total &#8212; slides from each class will be posted here for viewing or download, per a <a href="http://creativecommons.org/licenses/by-sa/4.0/">Free Culture license</a>. 
</p>


{% for lecture in site.data.lectures %}
<h3>
	<a name="{{ lecture.name }}" id="{{ lecture.name }}" href="https://drive.google.com/uc?id={{ lecture.id }}&export=download" >
	 <strong>Lecture {{ lecture.name }}:</strong> 	{{ lecture.description }}</a>
</h3>
<div class="resp-container">
   <iframe class="resp-iframe" 
   src="https://drive.google.com/file/d/{{ lecture.id }}/preview"></iframe>
</div>
{% endfor %}


<p> 
	
</p>