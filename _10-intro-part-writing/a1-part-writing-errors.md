---
layout: chapter
title: Lesson 10a - Part-writing Errors
abc: true
---

## Part-writing

The term *part-writing* can imply many things depending on its context, but for our purposes, this will be our first attempt to combine the fundamentals of melody (counterpoint) and harmony (voice-leading from circle-of-fifths progressions) into functional music using diatonic tonality. 

By applying the various rules and techniques that we have studied thus far, we can:
- Harmonize a melody
- Compose a melody given a harmony
- Fully voice four-part harmonies
- Create independent melodic lines that function harmonically together

Units 10 and 11 will help you solidify this process. First, we will establish a reference model by looking at classic errors that occur when writing in a general four-part chorale style. We will then apply these guidelines to our own attempts to compose basic four-part chorales in order to better understand the voice-leading principles of all tonal music.

We will be referring to this handout, [Part-Writing Error Checklist and Guide](https://docs.google.com/document/d/1s9Xd3LPqoaEevshTopxHzLX9jCzxVCZocOBLD_dceMU/edit?usp=sharing), for the next two units, so you may want to print this out or open it in a separate window.

## Why part-writing?

Before we begin, I would like to address a question that I have received many times from students. Why do we study part-writing, particularly in a strict style that is not performed regularly by modern musicians?

There are many answers for this, but there is one in particular that I think justifies the study of this in this course. Part-writing is the simplest way to study how voice-leading creates harmony. Even though most of its rules are archaic, and a modern student's ear is not nearly as offended by certain style characteristics (e.g. parallel perfect fifths), this is the most straightforward way to study every aspect of how music functions: voice-leading, chord progressions, voicing chords, chordal structure, tendency tones, melodic construction, and so on.

We could attempt to focus on only one style of modern music--whether pop, jazz, classical, or otherwise--but because each is a fully developed, complex language, you would still need to learn basic harmonic movement before beginning to write in that style. And because each of these musics has its roots in diatonic harmony, an understanding of basic chorale style part-writing will allow you to study and analyze *all* of these styles, rather than focusing your studies into only one area and being ignorant of the others.

In short, you may never use this directly, but a knowledge and understanding of these basic tenets will greatly enhance your ability to function as a musician, regardless of your career path.

## Traditional errors

In [Unit 6c]({{ site.baseurl }}/06-intro-harmonic/c1-voiceleadingerrors.html), we first looked at some basic rules for voicing a chord in a four-part chorale style. These rules included:
- Voice-crossing
    - In this style, voices should generally not cross
    - Exception: alto and tenor may cross briefly if musically necessary
- Spacing
    - In this style, the top three voices--soprano, alto, and tenor--should always be within an octave of the adjacent voices. To be more specific, there can never be more than an octave between *soprano* and *alto*, and there can never be more than an octave bteween *alto* and *tenor*. 
    - There **can** be more than an octave between *bass* and *tenor*.
    - There **can** be more than an octave between *soprano* and *tenor*, and this creates two different types of voicings.
        - A *closed voicing* has **less** than an octave between *soprano* and *tenor*. 
        - An *open voicing* has **more** than an octave between *soprano* and *tenor*.
- Range
    - Each part must stay within the typical range for that voice/instrument?
- Doubling
    - You can double the root of a chord when possible.
    - For triads, you may double the fifth instead of the root if necessary.
        - This is actually more preferable if the triad is in second inversion.
    - **Do not** double the third because it is a tendency tone. If this is doubled, it will force you to choose between the incorrect resolution of a tendency tone or unacceptable parallel octaves. Also, the third should also be least present chord tone in the balance for the chord to sound best.
    - **Do not** double the seventh because it is a tendency tone. If this is doubled, it will force you to choose between the incorrect resolution of a tendency tone or unacceptable parallel octaves.
    - **Do not** double the fifth of a seventh chord. This would require omitting the root, third, or seventh, and none of these are expendable.

## Part-writing errors

In addition to the voicing rules, there are a number of standard part-writing errors that should be avoided as well:
1. Parallel perfect octaves or perfect fifths 
2. Similar octaves or fifths (sometimes referred to as "direct", "hidden", or "exposed")
3. Unacceptable unequal fifths
4. Contrary perfect octaves or perfect fifths

Please note that these errors *must be within the same two voices* across both chords. Due to the effects of consistently doubling roots, there will almost always be consecutive perfect octaves and perfect fifths between two triads, but this is not *parallel*. For example, a root position C major triad moving to a root position G triad will have two voices on C in the first chord and two voices on G in the second chord, if standard doubling practices are observed. This is fine as long as its not in the *same* two voices in both chords (e.g. soprano and bass both have C and then both have a G).

Each of the four primary categories of part-writing errors are *symptoms* of voice-leading issues. If you understand the underlying voice-leading issues of each of these errors, you can find them more easily and avoid them in your own part-writing.

## Parallel perfect fifths and perfect octaves (PP5, PP8)

Part-writing errors result from poor voice-leading. For example, look at the progression below and try to find our first major error: *parallel perfect octaves* (PP8). Once you have found it, look to see if a voicing rule (e.g. spacing, doubling, etc.) has been broken. If the voicing error is not fixed, is there any way to avoid the parallel octaves without incorrectly resolving a tendency tone?

{% capture ex1 %}X:1
T:Parallel perfect octaves (PP8)
M:4/4
Q:1/4=80
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

Parallel perfect octaves and perfect fifths undermine the independence of lines, so you should always avoid them in this style. Listen to the following example, and try to locate the parallel perfect fifths aurally before you look through the parts. Once you have identified the voices that contain the PP5, try singing the upper of the two voices, and then listen to the example again. Do you have a difficult time differentiating the upper voice from the lower of these two voices?

{% capture ex2 %}X:2
T:Parallel perfect fifths (PP5)
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,A,] | [DG,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

In summary, you may never have parallel perfect octaves or parallel perfect fifths in this style of music. Please note that for an interval to be considered *parallel*, the interval must occur consecutively in the *same* two voices. For example, if your first P8 is between the bass and alto, the second P8 must also be in the bass and alto. If you find a P8 between the bass and tenor on the second chord, this is acceptable because it does not undermine the independence of the voices.

## Contrary perfect fifths and octaves (CP5, CP8)

Our next part-writing error, *contrary perfect fifths* and *contrary perfect octaves* (CP5 or CP8) are simply an attempt to cover up parallel perfect fifths and parallel perfect octaves by displacing one voice by an octave. The next two examples attempt to fix the errors from the first two examples on this page by displacing one voice of the parallel perfect intervals. Identify these by comparing them to the previous example (i.e. P) Notice that it creates multiple voicing and spacing errors as well as nearly unsingable parts!

{% capture ex3 %}X:3
T:Contrary perfect octaves (CP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C,]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}


