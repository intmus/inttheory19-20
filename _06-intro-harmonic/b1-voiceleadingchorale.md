---
layout: chapter
title: Lesson 6b - Voice-leading Considerations in Chorale-style Harmony
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

Counterpoint provides a clear starting point for this exploration. If we think about our progression through the course thus far, we began by studying individual pitches, and then combined pitches into intervals,combined simultaneous intervals into chords, and combined sequential intervals into melodies. Next, the simplified version of counterpoint that we studied allowed us to examine how the vertical and horizontal aspects of music interact to create melody and harmony. While this provides a framework for understanding harmony, it does not seek to establish the vertical aspect of music as its own function.

If we look at the basic interactions between two voices we can begin to understand how voice-leading creates harmonic function and how certain chords fit into their roles in diatonic function. By adding two more voices to this soprano/bass framework, we can then begin looking at fully functional harmony in one of its most basic forms -- the four-part chorale.

## Implied harmony in two parts

**Each measure of this first example is a two-voice version of the same two diatonic harmonies. Start by labeling the intervals between the harmonic intervals.**
- Which two harmonies do you think these measures imply? 
  - Is there more than one option for any of the harmonies?
- What are the Roman numerals and inversion figures for each measure? 
- Are all the intervals consonant? 
  - If not, to which chords do the dissonant intervals belong?  
- Do any particular chord members seem more important than the others? 
- Do any of these measures sound "weaker" than the others?

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

### Conclusion

All of the two-voice counterpoints in the first example implied harmonies of V moving to I in the key of C major. The bass movement of the first three measures highlights this, but even when the bass movement changes, you should still hear the same progression of V to I. From this, you may conclude that two lines--in this case the soprano and bass lines--are enough to imply tonality. You may also notice that the chordal fifth is the least common chordal member in these examples, and as we will see when we begin voicing four-part harmony, the chordal fifth is indeed expendable. The root and third are best at implying a triad, and the seventh is obviously necessary to create a seventh chord.

#### Cadences

Bass movement is a key factor in determining the strength of a cadence. For example, measures 1 and 3 in the first exercise above likely sound stronger to you than the last measure. The last measure not only lacks `sol` to `do` in the bass, it also does not have a tonic in the final chord. We will return to this idea when discussing cadences in detail in Unit 7c.

## Non-Chord Tones in Cadential Motion

**The next example contains the same harmonies from the first example, but we now with an additional pitch to each measure. Again, start by labeling all of the harmonic intervals.**
- Are the new intervals consonant or dissonant, and how does this line up with how you are hearing? 
- Which, if any, of these "new" notes belong to the chords that you assigned in the previous example? 
  - From this, you can label what you consider to be *chord tones* and *non-chord tones*--chord tones are pitches that belong to the harmony, and non-chord tones do not.
- What do intervals of the non-chord tones have in common? 
- Finally, how would you describe the types of motion between the chord tones and non-chord tones?

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

### Conclusion

As we first begin to study non-chord tones, the most important thing to remember is what the name "non-chord tone" emphasizes. **NCTs must not belong to the chord.** The first four measures added decorations that were simply part of the V or V<sup>7</sup> chords that were already implied. Of note, all students heard the added `F` in measures 3 and 4 as changing the harmony from V to V<sup>7</sup>, meaning that the harmony was altered rather than embellished.

Measure 5 continued this idea, but for teaching purposes, I asked them to consider this strictly as a triadic V chord. What does that make the `F`? Of course, it becomes a non-chord tone called a *passing tone*. A *passing tone* is *approached by step* and *left by step in the same direction*. 

One astute student then asked what would happen if we applied the same logic to measures 3 and 4. This was admittedly beyond the scope of what I intended to cover, but because we had briefly discussed the idea of the term *appogiatura* to describe a melodic shape when discussing second species counterpart, I admitted that if the `F` was considered to be a non-chord tone, both measures 3 and 4 would be considered to have a non-chord tone of an *appogiatura*. An *appogiatura* is a non-chord tone that is *approached by leap* and then *left by stepwise motion in the opposite direction*.

The final measure clearly contained an NCT, because the `A` could not be incorporated into a V or V<sup>7</sup> chord. This is an example of a *neighbor tone*: a non-chord tone that is *approached by step* and *left by step in the opposite direction*.

My final reminder to students when looking for non-chord tones: Always make sure that the pitch is not actually a chord tone! This is one of the most common mistakes for beginning analysts.

## Suspensions

**The suspension is another type of non-chord tone. Each of the measures in the next example are grouped in pairs to demonstrate how suspensions are formed. The first measure is a simple two-voice harmony from the examples above, but the next measure adds a suspension to that framework.**
- How would you define a suspension? What are the three parts of any suspension? 
- How do we determine the labels (i.e. numbers after the word *sus*)?

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

