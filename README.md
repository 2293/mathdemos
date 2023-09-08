math demos with sagecell 数学演示，用sagemath/sagecell驱动

<ul>
  {% for page in site.html_pages %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endfor %}
</ul>
<ul>
{% for post in site.posts %}	
    <li><a href="{{ post.url }}">{{ post.title }}</a><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} </small></li>	
{% endfor %}
</ul>