---
layout: chapter
title: Lesson 6b - Establishing Diatonic Function through Voice Leading
abc: true
---
<!--This should probably be broken into two parts: establishing diatonic function and then embellishing tones. Embellishing tones could be combined with voice-leading errors for its own unit, and then Roman numerals could be moved to the harmonic function unit...maybe? Would need to look at how that would affect the descriptions within function; maybe the Roman numerals are needed first. -->

If we think back on our progression through the course thus far, we began by studying individual pitches, then combined those pitches into intervals, and then assembled those intervals sequentially and simultaneously to create melodies and chords respectively. Next, we studied a simplified version of counterpoint in order to examine how the combined vertical and horizontal aspects of music interact to create basic tonality. While counterpoint provides a framework for understanding harmony, it is primarily a study of how the horizontal aspect of music, melody, combines and *implies* harmony; it does not establish the vertical aspect of music, harmony, as a standalone concept.

Because the Roman numeral system allows us to classify and label *context and function*, we can use it explore how harmonies function within a diatonic style, independent of melody.

## Harmonic functions in diatonic music

In diatonic music, there are three basic categories of harmonic function: *tonic*, *dominant*, and *pre-dominant*. 
- *Tonic* (**T**) harmonies feel stable and final.
  - This is primarily the I chord, but in some circumstances, this can include the vi chord.
- *Dominant* (**D**) harmonies have a strong tonal gravity to resolve to the *tonic* harmony*
  - This includes the V and vii<sup>o</sup> chords.
- *Pre-dominant* (**P**) harmonies are unstable and have a tonal gravity to resolve to *dominant* harmonies.
  - This includes the ii and IV chords, but can occasionally include the vi chord.
  - Note that there is a difference between the words "pre-dominant" and "predominant".

Counterpoint provides a clear starting point for exploring these diatonic functions. If we look at the basic interactions between two voices we can begin to understand how voice-leading creates harmonic function and how certain chords fit into their roles as tonic, dominant, and pre-dominant chords. Finally, by adding two more voices to this soprano/bass framework, we can then begin looking at fully functional harmony in one of its most basic forms--the four-part chorale.

## Implied harmony in two parts

<!-- When doing the following example, make sure that the class understands that each measure has the same two harmonies. It won't make sense to them otherwise. -->

**Each measure of this first example is a two-voice version that implies the same two harmonies repeatedly.**
- Which two harmonies do you think these measures imply? 
  - What are the Roman numerals and inversion figures for each measure?
  - Is there more than one option for any of the harmonies?
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

You can also draw some simple conclusions about voice-leading from looking at these examples--such as `ti` resolving to `do`, or `fa` resolving to `mi`--but be careful not to generalize to much; these are going to be correct for V<sup>7</sup> to I as they are in these examples, but these are only *contextual* rules for those scale degrees. We will explore the true nature of tendency tones and their resolution in Unit 7. 

#### Cadences

Because of the importance of the V-I progression, we should introduce an important term in understanding harmony: the *cadence*. We will explore cadences further in the next unit, but for now, you may think of a cadence as a harmonic progression used to conclude a musical phrase. There are many types of cadences, but all of the progressions above are *authentic cadences*--cadences that have a V chord moving to a I chord. Bass movement is a key factor in determining the strength of a cadence. For example, measures 1 and 3 in the examples likely sound stronger to you than the last measure. The last measure not only lacks `sol` to `do` in the bass, it also does not have a tonic in the final chord. We will return to this idea when discussing cadences in detail in Unit 7c.

## Embellishing Tones in Cadential Motion

**The next example contains the same harmonies from the first example, but we now with an additional pitch to each measure.**
- Are the new intervals consonant or dissonant?
  - For each new pitch, do you feel it strengthens or weakens the cadence?
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
Bc|| F/2D/2E|| d/2f/2e|| Bc|| Bc|| G/2A/2G|]
V:2 clef=bass
"M3"G,/2"M6"D,/2"P8"C,|| "m7"G,/2"P5"G,/2"M3"C,|| "P5"G,/2"m7"G,/2"M3"C,|| "+4"F,/2"M6"D,/2"m6"E,|| "P8"B,/2"M2"A,/2"P4"G,|| "M2"F,/2"M3"F,/2"m3"E,|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

