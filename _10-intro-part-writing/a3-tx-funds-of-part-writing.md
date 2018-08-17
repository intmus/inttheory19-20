---
layout: chapter
title: Lesson 10a - Fundamentals of Part-writing
abc: true
---

# Class discussion

After we discussed the idea of how part-writing will work, we briefly discussed "why." Why do we study part-writing when it is a style in which most students and music professionals will not perform or teach.

There are many answers for this, but there is one in particular that I think justifies the study of this in this course. Part-writing is the simplest way to study how voice-leading creates harmony. Even though most of its rules are archaic, and a modern student's ear is not nearly as offended by certain style characteristics (e.g. parallel fifths), this is the most straightforward way to study every aspect of how music functions: voice-leaeding, chord progressions, voicing chords, chordal structure, tendency tones, melodic construction, and every other aspect of how music functions.

In short, you may never use this directly, but a knowledge and understanding of these basic tenets will greatly enhance your ability to function as a musician, regardless of your career path.

## The Handout

We will be referring to Dr. Butterfield's handout, [Part-Writing Error Checklist and Guide](https://docs.google.com/document/d/1s9Xd3LPqoaEevshTopxHzLX9jCzxVCZocOBLD_dceMU/edit?usp=sharing), for the next two units, so it may be helpful to have this printed out and available.

## Harmonizing a melody

I started by writing a simple melody on the board:
{% capture ex1 %}X:1
T:Melody
M:4/4
L:1/4
K:C
V:1
cedf| gfed| c4|]
V:2 clef=bass
x| x|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

I asked the students how they would harmonize it, and two different approaches were given:
- Every pitch could get its own harmony OR
- We could look for patterns to create extended harmonies

I chose to explore the second option, so I asked the students how they would group the melody into harmonies. One student suggested that the first two pitches outline a I chord chord, so we decided to consider that all a tonic harmony. Because the next two pitches (beats 3 and 4) followed the same shape, we used the same logic and labeled these as a ii chord. From here, we refered to our circle-of-fifths progressions to determine that a ii chord has a pre-dominant function, so we needed a dominant harmony for the following chord. The next measure contains `sol`, `fa`, and `re`, so the entire measure is likely a V<sup>7</sup> chord with a non-chord tone of `mi`. The V<sup>7</sup> chord wants to resolve to a tonic harmony, so we ended the harmonization on a I chord.

Using only a simple understanding of diatonic progressions, we harmonized a melody with a standard tonic - pre-dominant - dominant - tonic progression. 

## Part-writing

Because we were short on time, I chose to simplify the melody and then added a suggested bass line based on our progression. This created:

{% capture ex2 %}X:2
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
{% include abc-example.html number="2" abc=ex2 %}

From here, we began referring to the handout to see if we had met the criteria:
- Our chords follow a standard progression.
- It establishes a key and then cadences in that key.
- The lines emphasize smooth voice-leading.

We were now ready to add inner voices, so I let the class suggest a voicing of the first chord based on our voicing and doubling rules from Unit 6b. They chose:

{% capture ex3 %}X:3
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
{% include abc-example.html number="3" abc=ex3 %}

Lastly, I asked them to create the alto and tenor lines while observing the melodic guidelines from the handout.
- Individual lines should create smooth voice-leading using primarily stepwise motion.
- Resolve tendency tones as we studied in our voice-leading discussions (Unit 6b.)

This led them to create:

{% capture ex4 %}X:4
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
{% include abc-example.html number="4" abc=ex4 %}

Of note, they first suggested jumping up to a `D` for the first beat of the second measure in the tenor line, but this created an unnecessarily disjunct tenor part. As we studied in Unit 6b, the chordal fifth can be ommitted on a seventh chord if the root is doubled.

This demonstrated that if we use only the tools that we have learned thus far in the course, we can already create a simple four-part chorale.