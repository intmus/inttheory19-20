---
layout: chapter
title: Lesson 11c - Voice-leading for Second Inversion Chords
abc: true
---

In diatonic harmony, second-inversion chords do not function in the same way as other inversions. Whereas root-position chords are stable, and first- and third-inversion chords create momentum by placing tendency tones in the bass, second-inversion chords are generally considered "weaker". For example, listen to the following sonority repeatedly. It contains both a P4 and P5 above the a root. Because there is a dissonance between the upper two voices, you will likely hear this as wanting to resolve in some way. Isolate the voice that you would like to resolve and then figure out how you are naturally resolving it by singing it.

{% capture ex6 %}X:6
T:Perfect 4th versus perfect 5th
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
[C2FG]| [C2FG]| [C2FG]|]{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

Most people will resolve this sonority as if it were a root position major triad that has a suspended third, although some might hear this as a minor triad instead. The P5 seems more stable as opposed to the P4. These resolutions would sound like this:

{% capture ex7 %}X:7
T:Resolving the perfect 4th
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
[CFG]"major"[CEG]| [CFG]"minor"[C_EG]|]{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

Conversely, if you were to hear the P4 as the more stable interval, you would resolve the P5 upward to create a second-inversion triad in either major or minor.

{% capture ex8 %}X:8
T:Resolving the perfect 5th
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
[CFG]"major"[CFA]| [CFG]"minor"[CF_A]|]{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}

## Alternate functions

Because second-inversion triads are not as stable as the other inversions, they must be used differently in your part-writing. Instead of fulfilling a primary function such as tonic, dominant, or pre-dominant, they will have one of four alternate functions:
- cadential
- passing
- pedal
- arpeggiated

For each of these functions, the chord will be extending the primary function of another chord rather than defining its own.

## Doubling

As a general rule, 6/4 chords function best when the bass voice is doubled. As you harmonize the chords in each of the examples below, notice how often this doubling occurs naturally in your part-writing.

## Cadential 6/4s

A cadential 6/4 chord is the most straightforward usage of second inversion chord, because it has the most specific rules.
- It occurs when a I<sup>6/4</sup> chord precedes a *root-position* V or V<sup>7</sup> chord. 
    - It cannot move to an inversion of a V chord or any version of a vii<sup>o</sup> chord.
- The I<sup>6/4</sup> loses its tonic function and instead acts as an extension of the dominant function. 
    - Some consider this chord a suspension of some of the chord tones of the dominant chord.
- It always occurs as part of the cadence for a phrase, hence the name.

Harmonize the following three examples to see how well the voice-leading works for a cadential 6/4 chord.

{% capture ex1 %}X:1
T:Cadential 6/4 chords
M:4/4
L:1/4
Q:1/4=70
K:C
V:1
[cE]xxx|| [cE]xxx|| [cE] [c] [c] [d]|]
V:2 clef=bass
[C,G,] [G,,] [G,,] [C,]|| [C,G,] [G,,] [G,,] [C,]|| [C,G,] [F,,] [G,,] [G,,]|]
w:C:I I6/4 V I I I6/4 V7 I I IV I6/4 V{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Conclusions

Cadential 6/4 progressions are often used to correct part-writing errors in approaching the V chord. Look at the third progression that you just harmonized. If the cadential 6/4 were removed, it would create parallel perfect 5ths between the soprano and bass.

Some theory methods teach that a cadential 6/4 should not be labeled as a I<sup>6/4</sup>; instead, they label it as a V<sup>6/4 - 5/3</sup>. The reasoning behind this is twofold:
- The I chord does not have a tonic function.
- The cadential 6/4 chord resembles a 4-3 suspension and a 6-5 suspension occurring at the same time.

These reasons enforce an understanding of the true nature of the cadential 6/4. I prefer to label it as a I<sup>6/4</sup> chord, however, because:
- We do not create special usage cases in our Roman numeral system for any other chord. It creates an unnecessary exception for students to learn and often confuses students on the difference between inversion figures and true figured bass.
- By having two different chords labeled as a V<sup>6/4</sup>, it is easy for students to confuse a cadential 6/4 with an actual V<sup>6/4</sup>, a chord that occurs regularly as a passing chord. (Read more on this below under the *passing 6/4* section.)
- When looking at an analysis, we are required to understand that all 6/4 chords function in one of the four alternate categories (i.e. passing, cadential, passing, and arpeggiated), but we do not create special Roman numeral cases for the other three. Students are more than capable of learning the other three usages of second inversion chords, and they can remember that a I<sup>6/4</sup> followed by a root-position V or V<sup>7</sup> chord is a cadential 6/4 and has a dominant function.

## Passing 6/4s - function over form (Part 4)

Passing chords are the second alternate function for second-inversion chords, and they function identically to the description of how first- and third-inversion chords are used as passing chords--a chord inserted between two other chords to create a bass line with stepwise motion. As before, *passing* is a function that replaces a chord's primary function, and instead extends the function of the chords on either side. Harmonize the following example of a passing 6/4.

{% capture ex2 %}X:2
T:Passing 6/4 chords
M:4/4
L:1/4
K:C
V:1
[cE][B][A][G]| [G4]|]
V:2 clef=bass
[C,G,] [G,,] [A,,] [B,,]| [C,4]|]
w:C:I V ii6/4 V6 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

