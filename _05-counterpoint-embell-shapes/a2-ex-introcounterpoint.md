---
layout: chapter
title: Examples 5a - Introduction to Counterpoint
abc: true
---

To begin studying basic counterpoint, we need to establish the fundamental concepts of intervallic consonance, intrevallic dissonance, and the types of contrapuntal motion.

From the following examples, determine:
- which intervals are considered consonant and dissonant
    - which consonances are considered perfect and imperfect
- what elements are necessary to create contrapuntal motion
- a simple way to describe each of the four types of contrapuntal motion: parallel, contrary, static, and oblique

## Consonant and dissonant intervals

The next two examples show an example of each possible perfect and imperfect consonance. All other intervals are considered dissonant. Make a list of perfect consonances, imperfect consonances, and dissonances. Do any of the dissonances surprise you? If so, discuss why.

{% capture ex1 %}X:1
T:Perfect consonance examples
M:4/4
L:1
K:C
V:1
_B|| G|| _A,|| _A|| ^F|| A|| ^G||
V:2 clef=bass
_B,|| C,|| _A,|| _D|| ^F,,|| D,|| ^G,||{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

{% capture ex2 %}X:2
T:Imperfect consonance examples
M:4/4
L:1
K:C
V:1
G|| E|| _C|| __B|| ^D|| G|| ^B||
V:2 clef=bass
_B,|| C,|| _A,|| _D|| ^F,,|| E,|| ^G,||{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Classifying types of contrapuntal motion

{% capture ex3 %}X:3
T:Types of contrapuntal motion
T:Each measure is an individual example. Do not consider motion between measures.
M:4/4
L:1/2
K:C
V:1
_BF|| Ge|| C_E|| _AG||
w:parallel
_Bf|| Ge|| c_A|| _AG||
w:contrary
_B_B|| GG|| _E_E|| _A_A||
w:static
_B_B|| Ge|| _E_E|| _AG||
w:oblique
_BA|| Ge|| _E_A|| _AG||
w:similar
V:2 clef=bass
_B,F,|| C,A,|| _A,C|| DC||
_B,F,|| C,B,,|| _A,C|| DE||
_B,_B,|| C,C,|| C,C,|| DD||
_B,F,|| C,C,|| _A,C|| DD||
_B,F,|| C,D,|| _A,C|| D_B,||{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}