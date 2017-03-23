## Facial Emojis

These emojis have `FACE` in their Unicode name or are otherwise basically required to be displayed primarily as a face or head.

{% for emoji in site.data.emoticons %}
  {% include mini-swatch.html codepoint=emoji.codepoint name=emoji.name %}
{% endfor %}

## Additional Face Emojis

Some vendors also display various animal emojis as head-only.

{% for emoji in site.data.possible-faces %}
  {% include mini-swatch.html codepoint=emoji.codepoint name=emoji.name %}
{% endfor %}

<!--
## Bust Emojis

Most people, man and woman emojis are shown as a bust with head and shoulders, possibly hands and arms.
Some activity emojis also have prominent faces.

{% for emoji in site.data.people %}
  {% include mini-swatch.html codepoint=emoji.codepoint name=emoji.name %}
{% endfor %}
-->