Understanding that the ii chord in this example acts as a passing chord rather than a pre-dominant chord also explains how a V chord moves convincingly to a ii chord. When a chord resolves against the normal flow of a circle-of-fifths flowchart (see [Unit 7a]({{ site.baseurl }}/07-harmonic-functions/a1-diaprogcirclefifths.html)), we call that a *regression*. In the example above, the first V chord *should* resolve to a tonic chord but instead regresses to a ii chord. This works because of the strength of the bass line, so it is the *passing function* that extends the dominant harmony through a stepwise bass line.**

**Now that we have practiced using a passing 6/4 chord, we can also clarify why vii<sup>o6</sup> chords function well as a passing chord. When studying first inversion chords (Unit 11b), we discussed two important ideas regarding vii<sup>o</sup> chords:**
- The vii<sup>o</sup> is a functional substitution for the V<sup>7</sup> chord and therefore takes its voice-leading and doubling conventions from the V<sup>7</sup> chord.
- The vii<sup>o6</sup> is often employed as a passing chord between I and I<sup>6</sup> to create a bass line with stepwise motion.

**This explains why a vii<sup>o6</sup> chord functions as a passing chord; it is actually a functional substitution for a passing V<sup>6/4</sup> chord. Harmonize the following two progressions to see how similar these two chords are.**

{% capture ex3 %}X:3
T:V6/4 and viio6
M:3/4
L:1/4
K:C
V:1
[e][d][c]|| [e][d][c]|]
V:2 clef=bass
[C,] [D,] [E,]|| [C,] [D,] [E,]|]
w:C:I V6/4 I6 I viio6 I6{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Pedal

**Like the cadential 6/4 and passing 6/4 chords, the pedal 6/4 is defined by the motion that it creates in the bass line. A pedal 6/4 occurs when the bass line remains static across multiple chords by employing a second inversion chord. *Note that this is different from a non-chord tone pedal*, because a pedal 6/4 chord uses only chord tones to create the static pedal; it does not use non-chord tones to create the pedal. Harmonize the following two examples of common pedal 6/4 chords.**

{% capture ex4 %}X:4
T:Pedal 6/4 chords
M:3/4
L:1/4
K:C
V:1
[cE]xx[][]|| [dG]xx[][]|]
V:2 clef=bass
[C,G,] [C,] [C,]|| [G,,B,] [G,,] [G,,]|]
w:C:I IV6/4 I V ii6/4 V{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

## Arpeggiated

**The fourth and final acceptable usage of 6/4 chords occurs when the bass line creates arpeggiates through a chord. Depending on the harmonic rhythm of the piece, an arpeggiated 6/4 may be viewed as a melodic bass line that does not change inversion rather than a new inversion.**

{% capture ex5 %}X:5
T:Arpeggiated 6/4 chords
M:4/4
L:1/4
Q:1/4=70
K:C
V:1
[cG] [c] [c] [B]| [c4]|]
V:2 clef=bass
[CE] [G,] [E,] [G,]| [C,4]|]
w:C:I I6/4 I6 V I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

## Conclusions

