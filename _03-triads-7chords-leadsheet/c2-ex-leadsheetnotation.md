---
layout: chapter
title: Examples 3c - Leadsheet Notation
abc: true
---

Using the examples below:
- determine the standard methods for labeling all chord qualities
    - match these to our current labels (e.g. Major minor (Mm) chords are the same as a dominant seventh chord which is then labeled as...)
- determine the method for denoting inversions
    - match these inversions to their corresponding inversion figures for both triads and seventh chords
- figure out the difference between using *sub* and *add* in your leadsheet notation

## Labeling triads

{% capture ex1 %}X:1
T:Leadsheet notation of triads
M:2/4
L:1/2
K:C clef=bass
"Bb+ (or Bbaug)"[_B,,D,^F,]| "Bb"[_B,,D,F,]| "Bbmin (or Bb-)"[_B,,_D,F,]| "Bbdim (or Bbo)"[_B,,_D,_F,]||{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Labeling seventh chords

{% capture ex2 %}X:2
T:Leadsheet notation of seventh chords
T:Everything other than the chord's root is typically written in superscript
T:---------------
M:2/4
L:1/2
K:C
"Dmaj7"[D^FA^c]| "D7"[D^FAc]| "Dm7 (or Dmin7)"[DFAc]| "D\/o7 or Dm7(b5)"[DF_Ac]| "Do7(or Ddim7)"[DF_A_c]||
w: major~seventh dominant~seventh minor~seventh half~diminished fully~diminished{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Labeling inversions

{% capture ex3 %}X:3
TT:Inversions in leadsheet notation
T:---------------
M:2/4
L:1/2
K:C
"D7"[D^FAc]| "D7/F#"[d^FAc]| "D7/A"[d^fAc]| "D7/C"[D^FAC]|
w:root~position first~inversion second~inversion third~inversion
w:7~(7/5/3) 6/5~(6/5/3) 4/3~(6/4/3) 4/2~(6/4/2){% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Extensions and Using Sub vs. Add

{% capture ex4 %}X:4
T:Labeling extensions in leadsheet notation
T:---------------
M:2/4
L:1/2
K:C
"D13"[D^FAcegb]| "D6/9"[D^FAeB]^c/2| "Dsus7"[DGAc]| "D9 or D7(add9)"[D^FAce]| "Dm7(add b5)"[DF_a=Ac]| "Dm7(sub b5)"[DF_Ac]||
w:_ _ implied{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}