{% capture ex4 %}X:4
T:Contrary perfect fifths (CP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,,A,] | [D,G,,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

Again, remember that for this to be considered an error, the contrary perfect octaves/fifths must be in the same two voices. If the interval changes voices, it does not undermine the independence of the voices.

## Unacceptable unequal fifths (UU5)

The last two common part-writing errors have specific clauses tied to them that specify which voices are acceptable and unacceptable. The first, *unacceptable unequal fifths* (UU5), must occur between the bass voice and one of the upper voices. In the following example, find the *unacceptable unequal fifths* where a d5 moves to a P5. What is wrong with the voice-leading here?

{% capture ex5 %}X:5
T:Unacceptable unequal fifths (UU5)
M:4/4
L:1/2
K:C
V:1
[cE] [Fd]| [dF] [cG]|]
V:2 clef=bass
[C,C] [D,A,] | [B,,G,] [E,C,]|]
w:C:I ii V6/5 I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

So for this course, we will consider a d5 moving to a P5 *unacceptable* unequal fifths, but we will consider a P5 moving to a d5 as *acceptable*--a P5 to a d5 does not require incorrect resolutions of tendency tones. Remember that these errors are best thought of as symptoms of the actual problem. In this case, the real issue is that the only two notes in a diatonic key that can form a d5 are `ti` and `fa`, and as discussed many times in this course, these two notes will imply a dominant harmony that wants to resolve inward with `ti` moving to `do` and `fa` moving to `mi`. For a d5 to be followed by a P5, it would mean that `fa` must resolve to `sol` which is poor voice-leading and therefore the error we are trying to avoid. There are some stricter versions of chorale part-writing that do not allow any form of unequal fifths.

## Unacceptable similar fifths or octaves (US5, US8)

The final common part-writing has many names, but we will use the term *unacceptable similar fifths or octaves*. This error can also be called "direct", "hidden", or "exposed". I prefer to use *similar* because it implies the motion like the other categories, but I also think that *exposed* does a fine job describing the effect. (I dislike the term *hidden* because students often confuse this with contrary fifths (or octaves), because the goal of contrary fifths is to "hide" parallel fifths.) *Unacceptable similar fifths or octaves* have the most restrictions. The conditions are:
- They can only occur between the soprano and the bass voices.
- They require a skip of a third or more in the soprano voice.
- The two voices must move in similar (not parallel) motion.
- The second interval must be a P5 or P8.

If any one of these conditions are not met, then there is not a part-writing error. Look at the following example to find an example of *similar octaves*. Once you have found it, look at the voice-leading around it. What does it do to spacing? Does it create more errors? Unacceptable similar octaves and fifths also often create melodies that imply different harmonies. To demonstrate, sing the melody alone. Do you hear it as C major or a different key?

{% capture ex6 %}X:6
T:Similar octaves (S8)
M:4/4
L:1/2
K:C
V:1
[Ge] [AA]| [FA] [FB]| [c2E2]|]
V:2 clef=bass
[C,C] [CA,,]| [F,,C] [DG,,]| [C2C,2]|]
w:C:I vi IV V7 I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

