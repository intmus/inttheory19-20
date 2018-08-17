---
layout: chapter
title: Lesson 6a - Roman Numerals in Harmonic Analysis
---

# Class discussion
 
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

## Add and sub

There are two more possible additions for Roman numerals, but these are advanced techniques are will not be necessary until Unit 19. For completeness, we will discuss them here, but if you would rather skip this for now, please do so.

The word <sup>add</sup> is used when a tone is a functional part of the chord but does not belong to a standard triad or seventh chord. A good example of this would be a triad that has a functional 9th above the root. For example, in C major, if a C major triad were to have a D as necessary to the function of that chord, it would be labeled I<sup>add 9</sup>. This clearly identifies the triad plus the additional ninth, but it also omits the chordal seventh. If it *were* a major seventh chord, you would not need use the <sup>add</sup> function, because a 9 would imply everything below it. So a I<sup>M9</sup> is assumed to have 9th, 7th, 5th, and 3rd above the root.

The word <sup>sub</sup> is used when a tone *replaces* another chord tone. The replaced chord tone is always the closest chord tone below the subbed chord tone. For example, if the tonic triad in C major had a 4th above the root instead of the chordal third, you would label that as I<sup>sub4</sup>. This implies that the 4th replaces the chord tone directly below it, so this would be a triad with C, F, and G.
  
# Further Reading

## From *Open Music Theory*

## Labeling chords

There are two ways in which we will label chords according to function. The first is to label chords with Roman numerals, thoroughbass figures, and functional labels. When doing so, place the appropriate Roman numeral *below* the bass line, the thoroughbass figure *above* the bass line (since it represents the upper voices), and place a functional label **T**/**S**/**D** below the Roman numeral (no **Tx**; simply call a **VI** chord **T**). For now this label can simply apply T, S, or D to individual chords; in the future, we will alter this practice slightly in order to show [functional prolongation](harmonicSyntax2.html). The first example shows individual chord functions, and the second example shows functional prolongation.

[![](/images/harmony/RNsIndividualFunctions.png)](/images/harmony/RNsIndividualFunctions.png)

[![](/images/harmony/RNsFunctionalProlongation.png)](/images/harmony/RNsFunctionalProlongation.png)

The second way to label a harmonic progression is what Quinn calls *functional bass*. Functional bass symbols combine a chord's function (**T**, **S**, **D**, or **Tx**) with an Arabic numeral denoting the scale degree of its bass note. A tonic chord with *do* in the bass is **T1**, a dominant chord with *ti* in the bass is **D7**, etc. If the bass note is chromatically altered, use a **+** or **–** to denote raised or lowered (*la* and *ti* in minor do not count, since *le*, *la*, *te*, and *ti* all belong to minor, but you can use +/– for clarity if you like). And if there is a chromatically altered note anywhere in the chord, put the functional bass symbol inside square brackets: **[S6]**, **[S+4]**, **[T–7]**, etc. (See [Chromatically altered subdominant chords](alteredSubdominants.html), [Applied chords](appliedChords.html), and [Modal mixture](modalMixture.html) for more information on common chromatically altered chords.)

[![](/images/harmony/FunctionalBassFunctions.png)](/images/harmony/FunctionalBassFunctions.png)

Quinn also advocates using what I call *interpreted functional bass*. This nomenclature uses the same symbols, but uses parentheses to denote [*contrapuntal prolongation*](http://openmusictheory.com/harmonicSyntax2.html) and lower-case postscripts to explain the contrapuntal role of the embellishing chord (p for passing, n for neighbor, i for incomplete neighbor, d for divider, e for embellishing — all of these refer to the voice-leading pattern in the bass voice). Following is an example of interpreted functional bass.

[![](/images/harmony/InterpretedFunctionalBass.png)](/images/harmony/InterpretedFunctionalBass.png)

In this text, we primarily use the first method of Roman numerals and (prolonged) harmonic functions, since it is the most common in North American music theory. However, functional bass can be helpful for identifying categories of chords that belong together. For example, in a dictation or transcription task, we might hear *re* in the bass but not know what specific chord it is. If context tells us it is likely a dominant chord, rather than subdominant, we can label it **D2**. This rules out **II** (a subdominant chord) but keeps open multiple dominant options like **V<sup>6/4</sup>** or **VII<sup>6</sup>** until we are able to make a final determination. Similarly, when composing, there are patterns that might take an **S4**, with the specific chord (**IV** or **II<sup>6</sup>**) determined by voice-leading rather than harmonic syntax, but where a **D4** chord (**V<sup>4/2</sup>**) would be syntactically inappropriate, regardless of voice-leading.

Thus, when referring to specific chords, we will use Roman numerals to label the chords and functional labels to interpret their role in context. When referring to broader categories of chords, we will more often use functional bass.