### Conclusion

As we first begin to study non-chord tones, the most important thing to remember is what the name "non-chord tone" emphasizes. **NCTs must not belong to the chord.** The first four measures added decorations that were simply part of the V or V<sup>7</sup> chords that were already implied. Of note, you will likely hear the added `F` in measures 3 and 4 as changing the harmony from V to V<sup>7</sup>, meaning that the embellishment was still part of the harmony. 

In measure 5 however, the A on beat 2 is certainly not part of the implied V or V7 harmonies. An embellishment that does not belong to the harmony is called a *non-chord tone* (NCT), and there a variety of NCTs that can be classified by how they are approached and left. The measure 5 NCT is called a *passing tone*, because it has a passing motion, so we can define a passing tone as a non-chord tone that is *approached by step* and *left by step in the same direction*. 

The final measure also clearly contains a non-chord tone, because the `A` can not be incorporated into a V or V<sup>7</sup> chord. This is an example of a *neighbor tone*--a non-chord tone that is *approached by step* and *left by step in the opposite direction*.

A final reminder: always make sure that the pitch is not actually a chord tone! This is one of the most common mistakes for beginning analysts.

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

After looking at the examples for suspensions, it may seem that a *suspension* is a pitch that is tied over from the previous chord. This is on the right track, but defining a suspension requires considerably more information. 

With this in mind, a suspension must have all three of the following qualities to be considered a suspension:
- It must start as a *chord tone* in the previous chord and then remain unchanged into the new chord.
- It must create a *non-chord tone* at the beginning of the new chord.
- It must then resolve down by step to a chord tone of the new chord.

Of note, it is a common misconception among students that a suspension is only present if you see a *tied* note. This is not true; the tone can be re-articulated.

These three rules directly relate to the terminology that we use to describe the three basic components of a suspension:
- *Preparation* - A chord tone that occurs as part of a chord before the suspension.
- *Suspension* - A non-chord tone that occurs at the moment that all other voices change to the new chord. This tone must be carried over from the previous chord, but it can be re-articulated.
- *Resolution* - The non-chord tone then resolves downward by step to a chord tone.

There are many common mistakes when creating or analyzing suspensions:
- There must be two chords. You cannot have a suspension with only one chord.
- It must resolve downward. If it resolves upward, it is a different kind of non-chord tone.
- It must resolve by step.

#### Labeling suspensions

Once you have familiarized yourself with these three concepts, review the examples above to ensure that you understand the form of a suspension. While doing this, you will notice that each of the suspensions is labeled with a pair of numbers in addition to the word *sus*.

Because suspensions can take many forms, we apply intervallic labels. When the suspension is in an upper voice, we always label the intervals of the suspension and its resolution against the *bass* meaning that the intervals will move from large to small (e.g. 4-3, 7-6, 9-8, etc.). When a suspended note is in the bass voice, however, we label the intervals against the most dissonant interval which means that the intervals will move from small to large (e.g. 2-3). This is because suspensions always resolve *down* by step. When you measure a downward resolution in an upper voice against a lower voice, the intervals get smaller as the upper voice moves *closer* to the bass. When you measure a downward resolution against a higher voice, the intervals get larger as the bass moves *away* from the upper voice.

Of note, because we use the most dissonant voice to label suspensions in the bass, you will use the "2-3" label in the vast majority of this type of suspension. These intervals will be present for suspensions resolving to either the root or chordal third as long as the chord is complete. You are unlikely to encounter a suspension above a chordal fifth in the bass because of the usage rules of second inversion chords, and a suspension above the chordal seventh would just be the root of the chord--meaning that it is not a non-chord tone.

The most common suspensions are the 4-3, 7-6, 9-8 (2-1), and 2-3 suspensions, but others can and do occur regularly. 

