math demos with sagecell 数学演示，以sagemath/sagecell驱动

0 Foundations of Mathematics | 1 Number Theory | 2 Discrete Mathematics | 3 Algebra |
4 Geometry | 5 Calculus and Analysis | 6 Applied Mathematics | 7 Probability and Statistics |
8 Topology | 9 History and Terminology | 10 Recreational Mathematics | 11 misc

<ul>
<li><a href="000001sagecell-examples.html">000001sagecell-examples.html</a></li>
<li><a href="000003solve_3n%2B1_problem/">000003solve_3n+1_problem/</a></li>
<li><a href="000087polar_plot.html">000087polar_plot.html</a></li>
<li><a href="100001historical%20prime%20factor.html">100001historical prime factor.html</a></li>
<li><a href="100003characteristic%20prime%20factor.draft.html">100003characteristic prime factor.draft.html</a></li>
<li><a href="100004OddPrimesMask.html">100004OddPrimesMask.html</a></li>
<li><a href="100004template.html">100004template.html</a></li>
<li><a href="100005Lucas%E2%80%93Lehmer%20primality%20test.html">100005Lucas–Lehmer primality test.html</a></li>
<li><a href="100012significant%20prime%20factor.html">100012significant prime factor.html</a></li>
<li><a href="110001simple-sagecell-editor.html">110001simple-sagecell-editor.html</a></li>
<li><a href="200009PaleyGraph.html">200009PaleyGraph.html</a></li>
<li><a href="500001Asymptotic%20Notation.html">500001Asymptotic Notation.html</a></li>
<li><a href="images/">images/</a></li>
<li><a href="LICENSE">LICENSE</a></li>
<li><a href="logo.png">logo.png</a></li>
<li><a href="logo.svg">logo.svg</a></li>
<li><a href="README.md">README.md</a></li>
<li><a href="todo.md">todo.md</a></li>
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