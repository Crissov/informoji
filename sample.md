{% for emoji in site.data.names %}
  {{ emoji.emojidata }} 
  {% include mini-swatch.html codepoint={{ emoji.codepoints }} name=emoji.emojidata %}
{% endfor %}

