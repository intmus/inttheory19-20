---
layout: chapter
title: Lesson 10a - Fundamentals of Part-writing
abc: true
---

The term "part-writing" implies many things, but for our purposes, this will be our first attempt to combine the fundamentals of melody (counterpoint) and harmony (voice-leading from circle-of-fifths progressions) into functional music using diatonic tonality. 

By simply applying the various skills and techniques that we have studied thus far, we can:
- Harmonize a melody
- Compose a melody given a harmony
- Fully voice chords
- Create independent melodic lines that function harmonically together

The goal of Units 10 and 11 are to solidify this process, beginning with a demonstration of the fundamentals of part-writing using only our basic knowledge, then exploring the stylistic errors of four-part chorale writing, and finally exploring the full application of part-writing in a chorale style.

We will be referring to Dr. Butterfield's handout, [Part-Writing Error Checklist and Guide](https://docs.google.com/document/d/1s9Xd3LPqoaEevshTopxHzLX9jCzxVCZocOBLD_dceMU/edit?usp=sharing), for the next two units, so you may want to print this out.

## Examples

**Harmonize the following melody in a four-part chorale style:**
- **Choose a cadence** for the end.
    - Refer to Unit 7c to review the types of cadences.
- **Create the rest of the diatonic progression** that begins on tonic and ends with your cadence. (If not already provided.)
    - This will establish your key center. Refer to Unit 6b for a review of the three primary harmonic functions: tonic, dominant, and pre-dominant.
- **Compose a bass line** based on your harmonization.
    - This will resemble 1:1 counterpoint, so refer to Unit 5b.
    - Contrary motion against the soprano line is preferred.
- **Fill in the alto and tenor voices.**
    - Refer to the rules for voicing, range, and doubling in Unit 6b.
- When writing your parts, always **strive to have voice-leading that is as smooth as possible** by emphasizing stepwise motion.
    - Bass lines are the exception and will often have more leaps, especially when using root-position chords.

{% capture ex1 %}X:1
T:A first attempt at part-writing
M:4/4
L:1/2
K:C
V:1
[c] [A]| [B] [c]|]
V:2 clef=bass
x x| x x|]
w:C:{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Conclusions

After we discussed the idea of how part-writing will work, we briefly discussed "why." Why do we study part-writing when it is a style in which most students and music professionals will not perform or teach.

There are many answers for this, but there is one in particular that I think justifies the study of this in this course. Part-writing is the simplest way to study how voice-leading creates harmony. Even though most of its rules are archaic, and a modern student's ear is not nearly as offended by certain style characteristics (e.g. parallel fifths), this is the most straightforward way to study every aspect of how music functions: voice-leaeding, chord progressions, voicing chords, chordal structure, tendency tones, melodic construction, and every other aspect of how music functions.

In short, you may never use this directly, but a knowledge and understanding of these basic tenets will greatly enhance your ability to function as a musician, regardless of your career path.

## The Handout

We will be referring to Dr. Butterfield's handout, [Part-Writing Error Checklist and Guide](https://docs.google.com/document/d/1s9Xd3LPqoaEevshTopxHzLX9jCzxVCZocOBLD_dceMU/edit?usp=sharing), for the next two units, so it may be helpful to have this printed out and available.

## Harmonizing a melody

I started by writing a simple melody on the board:

{% capture ex2 %}X:2
T:Melody
M:4/4
L:1/4
K:C
V:1
cedf| gfed| c4|]
V:2 clef=bass
x| x|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

I asked the students how they would harmonize it, and two different approaches were given:
- Every pitch could get its own harmony OR
- We could look for patterns to create extended harmonies

I chose to explore the second option, so I asked the students how they would group the melody into harmonies. One student suggested that the first two pitches outline a I chord chord, so we decided to consider that all a tonic harmony. Because the next two pitches (beats 3 and 4) followed the same shape, we used the same logic and labeled these as a ii chord. From here, we refered to our circle-of-fifths progressions to determine that a ii chord has a pre-dominant function, so we needed a dominant harmony for the following chord. The next measure contains `sol`, `fa`, and `re`, so the entire measure is likely a V<sup>7</sup> chord with a non-chord tone of `mi`. The V<sup>7</sup> chord wants to resolve to a tonic harmony, so we ended the harmonization on a I chord.

Using only a simple understanding of diatonic progressions, we harmonized a melody with a standard tonic - pre-dominant - dominant - tonic progression. 

## Part-writing

Because we were short on time, I chose to simplify the melody and then added a suggested bass line based on our progression. This created:

{% capture ex3 %}X:3
T:A first attempt at part-writing
M:4/4
L:1/2
K:C
V:1
[c] [A]| [B] [c]|]
V:2 clef=bass
[C,] [F,] | [G,] [C,]|]
w:C:I ii6 V7 I
w:T P D T{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

From here, we began referring to the handout to see if we had met the criteria:
- Our chords follow a standard progression.
- It establishes a key and then cadences in that key.
- The lines emphasize smooth voice-leading.

We were now ready to add inner voices, so I let the class suggest a voicing of the first chord based on our voicing and doubling rules from Unit 6b. They chose:

{% capture ex4 %}X:4
T:A first attempt at part-writing
M:4/4
L:1/2
K:C
V:1
[cE] [A]| [B] [c]|]
V:2 clef=bass
[C,G,] [F,] | [G,] [C,]|]
w:C:I ii6 V7 I
w:T P D T{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

Lastly, I asked them to create the alto and tenor lines while observing the melodic guidelines from the handout.
- Individual lines should create smooth voice-leading using primarily stepwise motion.
- Resolve tendency tones as we studied in our voice-leading discussions (Unit 6b.)

This led them to create:

{% capture ex5 %}X:5
T:A first attempt at part-writing
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [G,G,] [C,G,]|]
w:C:I ii6 V7 I
w:T P D T{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

Of note, they first suggested jumping up to a `D` for the first beat of the second measure in the tenor line, but this created an unnecessarily disjunct tenor part. As we studied in Unit 6b, the chordal fifth can be ommitted on a seventh chord if the root is doubled.

This demonstrated that if we use only the tools that we have learned thus far in the course, we can already create a simple four-part chorale.