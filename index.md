{% for pass in site.passes %}
  <h2>
    <a href="{{ pass.url }}">
      |{{ pass.Name }} | {{ pass.Cat }}|
    </a>
  </h2>
  <p>{{ pass.content | markdownify }}</p>
{% endfor %}
