{% for emoji in site.data.emoticons %}
  {% include mini-swatch.html codepoint=emoji.codepoint name=emoji.name %}
{% endfor %}
