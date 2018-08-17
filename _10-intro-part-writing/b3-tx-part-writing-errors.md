---
layout: chapter
title: Lesson 10b - Part-writing Errors
abc: true
---

# Class discussion

## Parallel Perfect Fifths and Octaves

{% capture ex1 %}X:1
T:Parallel perfect octaves (PP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

The class found two examples of parallel perfect octaves in this example.
- between the soprano and tenor moving from ii<sup>6</sup> to V<sup>7</sup>
- between the soprano and tenor moving from V<sup>7</sup> to I

Almost all unacceptable examples of parallel octaves and fifths are due to poor voice-leading and voicings. In this case, the third of the five chord is doubled. This third is a tendency tone that should resolve upward by step, but in doing so, it creates parallel perfect octaves. The third never should have been doubled.

{% capture ex2 %}X:2
T:Parallel perfect fifths (PP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,A,] | [DG,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

In this example, the class found two examples of parallel perfect fifths:
- between the bass and tenor from I to ii
- between the bass and tenor moving from ii to V<sup>7</sup>

From this, we decided that the definition of a parallel perfect fifths/octaves is:
- when two voices have consecutive perfect fifths/octaves and move in parallel motion
    - it is not parallel perfect fifths/octaves if the intervals change voices (e.g. the first P8/P5 is between the soprano and tenor, but the second P8/P5 is between the soprano and alto)
- These are unacceptable between any two voices.

Parallel perfect fifths and octaves undermine the independence of the individual voices. Even after listening to the example with PP5s repeatedly, only one person in the class was able to distinguish the tenor voice. I then had the class look at the tenor voice and practice singing it in order to get the line into their ears. Even after doing this, they had trouble distinguishing between the two voices. This is even more pronounced if the chords are tuned using just intonation, because the upper note will blend into the overtone series of the lower note.
  
## Contrary Octaves and Fifths

{% capture ex3 %}X:3
T:Contrary perfect fifths (CP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,,A,] | [D,G,,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

Contrary fifths and octaves occur when trying to mask parallel perfect fifths and octaves. In the example above, the class identified the CP5s between bass and tenor voices between:
- the I chord and ii chord
- the ii chord and the V<sup>7</sup> chord

From this, we decided that the definition of a contrary perfect fifths/octaves is:
- when two voices have consecutive perfect fifths/octaves and move in contrary motion
    - it is not contrary perfect fifths/octaves if the intervals change voices (e.g. the first P5 is between the soprano and tenor, but the second P5 is between the soprano and alto)
- These are unacceptable between any two voices.

## Unacceptable Unequal Fifths

{% capture ex4 %}X:4
T:Unacceptable unequal fifths (UU5)
M:4/4
L:1/2
K:C
V:1
[cE] [Fd]| [dF] [cG]|]
V:2 clef=bass
[C,C] [D,A,] | [B,,G,] [E,C,]|]
w:C:I ii V6/5 I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

Unacceptable unequal fifths are one of the easier part-writing errors to understand, because we are actually focusing on only one voice-leading issue. We defined a UUF as any time a d5 between the bass voice and another voice moves to a P5. Because it has to fill all of these conditions, it is relatively easy to find compared to parallel and contrary fifths/octaves which are not acceptable between any voices.

The voice-leading issue that causes UU5 centers around the one naturally occurring d5 in the major scale: when `ti` is below `fa`. This is only likely to happen on a dominant harmony which means that this occurs typically on a V<sup>6/5</sup> chord or a vii<sup>o</sup> chord. The problem arises when `fa` does not resolve downward to `mi` in the next chord. This is an incorrect resolution of a tendency tone, and that is what creates the part-writing error.

## Similar Fifths and Octaves

Similar fifths/octaves occur when 1) the soprano and bass voices 2) move in similar motion to a 3) perfect fifth/octave, and 4) the soprano voice has a skip of a third or larger. You can see an example of this between the first two chords in this example.

{% capture ex5 %}X:5
T:Similar octaves (S8)
M:4/4
L:1/2
K:C
V:1
[Ge] [AA]| [FA] [FB]| [c2E2]|]
V:2 clef=bass
[C,C] [CA,,]| [F,,C] [DG,,]| [C2C,2]|]
w:C:I vi IV V7 I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

Similar fifths/octaves are sometimes called "exposed" fifths/octaves, and both of these terms demonstrate a key feature about the part-writing error. Obviously, they must move in similar motion, but the term "exposed" highlights the fact that these must occur between the outer voices. By having similar motion to a perfect interval in the outer voices, it creates the impression of a parallel perfect interval. Most importantly, the leap in the soprano typically creates a poor soprano line in which the melody outlines/implies an unintentional harmony. In the example above, if you sing the melody line without the harmony it outlines A minor instead of C major.