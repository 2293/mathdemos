math demos with sagecell 数学演示，用sagemath/sagecell驱动

<ul>
<li><a href="100001historical%20prime%20factor.html">100001historical prime factor.html</a></li>
<li><a href="100012significant%20prime%20factor.html">100012significant prime factor.html</a></li>
<li><a href="200009PaleyGraph.html">200009PaleyGraph.html</a></li>
</ul>

<ul>
  {% for page in site.pages %}
  <li><a href="{{ page.url }}">{{ page.url }}</a></li>
  {% endfor %}
</ul>
<ul>
{% for post in site.posts %}	
    <li><a href="{{ post.url }}">{{ post.title }}</a><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} </small></li>	
{% endfor %}
</ul>