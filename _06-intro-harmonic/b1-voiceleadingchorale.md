---
layout: chapter
title: Examples 6b - Voice-leading Considerations in Chorale-style Harmony
abc: true
---

Because the Roman numeral system allows us to classify and label context and function, we can use it explore how harmonies function within a diatonic style.

In diatonic music, there are three basic categories of harmonic function: *tonic*, *dominant*, and *pre-dominant*. 
- *Tonic* (**T**) harmonies feel stable and final.
  - This is primarily the I chord, but in rare circumstances, this can include the vi.
- *Dominant* (**D**) harmonies feel unsettled and have a strong tonal gravity to resolve to the *tonic* harmony*
  - This includes the V and vii<sup>&oslash;</sup> chords.
- *Pre-dominant* (**P**) harmonies are harmonies are unstable and have a tonal gravity to resolve to the *dominant* harmonies.
  - This includes the ii and IV chords, but can occasionally include the vi chord.
  - Note that there is a difference between the words "pre-dominant" and "predominant".

Counterpoint provides a clear starting point for this exploration. If we think about our progression through the course thus far, we began by studying individual pitches, and then combined pitches into intervals,combined simultaneous intervals into chords, and combined sequential intervals into melodies. Next, the simplified version of counterpoint that we studied allowed us look at how rules that govern the vertical aspect of music could be used to create a horizontal line. This provides a framework for understanding harmony, but it does not seek to establish the vertical aspect of music as its own function.

If we look at the basic interactions between two voices we can begin to understand how voice-leading creates harmonic function and how certain chords fit into their roles in diatonic function. By adding two more voices to this soprano/bass framework, we can then begin looking at fully functional harmony in one of its most basic forms -- the four-part chorale.

## Goals for this topic

**Each measure of this first example is a two-voice version of the same two diatonic harmonies. Which two harmonies? What are the Roman numerals and inversion figures for each measure? Is there more than one option for any of the harmonies? Do any particular chord members seem more important than the others? Do any of these measures sound "weaker" than the others?**

{% capture ex1 %}X:1
T:Implied harmonies from two voices
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
Bc|| FE|| de|| Bc|| GE|| GG|]
V:2 clef=bass
"M3"G,"P8"C,|| "m7"G,"M3"C,|| "P5"G,"M3"C,|| "+4"F,"m6"E,|| "m6"B,,"M3"C,|| "M2"F,"m3"E,|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**The next example adds an additional pitch to each of the measures from the previous example. Which of these "new" notes belong to the chords that you assigned in the previous example? After reviewing your knowledge of approaching dissonances from second-species counterpoint, do the chord tones and non-chord tones follow any specific types of motion?**

{% capture ex2 %}X:2
T:Chord skips and passing/neighbor non-chord tones
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
Bc|| F/2D/2E|| d/2f/2e|| Bc|| G/2F/2E|| G/2A/2G|]
V:2 clef=bass
"M3"G,/2"M6"D,/2"P8"C,|| "m7"G,/2"P5"G,/2"M3"C,|| "P5"G,/2"m7"G,/2"M3"C,|| "+4"F,/2"M6"D,/2"m6"E,|| "m6"B,,/2"d5"B,,/2"M3"C,|| "M2"F,/2"M3"F,/2"m3"E,|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**The suspension is another type of non-chord tone. Each of the measures in the next example are grouped in pairs to demonstrate how suspensions are formed. The first measure is a simple two-voice harmony from the examples above, but the next measure adds a suspension to that framework. How would you define a suspension? What are the three parts of any suspension? How do we determine the labels (i.e. numbers after the word *sus*)?**

