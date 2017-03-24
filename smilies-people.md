## Smileys & People

{% for group in site.data.collation-groups %}
### {{ group.description }} `{{ group.name }}`
  {% for emoji in site.data.collation %}
    {% if emoji.Group == group.name %}
      {% include mini-swatch.html codepoint=emoji.codepoint name=emoji.name %}
    {% endif %}
  {% endfor %}
{% endfor %}
