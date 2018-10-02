---
layout: chapter
title: Lesson 7a - Diatonic Progressions Derived from Circle-of-fifths Voice-leading
abc: true
---

We now have the analytical foundation and tools to begin studying harmonic *function*--or how and why a chord works with other chords to build tonality. In this lesson, we will derive the basic aspects of function by combining two major concepts from previous units:
1. As shown in the two-part examples in [Unit 6b]({{ site.baseurl }}/06-intro-harmonic/b1-diafuncvoicelead.html), the progression from V to I creates a strong and natural sense of resolution. There are many reasons we hear this progression as a strong cadence, but perhaps the strongest reason is the voice-leading between the V<sup>7</sup> and I chords--meaning the way in which individual pitches naturally pull toward each other. 
2. When written as a scale, diatonic collections are simply a sequence of five whole steps and two half-steps--major scale, for example, is W-W-H-W-W-W-H--but as we determined in [Unit 2c]({{ site.baseurl }}/02-int-scales-keys/c1-keys.html), you can find all seven pitches in the diatonic collection by altering a a single half-step in a circle-of-fifths. This alteration changes one of the P5 intervals to a d5, and it is these two pitches within the diatonic collection, `ti` and `fa`, that establish the voice leading that pulls V<sup>7</sup> to I and therefore around which tonal harmony is constructed.

As a side note, the significance of cultural conditioning cannot be overlooked. A person raised around *any* style of music will be conditioned to hear the tendencies used in that music as a natural progression, and this holds true for those raised around music descended from the diatonic tradition. This does not change the importance of voice-leading in forming these progressions, but it is worth remembering the difference between laws, rules, and strategies discussed in the first reading from Unit 6.

## Dominant to tonic progressions

In the examples below, we will demonstrate how these half-steps create this foundation. If you understand the voice-leading principles that pull the V chord into the I chord, you can then extend these rules to create the basic progression from which all diatonic harmony evolves.

### Goals for this topic

**This example has two idealized progressions of a V chord resolving to a I chord: one as triads and the other with a seventh chord. Study how each voice resolves. It is tempting to focus on which scale degree resolves to which scale degree, but this does not provide a complete explanation. Instead focus on how each chordal member resolves as in the progression.**

{% capture ex1 %}X:1
T:Basic V to I progressions
M:4/4
L:1
K:C
V:1
[BG]| [cE]|| [BF]| [cE]|]
V:2 clef=bass
[G,D]| [C,C]|| [G,D]| [C,C]|]
w:C:V I V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**The next example focuses on a simple triadic progression and follows the circle-of-fifths backwards to add a ii chord. Does this follow the voice-leading explanation that you created after looking at the first examples? If not, how does it differ? After you have studied this, try creating a voicing for a vi chord.**

{% capture ex2 %}X:2
T:Adding the ii chord
M:4/4
L:1
K:C
V:1
[FA]| [BG]| [cG]|]
V:2 clef=bass
[D,D]| [G,,D]| [C,E]|]
w:C:ii V I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**The next example adds the vi chord. Were you able to correctly construct this using your voice-leading rules? Is it correct to explain the voice-leading of the progression using chordal members or scale degrees? If you continue around the circle-of-fifths, what would the voicing for the next chord be?**

{% capture ex3 %}X:3
T:Adding the vi chord
M:4/4
L:1
K:C
V:1
[EA]| [FA]| [BG]| [cG]|]
V:2 clef=bass
[A,,C]| [D,D]| [G,,D]| [C,E]|]
w:C:vi ii V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

**Again, we ask the same questions. Were you able to correctly add the iii chord using your voice-leading rules? Is it correct to explain the voice-leading of the progression using chordal members or scale degrees?**

{% capture ex4 %}X:4
T:Adding the iii chord
M:4/4
L:1
K:C
V:1
[EG]| [EA]| [FA]| [BG]| [cG]|]
V:2 clef=bass
[E,B,]| [A,,C]| [D,D]| [G,,D]| [C,E]|]
w:C:iii vi ii V I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

