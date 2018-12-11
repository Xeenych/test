{% for pass in site.passes %}
  <h2>
    <a href="{{ pass.url }}">
      {{ pass.Название }} - {{ pass.Категория }}
    </a>
  </h2>
  <p>{{ pass.content | markdownify }}</p>
{% endfor %}
