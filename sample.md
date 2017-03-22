{% for emoji in site.data.emoticons %}
  {% include mini-swatch.html codepoint={{ emoji.codepoint | downcase }} name={{ emoji.name | upcase }} %}
{% endfor %}
