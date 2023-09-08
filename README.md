math demos with sagecell 数学演示，用sagemath/sagecell驱动
<ul>
<li><a href="000003solve_3n%2B1_problem/">000003solve_3n+1_problem/</a></li>
<li><a href="000087polar_plot.html">000087polar_plot.html</a></li>
<li><a href="100001historical%20prime%20factor.html">100001historical prime factor.html</a></li>
<li><a href="100012significant%20prime%20factor.html">100012significant prime factor.html</a></li>
<li><a href="200009PaleyGraph.html">200009PaleyGraph.html</a></li>
<li><a href="images/">images/</a></li>
<li><a href="LICENSE">LICENSE</a></li>
<li><a href="logo.png">logo.png</a></li>
<li><a href="logo.svg">logo.svg</a></li>
<li><a href="README.md">README.md</a></li>
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
![mathdemos](logo.png)
<h5><a href="https://github.com/2293/mathdemos/new/main">Contribute to this site</a></h5>