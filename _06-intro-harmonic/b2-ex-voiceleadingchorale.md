---
layout: chapter
title: Examples 6b - Voice-leading Considerations in Chorale-style Harmony
abc: true
---

**Each measure of this first example is a two-voice version of the same two diatonic harmonies. Which two harmonies? What are the Roman numerals and inversion figures for each measure? Is there more than one option for any of the harmonies? Do any particular chord members seem more important than the others? Do any of these measures sound "weaker" than the others?**

{% capture ex1 %}X:1
T:Implied harmonies from two voices
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
Bc|| FE|| de|| Bc|| GE|| GG|]
V:2 clef=bass
"M3"G,"P8"C,|| "m7"G,"M3"C,|| "P5"G,"M3"C,|| "+4"F,"m6"E,|| "m6"B,,"M3"C,|| "M2"F,"m3"E,|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**The next example adds an additional pitch to each of the measures from the previous example. Which of these "new" notes belong to the chords that you assigned in the previous example? After reviewing your knowledge of approaching dissonances from second-species counterpoint, do the chord tones and non-chord tones follow any specific types of motion?**

{% capture ex2 %}X:2
T:Chord skips and passing/neighbor non-chord tones
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
Bc|| F/2D/2E|| d/2f/2e|| Bc|| G/2F/2E|| G/2A/2G|]
V:2 clef=bass
"M3"G,/2"M6"D,/2"P8"C,|| "m7"G,/2"P5"G,/2"M3"C,|| "P5"G,/2"m7"G,/2"M3"C,|| "+4"F,/2"M6"D,/2"m6"E,|| "m6"B,,/2"d5"B,,/2"M3"C,|| "M2"F,/2"M3"F,/2"m3"E,|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**The suspension is another type of non-chord tone. Each of the measures in the next example are grouped in pairs to demonstrate how suspensions are formed. The first measure is a simple two-voice harmony from the examples above, but the next measure adds a suspension to that framework. How would you define a suspension? What are the three parts of any suspension? How do we determine the labels (i.e. numbers after the word *sus*)?**

{% capture ex3 %}X:3
T:Suspensions
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
FE| F-"sus4-3"F/2E/2|| dc|| d-"sus9-8"d/2c/2|| GE|| GE|]
V:2 clef=bass
G,C,| G,C,|| G,C,| G,C,|| D,C,|| D,-"sus2-3"D,/2C,/2|]{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

**Our final voice-leading considerations arise when adding inner voices to our soprano-bass counterpoint. In the following example, each staff system highlights a different voicing error. Compare the correct measures to the incorrect measures to come up with descriptions of the first two basic voicing rules of *doubling* and *spacing*. Because *range* is a simple maximum and minimum, I have listed conservative estimates for each voice part. These can vary widely depending on the skill level of the intended performers but will be sufficient for our early exercises in part-writing.**

{% capture ex4 %}X:4
%%staffsep75%%
T:Voicing four-part harmony
M:2/4
L:1/2
K:C
V:1
"Doubling"[cE] [GE] [eE] [cE]|| [_BE] [cE] [_BE] [_BE] [_BE]|]
"Spacing "[cE] "(Range is ignored for this"[cE] "example)"[c'E] [c'e] [c'e]|]
"Conservative Ranges"[Cg]| [G,d]| x| x|]
w:soprano alto
V:2 clef=bass
[C,G,] [C,G,] [C,G,] [C,C]|| [C,G,] [C,_B,] [C,E,] [C,_B,] [G,,G,]|]
w:Good Good Bad Good Good Good Bad Bad Bad
[C,G,] [C,,G,] [C,G,] [C,G,] [C,G]|]
w:Good Good Bad Bad Good
x| x| [GC,]| [DE,,]|]
w:tenor bass{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}