{% capture ex3 %}X:3
T:Suspensions
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
FE| F-"sus4-3"F/2E/2|| dc|| d-"sus9-8"d/2c/2|| GE|| GE|]
V:2 clef=bass
G,C,| G,C,|| G,C,| G,C,|| D,C,|| D,-"sus2-3"D,/2C,/2|]{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

**Our final voice-leading considerations arise when adding inner voices to our soprano-bass counterpoint. In the following example, each staff system highlights a different voicing error. Compare the correct measures to the incorrect measures to come up with descriptions of the first two basic voicing rules of *doubling* and *spacing*. Because *range* is a simple maximum and minimum, I have listed conservative estimates for each voice part. These can vary widely depending on the skill level of the intended performers but will be sufficient for our early exercises in part-writing.**

{% capture ex4 %}X:4
%%staffsep75%%
T:Voicing four-part harmony
M:2/4
L:1/2
K:C
V:1
"Doubling"[cE] [GE] [eE] [cE]|| [_BE] [cE] [_BE] [_BE] [_BE]|]
"Spacing "[cE] "(Range is ignored for this"[cE] "example)"[c'E] [c'e] [c'e]|]
"Conservative Ranges"[Cg]| [G,d]| x| x|]
w:soprano alto
V:2 clef=bass
[C,G,] [C,G,] [C,G,] [C,C]|| [C,G,] [C,_B,] [C,E,] [C,_B,] [G,,G,]|]
w:Good Good Bad Good Good Good Bad Bad Bad
[C,G,] [C,,G,] [C,G,] [C,G,] [C,G]|]
w:Good Good Bad Bad Good
x| x| [GC,]| [DE,,]|]
w:tenor bass{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

## Conclusions

Some important things to notice here:
- The intervals go from small to large (2-3), but when the suspension is in an upper voice, the intervals go from large to small. This is because suspensions always resolve *down* by step. When you measure a downward resolution against a lower voice, the intervals get smaller as the upper voice moves *closer* to the bass. When you measure a downward resolution against a higher voice, the intervals get larger as the bass moves *away* from the upper voice.
- Assuming that there are more than two voices, there will always be a second and a third present above a suspension in the bass. We say that you measure it against the most dissonant interval, but the reality is that it is always a 2-3 suspension if the suspension is in the bass.

### Adding inner voices

To this point, everything that we have discussed has been based on a two-voice model, but to move into full diatonic harmony, we need to add inner voices and fully flesh out the harmonies. When doing this, there are certain rules that create better voice-leading and voicings when followed, but please note that these rules are generally strong suggestions rather than hard and fast rules. Good composers constantly bend or break these rules if it better serves their ideas.

### Doubling

When voicing triads in four-part harmony, at least one note must be doubled.

1. Doubling the root is the ideal choice.
2. Doubling the fifth is the second best option.
3. Doubling the third is generally *unacceptable*, although there are certain corner cases in which this can be necessary. As a rule of thumb, try to never double the third. The reason for this will be clear after we talk about chordal resolutions in Unit 7a.
4. If you need to omit a voice, the fifth is the only option, because the root and third are required to define the chord. Diminished triads are the only diatonic harmony that require a fifth as well.
4. You can triple the root if necessary, but this creates a difficult voicing to continue writing afterwards. This is most commonly used as an ending chord of the piece (often after a V7).

Doubling in a seventh chord is similar, but because you have four notes for four voices, there is less freedom.
1. There must always be a root, third, and seventh in the chord, because without any of them, the chord is no longer a functioning seventh chord.
2. If necessary, you can omit the fifth.
3. If the fifth is ommitted, the root is the only chord tone that can be doubled. Never double the third or the seventh.

### Spacing

Spacing is a relatively straightfoward idea, but it took the class quite a few tries to come up with working definitions based on the examples. The final conclusions were:
- The bass *can* be as far from the tenor as needed.
- Tenor and alto *cannot* have more than an octave between them.
- Soprano and alto *cannot* have more than an octave between them.
- Tenor and soprano *can* have more than an octave between them.
  - When the tenor and soprano are within an octave of each other, we call this a *closed voicing*.
  - When the tenor and soprano are more than an octave apart, we call this an *open voicing*.

In general, a good voicing will mimic the overtone series on which our harmony is created. This details of this concept are discussed in Unit 8, but a general rule of good voicing is to allow wider intervals between lower voices and narrower intervals between high voices.

### Range

The ranges for each voice in the examples are conservative, but will serve us well in our beginning part-writing. These are highly dependent on the intended performers.

### Voice-crossing

There was no easy way to notate this in the examples, but voice-crossing should be avoided unless absolutely necessary. It is almost never absolutely necessary.