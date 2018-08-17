---
layout: chapter
title: Examples 11b - Voice-leading for First and Third Inversion Chords
abc: true
---

## Resolving tendency tones

**Placing either the chordal third or chordal seventh in the bass voice not only creates more melodic bass lines, it also allows the upper voices more freedom because there is one less tendency tone to distribute and resolve correctly. Use the voicing and voice-leading guidelines discussed in the previous topic to harmonize the following progressions in an SATB style. As always, make note of any difficulties that you encounter for the class discussion.**

{% capture ex1 %}X:1
T:First- and third-inversion chords
T:in circle-of-fifths progressions
M:3/4
L:1/4
K:C
V:1
[cE]xx| [cE]xx|| [cE]xx|]
V:2 clef=bass
[C,G,] [B,,] [C,]| [C,G,] [B,,] [C,]| [C,G,] [F,] [E,]|]
w:C:I V6 I I V6/5 I I V4/3 I6{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**Assuming that the progression follows the circle-of-fifths, what inversion must a chord be that follows a first-inversion chord? Following a third-inversion?**

## Function over form (Part 2)

**When harmonizing the short chord progressions in the previous topic, we discussed why we have to treat the vi chord in a deceptive cadence as a *functional substitute* for tonic. Because the vi chord acts as a replacement for a I chord, we double the scale degree that works best for a I chord, `do`, rather than the standard doubling of the root, `la` or fifth, `mi`. In this progression, it is correct to break standard convention and double the chordal third of the vi chord. Now that we are looking at first inversion voice-leading, we have another *functional substitution* to discuss.**
- vii<sup>o</sup> is a dominant function, so therefore functions as V<sup>7</sup> chord without its root

**Because of this, the vii<sup>o</sup> chord must follow different *doubling* rules in order to avoid poor voice-leading. With this in mind, try to harmonize the following progressions; first a simple I-V<sup>6/5</sup>-I progression, and then with an added root-position vii<sup>o</sup> chord. You will discover that:**
- the two chords have all but one pitch in common.
- resolving a root-position vii<sup>o</sup> is extremely difficult and will require one voice to make consecutive jumps of a P5 to avoid issues due to tendency tone resolutions.**

{% capture ex2 %}X:2
T:Voicing a viio using functional substitution
M:4/4
L:1/4
K:C
V:1
[cE] xx2|| [cE] xxx|]
V:2 clef=bass
[C,G,] [B,,] [C,2]|| [C,G,] [B,,] [B,,] [C,]|]
w:C:I V6/5 I I viio V6/5 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**Because the root position vii<sup>o</sup> triad is so difficult, it is rarely used. It is not possible to resolve a root-position vii<sup>o</sup> triad to a I chord without creating at least one unacceptable part-writing error. A root-position vii<sup>o</sup> must either pass through another chord or be inverted to resolve directly to I.**

**As a general rule of thumb, any diminished chord (including the ii<sup>o</sup> in minor) will typically need to have the chordal third doubled, because the tension of the diminished fifth and its tendency tones.**

## Function over form (Part 3)

**The pre-dominant function presents an issue that the functional substitutions in tonic and dominant functions do not. To this point, we have considered the circle-of-fifths as the voice-leading foundation for diatonic harmony. In this case, the ii chord would be the "primary" pre-dominant function, and in many ways, this is true. The IV chord, however, holds a special place in harmony because of its role as the *subdominant* -- the opposite pole of the dominant -- as well as the high frequency throughout history of the I-IV-V-I progression.**

**Generally speaking, root position ii chords and root position IV chords are equally strong and follow standard doubling conventions. When the ii chord is in first inversion, however, it becomes a functional substitution for a root-position IV chord. This means that a ii<sup>6</sup> chord most often takes its doubling from a root-position IV chord. (In the same way that a vii<sup>o</sup> chord takes its doubling from a V<sup>7</sup> chord.) Try this on the following progressions. (Make sure to consider the common direction and motion for upper voices tend to do when a root position IV chord moves to a V chord.)**

{% capture ex3 %}X:3
T:Using functional substitutions for pre-dominants
M:4/4
L:1/4
K:C
V:1
[cE]xxx| [cE]xxx|| [cE]xxx|]
V:2 clef=bass
[C,G,] [F,,] [G,,] [C,]| [C,G,] [F,,] [G,,] [C,]| [C,G,] [F,,] [G,,] [C,]|]
w:C:I IV V I I ii6 V I I ii6/5 V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Passing chords

**When a chord is inserted between two other chords to create a bass line with stepwise motion, we call this a *passing chord*. First- and third-inversion chords often function in this way. You can consider *passing* a function that replaces a chord's standard function (i.e. tonic, dominant, and predominant), and instead extends the function of the chords on either side. In the following example, notice that the V<sup>6</sup> chord has a doubled third, and if it were to resolve directly to a I chord, it would create parallel octaves. In this case, the IV<sup>6</sup> chord in no longer strictly a pre-dominant function, because it's primary role in this case is to extend the dominant function to allow the V<sup>6</sup> to fix its doubling before resolving to a tonic chord. Harmonize the following progression to practice using a passing chord.**

{% capture ex4 %}X:4
T:A passing chord
M:3/4
L:1/4
K:C
V:1
[DG] [A] [B]|]
V:2 clef=bass
[B,,B,] [A,,] [G,,]|]
w:C:V6 IV6 V{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}