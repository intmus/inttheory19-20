---
layout: chapter
title: Examples 3a - Triads
abc: true
---

## Goals for this topic

Using the examples below:
- determine what role each chord member -- root, third, and fifth -- plays in determining the quality of a triad
- find all three intervals contained in a *root-position* triad for each chord quality
- find the rest of the interval *sizes* beteween chord members of a triad (Hint: This may involve moving some chord members up or down an octave)
    - thirds (2)
    - fourth (1)
    - fifth (1)
    - sixths (2)
- relate these interval sizes to our system for labeling triad inversions
    - provide inversion figures for root position, first-inversion, and second-inversion triads
- be able to explain how to turn any inverted and/or open-voiced triad into a root-position triad in a closed voicing

## Triad qualities

{% capture ex1 %}X:1
T:Triad qualities
M:2/4
L:1/2
K:C clef=bass
"Augmented (A)"[_B,,D,^F,]| "Major (M)"[_B,,D,F,]| "Minor (m)"[_B,,_D,F,]| "diminished (d)"[_B,,_D,_F,]||{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Triad inversions

Because ABC notation is not capable of using superscript, the inversion figures in the next example are notated as fractions. If you were to write these by hand or use custom notation software, you would notate all inversion figures using superscript. For example, a major chord in first inversion would be written as M<sup>6</sup>

{% capture ex2 %}X:2
T:Triad inversions
T:1) Inversion names are listed above the staff
T:2) Inversion figures are listed below the staff
T:---------
M:2/4
L:1/2
K:C
"Root-position"[_Bdf]| "First-inversion"[_BDF]| "Second-inversion"[_BdF]||
w:5/3 6~(6/3) 6/4{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Triad voicings

{% capture ex3 %}X:3
T:Triad voicings
M:2/4
L:1/2
K:C
V:1
"Closed"z| "Closed"[_BF]| "Open"[_Bf]| "Open"[fdF]|
V:2 clef=bass
[_B,,D,F,_B,]| [D]| [_B,,D]| [F,_B,]|{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}