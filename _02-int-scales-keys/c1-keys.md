---
layout: chapter
title: Lesson 2c - Key Signatures
abc: true
---

As discussed in the previous topic, scales represent a pitch collection, centered around a tonic pitch. Because we can transpose these pitch collections to center around any pitch-class, we create twelve unique pitch centers--called *keys*--and even more if we include enharmonic equivalents. Because writing accidentals for many of these keys would be clunky and difficult to read, we use a system of key signatures to give the performer a simple way of knowing which pitches in the key are raised and lowered.

## Key signatures

The structure of key signatures relates to the very nature of diatonic harmony. This music is built around perfect intervals, although as we will see below, introducing one non-perfect interval to a series of perfect intervals can create the major scale and consequently diatonic tonality. Because of this non-perfect interval, key signatures follow a very simple pattern that can be reversed whether you are raising or lowering pitches.

### Goals for this topic

In the examples below, you will find sets of three keys. Use these to find:
- the order of sharps and flats
    - including any mnemonic devices to remember these
    - and the intervallic structure of the order of sharps and flats
- what differentiates *diatonic* and *chromatic* pitches
- a method for determining the *relative* and *parallel* minor keys from a major key
    - as well as the *relative* and *parallel* major keys from a minor key

### A caveat

Please note that any *scale* that shares a tonic note is considered to be one key. Even though this may contradict your intuitive thoughts, this means that G major and G minor are considered the same **key**! Instead, we call them *modes* of each other, not different keys. The explanation for this terminology is best left for once we have more tools to examine it, but for now, practice using the correct terminology to avoid a confusing "re-learning" moment later in the course.

### Keys that use sharps and the minor keys that are related to them

Use these examples to determine the order of sharps. Pay particular attention to which **scale degrees** are affected in each key as sharps are added. Is it the same scale degree in each key? How is this related to the tonic? If you continue the pattern, are you able to discern the name of the next key and which accidentals are added? You should also be able to determine the relationship between a major key and its parallel and relative minors.

{% capture ex1 %}X: 1
T:3 major scales that use sharps
M:4/4
L:1/8
K:G clef=bass
G,,A,, B,,C, D,E, F,G, ||[K:D] D,E, F,G, A,B, CD||[K:A] A,,B,, C,D, E,F, G,A,|]
w: G maj _ _ _ _ _ _ D maj _ _ _ _ _ _ A maj{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}


{% capture ex2 %}X: 2
T:3 natural minor scales that use sharps
T:Each of these minor keys is a *relative* minor to the major key listed in parentheses
M:4/4
L:1/8
K:G clef=bass
E,,F,, G,,A,, B,,C, D,E, ||[K:D] B,,C, D,E, F,G, A,B,||[K:A] F,,G,, A,,B,, C,D, E,F,|]
w: E min (G maj) _ _ _ _ B min (D maj) _ _ _ _ F-sharp min (A maj){% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}


{% capture ex3 %}X: 3
T:3 more natural minor scales
T:Each of these minor keys is a *parallel* minor to the major key listed in parentheses
M:4/4
L:1/8
K:Bb clef=bass
G,,A,, B,,C, D,E, F,G, ||[K:F] D,E, F,G, A,B, CD||[K:C] A,,B,, C,D, E,F, G,A,|]
w: G min (G maj) _ _ _ _ D min (D maj) _ _ _ _ _ _ A min (A maj){% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

### Keys that use flats and the minor keys that are related to them

Use these examples to determine the order of flats. Pay particular attention to which **scale degrees** are affected in each key as flats are added. Is it the same scale degree in each key? How is this related to the tonic? If you continue the pattern, are you able to discern the name of the next key and which accidentals are added? You should also be able to determine the relationship between a major key and its parallel and relative minors.

{% capture ex4 %}X: 4
T:3 major scales that use flats
M:4/4
L:1/8
K:Bb clef=bass
B,,C, D,E, F,G, A,B,|| [K:Eb] E,F, G,A, B,C DE|| [K:Ab] A,,B,, C,D, E,F, G,A,|]
w: B-flat maj _ _ _ _ _ E-flat maj _ _ _ _ _ A-flat maj{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}


