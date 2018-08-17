---
layout: chapter
title: Examples 4b - Compound Meters
abc: true
---

Using the following examples, determine:
- the defining characteristic of all *compound* meters
- what the top and bottom numbers mean in a compound time signature
- what *duple*, *triple*, and *quadruple* mean when describing a compound meter
- "theoretically ideal" beaming in compound meters 
- a list of common meters in *compound duple*, *compound triple*, and *compound quadruple*
- the common beat-counting system that we'll be using in this course (written in the "Compound Quadruple" example)
- how to decide whether 3/4 (or 3/8, 3/16, etc.) is a simple or compound meter

{% capture ex1 %}X:1
T:Common examples of compound duple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:6/8
L:1/8
K:C
G3 GGG | G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:6/4][L:1/4] G3 GGG | G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:6/16][L:1/16] G3 GGG | G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:6/32][L:1/32] G3 GGG | G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

{% capture ex2 %}X:2
T:Common examples of compound triple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:9/8
L:1/8
K:C
G3 GGG G2G| (2GG G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:9/4][L:1/4] G3 GGG G2G| (2GG G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:9/16][L:1/16] G3 GGG G2G| (2GG G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:9/32][L:1/32] G3 GGG G2G| (2GG G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

{% capture ex3 %}X:3
T:Common examples of compound quadruple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:12/8
L:1/8
K:C
G3 GGG G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2 G/2GGG/2 GGG||
w:1 2 la li 3 li 4 & 1 to la ta li ti 2 to la li ti 3 to ta ti 4 la li
[M:12/4][L:1/4] G3 GGG G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2 G/2GGG/2 GGG||
[M:12/16][L:1/16] G3 GGG G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2 G/2GGG/2 GGG||
[M:12/32][L:1/32] G3 GGG G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2 G/2GGG/2 GGG||{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## The problem with 3

Use the MIDI player to listen to the following two examples. Even though they are identical excerpts, one thing has been altered in the second example. What was altered, and does it change your perception of whether the tune is simple or compound? Provide your final classifications for both examples.

{% capture ex4 %}X:4
T:Amelia's Waltz
M:3/4
K:D
Q:1/4=100
L:1/8
A,|"D"D3 E D2|"D"D2 F3 E|"Bm"D2 F2 BF|"F#m"A3 F A2|\
"G"B2 G3 B|"D"A2 F3 E|"Bm"D2 B,3 A,|"G"B,4 A,2 |
"D"D3 E D2|"D"D2 F3 E|"Bm"D2 F2 BF|"F#m"A3 F A2|\
"G"B3 c d2|"G"d2 e2 f2|"A"e2 B2 c2| "D"d6 ||{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

{% capture ex5 %}X:5
T:Amelia's Waltz
M:3/4
K:D
Q:1/4=180
L:1/8
A,|"D"D3 E D2|"D"D2 F3 E|"Bm"D2 F2 BF|"F#m"A3 F A2|\
"G"B2 G3 B|"D"A2 F3 E|"Bm"D2 B,3 A,|"G"B,4 A,2 |
"D"D3 E D2|"D"D2 F3 E|"Bm"D2 F2 BF|"F#m"A3 F A2|\
"G"B3 c d2|"G"d2 e2 f2|"A"e2 B2 c2| "D"d6 ||{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}