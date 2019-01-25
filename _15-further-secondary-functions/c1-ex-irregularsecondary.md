---
layout: chapter
title: 15c Examples - Irregular Usage of Secondary Chords
abc: true
---

## Voice-leading exceptions for secondary dominants

In Unit 11, we discussed how repeated patterns and sequences in voice-leading can override standard voice-leading practices. One such example was how a sequence of seventh chords can require "incorrectly" resolved chordal thirds and sevenths. To demonstrate this, harmonize the excerpt below paying attention to the chordal resolutions between the ii<sup>7</sup> and V<sup>4/3</sup> chords. Which voices must use non-standard resolutions to accommodate the progression?

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

### Conclusion

In order to use complete chords, the chordal third of the ii<sup>7</sup> chord must remain static to become the chordal seventh of the V<sup>7</sup> like so:

{% capture ex5 %}X:5
T:Harmonizing consecutive seventh chords
M:4/4
L:1/2
Q:1/4=90
K:C
V:1
[cF] [BF]| [c2E]|]
V:2 clef=bass
[D,A,] [D,G,]| [C,2G,]|]
w:C:ii7 V4/3 I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}


## Secondary dominant chord cycles

Because secondary dominant chords are so closely related to diatonic circle-of-fifths progressions, you may apply the same principle to repeated series of secondary dominant seventh chords. Try the same voice-leading on the following example. What changes? How does this affect accidentals within the bar.

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

### Conclusion

You may keep the same resolutions that you used in the diatonic example above--the chordal third of the first chord becomes the chordal seventh of the following chord. There static motion in this voice is eliminated though, because you must resolve down by half-step now that the chordal third has been raised.

{% capture ex6 %}X:6
T:Harmonizing consecutive seventh chords
T:with a secondary dominant chord
M:4/4
L:1/2
Q:1/4=90
K:C
V:1
[c^F] [B=F]| [c2E]|]
V:2 clef=bass
[D,A,] [D,G,]| [C,2G,]|]
w:C:V7/V V4/3 I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

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

We used this progression in Unit 14 to introduce secondary dominant chords by altering the ii chord. We then altered the vi chord from the same progression in Unit 15a in order to demonstrate how to tonicize chords other than V. Because the voice-leading is so similar, secondary dominant functions can lead into *each other* creating series of secondary dominant chords. In the example above, alter your voicing of the ii chord to create a V/V chord and alter the vi chord to create a V/ii creating a progression of:

I - V/ii - V/V - V - I

### Conclusions

This progression now simply extends your seventh chord resolutions from the examples above.

{% capture ex7 %}X:7
T:Consecutive secondary dominant chords
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
[cE] [^cG]| [d^F] [d=F]| [c2E]|]
V:2 clef=bass
[C,G,] [A,,A,]| [D,C] [G,,B,]| [C,2C]|]
w:C:I V7/ii V7/V V I{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

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