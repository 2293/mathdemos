math demos with sagecell 数学演示，用sagemath/sagecell驱动

<ul>
  {% for page in site.html_pages %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endfor %}
</ul>
