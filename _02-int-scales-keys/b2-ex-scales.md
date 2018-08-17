---
layout: chapter
title: Examples 2b - Scales and Scale Degrees - Diatonic, Pentatonic, and Chromatic
abc: true
---

<!--  MUST ADD MODES BEFORE NEXT YEAR IN ORDER TO PREPARE MODE MIXTURE -->

## Goals for this topic:

Using the examples below, create definitions and/or simple explanations for:
- the intervallic pattern of the *major* scale and all forms of *minor* scales
- how major and minor *pentatonic* scales relate to the major and minor scales
- why *natural, melodic,* and *harmonic* minors are named as they are
- the names for each scale degree (i.e. tonic) as well as the corresponding numeral notation
    - how the names for each scale degree are derived (e.g. How are dominant and subdominant scale degrees related?)
- the Latin spelling for every solfege

## Instructions for these examples

The following examples demonstrate how the tune of *Happy Birthday* would be written if only using the notes from a particular scale. In all examples, scale degrees are numbered below each pitch as well as solfege using movable "do". Additionally,scale degrees are named above the pitches for the examples in major and melodic minor. When determining your pitch collections, pay particular attention to the differences of the sixth and seventh scale degrees.

### Major

(Because ABC notation does not support scale degrees, I have placed a `^` in front of each scale degree. In normal scale degree notation, the `^` would appear *above* the numeral for each scale degree, not before it.)

{% capture ex1 %}X: 1
%%staffsep 100%
T:Happy Birthday in G major
M:3/4
L:1/4
Q:1/4=90
K:G
"dominant"D/2>D/2| "submediant"E D "tonic"G| "leading tone"F2 D/2>D/2| E D "supertonic"A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol la sol do ti sol sol la sol re do sol sol
d "mediant"B G| F E "subdominant"c/2>c/2| B G A| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol mi do ti la fa fa mi do re do{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Minor scales

There are three forms of the minor scale, and each has a specific role. As you listen to these three melodies, only one of them will sound as if it has no surprising pitches. Once you have found the example that doesn't have a "surprise moment, consider the name of the mode. Does it give you some insight into why it sounds best playing this melody?

### Natural minor

{% capture ex2 %}X:2
%%staffsep 75%
T:Happy Birthday in G natural minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
D/2>D/2| E D G| F2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do te sol sol le sol re do sol sol
d B G| F E c/2>c/2| B G A| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol me do te le fa fa me do re do{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

### Harmonic minor

{% capture ex3 %}X:3
%%staffsep 75%
T:Happy Birthday in E harmonic minor
T:using the relative minor to G major
M:3/4
L:1/4
Q:1/4=90
K:G
B,/2>B,/2| C B, E| ^D2 B,/2>B,/2| C B, F| E2 B,/2>B,/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
B G E| ^D C A/2>A/2| G E F| E2|]
w:^5 ^3 ^1 ^#7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol me do ti le fa fa me do re do{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

### Melodic minor

When first determining your basic rules for melodic minor, you may want to choose to ignore 'le' in measure 6. That pitch serves a harmonic goal as part of a *cadence*, rather than a melodic function.

{% capture ex4 %}X:4
%%staffsep 100%
T:Happy Birthday in G melodic minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
"dominant"D/2>D/2| "submediant"E D "tonic"G| "leading tone"^F2 D/2>D/2| E D "supertonic"A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
d "mediant"B G| "subtonic"F HE "subdominant"c/2>c/2| B G A/4D/4"raised submediant"=E/4^F/4| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^5 ^#6 ^#7 ^1
w:sol me do te le fa fa me do re sol la ti do{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

### Major pentatonic

This is more of a teaching example rather than an actual modal shift, because the major scale and major pentatonic scales do not share the same type of relationship that the major and minor scales have. Certain scale degrees do not exist in the pentatonic scale, so it requires some "artistic license" to translate any tune that utilizes all seven scale degrees.

{% capture ex5 %}X:5
%%staffsep 75%
T:Happy Birthday in G major pentatonic
M:3/4
L:1/4
Q:1/4=90
K:G
D/2>D/2| E D G| D2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^6 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol la sol do sol sol sol la sol re do sol sol
d B G| D E d/2>d/2| B G A| G2|]
w:^5 ^3 ^1 ^5 ^6 ^5 ^5 ^3 ^1 ^2 ^1
w:sol mi do sol la sol sol mi do re do{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

### Minor pentatonic

The same can be stipulation applies to the minor pentatonic scale that applied to the major pentatonic scale. These scales do not correlate directly to their seven-note counterparts, so this is more of a re-imagining of Happy Birthday.

{% capture ex6 %}X:6
%%staffsep 75%
T:Happy Birthday in G minor pentatonic
M:3/4
L:1/4
Q:1/4=75
K:Bb
D/2>D/2| F D G| D2 D/2>D/2| F D B| G2 D/2>D/2|
w:^5 ^5 ^7 ^5 ^1 ^5 ^5 ^5 ^7 ^5 ^3 ^1 ^5 ^5
w:sol sol te sol do sol sol sol te sol me do sol sol
d c B| G HF c/2>c/2| B G F| G2|]
w:^5 ^4 ^3 ^1 ^7 ^4 ^4 ^3 ^1 ^7 ^1
w:sol fa me do te fa fa me do te do{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

### Chromatic scale

This final example is a heavily ornamented version of *Happy Birthday* that demonstrates every possible solfege as well as the correct resolution for all chromatic tones. This arrangement is still technically in G major, because strictly speaking, the chromatic scale is a collection of pitches and does not necessarily center around one tone. (Note that because ABC notation has no way to represent scale degrees, I was forced to omit the `^` that would normally appear above each scale degree and to use a `b` to represent a flat and a `#` to represent a sharp. Please forgive the misuses.)

{% capture ex7 %}X:7
%%staffsep 75%
T:Happy Birthday in G major (a la R. Strauss)
T:decorated to demonstrate all possible scale degrees and solfege
M:3/4
L:1/4
Q:1/4=75
K:G
"5"D/2>"#5"^D/2| "6"E/2"b6"_E/2 "5"D "1"G/2"#6"^E/2| "7"F2 (3"5"D/2"#4"^C/2"5"D/2| "6"E "5"=D "2"A/2"7"^F/2| "1"G2 "5"D/2>"5"D/2|
w:sol si la le sol do li ti sol fi sol la sol re ti do sol sol
"5"d/2"b5"_d/4"4"c/4 "3"B/2"b3"_B/4"2"A/4 "1"G| "7"F/2"b6"=F/2 "6"HE "4"c/2>"4"c/2| (3"3"B/2"#2"^A/2"3"B/2 "1"G/2"#1"^G/2 "2"=A/2"b2"_A/2| "1"G2|]
w:sol se fa me me re do ti te la fa fa mi ri mi do di re ra do{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}
