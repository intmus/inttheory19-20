---
layout: chapter
title: Examples 2c - Key Signatures
abc: true
---


## Goals for this topic

In the examples below, you will find sets of three keys. Use these to find:
- the order of sharps and flats
    - including any mnemonic devices to remember these
    - and the intervallic structure of the order of sharps and flats
- what differentiates *diatonic* and *chromatic* pitches
- a method for determining the *relative* and *parallel* minor keys from a major key
    - as well as the *relative* and *parallel* major keys from a minor key

## A caveat

Please note that any *scale* that shares a tonic note is considered to be one key. Even though this may contradict your intuitive thoughts, this means that G major and G minor are considered the same **key**! Instead, we call them *modes* of each other, not different keys. The explanation for this terminology is best left for once we have more tools to examine it, but for now, practice using the correct terminology to avoid a confusing "re-learning" moment later in the course.

## Keys that use sharps and the minor keys that are related to them

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

## Keys that use flats and the minor keys that are related to them

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
{% include abc-example.html number="3" abc=ex3 %}