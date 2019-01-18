---
layout: chapter
title: 14b Examples - Secondary Leading-tone Chords
abc: true
---

## Secondary leading-tone chords

Just as we can tonicize non-tonic chords by borrowing their dominant chords, we can also tonicize non-tonic chords by borrowing the leading-tone chord (vii<sup>o</sup>) from that same key. A secondary leading-tone chord follows all of the same voice-leading rules as if it were written in the borrowed key.

There are two different ways to explore secondary leading-tone chords(vii<sup>o</sup>/x)--through functional substitution as a dominant chord or through functional substitution as a pre-dominant chord.

## Secondary leading-tone chords through functional substitution

In Unit 11b, we introduced the idea of functional substitution as a way to explore how chords with similar functions are related. To better understand the voice-leading of vii<sup>o</sup> chords, I asked you to think of them as V<sup>7</sup> chords without the root. This explains why vii<sup>o</sup> breaks many of standard part-writing doubling conventions.
- You *should not* double the root, because it's a tendency tone...like the third of the V<sup>7</sup> chord.
- You *should* double the chordal third, because it is not a tendency tone...like the fifth of the V<sup>7</sup> chord.

First, harmonize the following example as written, and then turn the ii<sup>7</sup> chord into a V<sup>7</sup>/V by adding the appropriate accidental.

{% capture ex1 %}X:1
T:Creating a V7/V
M:4/4
L:1/2
K:C
V:1
[cE] [c]| [c] [B]| [c2]|]
V:2 clef=bass
[C,G,] [A,,]| [D,] [G,,]| [C,2]|]
w:C:I vi V7/V V I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

In doing this, you have created a well-voiced secondary dominant seventh chord, V<sup>7</sup>/V that should look something like this:

{% capture ex3 %}X:3
T:Completed secondary dominant chord progression
M:4/4
L:1/2
K:C
V:1
[cE] [cE]| [c^F] [BG]| [c2E]|]
V:2 clef=bass
[C,G,] [A,,A,]| [D,A,] [G,,G,]| [C,2G,]|]
w:C:I vi V7/V V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

To turn this into a secondary *leading-tone* chord, you need to replace the root--in this case, the pitch D--with a note from vii<sup>o</sup>/V. While this is a simple statement, I hope that you remember our discussions of the difficulties in voicing a vii<sup>o</sup> triad. You do not want to double the tendency tones, because one of them will need to resolve incorrectly to avoid objectionable parallels with each other. And because there are so many tendency tones, you need to be careful of where each voice is placed to avoid parallelisms, poor resolutions, and spacing errors. What note should you double? How do you have to re-voice the chord? What inversion does this create for your vii<sup>o</sup>/V chord? Try it using the following voicing.

{% capture ex4 %}X:4
M:4/4
L:1/2
K:C
V:1
[cE] [cE]| [c^F] [BG]| [c2E]|]
V:2 clef=bass
[C,G,] [A,,A,]| [D,A,] [G,,G,]| [C,2G,]|]
w:C:I vi V7/V V I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

It is likely that you immediately ran into issues in trying to eliminate the D from the bass chord. Substituting the an A in the same octave creates parallel octaves against the tenor. Substituting an F-sharp in the same octave creates parallel octaves against the alto. You could frustrate the leading tone in the alto as a workaround, but the fact remains: vii<sup>o</sup> *triads* are extremely difficult to use as a dominant function. Instead it is much easier to use a seventh chord. 

In the following example, try to using a vii<sup>o7</sup>/V using the provided bass line. You may use either a fully diminished or half-diminished seventh chord. 

{% capture ex5 %}X:5
T:Using a secondary leading-tone seventh chord
M:4/4
L:1/2
K:C
V:1
[cE] [cE]| x x| [c2]|]
V:2 clef=bass
[C,G,] [A,,A,]| [^F,,] [G,,]| [C,2]|]
w:C:I vi viio7/V V I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

As you can see, the part-writing mostly takes care of itself in voicing this chord. The most obvious solution is listed below. Notice that the resolutions are smooth and allow every tendency tone to resolve correctly without creating objectional parallels.

{% capture ex6 %}X:6
T:A completed secondary leading-tone seventh chord
M:4/4
L:1/2
K:C
V:1
[cE] [cE]| [c_E] [DB]| [c2]|]
V:2 clef=bass
[C,G,] [A,,A,]| [^F,,A,] [G,,G,]| [C,2]|]
w:C:I vi viio7/V V I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

## Secondary leading-tone chords through similar chords

It is also helpful to approach secondary leading-tone chords by exploring the dual nature of their function. To this point, we have focused on their role as dominant function chords in a second key. For example, we have shown repeatedly that a V<sup>7</sup>/V functions as the V chord *in the key of* V. This explains their voice-leading, but it does not address their *actual* function within the progression as a whole in the home key--the key of I. In the home key, the V<sup>7</sup>/V takes the place of a *pre-dominant* chord, most often replacing a ii chord.

This can be applied to vii<sup>o7</sup>/x as well. Notice that the roots of both dominant function chords--V and vii<sup>o</sup>--and the roots of pre-dominant chords--ii and IV--are separated by the interval of a third. If we add this observation to the idea that a V/V chord is a functional substitution for a ii chord, it reasons that a vii<sup>o</sup> chord is therefore a functional substitution for a IV chord. They share a function and have a root that is a third higher than their more commonly used counterpart.

You can demonstrate this by harmonizing the following diatonic progression. Once you have a harmonization with good voice-leading, alter the IV<sup>6</sup> chord to become the vii<sup>o7</sup> chord from the key of the chord you will be tonicizing--in this case, the vii<sup>o7</sup> from G major. What note(s) do you have to alter to achieve this? How do these notes relate to a V<sup>7</sup>/V? Did you have to re-voice this to accommodate the alterations?

{% capture ex2 %}X:2
T:viio7/V as it relates to IV
M:4/4
L:1/2
K:C
V:1
[cE] [c]| [c] [B]| [c2]|]
V:2 clef=bass
[C,G,] [A,,]| [A,,] [G,,]| [C,2]|]
w:C:I vi IV6 V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

After having done this, do you feel that vii<sup>o</sup> is more closely related to ii<sup>7</sup> or IV? Why?

