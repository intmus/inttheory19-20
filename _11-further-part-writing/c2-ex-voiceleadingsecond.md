---
layout: chapter
title: Examples 11c - Voice-leading for Second Inversion Chords
abc: true
---

## Doubling

As a general rule, 6/4 chords function best when the bass voice is doubled. As you harmonize the chords in each of the examples below, notice how often this doubling occurs naturally in your part-writing.

## Cadential 6/4s

**A cadential 6/4 chord is the most straightforward usage of second inversion chord, because it has the most specific rules.**
- It occurs when a I<sup>6/4</sup> chord precedes a *root-position* V or V<sup>7</sup> chord. 
    - It cannot move to an inversion of a V chord or any version of a vii<sup>o</sup> chord.
- The I<sup>6/4</sup> loses its tonic function and instead acts as an extension of the dominant function. 
    - You can consider it an anticipation of the arrival of the dominant chord.
- It always occurs as part of the cadence for a phrase, hence the name.

**Harmonize the following three examples to see how well the voice-leading works for a cadential 6/4 chord.**

{% capture ex1 %}X:1
T:Cadential 6/4 chords
M:4/4
L:1/4
Q:1/4=70
K:C
V:1
[cE]xxx|| [cE]xxx|| [cE] [c] [c] [d]|]
V:2 clef=bass
[C,G,] [G,,] [G,,] [C,]|| [C,G,] [G,,] [G,,] [C,]|| [C,G,] [F,,] [G,,] [G,,]|]
w:C:I I6/4 V I I I6/4 V7 I I IV I6/4 V{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**Cadential 6/4 chords are often used to correct part-writing difficulties in apparoaching the V chord. Look at the third progression that you just harmonized. If the cadential 6/4 were removed, it would create parallel perfect 5ths between the soprano and bass.**

**Some theory methods teach that a cadential 6/4 should not be labeled as a I<sup>6/4</sup>; instead, they label it as a V<sup>6/4 - 5/3</sup>. The reasoning behind this is twofold:**
- The I chord does not have a tonic function.
- The cadential 6/4 often strongly resembles a 4-3 suspension and a 6-5 suspension occurring at the same time.

**These are both certainly good reasons and enforce an understanding of the true nature of the cadential 6/4. I prefer to label it as a I<sup>6/4</sup> chord, however, because:**
- We do not create special usage cases in our Roman numeral system for any other chord. It creates an unnecessary exception for students to learn and often confuses students on the difference between inversion figures and true figured bass.
- By having two different chords labeled as a V<sup>6/4</sup>, it is easy for beginning theorits to confuse a cadential 6/4 with an actual V<sup>6/4</sup>, a chord that occurs regularly as a passing chord. (Read more on this below under the *passing 6/4* section.)
- When looking at an analysis, we are required to understand that all 6/4 chords function in one of the four alternate categories (i.e. passing, cadential, passing, and arpeggiated), but we do not create special Roman numeral cases for the other three. Students are more than capable of learning the other three usages of second inversion chords, and they can remember that a I<sup>6/4</sup> followed by a root-position V or V<sup>7</sup> chord is a cadential 6/4 and has a dominant function.

## Passing 6/4s - function over form (Part 4)

**Passing chords are the second standard usage for second-inversion chords,and they function identically to the description of how first- and third- inversion chords are used as passing chords -- a second-inversion chord inserted between two other chords to create a bass line with stepwise motion. *Passing* is a function that replaces a chord's standard function (i.e. tonic, dominant,and predominant), and instead extends the function of the chords on either side. Harmonize the following example of a passing 6/4.** 

{% capture ex2 %}X:2
T:Passing 6/4 chords
M:4/4
L:1/4
K:C
V:1
[cE][B][A][G]| [G4]|]
V:2 clef=bass
[C,G,] [G,,] [A,,] [B,,]| [C,4]|]
w:C:I V ii6/4 V6 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**Understanding that the ii chord in this example acts as a passing chord rather than a pre-dominant chord also explains how a V chord moves convincingly to a ii chord. When a chord resolves against the normal flow of a circle-of-fifths flowchart (see Unit 7a), we call that a *regression*. In the example above, the first V chord *should* resolve to a tonic chord but instead regresses to a ii chord. This works because of the strength of the bass line, so it is the *passing function* that extends the dominant harmony through a stepwise bass line.**

**Now that we have practiced using a passing 6/4 chord, we can also clarify why vii<sup>o6</sup> chords function well as a passing chord. When studying first inversion chords (Unit 11b), we discussed two important ideas regarding vii<sup>o</sup> chords:**
- The vii<sup>o</sup> is a functional substitution for the V<sup>7</sup> chord and therefore takes its voice-leading and doubling conventions from the V<sup>7</sup> chord.
- The vii<sup>o6</sup> is often employed as a passing chord between I and I<sup>6</sup> to create a bass line with stepwise motion.

**This explains why a vii<sup>o6</sup> chord functions as a passing chord; it is actually a functional substitution for a passing V<sup>6/4</sup> chord. Harmonize the following two progressions to see how similar these two chords are.**

{% capture ex3 %}X:3
T:V6/4 and viio6
M:3/4
L:1/4
K:C
V:1
[e][d][c]|| [e][d][c]|]
V:2 clef=bass
[C,] [D,] [E,]|| [C,] [D,] [E,]|]
w:C:I V6/4 I6 I viio6 I6{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Pedal

**Like the cadential 6/4 and passing 6/4 chords, the pedal 6/4 is defined by the motion that it creates in the bass line. A pedal 6/4 occurs when the bass line remains static across multiple chords by employing a second inversion chord. *Note that this is different from a non-chord tone pedal*, because a pedal 6/4 chord uses only chord tones to create the static pedal; it does not use non-chord tones to create the pedal. Harmonize the following two examples of common pedal 6/4 chords.**

{% capture ex4 %}X:4
T:Pedal 6/4 chords
M:3/4
L:1/4
K:C
V:1
[cE]xx[][]|| [dG]xx[][]|]
V:2 clef=bass
[C,G,] [C,] [C,]|| [G,,B,] [G,,] [G,,]|]
w:C:I IV6/4 I V ii6/4 V{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

## Arpeggiated

**The fourth and final acceptable usage of 6/4 chords occurs when the bass line creates arpeggiates through a chord. Depending on the harmonic rhythm of the piece, an arpeggiated 6/4 may be viewed as a melodic bass line that does not change inversion rather than a new inversion.**

{% capture ex5 %}X:5
T:Arpeggiated 6/4 chords
M:4/4
L:1/4
Q:1/4=70
K:C
V:1
[cG] [c] [c] [B]| [c4]|]
V:2 clef=bass
[CE] [G,] [E,] [G,]| [C,4]|]
w:C:I I6/4 I6 V I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}