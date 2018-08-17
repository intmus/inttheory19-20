---
layout: chapter
title: Examples 2a - Identifying and Labeling Intervals
abc: true
---

## Goals for this topic

Using the examples below, develop a simple explanation for how we find each of the following:
- the *size* of the interval between two pitches as represented by a numeral
- the *quality* of the interval as represented by the labels *perfect, major, minor, diminshed, and augmented*
- which *sizes* can use which *qualities* as well as the hierarchy of *qualities* for each *size*
- *chromatic* versus *diatonic* intervals
- *simple* versus *compound* intervals and how this affects classifying of *quality* and *size*
- how the *size* and *quality* change when the upper and lower pitches of an interval are inverted

In the examples, each interval represents the concept stated at the beginning of its staff, but each measure also has an important intervallic relationship to the measures above and below it.

### Important concepts

*Qualities*: P = perfect, M = major, m = minor, A = augmented, d = diminished

*Diatonic intervals in the examples below*
- Major 3rd from the harmonic intervals
- Major 2nd from the melodic intervals
- Major 6th from simple intervals
- Perfect 15th and major 10th from the compound intervals
- Minor 6th from the inversion pairs

*Chromatic intervals in the examples below*
- All other intervals

{% capture ex1 %}X:1
T:Intervals
M:1/4
L:1/4
K:C
V:1 name=Harmonic
[_BA]| [ce]| [_e_B]| [D_A]| [^dF]| [CB]| [^f^F]||
w: m2 M3 P4 d5 A6 M7 P8
V:2 name=Melodic
B/2A/2| c/2^e/2| e/2_B/2| _D/2_A/2| F/2_d/2| ^C/2B/2| f/2^F/2||
w:M2 _ A3 _ A4 _ P5 _ m6 _ m7 _ d8 
V:3 name=Simple
[_B^A]| [^c_e]| [_eB]| D/2^A/2| d/2F/2| [C__B]| [^fF]||
w: d2 d3 d4 A5 _ M6 _ d7 A8
V:4 name=Compound clef=bass
[^B,A,,]| [C,_E]| [_E_B,,]| _A,/2_D,,/2| F,,/2_D/2| ^B,/2C,,/2| [FF,,]||
w:A9 m10 P11 P12 _ m13 _ A14 _ P15||
V:5 name=Inversions
[_B,A]| [cE]| [_E_B]| [d_A]| [_df]| [Bc]| [^f^F]||
w: M7 m6 P5 A4 M3 m2 P8{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}