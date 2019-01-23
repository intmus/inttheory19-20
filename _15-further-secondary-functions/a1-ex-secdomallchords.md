---
layout: chapter
title: 15a Examples - More Secondary Dominant Functions
abc: true
---

## Secondary dominant functions for chords other than V

At the end of the Unit 14a, you completed the process of transforming a ii<sup>7</sup> chord into V<sup>7</sup>/V. In the final instructions, I suggested that you try altering chords other than the ii chord to see if you could create secondary dominants for chords other than V. 

Let's work through this in the following example. Harmonize the progression in four-part harmony; then alter chords to create secondary dominant chords. How many options are possible if you only alter existing chords? Assuming that you created a secondary dominant chord, try changing it into secondary leading-tone chord.

{% capture ex1 %}X:1
T:Creating secondary dominant functions
M:4/4
L:1/2
K:C
V:1
[cE] [c]| [d] [d]| [c2]|]
V:2 clef=bass
[C,G,] [A,,]| [D,] [G,,]| [C,2]|]
w:C:I vi ii7 V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

### Conclusions

The previous example has multiple chords that are connected by root movement of a descending P5, which is the reason that it provides such obvious opportunities for secondary dominant chords. In the example below, you can see the secondary chords next to their closely related diatonic counterparts. By placing them next to each other, you can see not only how similar the secondary dominant chords are to their diatonic counterparts, but it is also easy to see that they share a function with the chord with the chord that precedes them. This includes a secondary dominant chord that we had not looked at yet: V<sup>7</sup>/ii. You will notice that this chord is as closely related to the vi chord as the V<sup>7</sup>/V was related to the ii chord. 

{% capture ex4 %}X:4
T:Possible secondary dominant functions
M:4/4
L:1/2
K:C
Q:1/4=60
V:1
[cE] [c/2G][^c/2G]| [d/2F][d/2^F] [dG]| [c2E]|]
V:2 clef=bass
[C,G,] [A,,/2A,][A,,/2A,/2]| [D,/2C][D,/2C] [G,,B,]| [C,2G,]|]
w:C:I vi7 V7/ii ii7 V7/V V I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

## Tonicizing chords other than V

In music, secondary dominant functions can appear anywhere the composer would like to emphasize a chord or prolong its function. *Any major or minor diatonic chord can be tonicized.* 

For secondary leading-tone chords:
- For minor chords, you may use a V, a V<sup>7</sup>, a vii<sup>o</sup>, or a vii<sup>o7</sup>. You may not use a vii<sup>&oslash;7</sup> (half-diminshed seventh chord) because the chordal seventh will sound strange.
- For major chords, you may use a V, a V<sup>7</sup>, a vii<sup>o</sup>, *vii<sup>&oslash;7</sup>, or a vii<sup>o7</sup>*. Notice that you may use either a fully diminished or half-diminished seventh chord, even though the half-diminished chord is the diatonic vii chord in a major key. For tonicizing a major chord, fully diminished chords actually appear more often than half-diminished chords.

## Altering root movement

The following example uses a IV chord instead of a ii chord, and this changes the root movement for much of the passage. Try adding secondary dominant or leading-tone chords in the spots marked with an "x". The note in the bass is just a placeholder, so please feel free to change it. You should  experiment with various inversions to see if you can create more melodic bass lines as well.

{% capture ex2 %}X:2
T:Inserting secondary dominant functions 
T:into various root movement patterns
M:4/4
L:1/2
K:C
Q:1/4=80
V:1
[cE]x| [c]x| [c]x| [d2]| [c2]|]
V:2 clef=bass
[C,G,][C,]| [A,,][A,,]| [F,,][F,,]| [G,,2]| [C,2]|]
w:C:I x vi x IV x V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

Which chords created the smoothest voice-leading? Were you able to create a harmonization that has good voice-leading while also sounding convincing?

### Conclusions

Your first option is to use root position secondary dominant functions in each spot creating a progression that would look something like this:

{% capture ex5 %}X:5
T:Inserting secondary dominant functions 
T:in root positions
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
[cE][dE]| [cE][cE]| [cF][d^F]| [d2F]| [c2E]|]
V:2 clef=bass
[C,G,][E,^G,]| [A,,A,][C,_B,]| [F,,A,][D,C]| [G,,2B,]| [C,2G,]|]
w:C:I V7/vi vi V7/IV IV V7/V V7 I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

The voice-leading is easy to determine as long as you follow the standard resolutions for the tendency tones in each secondary dominant chord. In this progression you will have to alternate between complete and incomplete chords to avoid objectional parallels.

## Secondary functions used to create a smooth bass line

You probably noticed in the previous example that the bass line was disjunct, but the other lines had smooth voice-leading. By using inversions of secondary dominant chords and/or secondary leading-tone chords, you can create much more melodic bass lines. Take your previous harmonization (or use the clean version below), and alter it by inserting secondary dominant functions at each spot marked with an x. You should be able to create an entirely stepwise bass line. Remember that if you need to change the openness of a chord's voicing, it can be helpful to have one voice jump a fourth by moving from the third of the first chord to the third of the second chord.

{% capture ex3 %}X:3
T:Creating a step-wise bass line
M:4/4
L:1/2
K:C
Q:1/4=80
V:1
[cE][d]| [e][e]| [f][d]| [d2]| [c2]|]
V:2 clef=bass
[C,G,][B,,]| [A,,][G,,]| [F,,][^F,,]| [G,,2]| [C,2]|]
w:C:I x vi x IV x V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

Are there multiple options for any of the chords? Where does the soprano force difficult decisions and resolutions?

### Conclusions

{% capture ex6 %}X:6
T:Inserting secondary dominant functions 
T:in root positions
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
[cE][dE]| [cE][cE]| [cF][d^F]| [d2F]| [c2E]|]
V:2 clef=bass
[C,G,][E,^G,]| [A,,A,][C,_B,]| [F,,A,][D,C]| [G,,2B,]| [C,2G,]|]
w:C:I V7/vi vi V7/IV IV V7/V V7 I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

