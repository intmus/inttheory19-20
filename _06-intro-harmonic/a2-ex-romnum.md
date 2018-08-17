---
layout: chapter
title: Examples 6a - Roman Numerals in Harmonic Analysis
abc: true
---


Using the examples below, determine:
- what are the diatonic qualities of all triads in seventh chords in major and minor
  - If we consider these examples to be "diatonic", does every quality occur naturally or do some require accidentals?
  - What is the relationship between chords in major and minor?
- how Roman numerals are created and labeled
  - What information does each part  (e.g. Roman numeral, lower-case vs. upper-case, inversion figures, etc.) of the Roman numeral convey?
  - Are the inversion figures identical to the figured bass discussed in the class reading from this unit? If not, how do they differ?
  - How do leadsheet notation and Roman numerals differ in the information that they convey?


**Note that the ABC notation used in these examples has limitations on what kind of text can be entered. In the Roman numeral system, everything other than the Roman numeral itself should be written as superscript.**

{% capture ex1 %}X:1
%%staffsep 75%
T:Diatonic chord qualities with Roman numerals
M:C
L:1/2
K:C
"triads"[CEG]"in major" [DFA]| [EGB] [FAc]| [GBd] [Ace]| [Bdf] [ceg]||
w:I ii iii IV V vi viio I
"seventh"[CEGB]"chords"[DFAc]|"in major" [EGBd] [FAce]| [GBdf] [Aceg]| [Bdfa] [cegb]||
w:IM7 ii7 iii7 IVM7 V7 vi7 vii\/o7 IM7
[K:Eb]"triads"[CEG]"in minor"[DFA]| [EGB] [FAc]| [G=Bd] [Ace]| [=Bdf] [ceg]||
w:i iio III iv V VI viio i
[K:Eb]"seventh"[CEGB]"chords"[DFAc]| "in minor"[EGBd] [FAce]| [G=Bdf] [Aceg]| [=Bdfa] [cegb]||
w:i7 ii\/o7 IIIM7 iv7 V7 VIM7 viio7 i7{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

{% capture ex2 %}X:2
T:Altering Roman numerals for non-diatonic chord qualities
T:(Each of these examples is in the key of C.)
M:4/4
L:1
K:C
V:1
[Ace]| [A^ce]| [_Ace]| [Aceg]| [_Ac_eg]| [^D^F^A]|
w:  vi VI bVI vi7 bVIM7 #ii{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

{% capture ex3 %}X:3
%%staffsep 100%
T:Using inversion figures with Roman numerals
M:C
L:1/2
K:C
"triads"[CEG] [dFA]| [egB] [FAc]| [gBd] [ACE]| [BDF] [cEG]||
w:I ii6 iii6/4 IV V6 vi6/4 viio6/4 I6
"seventh"[CEGB]"chords"[dFAc]| [egBd] [FAcE]| [GBDF] [Aceg]| [BdfA] [cEGB]||
w:IM7 ii6/5 iii4/3 IVM4/2 V4/3 vi7 vii\/o4/2 IM6/5{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}