**Beyond the iii chord, the voice-leading runs into an issue with harmonic function. While it is possible to continue this pattern through these two chords, in tonal harmony, the IV and vii<sup>o</sup> chords actually function most often as if they are extensions of the ii<sup>7</sup> and V<sup>7</sup> chords respectively. Look at the following example to see voice-leading using both of these chords. The first measure uses the ii<sup>7</sup> and V<sup>7</sup> chords as part of a diatonic progression, but the second progression substitutes the IV for the ii<sup>7</sup> chord and the vii<sup>o</sup> chord for the V<sup>7</sup> chord. After looking at this example, explain why IV and vii<sup>o</sup> function similarly to ii<sup>7</sup> and V<sup>7</sup>.**

*Please note that to demonstrate how closely related these chords are, many voice-leading rules are being broken in this example -- most notably the parallel octaves between the soprano and bass between vii<sup>o</sup> and I. This is for demonstration purposes only, do not assume that this good voice-leading for IV or vii<sup>o</sup>. We will discuss the rules of voice-leading in this style when we study part-writing in Units 10 and 11.*

{% capture ex5 %}X:5
T:Adding the IV and viio chords
M:4/4
L:1
K:C
V:1
[Fc]| [BF]| [cE]|| [Fc]| [BF]| [cE]|]
V:2 clef=bass
[D,D]| [G,,D]| [C,C]|| [A,,C]| [B,,D]| [C,C]|]
w:C:ii7 V7 I IV6 viio I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

**These examples allow you to create a basic framework for diatonic harmonic progressions. Use these progressions here to create a flowchart for standard diatonic progressions that includes all diatonic harmonies. Note that there are notable exceptions that are commonly used in diatonic harmony, so please discuss these with your instructor to add the missing exceptions.**

## Conclusions

As we look at implied harmony in two-voice counterpoint, we can demonstrate that simple voice-leading is all that is necessary to *imply* diatonic function. If we take that further, we should be able to create the fundamentals of harmonic progression using the voice-leading inherent in diatonic systems.

Beginning theory students often learn two general rules of thumb for voice-leading:
- `ti` resolves to `do`
- `fa` resolves to `mi`

This is helpful to get students thinking about voice-leading in the most basic of ways, but it only applies to a specific, albeit common, set of circumstances that may arise in common practice harmony. For example, look at the following two-voice outline of one of the most common progressions in tonal music.