**As a final demonstration of the difficulties that these part-writing errors create, try to fix each of the part-writing errors on this page. What do you have to change? Do you get to keep the harmony? Voice-leading? Voicing? In trying to fix it, do you just create further errors?**

## Conclusions

## Parallel Perfect Fifths and Octaves

{% capture ex7 %}X:7
T:Parallel perfect octaves (PP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

The class found two examples of parallel perfect octaves in this example.
- between the soprano and tenor moving from ii<sup>6</sup> to V<sup>7</sup>
- between the soprano and tenor moving from V<sup>7</sup> to I

Almost all unacceptable examples of parallel octaves and fifths are due to poor voice-leading and voicings. In this case, the third of the five chord is doubled. This third is a tendency tone that should resolve upward by step, but in doing so, it creates parallel perfect octaves. The third never should have been doubled.

{% capture ex8 %}X:8
T:Parallel perfect fifths (PP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,A,] | [DG,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}

In this example, the class found two examples of parallel perfect fifths:
- between the bass and tenor from I to ii
- between the bass and tenor moving from ii to V<sup>7</sup>

From this, we decided that the definition of a parallel perfect fifths/octaves is:
- when two voices have consecutive perfect fifths/octaves and move in parallel motion
    - it is not parallel perfect fifths/octaves if the intervals change voices (e.g. the first P8/P5 is between the soprano and tenor, but the second P8/P5 is between the soprano and alto)
- These are unacceptable between any two voices.

Parallel perfect fifths and octaves undermine the independence of the individual voices. Even after listening to the example with PP5s repeatedly, only one person in the class was able to distinguish the tenor voice. I then had the class look at the tenor voice and practice singing it in order to get the line into their ears. Even after doing this, they had trouble distinguishing between the two voices. This is even more pronounced if the chords are tuned using just intonation, because the upper note will blend into the overtone series of the lower note.
  
## Contrary Octaves and Fifths

{% capture ex9 %}X:9
T:Contrary perfect fifths (CP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,,A,] | [D,G,,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="9" abc=ex9 %}

Contrary fifths and octaves occur when trying to mask parallel perfect fifths and octaves. In the example above, the class identified the CP5s between bass and tenor voices between:
- the I chord and ii chord
- the ii chord and the V<sup>7</sup> chord

From this, we decided that the definition of a contrary perfect fifths/octaves is:
- when two voices have consecutive perfect fifths/octaves and move in contrary motion
    - it is not contrary perfect fifths/octaves if the intervals change voices (e.g. the first P5 is between the soprano and tenor, but the second P5 is between the soprano and alto)
- These are unacceptable between any two voices.

## Unacceptable Unequal Fifths

{% capture ex10 %}X:10
T:Unacceptable unequal fifths (UU5)
M:4/4
L:1/2
K:C
V:1
[cE] [Fd]| [dF] [cG]|]
V:2 clef=bass
[C,C] [D,A,] | [B,,G,] [E,C,]|]
w:C:I ii V6/5 I{% endcapture %}
{% include abc-example.html number="10" abc=ex10 %}

Unacceptable unequal fifths are one of the easier part-writing errors to understand, because we are actually focusing on only one voice-leading issue. We defined a UUF as any time a d5 between the bass voice and another voice moves to a P5. Because it has to fill all of these conditions, it is relatively easy to find compared to parallel and contrary fifths/octaves which are not acceptable between any voices.

The voice-leading issue that causes UU5 centers around the one naturally occurring d5 in the major scale: when `ti` is below `fa`. This is only likely to happen on a dominant harmony which means that this occurs typically on a V<sup>6/5</sup> chord or a vii<sup>o</sup> chord. The problem arises when `fa` does not resolve downward to `mi` in the next chord. This is an incorrect resolution of a tendency tone, and that is what creates the part-writing error.

## Similar Fifths and Octaves

Similar fifths/octaves occur when 1) the soprano and bass voices 2) move in similar motion to a 3) perfect fifth/octave, and 4) the soprano voice has a skip of a third or larger. You can see an example of this between the first two chords in this example.

{% capture ex11 %}X:11
T:Similar octaves (S8)
M:4/4
L:1/2
K:C
V:1
[Ge] [AA]| [FA] [FB]| [c2E2]|]
V:2 clef=bass
[C,C] [CA,,]| [F,,C] [DG,,]| [C2C,2]|]
w:C:I vi IV V7 I{% endcapture %}
{% include abc-example.html number="11" abc=ex11 %}

Similar fifths/octaves are sometimes called "exposed" fifths/octaves, and both of these terms demonstrate a key feature about the part-writing error. Obviously, they must move in similar motion, but the term "exposed" highlights the fact that these must occur between the outer voices. By having similar motion to a perfect interval in the outer voices, it creates the impression of a parallel perfect interval. Most importantly, the leap in the soprano typically creates a poor soprano line in which the melody outlines/implies an unintentional harmony. In the example above, if you sing the melody line without the harmony it outlines A minor instead of C major.