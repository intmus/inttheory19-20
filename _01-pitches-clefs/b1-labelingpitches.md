---
layout: chapter
title: Lesson 1b - Labeling Pitches
---

## Accidentals

This course assumes that you have a basic knowledge of how to raise and lower pitches in standard music notation. If you need to review proper usage of accidentals, please refer to the *Further Reading* section under [Lesson 1b]({{ site.baseurl }}/1b3-tx-labelingpitches.html).

## Labeling Octaves

When labeling pitches, we also need a way to refer to specific octaves or registers. We will be using the system used by the International Standard Organization (ISO). In this system, middle C is labeled as C4. 

## Enharmonic Equivalence

At its core, enharmonic equivalence is an easy concept: When two pitches sound the same -- meaning that they share identical wavelength frequencies -- but have different note names (i.e. letters), they are considered to be enharmonically equivalent. All pitches that are enharmonic equivalents create a *pitch-class*, so there are twelve possible pitch-classes. Every pitch has multiple enharmonic equivalents, but some are used less frequently due to the necessity for uncommon accidentals such as double-sharps and double-flats. Review the examples under Lesson 1b to make sure that you understand  the less common examples. Note that all but one pitch-class has at least three enharmonic equivalents when using the five most-common accidentals: *naturals, flats, sharps, double-flats, and double-sharps*. (The remaining pitch-class only has two possible enharmonic equivalents without creating accidentals that exist only in theory such as triple-sharps or triple-flats.)

## Goals for this topic

Using the examples below, determine:
- three *enharmonic equivalents* for every *pitch-class*
    - one *pitch-class* only has two enharmonic equivalents if only using the five most common accidentals
- where C4 lies in each clef
- what the numeral refers to in the ISO system for labeling octaves
- how these numerals interact with letters

## Accidentals and Enharmonic Equivalence

{% capture ex1 %}X:1
T:Enharmonic Equivalence
T:Each measure contains two notes that are enharmonically equivalent.
M:2/4
L:1/4
K:C
V:1 name="Treble Clef"
_B ^A |f ^e |^^E ^F |]
V:2 name="Alto Clef" clef="alto"
^G _A |B, _C |^^G, A,|]
V:3 name="Tenor Clef" clef="tenor"
^F, _G, |F, ^E, |D, ^^C,|]
V:4 name="Bass Clef" clef="bass"
_D, ^C, |^B,, C, |D, __E,|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Labeling Octaves and Clef Relationships

{% capture ex2 %}X:2
T:Pitches and Clefs
M:C
L:1/4
K:C
V:1 name="Treble Clef"
e a f b g ^c B|]
w: E5 A5 F5 B5 G5 C#5 B4
V:2 name="Alto Clef" clef=alto
E A F B G ^C B,|]
w: E4 A4 F4 B4 G4 C#4 B3
V:3 name="Tenor Clef" clef=tenor
E, A, F, B, G, ^C, B,,|]
w: E3 A3 F3 B3 G3 C#3 B2
V:4 name="Bass Clef" clef=bass
E, A, F, B, G, ^C, B,,|]
w: E3 A3 F3 B3 G3 C#3 B2{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}