{% capture ex6 %}X:6
T:Implied harmonies from two voices
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
AB| c2|]
V:2 clef=bass
F,G,| C,2
w:IV V I|]{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

In this progression the movement of the bass voice has `fa` moving to `sol`, and this is a normal, acceptable progression. This implies that there is far more detail necessary to understand voice-leading in harmony than general rules of thumb.

## Developing Progressions Based on Voice-leading

By studying the voice-leading of a simple V (or V<sup>7</sup>) to I progression, the students proposed a couple of rules -- that *do not* rely on scale degrees -- to explain the voice-leading between the two chords.
- For chords that have roots separated by a P5:
    - The *seventh* of the first chord resolves to the *third* of the second chord.
    - the *third* of the first chord resolves to the *root* of the second chord.
    - If both chords are in root position, the bass voice moves from the *root* of the first chord to the *root* of each chord.

This is the beginning of a *circle-of-fifths progression*: a progression in which each chord root follows the circle of fifths. Using these new rules in combination with the general voicing rules that the topics from [Unit 6b]({{ site.baseurl }}/06-intro-harmonic/b1-diafuncvoicelead.html), you should be able to create a voicing for the chord that precedes the V chord in a circle-of-fifths progression. A P5 above `G` is `D`, and the chord built off of that pitch is the ii chord.

There are two likely voicings for creating this next chord in the progression:
{% capture ex7 %}X:7
T:Two possible voicings for a ii chord
M:4/4
L:1/2
K:C
V:1
[Fd]| [BG]| [c2G2]|| [FA]| [BG]| [c2G2]|]
V:2 clef=bass
[D,A,]| [G,D]| [C,2E2]|| [D,D]| [G,D]| [C,2E2]|]
w:C:ii V I ii V I{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

Some will prefer the sound of the first voicing, probably because they find the melodic shape in the soprano more interesting. Unfortunately, this voicing creates multiple issues. Not only are the parts more difficult to sing, particularly for the tenor voice, but unacceptable parallel perfect 5ths are created between the tenor and bass voices. 

The second progression has less melodic variety, but it provides the smoothest, easiest voice-leading for each part with no voice-leading errors. I asked the class to add two more chords to the progression, vi and iii, and they were able to create these without much issue by following the pattern that they had created.

From this, we demonstrated the process by which voice-leading creates one of the most fundamental progressions of all diatonic harmony, the circle-of-fifths progression.
  
{% capture ex8 %}X:8
T:Adding the iii chord
M:4/4
L:1
K:C
V:1
[EG]| [EA]| [FA]| [BG]| [cG]|]
V:2 clef=bass
[E,B,]| [A,,C]| [D,D]| [G,,D]| [C,E]|]
w:C:iii vi ii V I{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}

## Adding IV and vii<sup>o</sup>

It is possible to continue this pattern backwards to add the last two diatonic chords, IV and vii<sup>o</sup>, but these chords actually function differently. Instead, the IV and vii<sup>o</sup> chords function similarly to there two functional counterparts, ii<sup>7</sup> and V<sup>7</sup>. The logic is fairly simple, if you remove the root from a ii<sup>7</sup> chord, `D-F-A-C` in C major, you are left with a IV chord, `F-A-C` in C major. Likewise, if you remove the root from a V<sup>7</sup> chord, you are left with a vii<sup>o</sup> chord. When we add these to our harmonic progression flowchart, we get our basic outline for harmonic progressions.

| (*unnamed*) | (*unnamed*) | pre-dominant | dominant | tonic |
--- | --- | --- | --- | --- |
| iii | vi | ii | V | I |
| | | IV | vii<sup>o</sup> | |

Using just this flowchart, you can build basic chordal progressions for a given melody by harmonizing the pitches with the correct progressions. Please note that the I chord can go jump back to anywhere in the progressions.

## Adding in the Common Exceptions

There are a few common exceptions that should be added to this progression flowchart. We will discuss how these are used as we work through their appropriate topics (e.g. cadences, chordal substitutions), but for now, please add them to your list of possible progressions.
- chords that have the same function can move to each other
    - ii can move to IV, and IV can move to ii.
- V can move to vi 
    - This is most commonly used at the end of a phrase. In this case, vi is "replacing" a I chord, so it must be used correctly. See 7c (later in this unit) for a full explanation of cadences.
- IV can go to I
    - This is most commonly used at the end of a phrase, and in this case, IV is "replacing" the V chord. This is another cadence, so it must be prepared properly. It better to avoid using this progression in the middle of a phrase, so in your early attempts at part-writing, do not attempt to use this.
- RARE: iii can move to IV
    - It is difficult to use this without creating multiple voice-leading issues, so in your early attempts at part-writing, do not attempt to use this.

## Changes in Minor

Minor follows all of the same progressions, but the chord qualities change to match the naturally occurring pitches in the key signature. Please remember that minor keys must have a major V chord and diminished vii chord to function diatonically. This means that both of these chords are built using the raised seventh scale degree.

| (*unnamed*) | (*unnamed*) | pre-dominant | dominant | tonic |
--- | --- | --- | --- | --- |
| III | VI | ii<sup>o</sup> | V | i |
| | | iv | vii<sup>o</sup> | |