---
layout: chapter
title: Lesson 7a - Diatonic Progressions Derived from Circle-of-fifths Voice-leading
abc: true
---

# Class discussion

As we looked at implied harmony in two-voice counterpoint, we demonstrated that simple voice-leading is all that is necessary to *imply* diatonic function. If we take that further, we should be able to create the fundamentals of harmonic progression using the voice-leading inherent in diatonic systems.

Beginning theory students often learn two general rules of thumb for voice-leading:
- `ti` resolves to `do`
- `fa` resolves to `mi`

This is helpful to get students thinking about voice-leading in the most basic of ways, but it does not accurately reflect common practice harmony. For example, look at the following two-voice outline of one of the most common progressions in tonal music.

{% capture ex1 %}X:1
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
{% include abc-example.html number="1" abc=ex1 %}

In this progression the movement of the bass voice has `fa` moving to `sol`, and this is a normal, acceptable progression. This implies that there is far more detail necessary to understand voice-leading in harmony than general rules of thumb.

## Developing Progressions Based on Voice-leading

By studying the voice-leading of a simple V (or V<sup>7</sup>) to I progression, the students proposed a couple of rules -- that *do not* rely on scale degrees -- to explain the voice-leading between the two chords.
- For chords that have roots separated by a P5:
    - The *seventh* of the first chord resolves to the *third* of the second chord.
    - the *third* of the first chord resolves to the *root* of the second chord.
    - If both chords are in root position, the bass voice moves from the *root* of the first chord to the *root* of each chord.

This is the beginning of a *circle-of-fifths progression*: a progression in which each chord root follows the circle of fifths. Using their new rules in combination with the general voicing rules that we discussed in Unit 6b, I then asked the class to create a voicing for the chord that would preceded the V chord in a circle-of-fifths progression. A P5 above `G` is `D`, and the chord built off of that pitch is the ii chord.

The class came up with two voicings that they liked:
{% capture ex2 %}X:2
T:Two possible voicings for a ii chord
M:4/4
L:1/2
K:C
V:1
[Fd]| [BG]| [c2G2]|| [FA]| [BG]| [c2G2]|]
V:2 clef=bass
[D,A,]| [G,D]| [C,2E2]|| [D,D]| [G,D]| [C,2E2]|]
w:C:ii V I ii V I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

Some of the class preferred the sound of the first voicing, probably because they found the melodic shape in the soprano more interesting. Unfortunately, this voicing created multiple issues. Not only are the parts more difficult to sing, particularly the tenor voice, but parallel 5ths are created between the tenor and bass voices. 

The second progression has less melodic variety, but it provides the smoothest, easiest voice-leading for each part with no voice-leading errors. I asked the class to add two more chords to the progression, vi and iii, and they were able to create these without much issue by following the pattern that they had created.

From this, we demonstrated the process by which voice-leading creates one of the most fundamental progressions of all diatonic harmony, the circle-of-fifths progression.
  
{% capture ex3 %}X:3
T:Adding the iii chord
M:4/4
L:1
K:C
V:1
[EG]| [EA]| [FA]| [BG]| [cG]|]
V:2 clef=bass
[E,B,]| [A,,C]| [D,D]| [G,,D]| [C,E]|]
w:C:iii vi ii V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

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

# Further reading

## From *Open Music Theory*

Analyzing harmony in a piece or passage of music involves more than labeling chords. Even the most basic analysis also involves *interpreting* the way that specific chords and progressions function within a broader context. Ultimately, no analysis is complete until individual musical elements are interpreted in light of the work as a whole and the historical setting in which the piece occurs. But this resource simply walks through the steps of performing a basic harmonic analysis, interpreting each chord and chord progression in light of the musical phrase in which it occurs.

The first step in a harmonic analysis is to *identify phrases*. For the most part, that means beginning by identifying *cadences*. However, not every type of phrase ends with a cadence, so sensitivity to theme types is important. In classical instrumental music, that means listening for [period- and sentence-like structures](classicalThemes.html). In Classical or Romantic music with text, that means listening in particular for the ends of poetic lines and melodic phrases.

Once you have identified the musical phrases, it can be helpful to perform a harmonic reduction (thoroughbass reduction, for example) for each phrase. Below the score/thoroughbass line, write the appropriate Roman numeral, **T/S/D** label for each chord, and/or an uninterpreted functional bass symbol for each chord (**T1 T3 S4** etc.). [This handout]({{ site.baseurl }}/images/Handouts/HarmoniesByBassScaleDegree.pdf) can help you determine the functions of chords in the thoroughbass reduction.

