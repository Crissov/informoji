{% for emoji in site.data.emoticons %}
  {{ emoji.codepoint | downcase }} => {{ emoji.name | upcase }}
{% endfor %}
