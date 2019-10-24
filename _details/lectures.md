---
layout: page
title: Lectures
permalink: /lectures/
output: true
---
<p>
	From empathy to the ecosystem, from data to delivery, and from startups to sustainability... A master class on leveraging technology -- software, data, and design -- for the public good.
</p>
<p>
	The Civic Technology Course is part product, part theory, and part technical, with a focus on the characteristics unique to public interest tech. There were 16 lectures total delivered between April and June 2019. Slides from each class are posted here for viewing or download, per a <a href="http://creativecommons.org/licenses/by-sa/4.0/">Free Culture license</a>. 
</p>

<ul>
	{% for lecture in site.data.lectures %}
	<li>
		<a href="#{{ lecture.name }}" >
			<strong>Lecture {{ lecture.name }}:</strong> 	{{ lecture.description }}
		</a>
	</li>
	{% endfor %}
</ul>

<p style="text-align: center">
 ***	
	
</p>

{% for lecture in site.data.lectures %}
<h3>
    <a name="{{ lecture.name }}" id="{{ lecture.name }}" href="https://drive.google.com/uc?id={{ lecture.id }}&export=download" >
        <strong>Lecture {{ lecture.name }}:</strong> 	{{ lecture.description }} (pdf)
    </a>
</h3>
<div class="resp-container">
   <iframe class="resp-iframe" 
   src="https://drive.google.com/file/d/{{ lecture.id }}/preview"></iframe>
</div>
{% endfor %}


<p> 
	
</p>
