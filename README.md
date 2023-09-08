# https://2293.github.io/mathdemos
math demos with sagecell 数学演示，用sagemath/sagecell制作

### mathdemos
<ul>
  {% for page in site.pages %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endfor %}
</ul>
