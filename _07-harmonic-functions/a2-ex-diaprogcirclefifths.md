---
layout: chapter
title: Examples 7a - Diatonic Progressions Derived from Circle-of-fifths Voice-leading
abc: true
---

**This example has two idealized progressions of a V chord resolving to a I chord: one as triads and the other with a seventh chord. Study how each voice resolves. It is tempting to focus on which scale degree resolves to which scale degree, but this does not provide a complete explanation. Instead focus on which chordal members resolve to which chordal members.**

{% capture ex1 %}X:1
T:Basic V to I progressions
M:4/4
L:1
K:C
V:1
[BG]| [cE]|| [BF]| [cE]|]
V:2 clef=bass
[G,D]| [C,C]|| [G,D]| [C,C]|]
w:C:V I V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**The next example focuses on the simple triadic progression and follows the circle-of-fifths backwards to add a ii chord. Does this follow the voice-leading explanation that you created after looking at the first examples? If not, how does it differ? After you have studied this, try creating a voicing for a vi chord.**

{% capture ex2 %}X:2
T:Adding the ii chord
M:4/4
L:1
K:C
V:1
[FA]| [BG]| [cG]|]
V:2 clef=bass
[D,D]| [G,,D]| [C,E]|]
w:C:ii V I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**The next example adds the vi chord. Were you able to correctly construct this using your voice-leading rules? Is it correct to explain the voice-leading of the progression using chordal members or scale degrees? If you continue around the circle-of-fifths, what would the voicing for the next chord be?**

{% capture ex3 %}X:3
T:Adding the vi chord
M:4/4
L:1
K:C
V:1
[EA]| [FA]| [BG]| [cG]|]
V:2 clef=bass
[A,,C]| [D,D]| [G,,D]| [C,E]|]
w:C:vi ii V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

**Again, we ask the same questions. Were you able to correctly add the iii chord using your voice-leading rules? Is it correct to explain the voice-leading of the progression using chordal members or scale degrees?**

{% capture ex4 %}X:4
T:Adding the iii chord
M:4/4
L:1
K:C
V:1
[EG]| [EA]| [FA]| [BG]| [cG]|]
V:2 clef=bass
[E,B,]| [A,,C]| [D,D]| [G,,D]| [C,E]|]
w:C:iii vi ii V I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

**Beyond the iii chord, the voice-leading runs into an issue with harmonic function. While it is possible to continue this pattern through these two chords, in tonal harmony, the IV and vii<sup>o</sup> chords actually function most often as if they are extensions of the ii<sup>7</sup> and V<sup>7</sup> chords respectively. Look at the following example to see voice-leading using both of these chords. The first measure uses the ii<sup>7</sup> and V<sup>7</sup> chords as part of a diatonic progression, but the second progression substitutes the IV for the ii<sup>7</sup> chord and the vii<sup>o</sup> chord for the V<sup>7</sup> chord. After looking at this example, explain why IV and vii<sup>o</sup> function similarly to ii<sup>7</sup> and V<sup>7</sup>.**

*Please note that to demonstrate how closely related these chords are, many voice-leading rules are being broken in this example -- most notably the parallel octaves between the soprano and bass between vii<sup>o</sup> and I. This is for demonstration purposes only, do not assume that this good voice-leading for IV or vii<sup>o</sup>.*

{% capture ex5 %}X:5
T:Adding the IV and viio chords
M:4/4
L:1
K:C
V:1
[Fc]| [BF]| [cE]|| [Fc]| [BF]| [cE]|]
V:2 clef=bass
[D,D]| [G,,D]| [C,C]|| [A,,C]| [B,,D]| [C,C]|]
w:C:ii7 V7 I IV6 viio I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

**These examples allow you to create a basic framework for diatonic harmonic progressions. Use these progressions here to create a flowchart for standard diatonic progressions that includes all diatonic harmonies. Note that there are notable exceptions that are commonly used in diatonic harmony, so please discuss these with your instructor to add the missing exceptions.**