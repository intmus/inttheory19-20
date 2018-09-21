---
layout: chapter
title: Examples 6a - Roman Numerals in Harmonic Analysis
abc: true
---

To this point in the course, we have focused on essential elements -- the building blocks for constructing music -- such as pitches, intervals, chords, and melodic interaction. But we have not looked at how these elements combine to create harmony. To study harmony, we need a tool that describes chords and sonorities based on their function rather than their components. 

To this point, we have used leadsheet notation to convey the essential components of a chord: root, bass note, quality, inversion, and any additional pitches. But a single leadsheet chord does not provide context about its role in the music. 

Cmin<sup>7</sup>/E-flat

From this, we know that the chord has the pitches C, E-flat, G, and B-flat with the E-flat as the lowest voice, but we do not know how it relates to the chords around it. Is it stable, and does it sound final? Or is it unstable and pulling toward a different chord?

When music theorists want to discuss diatonic (key-based) function, we label chords using a Roman numeral system based on the chord's position within a particular key.

## Goals for this topic

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

## Conclusions
 
Most of the class was familiar with the basics of using Roman numerals to label diatonic chords, but we broke the system into its fundamental components.
- *Root* - The number associated with a Roman numeral denotes the scale degree on which the chord is built.
  - If there is no accidental in front of the Roman numeral, the chord is built off the diatonic scale degree.
    - The only exception to this rule is the vii<sup>&oslash;</sup> chord in minor; this chord is built off of `ti` (raised seventh scale degree), and this is considered the diatonic function. The naturally-occurring VII chord serves little diatonic purpose.
  - If there is an accidental in front of the Roman numeral, this affects only the root of the chord by raising or lowering it.
    - The vii<sup>&oslash;</sup> chord in minor does not require an accidental because it is assumed because of its diatonic function.
- *Chordal third* - The case (i.e. upper-case versus lower-case) of the Roman numeral denotes the quality of the chordal third.
  - All upper-case Roman numerals have a major third. This includes major triads, augmented triads, major major chords, and major minor chords.
  - All lower-case Roman numerals have a minor third. This includes all minor triads, diminished triads, minor minor chords, diminished minor chords, and diminished diminished chords.
- *Chordal fifth* - The chordal fifth is altered by adding either a <sup>&oslash;</sup> for lowered fifths or a <sup>+</sup> for raised fifths.
- *Chordal sevenths* - Simply having an inversion figure that implies a seventh chord (i.e. <sup>7, 6/5, 4/3, or 4/2</sup>) is all that is needed for a seventh chord.
  - A <sup>M</sup> is added as a courtesy for all major seventh chords, even though they occur naturally. This allows us to differentiate chord qualities clearly once secondary functions and mode mixture are introduced later in the course.
  - If necessary, the chordal seventh could be raised or lowered by adding a flat or sharp sign respectively in front of the appropriate interval of the inversion figure. This is almost never necessary in diatonic harmony.

When you add an inversion to a seventh chord, you do not need a <sup>7</sup> anymore. The inversion implies the seventh.

By having each part of a Roman numeral describe an isolated chord tone, we are able to accurately describe even borrowed chords.

Chordal member | Default implied pitch | To raise by semitone from default | To lower by semitone from default
 --- | --- | --- | ---
 root | diatonic scale degree | sharp symbol in front of Roman numeral* | flat symbol in front of Roman numeral*
 third | based on case of Roman numeral | upper case (M3) | lower case (m3)
 fifth | P5 above root | <sup>+</sup> after Rom num | <sup>o</sup> after Rom num
 seventh | m7 above root | <sup>M</sup> before inversion figure | <sup>o</sup> before inversion figure**

 *For clarity's sake, we **always** use a sharp or flat symbol to show that we are raising or lowering the root, even if you are actually adding a natural.

 **Because the diminished <sup>o</sup> implies the interval of a d5 AND a d7, you must use the half-diminished symbol if you wish to alter the fifth but leave the chordal seventh as a m7 above the root.

### Add and sub

There are two more possible additions for Roman numerals, but these are advanced techniques are will not be necessary until Unit 19. For completeness, we will discuss them here, but if you would rather skip this for now, please do so.

The word <sup>add</sup> is used when a tone is a functional part of the chord but does not belong to a standard triad or seventh chord. A good example of this would be a triad that has a functional 9th above the root. For example, in C major, if a C major triad were to have a D as necessary to the function of that chord, it would be labeled I<sup>add 9</sup>. This clearly identifies the triad plus the additional ninth, but it also omits the chordal seventh. If it *were* a major seventh chord, you would not need use the <sup>add</sup> function, because a 9 would imply everything below it. So a I<sup>M9</sup> is assumed to have 9th, 7th, 5th, and 3rd above the root.

The word <sup>sub</sup> is used when a tone *replaces* another chord tone. The replaced chord tone is always the closest chord tone below the subbed chord tone. For example, if the tonic triad in C major had a 4th above the root instead of the chordal third, you would label that as I<sup>sub4</sup>. This implies that the 4th replaces the chord tone directly below it, so this would be a triad with C, F, and G.