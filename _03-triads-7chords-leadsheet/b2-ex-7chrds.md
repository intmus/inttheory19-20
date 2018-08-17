---
layout: chapter
title: Examples 3b - Seventh Chords
abc: true
---

## Goals for this topic

Using the examples below:
- determine what role each chordal member (e.g. root, third, fifth, etc.) plays in determining the quality of a seventh chord
    - How does this relate to triads?
- find all six intervals between the chordal members of a root-position seventh chord for each of the following chord qualities:
    - *major seventh, minor seventh, dominant seventh, half-diminished, fully-diminished*
- explain what each part of the the alternate names for each seventh chord
    - *Major major* (MM), *major minor* (Mm), *minor minor* (mm), *diminished minor* (dm), and *diminished diminshed* (dd)
- find the following interval sizes between chordal members of a seventh chord (Hint: This may involve moving some chord members up or down an octave)
    - seconds (1)
    - thirds (3)
    - fourths (2)
    - fifths (2)
    - sixths (3)
    - sevenths (1)
- relate these intervals to our system for labeling seventh-chord inversions
    - provide inversion figures for root-position, first-inversion, second-inversion, and third-inversion seventh chords
- be able to explain how to turn any inverted and/or open-voiced seventh chord into a root-position seventh chord in a closed voicing

## Seventh chord qualities

{% capture ex1 %}X:1
T:Seventh chord qualities
M:2/4
L:1/2
K:C
"Major seventh (MM)"[D^FA^c]| "Dominant seventh (Mm)"[D^FAc]| "Minor seventh (mm)"[DFAc]| "half-diminished (dm)"[DF_Ac]| "fully-diminished (dd)"[DF_A_c]||{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Seventh chord inversions

Because ABC notation is not capable of using superscript, the inversion figures in the next example are notated as fractions. If you were to write these by hand or use custom notation software, you would notate all inversion figures using superscript. For example, a dominant seventh chord would be written as Mm<sup>7</sup>

{% capture ex2 %}X:2
T:Seventh chord inversions
T:1) Inversion names are listed above the staff
T:2) Inversion figures are listed below the staff
T:---------
M:2/4
L:1/2
K:C
"Root position"[D^FAc]| "First-inversion"[d^FAc]| "Second-inversion"[d^fAc]| "Third-inversion"[D^FAC]||
w:7~(7/5/3) 6/5~(6/5/3) 4/3~(6/4/3) 4/2~(6/4/2){% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Seventh chord voicings

{% capture ex3 %}X:3
T:Seventh chord voicings
M:2/4
L:1/2
K:C
V:1
"Closed"[dFAc]| "Closed"[Ac]| "Open"[dF]| "Open"[dFAC]|
V:2 clef=bass
z| [DF]| [A,,C]| [D,,D,]|{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}