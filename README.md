math demos with sagecell 数学演示，以sagemath/sagecell驱动

0 Foundations of Mathematics | 1 Number Theory | 2 Discrete Mathematics | 3 Algebra |
4 Geometry | 5 Calculus and Analysis | 6 Applied Mathematics | 7 Probability and Statistics |
8 Topology | 9 History and Terminology | 10 Recreational Mathematics | 11 misc

<ul>
<li><a href="000000template0.html">000000template0.html</a></li>
<li><a href="000001sagecell-examples.html">000001sagecell-examples.html</a></li>
<li><a href="000003solve_3n%2B1_problem/">000003solve_3n+1_problem/</a></li>
<li><a href="000087polar_plot.html">000087polar_plot.html</a></li>
<li><a href="100000template1.html">100000template1.html</a></li>
<li><a href="100001historical%20prime%20factor.html">100001historical prime factor.html</a></li>
<li><a href="100003characteristic%20prime%20factor.draft.html">100003characteristic prime factor.draft.html</a></li>
<li><a href="100004OddPrimesMask.html">100004OddPrimesMask.html</a></li>
<li><a href="100005Lucas%E2%80%93Lehmer%20primality%20test.html">100005Lucas–Lehmer primality test.html</a></li>
<li><a href="100006Ramanujan%27s%20ternary%20quadratic%20form.html">100006Ramanujan's ternary quadratic form.html</a></li>
<li><a href="100007is_prime%282%5Ei%2B3%5Ej%29.html">100007is_prime(2^i+3^j).html</a></li>
<li><a href="100008Triangle-of-m%3D2ij%2Bi%2Bj.html">100008Triangle-of-m=2ij+i+j.html</a></li>
<li><a href="100012significant%20prime%20factor.html">100012significant prime factor.html</a></li>
<li><a href="110001simple-sagecell-editor.html">110001simple-sagecell-editor.html</a></li>
<li><a href="200009PaleyGraph.html">200009PaleyGraph.html</a></li>
<li><a href="500001Asymptotic%20Notation.html">500001Asymptotic Notation.html</a></li>
<li><a href="_config.yml">_config.yml</a></li>
<li><a href="drafts/">drafts/</a></li>
<li><a href="LICENSE">LICENSE</a></li>
<li><a href="logo.png">logo.png</a></li>
<li><a href="logo.svg">logo.svg</a></li>
<li><a href="README.md">README.md</a></li>
<li><a href="sage-help.html">sage-help.html</a></li>
<li><a href="todo.md">todo.md</a></li>
</ul>

<ul>
  {% for page in site.pages %}
  <li><a href="{{ page.url | relative_url }}">{{ page.url }}</a></li>
  {% endfor %}
</ul>
<ul>
{% for post in site.posts %}	
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} </small></li>	
{% endfor %}
</ul>
![mathdemos](logo.png)
<h5><a href="https://github.com/2293/mathdemos/new/main">Contribute to this site</a></h5>