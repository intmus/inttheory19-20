---
layout: chapter
title: Examples 7c - Cadences
abc: true
---

In the following examples, determine:
- what chord progressions are associated with each type of cadence.
    - *perfect authentic cadence*
    - *imperfect authentic cadence*
    - *half cadence*
    - *deceptive cadence*
    - *plagal cadence*
    - *phrygian cadence*
- what chord functions (i.e. tonic, dominant, pre-dominant) are used in each type of cadence.
- what chord tones are present in the soprano and bass.
- what other musical elements affect the phrase ending.
- 
{% capture ex1 %}X:1
T:Standard cadences
T:Old hundredth psalm
M:4/4
L:1/4
Q:1/4=80
K:G
V:1
[GD]| [GD] [FD] [EB,] [DD]| [GB,] [AD] H[BD]
[BD]| [BD] [BG] [AF] [GG]| [cG] [BG] H[AF]
[GG]| [AF] [GB] [AF] [DG]| [EE] [FC] H[GB,]
[dD]| [BD] [GG] [AF] [cA]| [GB] [AF] H[GG]|| [G4C4]| [G4B,4]|]
V:2 clef=bass
[G,B,]| [G,B,] [A,D,] [E,G,] [B,,G,]| [E,G,] [D,F,] H[G,G,,]
w: _ _ _ _ _ _ _ IAC
[G,G,]| [G,G,] [G,D] [DD,] [E,B,]| [C,E] [G,,D] H[DD,]
w:  _ _ _ _ _ _ _ HC
[E,B,]| [D,D] [G,D] [D,D] [B,,G]| [C,G,] [D,A,] H[G,E,]
w: _ _ _ _ _ _ _ DC
[G,B,]| [G,G,] [E,B,] [D,D] [A,,E]| [D/2B,,/2]-[D/2C,/2] [D/2D,/2]-[C/2D,/2] H[G,,B,]|| [C,4E,4]| [G,,4D,4]|]
w: _ _ _ _ _ _ _ _ _ PAC _ plagal{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

{% capture ex2 %}X:2
T:Phrygian cadence
M:4/4
L:1
K:Eb
V:1
[FC]| [GD]|]
V:2 clef=bass
[CA,,]| [=B,G,,]|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}