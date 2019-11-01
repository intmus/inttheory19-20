---
layout: chapter
title: Lesson 11a - Fundamentals of Part-writing
abc: true
---

## Introduction

How would you go about harmonizing the following melody?

Without actually doing so, look at the following example and make a list of all the things you would need to do to harmonize this melody.

{% capture ex1 %}X:1
T:Melody
M:4/4
L:1/4
K:C
V:1
cedf| gfed| c4|]
V:2 clef=bass
xxxx| xxxx| x4|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

In no particular order, you would need to determine: 
- Harmonies
- Harmonic rhythm
- Cadences
- Bass lines
- Inner voices
- Texture

To this point in the course, we have discussed each of these, but you have spent most of your assignments analyzing existing examples rather than creating your own music. Fortunately, you can now combine all the tools that we have studied to begin creating your own music. We will begin by establishing our guidelines for *part-writing*--rules and structures that are used to create a relatively basic chorale structure.  

## Part-writing

The term *part-writing* can imply many things depending on its context, but for our purposes, this will be our first attempt to combine the fundamentals of melody (counterpoint) and harmony (voice-leading from circle-of-fifths progressions) into functional music using diatonic tonality. 

By applying the various rules and techniques that we have studied thus far, we can:
- Harmonize a melody
- Compose a melody given a harmony
- Fully voice four-part harmonies
- Create independent melodic lines that function harmonically together

Units 10 and 11 will help you solidify this process, beginning with a demonstration of the fundamentals of part-writing using only our basic knowledge, then exploring the stylistic errors of four-part chorale writing, and finally fully applying part-writing in a chorale style.