Second inversion chords have the most rules when it comes to part writing. 
To exist in a progression, they have to be used for one of 4 functions:
1. Cadential
2. Passing
3. Pedal
4. Arpeggiated

A I6/4 chord is close to functioning in the same way as the V. 
It has the most static motion in a movement to the V. 

### Cadential Motion

The Cadential 6/4 uses a I6/4 as an extention of the dominant leading to a cadence. 
Progression: I - IV - I6/4 - V - I. 
- doubling the 5th in the I6/4 makes it an extention of the V as it leads to I
- must go from a I6/4 to a root position V or V7
- leads to static motion between the two chords

#### Example: In C

Lead Sheet: C - F - C/G - G

Soprano: C5 - C5 - C5 - D5

Alto: E4 - F4 - E4 - G4

Tenor: G3 - A3 - G3 - B3

Bass: C3 - F2 - G2 - G2

Roman Numerals: I - IV - I6/4 - V

Without the cadential 6/4, we would have parallel perfect fifths in the soprano and alto voices between the IV and the V.
The cadential 6/4 avoids this problem by sticking a I6/4 in between the two chords as an extention of the dominant. 
It functions with the dominant chord as one. 
The I6/4 goes to a root position V chord.
This means that the interval of a 6th resolves to a 5th, and the interval of a 4th resolves to a 3rd.

#### Labeling the Cadential 6/4

- sometimes it is just labelled with a I6/4 - V
- sometimes it's also bracketed as a V underneath the I6/4 - V progression
- it is also labelled underneath all of this as a V(I6/4)
  - that is overkill and unnecessary
  - just using the second option is the most efficient
  
### Passing 6/4 Chords

If you have a progression of I - V - ii6/4 - V6 - I, the last 4 chords move the bassline in a sol - la - ti - do motion.
With do in the soprano voice on the I chord, the soprano line moves in contrary motion to the bass line as do - ti - la - sol - sol.
The inversions in the bass line create smooth voice leading in all the voices that make it easier to avoid part writing errors.
- leads to passing motion in the bass

#### Example

Lead Sheet: C - G - Dm/A - G/B - C

Soprano: C5 - B4 - A4 - G4 - G4 

Alto: E4 - D4 - D4 - D4 - E4

Tenor: G3 - G3 - F3 - G3 - G3

Bass: C3 - G2 - A2 - B2 - C3

Roman Numerals: I - V - ii6/4 - V6 - I

### Seven Diminished Chords (viio)

The viio chord functions as a dominant chord. 
It is the same as a V7 without the root. 
It mostly consists of tendancy tones which makes it more difficult to resolve. 
As far as voice leading, the V6/4 is the same as a viio6.

#### Example

Lead Sheet: C - G/D - C/E - C - Bo/D - C/E

Soprano: E5 - D5 - C5 - E5 - D5 - C5 

Alto: G4 - G4 - G4 - G4 - F4 - G4

Tenor: C4 - B3 - C4 - C4 - B3 - C4

Bass: C3 - D3 - E3 - C3 - D3 - E3

Roman Numerals: I - V6/4 - I6 - I - viio6 - I6

- the two sets of three chords have the same notes aside from one in the alto line to outline the different chords
- the V6/4 and viiio6 resolve to the same notes and chordal inversion 

### Arpeggiated Motion

If you have a bass line that wants to outline a triad, but you still feel that each beat deserves its own chord, you have arpeggiated motion.
There may be different chords, but if the bass line outlines a triad of any kind it is arpeggiated motion.

### Pedal Motion

- pedal 6/4 chords are pedal figures
- it leads to complete static motion in the bass line between multiple chords
The pedal 6/4 is a 6/4 chord that creates static motion in the bass line between multiple chords.

#### Example

Lead Sheet: C - F/C - C - G

Soprano: C5 - C5 - C5 - D5 

Alto: E4 - F4 - E4 - G4

Tenor: G3 - A3 - G3 - B3

Bass: C3 - C3 - C3 - G2

Roman Numerals: I - IV6/4 - I - V

## Figures

Any non-chord tone shape classification can be used to describe chord tones. 

This includes:
- passing
- neighbor
- pedal
- appoggiatura
- escape tone
- suspension
- retardation
- anticipation

All of these terms can be used to describe movement between chord tones by tagging on the word "figure."