{% capture ex5 %}X: 5
T:3 natural minor scales that use flats
T:Each of these minor keys is a *relative* minor to the major key listed in parentheses
M:4/4
L:1/8
K:Bb clef=bass
G,,A,, B,,C, D,E, F,G,|| [K:Eb] C,D, E,F, G,A, B,C|| [K:Ab] F,,G,, A,,B,, C,D, E,F,|]
w: G min (B-flat maj) _ _ _ C min (E-flat maj) _ _ _ F min (A-flat maj){% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}


{% capture ex6 %}X: 6
T:3 more natural minor scales
T:Each of these minor keys is a *parallel* minor to the major key listed in parentheses
M:4/4
L:1/8
K:Db clef=bass
B,,C, D,E, F,G, A,B,||[K:Gb] E,F, G,A, B,C DE||[K:Cb] A,,B,, C,D, E,F, G,A,|]
w: B-flat min (B-flat maj) _ _ E-flat min (E-flat maj) _ _ A-flat min (A-flat maj)(A maj){% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

## Conclusions

Your ultimate goal for key signatures should be the ability to instantly recall all key signatures from memory. However, we also can use the examples above to try to understand "how" key signatures are related to keys.

The division of the octave into twelve parts is our brains' interpretations of a simple mathematical phenomenon. When the frequency of a soundwave doubles, our brains hear those two frequencies as sharing some fundamental commonality, so it interprets those two pitches as the "same" but separated by an octave. Therefore, octaves always have a 2:1 ratio. (A110, A220, A440, and A880 are all `A` separated by octaves.) The next two simplest ratios are a 3:2 ratio and a 4:3 ratio, which create a perfect 5th and a perfect 4th respectively. 

Not only does your brain's interpretation of these ratios create the ideas of consonance and dissonance, it is also the reason we divide the octave into twelve instead of a "simpler" number such as ten. You can observe this effect most easily in the circle of fifths. If you begin on any pitch-class and begin moving by ascending perfect 5ths (or 4ths), you will find yourself back at the beginning after cycling through all twelve pitch-classes. We call this the circle of fifths.

C - G - D - A - E - B - F-sharp - C-sharp - G-sharp - D-sharp/E-flat - B-flat - F - *C*

Perhaps more important for our discussion, though, is what happens when we introduce a non-perfect 5th into the pattern. If we begin on a pitch-class and begin moving through ascending perfect 5ths, each new perfect 5th will move us to a *new letter*. After the first six letters, we begin adding accidentals and then repeating letters as seen in the circle of fifths above. If, however, we alter the last perfect 5th by a half-step to create a diminished 5th, we can break the pattern and shortcut to the end with one final perfect 5th. 

C (P5) G (P5) D (P5) A (P5) E (P5) B (d5) *F* (P5) C

This slight change creates the necessary tension for keys to function diatonically, so diatonic function could be described as a slight imperfection on an otherwise perfect series of intervals. 

This can be further shown by looking at the naturally occuring intervals if we write diatonic 5ths above the notes of a major scale.

{% capture ex7 %}X:7
%%staffsep 100%
T:Diatonic 5ths in the Major Scale
M:C
L:1/2
K:C
[CG] [DA]| [EB] [Fc]| [Gd] [Ae]| [Bf] [cg]||
w:P5 P5 P5 P5 P5 P5 d5 P5{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

When we begin exploring harmonic function in Unit 6, the tension provided by the one non-perfect 5th and its subsequent release will become obvious.

Key signatures reflect the importance of the one non-perfect interval. When studying the consecutive key signatures, you should focus on *which scale degree* is changed between consecutive keys. This will likely lead to two basic principles:
- When a sharp is added to a key, it always raises the 7th scale degree in the new key, thereby creating the new `ti`.
    - You can find the new `do` by going up a half-step from the new `ti`.
- When a flat is added to a key, it always lowers the 4th scale degree in the new key, thereby creating the new `fa`.
    - You can find the new `do` by going down a P4 (or up a P5) from the new `fa`.

### Order of sharps and flats

This directly reflects how diatonic function works; if we change *where* the one non-perfect 5th occurs, we change the key. From this we can determine a permanent order of flats or sharps, which cycles to the beginning if you need to continue raising or lowering pitches. Unsurprisingly, these orders follow the circle-of-fifths and play a critical role in defining diatonic function and key signatures. Note that the two orders are simply reversed sequences of each other. 
- Order of sharps: F - C - G - D - A - E - B
- Order of flats: B - E - A - D - G - C - F