### Conclusion

After looking at the examples for suspensions, it may seem that a *suspension* is a pitch that is tied over from the previous chord. This is on the right track, but defining a suspension requires considerably more information. The first and most easily dispelled misconception is that it must be *tied*; the tone can be re-articulated. 

With this in mind, a suspension must have all three of the following qualities to be considered a suspension:
- It must start as a *chord tone* in the previous chord and then remain unchanged into the new chord.
- It must create a *non-chord tone* at the beginning of the new chord.
- It must then resolve down by step to a chord tone of the new chord.

These three rules directly relate to the terminology that we use to describe the three basic components of a suspension:
- *Preparation* - A chord tone that occurs as part of a chord before the suspension.
- *Suspension* - A non-chord tone that occurs at the moment that all other voices change to the new chord. This tone must be carried over from the previous chord, but it can be re-articulated.
- *Resolution* - The non-chord tone then resolves downward by step to a chord tone.

There are many common mistakes when creating or analyzing suspensions:
- There must be two chords. You cannot have a suspension with only one chord.
- It must resolve downward. If it resolves upward, it is a different kind of non-chord tone.
- It must resolve by step.

#### Labeling suspsensions

Once you have familiarized yourself with these three concepts, review the examples above to ensure that you understand the form of a suspension. While doing this, you will notice that each of the suspensions is labeled with a pair of numbers in addition to the word *sus*.

Because suspensions can take many forms, we apply intervallic labels. When the suspension is in an upper voice, we always label the intervals of the suspension and its resolution against the *bass* meaning that the intervals will move from large to small (e.g. 4-3, 7-6, 9-8, etc.). When a suspended note is in the bass voice, however, we label the intervals against the most dissonant interval which means that the intervals will move from small to large (e.g. 2-3). This is because suspensions always resolve *down* by step. When you measure a downward resolution in an upper voice against a lower voice, the intervals get smaller as the upper voice moves *closer* to the bass. When you measure a downward resolution against a higher voice, the intervals get larger as the bass moves *away* from the upper voice.

Of note, because we use the most dissonant voice to label suspensions in the bass, you will use the "2-3" label in the vast majority of this type of suspension. These intervals will be present for suspensions resolving to either the root or chordal third as long as the chord is complete. You are unlikely to encounter a suspension above a chordal fifth in the bass because of the usage rules of second inversion chords, and a suspension above the chordal seventh would just be the root of the chord--meaning that it is not a non-chord tone.

The most common suspensions are the 4-3, 7-6, 9-8 (2-1), and 2-3 suspensions, but others can and do occur regularly. 

## Voice-leading errors

**Our final voice-leading considerations arise when adding inner voices to our soprano-bass counterpoint. In the following example, each staff system highlights a different voicing error.**
- Compare the correct measures to the incorrect measures to come up with descriptions of the first two basic voicing rules of *doubling* and *spacing*. 
- Because *range* is a simple maximum and minimum, I have listed conservative estimates for each voice part. 
  - These can vary widely depending on the skill level of the intended performers but will be sufficient for our early exercises in part-writing.

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

### Conclusions 

To this point, everything that we have discussed has been based on a two-voice model, but to move into full diatonic harmony, we need to add inner voices and fully flesh out the harmonies. When doing this, there are certain rules that create better voice-leading and voicings when followed, but please note that these rules are generally strong suggestions rather than hard and fast rules. Good composers constantly bend or break these rules if it better serves their ideas.

#### Doubling

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

#### Spacing

Spacing is a relatively straightfoward idea, but it took the class quite a few tries to come up with working definitions based on the examples. The final conclusions were:
- The bass *can* be as far from the tenor as needed.
- Tenor and alto *cannot* have more than an octave between them.
- Soprano and alto *cannot* have more than an octave between them.
- Tenor and soprano *can* have more than an octave between them.
  - When the tenor and soprano are within an octave of each other, we call this a *closed voicing*.
  - When the tenor and soprano are more than an octave apart, we call this an *open voicing*.

In general, a good voicing will mimic the overtone series on which our harmony is created. This details of this concept are discussed in Unit 8, but a general rule of good voicing is to allow wider intervals between lower voices and narrower intervals between high voices.

#### Range

The ranges for each voice in the examples are conservative, but will serve us well in our beginning part-writing. These are highly dependent on the intended performers.

#### Voice-crossing

There was no easy way to notate this in the examples, but voice-crossing should be avoided unless absolutely necessary. It is almost never absolutely necessary.