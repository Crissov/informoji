## Semitic Emoji Alphabet

{% include mini-swatch.html codepoint="1f42e" name="A (ox)" %}
{% include mini-swatch.html codepoint="1f3e0" name="B (house)" %}
{% include mini-swatch.html codepoint="1f42a" name="G (camel)" %}<!-- boomerang -->
{% include mini-swatch.html codepoint="1f6aa" name="D (door)" %}
{% include mini-swatch.html codepoint="1f64c" name="E (jubilation)" %}<!-- window -->
{% include mini-swatch.html codepoint="1f4a9" name="V (pile)" %}<!-- hook; W, U -->
{% include mini-swatch.html codepoint="1f5e1" name="Z (weapon)" %}
{% include mini-swatch.html codepoint="2696" name="H (courtyard)" %}<!-- wall, thread, yarn; X -->
{% include mini-swatch.html codepoint="1f6b2" name="T (wheel)" %}<!-- wheel, spindle -->
{% include mini-swatch.html codepoint="270b" name="Y (hand)" %}<!-- hand, arm; I, J -->
{% include mini-swatch.html codepoint="1f302" name="L (goad)" %}<!-- goad -->
{% include mini-swatch.html codepoint="1f4a7" name="M (water)" %}<!-- water -->
{% include mini-swatch.html codepoint="1f40d" name="N (snake)" %}<!-- snake, tropical fish -->
{% include mini-swatch.html codepoint="1f41f" name="S (fish)" %}<!-- fish, support -->
{% include mini-swatch.html codepoint="1f441" name="A (eye)" %}<!-- eye -->
{% include mini-swatch.html codepoint="1f444" name="P (mouth)" %}<!-- mouth, corner; F -->
{% include mini-swatch.html codepoint="1f331" name="C (plant)" %}<!-- plant, locust; S -->
{% include mini-swatch.html codepoint="1f435" name="Q (monkey)" %}<!-- monkey, needle eye -->
{% include mini-swatch.html codepoint="1f464" name="R (head)" %}<!-- head -->
{% include mini-swatch.html codepoint="1f31e" name="S (sun)" %}<!-- tooth; ^S -->
{% include mini-swatch.html codepoint="271d" name="T (mark)" %}<!-- cross -->

## Sources
- https://twitter.com/qvarie/status/822434723490197504
- https://github.com/Crissov/css-counters/blob/master/scientific-counter-styles.css

~~~~ css
/*
 * `proto-sinaitic-emoji`
 *
 *  ox house/floorplan jubilation/window handpalm water snake/fish eye head sun/tooth mark
 *  🐮🐃🐂🐄♉️ 🏠🏡⬆🛐🗺 ️ 🙌☺️🙋👻/🖼🖥📺 ✋🖐 🌊💧💦♒️🚰 🐍/♓️🐠🐟🐡🐬🐳🐋🎣 👁👀 😀☺️👤😺🤖👽💀☠️🗣🗽🗿 🌞☀️/👄😬🤓👹 ✝️❌❎✖️➕
 *  => A B E K M N O PR S T
 * @issue
 */
@counter-style proto-sinaitic-emoji {
  system: alphabetic;
  speak-as: proto-sinaitic-phonics;
  symbols: '\1F42E'/*ox*/ '\1F3E0'/*house*/ '\1F64C'/*celebration*//*'\1F5BC'window*/
           '\270B\FE0F'/*palm*/ '\1F30A'/*water*/ '\1F40D'/*snake*//*'\1F41F'fish*/
           '\1F441'/*eye*/ '\1F5FF'/*head*/ '\2600\FE0F'/*sun*//*'\1F479'mouth*/
           '\274C\FE0F'/*mark*/;
}
~~~~
