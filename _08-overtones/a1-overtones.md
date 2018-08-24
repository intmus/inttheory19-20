---
layout: chapter
title: Lesson 8a - The Overtone Series
abc: true
---

The overtone series occurs naturally in non-synthetic tone production. When a person sings, the overtone series is present above every pitch. When any woodwind, string, or brass instrument creates a pitch, the overtone series is present above every pitch. Perhaps even more importantly for our discussions, the mathematics behind creating the overtone series are not only fascinating, but also explain the fundamentals of Western harmony 
- Why do we divide the octave into twelve parts?
    - The overtone series
- Why do we hear some intervals as consonant and others as dissonant?
    - The overtone series
- How do we determine if an interval is in tune?
    - The overtone series
- Why do we use a harmonic system based on perfect intervals and thirds?
    - The overtone series

To put it succinctly, the overtone series explains why music evolved as it did.

**The overtone series is a series of intervals above a given pitch. We call the lowest pitch the *fundamental*, and every tone above it is considered an *overtone*. In the example below, `C2` is the fundamental, `C3` is the first overtone, `G3` is the second overtone, and so on.**

**The other system used to discuss the overtone series is label each overtone as a *partial*. In this system, the fundamental is considered equal to all other tones, so it is labeled as the first partial. In the example below, `C2` is the first partial, `C3` is the second partial, `G3` is the third partial, and so on.**

**For the example below, determine the numbering for each of these notes as both overtones and partials. Then practice transposing the entire series to other pitches.**

{% capture ex1 %}X:1
T:The overtone series
M:2/2
L:1/2
K:C
V:1
x x x x E G _B c d e ^f g|]
V:2 clef=bass
C,,C,G,C x x x x x x x x|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Bernstein on the importance of the overtone series

Next, please watch this wonderful video of Leonard Bernstein explaining how the overtone series explains harmony's evolution throughout the ages. Keep in mind that each evolutionary step he discusses adds another partial from the overtone series.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Gt2zubHcER4" frameborder="0" allowfullscreen></iframe>

### The Physics of Music

Because class time was running short and the students were already familiar with key signatures, we did not spend much time figuring out the basics of key signatures. Instead, we used the examples on the previous page to try to understand "how" key signatures effect keys.

The division of the octave into twelve parts is our brains' interpretations of a simple mathematical phenomenon. When the frequency of a soundwave doubles, our brains hear those two frequencies as sharing some fundamental commonality, so it interprets those two pitches as the "same" but separated by an octave. Therefore, octaves always have a 2:1 ratio. (A110, A220, A440, and A880 are all `A` separated by octaves.) The next two simplest ratios ares a 3:2 ratio and a 4:3 ratio, which create a perfect 5th and a perfect 4th respectively. 

The importance of these ratios is most easily observed in the circle of fifths. If you begin on any pitch-class and begin moving by ascending perfect 5ths (or 4ths), you will find yourself back at the beginning after cycling through all twelve pitch-classes. We call this the circle of fifths.

C - G - D - A - E - B - F-sharp - C-sharp - G-sharp - D-sharp/E-flat - B-flat - F - *C*

Perhaps more important for our discussion, though, is what happens when we introduce a non-perfect 5th into the pattern. If we begin on a pitch-class and begin moving through ascending perfect 5ths, each new perfect 5th will move us to a *new letter*. After seven letters, we will begin repeating letters but adding accidentals to them as seen in the circle of fifths above. If, however, we alter the last perfect 5th by a half-step to create a diminished 5th, we can break the pattern and shortcut to the end. 

C - G - D - A - E - B - *F* - C

This slight change creates the necessary tension for keys to function diatonically, so diatonic function could be described as a slight imperfection on an otherwise perfect series of intervals. 

This can be further shown by looking at the naturally occuring intervals if we write diatonic 5ths above the notes of a major scale.

{% capture ex1 %}X:1
%%staffsep 100%
T:Diatonic 5ths in the Major Scale
M:C
L:1/2
K:C
[CG] [DA]| [EB] [Fc]| [Gd] [Ae]| [Bf] [cg]||
w:P5 P5 P5 P5 P5 P5 d5 P5{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

When we begin exploring harmonic function in Unit 6, the tension provided by the one non-perfect 5th and its subsequent release will become obvious.

Key signatures reflect the importance of the one non-perfect interval. When studying the consecutive key signatures on the previous page, I asked the students to focus on *which scale degree* is changed between consecutive keys. The class came up with two rules:
- When a sharp is added to a key, it always raises the 7th scale degree in the new key, thereby creating the new `ti`.
- When a flat is added to a key, it always lowers the 4th scale degree in the new key, thereby creating the new `fa`. 

### Order of sharps and flats

This directly reflects how diatonic function works; if we change *where* the one non-perfect 5th occurs, we change the key. We did not need to spend time determining the order of sharps and flats, because the class was already familiar with this from previous courses. It did not surprise them that circle-of-fifths plays a critical role in defining diatonic function and key signatures. The two orders are simply the reverses of each other. 
- Order of sharps: F - C - G - D - A - E - B
- Order of flats: B - E - A - D - G - C - F


