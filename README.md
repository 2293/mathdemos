math demos with sagecell 数学演示，以sagemath/sagecell驱动

0 Foundations of Mathematics | 1 Number Theory | 2 Discrete Mathematics | 3 Algebra |
4 Geometry | 5 Calculus and Analysis | 6 Applied Mathematics | 7 Probability and Statistics |
8 Topology | 9 History and Terminology | 10 Recreational Mathematics | 11 misc

<ul>
{% for file in site.static_files %}
  {% if file.extname == ".html" %}
  <li><a href="{{ file.path }}">{{ file.path | replace_first: '/', '' }}</a></li>
{% endif %}
{% endfor %}
</ul>

<ul>
{% for post in site.posts %}	
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} </small></li>	
{% endfor %}
</ul>

![mathdemos](logo.png)
<h5><a href="https://github.com/2293/mathdemos/new/main">Contribute to this site</a></h5>