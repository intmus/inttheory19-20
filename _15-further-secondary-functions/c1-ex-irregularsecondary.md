---
layout: chapter
title: 15c Examples - Irregular Usage of Secondary Chords
abc: true
---

## Voice-leading exceptions for secondary dominants

In Unit 11, we discussed how repeated patterns and sequences in voice-leading can override standard voice-leading practices. One such example was how a sequence of seventh chords can require "incorrectly" resolved chordal thirds and sevenths. To demonstrate this, harmonize the excerpt below paying attention to the chordal resolutions between the ii<sup>7</sup> and V<sup>4/3</sup> chords.

{% capture ex1 %}X:1
T:Harmonizing consecutive seventh chords
M:4/4
L:1/2
K:C
V:1
[c] [B]| [c2]|]
V:2 clef=bass
[D,] [D,]| [C,2]|]
w:C:ii7 V4/3 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

What chordal resolution changes? Because secondary dominant chords are so closely related to diatonic circle-of-fifths progressions, you may apply the same principle to repeated series of secondary dominant seventh chords. Try the same voice-leading on the following example. What changes? How does this affect accidentals within the bar.

{% capture ex2 %}X:2
T:Harmonizing consecutive seventh chords
T:with a secondary dominant chord
M:4/4
L:1/2
K:C
V:1
[c] [B]| [c2]|]
V:2 clef=bass
[D,] [D,]| [C,2]|]
w:C:V7/V V4/3 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Series of secondary dominants

Secondary dominant functions have one more commonly-used progression because of their relationship with the diatonic circle-of-fifths progression. Begin by harmonizing the following standard progression.

{% capture ex3 %}X:3
T:Consecutive secondary dominant chords
M:4/4
L:1/2
K:C
V:1
[cE] [c]| [d] [d]| [c2]|]
V:2 clef=bass
[C,G,] [A,,]| [D,] [G,,]| [C,2]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

We used this progression in Unit 14 to introduce secondary dominant chords by altering the ii chord. We then altered the vi chord from the same progression in Unit 15a in order to demonstrate how to tonicize chords other than V. Because the voice-leading is so similar, secondary dominant functions can lead into *each other* creating series of secondary dominant chords. In the example above, alter your voicing of the ii chord to create a V/V chord and alter the vi chord to create a V/ii. This creates a progression of:

I - V/ii - V/V - V - I

Therefore, secondary dominant chords can be substituted freely within a circle-of-fifths progression.

## Deceptive resolutions of secondary dominant functions

There is a less common resolution of secondary dominant chords that relies on the voice-leading from a deceptive cadence. Analyze the following example, and you will notice that at first glance, the progression does not follow our established progressions between the second and third chords. To understand this, you must think in the *borrowed* key. What key would this chromatic chord *normally* tonicize? If you were in that key, how would label the progression between these two chords? It is very helpful to use leadsheet symbols here.

{% capture ex4 %}X:4
T:Deceptive resolutions of secondary dominant functions
M:4/4
L:1/2
K:C
V:1
[cE] [BD]| [AC] [GD]| [G2C]|]
V:2 clef=bass
[C,G,] [E,^G,]| [F,A,] [B,F,]| [C2E,]|]
w:C:I V7/vi IV V4/2 I6{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}