Next identify the general harmonic structure of each phrase. Typical phrases in classical music will do one of the following:

- prolong tonic without a cadence (a classical *presentation* phrase, for example)  
- progress toward an authentic cadence (ending with **V<sup>(7)</sup> I**, **D5 T1** in functional bass)  
- progress toward a half cadence (ending with **V**, **D5** in functional bass)

If the phrase prolongs tonic (no cadence), label the *entire* phrase **T–––.**

If the phrase ends with a cadence, identify the *cadential progression*. This includes the last chord of the tonic zone, optionally followed by a subdominant chord or zone (most often a single chord), and a required dominant zone (most often a single chord or compound cadence formula). Half-cadence phrases end there. Authentic-cadence phrases continue on to a final tonic zone (usually a single chord). 

The the **(P) D T** of the cadential progression should be labeled as such. Once the cadential progression is identified, everything before it is labeled as tonic prolongation. Regardless of whether it is contrapuntal prolongation, a subsidiary progression, or a combination of the two, it will be labeled **T–––.** (See [Harmonic syntax – prolongation](http://openmusictheory.com/harmonicSyntax2.html) if those terms are unfamiliar to you.)

Thus a phrase ending with a half cadence will have a functional analysis that looks like:

> T—————— (P) D 

A phrase ending with an authentic cadence will have a functional analysis that looks like:

> T—————— (P) D T

Following is an excerpt from the opening of Haydn's Piano Sonata in C Major, Hob. HVI:21, I. Chords are labeled with Roman numerals and a **T/S/D** functional label for each chord. The tonic prolongation is shown below that with a T followed by a line for the duration of the tonic zone. The cadential progression is comprised of the last tonic chord (m. 4) through **S D T** to the **PAC** in m. 6.

[![](/images/harmony/XVI-21-prolongation.png)](/images/harmony/XVI-21-prolongation.png)

<iframe src="https://embed.spotify.com/?uri=spotify:track:6k7Sa5GrujYsn7Ul85gjWQ" width="300" height="80" frameborder="0" allowtransparency="true"></iframe><br/>

*Harmonic syntax* concerns the norms or principles according to which harmonies (chords) are placed into meaningful successions. These norms include progressions that are more or less common than others. Those norms generate expectations for listeners familiar with the style: if **IV–V** is more common than **IV–VI**, the appearance of a **IV** chord generates an expectation that the next chord is more likely to be **V** than it is to be **VI**.

In Western classical music, harmonies generally group into three *harmonic functions* — tonic (T), subdominant (S), and dominant (D) — and these functions group together chords that progress to and from other chords in similar ways. For example, since **II** and **IV** are both subdominant chords, they will participate in many of the same kinds of chord progressions, and at times can be substituted for each other with only a minimal change to the musical effect.

On a local level (chord-to-chord progressions), we can summarize the tendencies of these functions with the cycle **T–S–D–T**. That is, harmonies tend to progress through a cyclical progression of those three functions:

> **T → S → D → T →** and so on . . .

That does not rule out T progressing to D, D progressing to S, etc. But it does mean that those progressions tend to be less common, at least in classical music.

Higher-level musical structures also impact the norms according to which these harmonic functions progress. For now, we will consider one higher-level structure that influences chord-progression tendencies — the phrase — and we will limit our study to isolated, complete, self-sufficient phrases. This is an idealized, oversimplified setting — like strict voice-leading — that is useful for learning the basics. Some such phrases even exist in real music! But most of the time there are a number of competing factors that influence the chord-progression strategies employed by a composer at any given moment. However, the idealized phrase is a helpful starting point. Future study will explore how classical composers employ harmonic progressions in larger musical works that combine multiple phrases (which are not self-sufficient) into larger themes and movements.


## The idealized phrase

The *idealized phrase* (also called the *phrase model*) is a single musical phrase that progresses through an entire cycle of harmonic functions, beginning and ending on tonic. (Strict voice-leading exercises are such phrases.) These phrases begin with a point of stability (tonic), move away from that stable point, and then eventually lead to a point of high tension and resolution (an *authentic cadence*). This pattern of stability–instability–stability, or rest–motion–rest, with a single goal at the end, should be familiar both from species counterpoint and from strict keyboard-style voice-leading. (This pattern also governs large-scale formal structures in classical music.)

The simplest phrase that exhibits this complete harmonic cycle is a tonic-dominant-tonic progression: **I–V–I.** This phrase begins and ends with the most stable harmony (**I**), and includes an *authentic cadence* (**V–I**). The **V** is the high point of instability, containing the tendency tone (*ti*) that most strongly points to the final point of arrival (*do*, or tonic).

This harmonic cycle can be expanded by inserting a subdominant chord, a destabilized tonic chord, or both, as in the following examples: 

> **I IV V I**  
> **I II V I**  
> **I VI V I**  
> **I VI II V I**

In *functional bass* terms, any harmonic progression that follows the pattern

> **T1 → (S_) → D5 → T1**

can serve as the basis for a complete idealized phrase. (Harmonies in parentheses are optional.)

Phrases are seldom 3–5 chords long, however, and a harmonic function can be expressed by more than a single chord. Thus we can understand the harmonic functions not simply as chords, but as *zones* of varying length in a phrase, which can be created by a number of chords or short chord progressions. More generally, then, our idealized musical phrase contains a single progression of functional zones **T → (S) → D → T**, begins with **T1**, and ends with an authentic cadence (**D5–T1**), as seen in the example below.


## Triggering and prolonging harmonic functions in an idealized phrase

To establish, or trigger, a harmonic functional zone, composers tend to use *a fixed scale degree in the bass*. In other words, tonic tends to be triggered by **T1** (always **I**), subdominant by **S2** or **S4** (including a variety of **II** and **IV** chords, in in root position or inversions, with and without sevenths), and dominant by **D5** (**V**, with or without a seventh, or a [*compound cadence*](cadenceTypes)). These four categories of chords — **T1**, **S2**, **S4**, and **D5** — are called *functional chords* (because they trigger the function) or *cadential chords* (because they can participate in a cadence). 

Other chords are often called *contrapuntal chords* or *embellishing chords*, and are typically used to *prolong* a function throughout the zone. 

Functional prolongations are shown in a harmonic analysis by writing/typing T, S, or D underneath the individual chord labels (Roman numerals or functional bass) and extending a line from the beginning of the functional zone to the end.

The following excerpt is from Mozart's Piano Sonata in A Major, K. 331, I., mm. 1–4, with a harmonic reduction and analysis provided below the original score. Such an analysis is called an *interpreted* harmonic analysis, because the harmonies are interpreted according to the way they behave in the phrase, rather than merely labeled. In this phrase, note the following:

- The tonic zone is triggered by a root-position tonic triad (**I** or **T1**).  
- Contrapuntal dominant chords (**D7** — first-inversion dominant chords) create a passing bass motion between the opening **I** chord, the **vi** in m. 3, and the return of **I** in m. 4.  
- The [cadential progression](harmonicAnalysis) begins in m. 4 with the move from **I** to <strong>ii<sup>6</sup></strong> (**S4**) and then to the cadential six-four and dominant triad (**D5**). Note that the entirety of the cadential progression in m. 4 is made up of *cadential chords* — chords with fixed scale degrees in the bass.  
- In contrast, the entire tonic-prolongation zone is made up of *contrapuntal chords* — variable scale degrees in the bass — with the exception of the **I** chord that triggered the tonic function.  
- The **vi** chord is a root-position chord, but still an embellishing chord, while the <strong>ii<sup>6</sup></strong> is an inverted chord, but still a functional/cadential chord. The difference is not the inversion, but the scale degree of the bass.

[![](/images/harmony/k331-reduction.png)](/images/harmony/k331-reduction.png)

<iframe src="https://embed.spotify.com/?uri=spotify:track:5yfZxPrcN0hjwzU1OKIsdQ" width="300" height="80" frameborder="0" allowtransparency="true"></iframe><br/>

Not all classical phrases as neatly fit the general trends outlined in this resource. As discussed in [Style and tendency](tendency), the principles of harmonic syntax are both reliable and bendable/breakable, and it is often the music that bends/breaks the "rules" in interesting ways that we care about the most. So in your own analyses, keep these principles in mind as *general* principles, and simultaneously look for where composers meet these expectations as well as where they break them. 

For more details on the triggering and prolonging of harmonic functions in a classical phrase, see [Harmonic syntax – prolongation](harmonicSyntax2).