We will be referring to this handout, [Part-Writing Error Checklist and Guide](https://docs.google.com/document/d/1s9Xd3LPqoaEevshTopxHzLX9jCzxVCZocOBLD_dceMU/edit?usp=sharing), for the next two units, so you may want to print this out or open it in a separate window.

## Why part-writing?

Before we begin, I would like to address a question that I have received many times from students. Why do we study part-writing, particularly in a strict style that is not performed regularly by modern musicians?

There are many answers for this, but there is one in particular that I think justifies the study of this in this course. Part-writing is the simplest way to study how voice-leading creates harmony. Even though most of its rules are archaic, and a modern student's ear is not nearly as offended by certain style characteristics (e.g. parallel perfect fifths), this is the most straightforward way to study every aspect of how music functions: voice-leading, chord progressions, voicing chords, chordal structure, tendency tones, melodic construction, and so on.

We could attempt to focus on only one style of modern music--whether pop, jazz, classical, or otherwise--but because each is a fully developed, complex language, you would still need to learn basic harmonic movement before beginning to write in that style. And because each of these musics has its roots in diatonic harmony, an understanding of basic chorale style part-writing will allow you to study and analyze *all* of these styles, rather than focusing your studies into only one area and being ignorant of the others.

In short, you may never use this directly, but a knowledge and understanding of these basic tenets will greatly enhance your ability to function as a musician, regardless of your career path.

## A first attempt

Let's try to harmonize the simple melody below with one harmony per pitch.

**To harmonize a melody in a four-part chorale style, you should:**
- **Identify the key**
    - Look for melodic patterns, starting pitches, and ending pitches for clues as to an implied key. 
- **Determine your phrase**
    - For the excerpt below, you have little room for decision making, but for a larger melody, try singing the phrase repeatedly and listen to your natural inclination for breaths or pauses. 
    - It can also be helpful to look for spots in which the rhythm slows naturally.
- **Choose a cadence** to complete your phrase.
    - Refer to [Unit 7c]({{ site.baseurl }}/07-harmonic-functions/c1-cadences.html) to review the types of cadences.
- **Create the rest of the diatonic progression** beginning on tonic and ending with your cadence. (If not already provided.)
    - Beginning on tonic will establish your key center. Refer to [Unit 6b]({{ site.baseurl }}/06-intro-harmonic/b1-diafuncvoicelead.html) for a review of the three primary harmonic functions: tonic, dominant, and pre-dominant.
    - Refer to [Unit 7a]({{ site.baseurl }}/07-harmonic-functions/a1-diaprogcirclefifths.html) to determine a functional harmonic progression.
- **Compose a bass line** based on your harmonization.
    - This will resemble 1:1 counterpoint, so refer to [Unit 5b]({{ site.baseurl }}/05-counterpoint-embell-shapes/b1-cantfirmand1st.html).
    - It is okay for the bass line to be more disjunct than the other voices, so feel free to leave your chords in root position to make doubling simpler.
    - Contrary motion against the soprano line is preferred.
- **Fill in the alto and tenor voices.**
    - Refer to the guidelines for voicing, range, and doubling in [Unit 6c]({{ site.baseurl }}/06-intro-harmonic/c1-voiceleadingerrors.html).
- When writing your parts, always **strive to have voice-leading that is as smooth as possible** by emphasizing stepwise motion.
    - As mentioned above, bass lines are the exception and will often have more leaps, especially when using root-position chords.

{% capture ex2 %}X:2
T:A first attempt at part-writing
M:4/4
L:1/2
K:C
V:1
[c] [A]| [B] [c]|]
V:2 clef=bass
x x| x x|]
w:C:{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Conclusions

The first steps in harmonizing any melody should involve: 
1. Developing an ending--which cadences would make this a complete musical phrase? 
2. Determine a harmonic rhythm and chords that both works with the melody and fills in the gaps on our way to the cadence. 
    - Will you have non-chord tones or are all notes part of the harmonic structure? 
    - Will you prolong a certain tonal function such as the dominant harmony, or is it interesting enough to move quickly through your progression?
    - Does your phrase sound convincing when played? If not, restructure your harmony and try again. 
    
Please do not be afraid of failing! Your first attempts will likely sound clunky and unconvincing. This is a normal and important part of the learning process, so rather than be disappointed, try focusing on the parts that you do not like, and then analyze them for errors. You should be able to use the analytical tools that you have developed thus far to find mistakes, and then you can correct those. Iteration is key.

With a four note melody such as this, we have little room for development, so it is easiest to stick with a simple idea. For example, the melody ends on the tonic, so this eliminates a half cadence. The penultimate note is the seventh scale degree, so this eliminates a plagal cadence, leaving us with either an authentic cadence or a deceptive cadence.

To keep this simple, let's choose a perfect authentic cadence. This locks in the bass line for our last two notes, because we know that a PAC has a root position V and I chords at the end of the phrase. It is hopefully clear that the first pitch should start on the tonic chord to establish the key in our ear, which leaves only the second chord undetermined.

Because the chord that *follows* our undetermined chord is a dominant chord, it makes sense to use a pre-dominant chord, and the `A` in the melody would allow for either a ii chord or a IV chord. (If you are struggling to remember the standard diatonic chord progressions, please refer to Refer to [Unit 7a]({{ site.baseurl }}/07-harmonic-functions/a1-diaprogcirclefifths.html).)Let's choose an inverted ii chord to provide some variety.

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

You now can refer to the handout to see if we met some basic criteria:
- Our chords follow a standard progression.
- It establishes a key and then cadences in that key.
- The lines emphasize smooth voice-leading.

We are now ready to add inner voices, and we can use our voicing and doubling rules from Unit 6b to establish a first chord.

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

And lastly, we can create the alto and tenor lines while observing the melodic guidelines from the handout.
- Individual lines should create smooth voice-leading using primarily stepwise motion.
- Resolve tendency tones as we studied in our voice-leading discussions (Unit 6b.)

Leading to...

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

Of note, you may have tried to jump to a `D` for the first beat of the second measure in the tenor line, but this creates an unnecessarily disjunct tenor part. As we studied in Unit 6b, the chordal fifth can be ommitted on a seventh chord if the root is doubled.

Therefore, if we use only the tools that we have developed thus far in the course, we can already create a simple four-part chorale.