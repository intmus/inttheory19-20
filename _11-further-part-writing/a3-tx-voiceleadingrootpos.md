---
layout: chapter
title: Lesson 11a - Voice-leading for Root Position Triads and Seventh Chords
abc: true
---

# Class discussion 

Before we started our first attempts at part-writing, I asked the class to review the guidelines listed at the top of Example 11a. They were:

In your early part writing, you should strive for a simple, clean texture that:
- follows the standard harmonic progressions outlined by circle-of-fifths progressions
    - correctly uses cadences as well as tonic, dominant, and pre-dominant functions
- has the smoothest possible voice-leading for each line
    - the bass can be slightly more disjunct than the upper parts, particularly when using root-position chords
- does not cross voices
- has no spacing or range errors
- avoids incorrect doubling
- resolves tendency tones correctly
- does not create unacceptable part-writing such as consecutive perfect 5ths/8ves or similar 5ths/8ves

The first question was, "What constitutes "smooth" voice-leading?" *The simple answer is that stepwise (or even static) motion is preferred.* When you are creating a line for a particular voice (i.e. soprano, alto, tenor, bass), you will have few options when choosing what the next pitch will be. It must be a chord-tone, and you must also consider the notes that are already fixed. (Bass lines and melodies are often written first and are therefore unchangeable.) When you add in doubling and range limitations, you will usually have one or possibly two options for smooth (conjunct) voice-leading. 

The other question was "Is there a general rule for the correct for resolution of tendency tones?" Unfortunately, there is no simple answer for this. At its most basic, `ti` resolves up by step, and `fa` resolves down by step. When part-writing, however, this is too simplistic a view. For example, `fa` often moves upward by step to `sol`, either as part of an ascending scalar melodic line or in the bass line when a root-position IV chord moves to a root-position V chord. The next level of thinking would be to say that `ti` and `fa` are tendency tones when they are part of a V<sup>7</sup> chord, so therefore, the rule for tendency tones should be that *chordal thirds* resolve up by step and *chordal sevenths* resolve down by step. This is a better rule, but it also falls apart when we leave circle-of-fifths progressions (chords with roots separated by a descending P5). When a IV chord moves to a V chord, it is impossible for the third to move *up by step* to the root of the V chord. For now, the easiest rule for tendency tones is:
- *Chordal thirds* resolve up by step and *chordal sevenths* resolve down by step *when part of a circle-of-fifths progression*.

## Part-writing

Using our guidelines as a framework for part-writing, we discussed the best order for the process of composing our SATB examples.

If given a melody:
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

If given a harmonic progression (and likely a bass line):
- **Compose a melody** and then check it against your bass line for part-writing errors.
    - This will resemble 1:1 counterpoint, so refer to Unit 5b.
    - Contrary motion against the soprano line is preferred.
- **Fill in the alto and tenor voices.**
    - Refer to the rules for voicing, range, and doubling in Unit 6b.
- When writing your parts, always strive to have voice-leading that is as smooth as possible by emphasizing stepwise motion.
    - Bass lines are the exception and will often have more leaps.

With this in mind, I asked them to harmonize the first example from the previous page, and they came up with the following answer:

{% capture ex1 %}X:1
T:Circle-of-fifths triadic progression
M:4/4
L:1
K:C
V:1
[cE]| [cE]| [dF]| [dG]| [eG]|]
V:2 clef=bass
[C,G,]| [A,,A,]|[D,A,]| [G,,B,]| [C,C]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

The students were surprised by two things:
- How similar almost every groups answer was.
- That this is not as difficult as it first seems.

Because the chord progession provides a vertical framework and smooth voice-leading provides a horizontal framework, most of the work is simply following the pattern correctly. This example is admittedly straightforward because it relies entirely on root-position triads in a circle-of-fifths progression. I next asked them to add two seventh chords along with the rule that the *chordal seventh should resolve down by step*.

{% capture ex2 %}X:2
T:Root-position part-writing with
T:seventh chords and root movement by P4/P5
M:4/4
L:1
K:C
V:1
c| x| x| x| x|]
V:2 clef=bass
[C,]| [A,,]|[D,]| [G,,]| [C,]|]
w:C:I vi7 ii V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

This single new wrinkle created considerably more issues. The first arose between the second and third chords. By placing a chordal seventh in the tenor voice on the vi<sup>7</sup> chord, it locked the voice-leading of that voice into resolving downard by step to the third of the following chord. Because we did not want to double the third on that chord, we could only choose to move to the closest D or A in the alto voice. If we were to move to the A, that would create parallel perfect 5ths with the bass voice, so we could only choose the D for the alto voice.

Example: "Short Chord Progressions"

1a. Key: C

Bass: C3 - F2 - G2 - C3

Roman Numerals: I - IV - V7 - I

- potential problems: the parallel motion from the IV to V7 in root position
  - the V7 can make that problem easier to solve by keeping the F static
  - whenever you have stepwise motion in the bass, parallel motion can be a problem
- functional substitution: when the vi chord substitutes for the I chord

1b. Key: C

Soprano: C5 - D5 - C5 - C5 - B4 - C5

Alto: E4 - G4 - E4 - E4 - D4 - C4

Tenor: G3 - B3 - C4 - G3 - G3 - E3

Bass (given): C3 - G2 - C3 - C3 - G2 - A2

Roman Numerals: I - V - I - I - V - vi (Isub6)

Isub6 means that you take a I chord, put a 6 on top, and the 6 substitutes the nearest chord tone. 
This creates a vi chord. 

2. Key: C

Bass (given): C3 - F2 - G2 - A2

Roman Numerals: I - IV - V - vi 

3. Key: C

Bass (given): C3 - D3 - F4 - G4

Roman Numerals: I - ii - IV - V

Chordal Third to Chordal Third:
- moving from third to third between chords can avoid ppart writing errors
- using open to closed voiceing (or vice versa) to change the texture
    - this cannot be applied to outer voices

Frustrated leading tone:
- when the leading tone does not resolve to the tonic
    - can only be done in the alto or tenor voices
    - Ti resolves to Sol (and sometimes La) instead of Do

Deceptive cadences apply the frustrated leading tone by resolving Ti to La instead of Sol. 

# Further reading

## From *Open Music Theory*

### Harmonic syntax

*Harmonic syntax* concerns the norms or principles according to which harmonies (chords) are placed into meaningful successions. These norms include progressions that are more or less common than others. Those norms generate expectations for listeners familiar with the style: if **IV–V** is more common than **IV–VI**, the appearance of a **IV** chord generates an expectation that the next chord is more likely to be **V** than it is to be **VI**.

In Western classical music, harmonies generally group into three *harmonic functions* — tonic (T), pre-dominant (P), and dominant (D) — and these functions group together chords that progress to and from other chords in similar ways. For example, since **II** and **IV** are both pre-dominant chords, they will participate in many of the same kinds of chord progressions, and at times can be substituted for each other with only a minimal change to the musical effect.

On a local level (chord-to-chord progressions), we can summarize the tendencies of these functions with the cycle **T–P–D–T**. That is, harmonies tend to progress through a cyclical progression of those three functions:

> **T → P → D → T →** and so on . . .

That does not rule out T progressing to D, D progressing to P, etc. But it does mean that those progressions tend to be less common, at least in classical music.

Higher-level musical structures also impact the norms according to which these harmonic functions progress. For now, we will consider one higher-level structure that influences chord-progression tendencies — the phrase — and we will limit our study to isolated, complete, self-sufficient phrases. This is an idealized, oversimplified setting — like strict voice-leading — that is useful for learning the basics. Some such phrases even exist in real music! But most of the time there are a number of competing factors that influence the chord-progression strategies employed by a composer at any given moment. However, the idealized phrase is a helpful starting point. Future study will explore how classical composers employ harmonic progressions in larger musical works that combine multiple phrases (which are not self-sufficient) into larger themes and movements.

### The idealized phrase

The *idealized phrase* (also called the *phrase model*) is a single musical phrase that progresses through an entire cycle of harmonic functions, beginning and ending on tonic. (Strict voice-leading exercises are such phrases.) These phrases begin with a point of stability (tonic), move away from that stable point, and then eventually lead to a point of high tension and resolution (an *authentic cadence*). This pattern of stability–instability–stability, or rest–motion–rest, with a single goal at the end, should be familiar both from species counterpoint and from strict keyboard-style voice-leading. (This pattern also governs large-scale formal structures in classical music.)

The simplest phrase that exhibits this complete harmonic cycle is a tonic-dominant-tonic progression: **I–V–I.** This phrase begins and ends with the most stable harmony (**I**), and includes an *authentic cadence* (**V–I**). The **V** is the high point of instability, containing the tendency tone (*ti*) that most strongly points to the final point of arrival (*do*, or tonic).

This harmonic cycle can be expanded by inserting a pre-dominant chord, a destabilized tonic chord, or both, as in the following examples: 

> **I IV V I**  
> **I II V I**  
> **I VI V I**  
> **I VI II V I**

In *functional bass* terms, any harmonic progression that follows the pattern

> **T1 → (P_) → D5 → T1**

can serve as the basis for a complete idealized phrase. (Harmonies in parentheses are optional.)

Phrases are seldom 3–5 chords long, however, and a harmonic function can be expressed by more than a single chord. Thus we can understand the harmonic functions not simply as chords, but as *zones* of varying length in a phrase, which can be created by a number of chords or short chord progressions. More generally, then, our idealized musical phrase contains a single progression of functional zones **T → (P) → D → T**, begins with **T1**, and ends with an authentic cadence (**D5–T1**), as seen in the example below.

### Triggering and prolonging harmonic functions in an idealized phrase

To establish, or trigger, a harmonic functional zone, composers tend to use *a fixed scale degree in the bass*. In other words, tonic tends to be triggered by **T1** (always **I**), pre-dominant by **S2** or **S4** (including a variety of **II** and **IV** chords, in in root position or inversions, with and without sevenths), and dominant by **D5** (**V**, with or without a seventh, or a [*compound cadence*](cadenceTypes)). These four categories of chords — **T1**, **P2**, **P4**, and **D5** — are called *functional chords* (because they trigger the function) or *cadential chords* (because they can participate in a cadence). 

Other chords are often called *contrapuntal chords* or *embellishing chords*, and are typically used to *prolong* a function throughout the zone. 

Functional prolongations are shown in a harmonic analysis by writing/typing T, P, or D underneath the individual chord labels (Roman numerals or functional bass) and extending a line from the beginning of the functional zone to the end.

The following excerpt is from Mozart's Piano Sonata in A Major, K. 331, I., mm. 1–4, with a harmonic reduction and analysis provided below the original score. Such an analysis is called an *interpreted* harmonic analysis, because the harmonies are interpreted according to the way they behave in the phrase, rather than merely labeled. In this phrase, note the following:

- The tonic zone is triggered by a root-position tonic triad (**I** or **T1**).  
- Contrapuntal dominant chords (**D7** — first-inversion dominant chords) create a passing bass motion between the opening **I** chord, the **vi** in m. 3, and the return of **I** in m. 4.
- The [cadential progression](harmonicAnalysis) begins in m. 4 with the move from **I** to <strong>ii<sup>6</sup></strong> (**S4**) and then to the cadential six-four and dominant triad (**D5**). Note that the entirety of the cadential progression in m. 4 is made up of *cadential chords* — chords with fixed scale degrees in the bass.  
- In contrast, the entire tonic-prolongation zone is made up of *contrapuntal chords* — variable scale degrees in the bass — with the exception of the **I** chord that triggered the tonic function.  
- The **vi** chord is a root-position chord, but still an embellishing chord, while the <strong>ii<sup>6</sup></strong> is an inverted chord, but still a functional/cadential chord. The difference is not the inversion, but the scale degree of the bass.

[![](/images/harmony/k331-reduction.png)](/images/harmony/k331-reduction.png)

<iframe src="https://embed.spotify.com/?uri=spotify:track:5yfZxPrcN0hjwzU1OKIsdQ" width="300" height="80" frameborder="0" allowtransparency="true"></iframe><br/>

Not all classical phrases as neatly fit the general trends outlined in this resource. As discussed in [Style and tendency](tendency), the principles of harmonic syntax are both reliable and bendable/breakable, and it is often the music that bends/breaks the "rules" in interesting ways that we care about the most. So in your own analyses, keep these principles in mind as *general* principles, and simultaneously look for where composers meet these expectations as well as where they break them. 

## Prolonging harmonic functions

The following are the primary techniques used to prolong functional zones in an idealized classical phrase. Examples of specific progressions and notational conventions are provided.

### Change-of-figure prolongation

A *change-of-figure prolongation* occurs when the bass repeats (or is sustained, or drops an octave) while one or more of the upper voices change. The function remains the same (T/P/D), but the Roman numeral may change.

Examples include progressions like **V–V<sup>7</sup>** (both **D5**) or **IV–II<sup>6</sup>** (both **P4**). 

### Change-of-bass prolongation

A *change-of-bass prolongation* occurs when two chords of the same function appear back-to-back, but with different bass pitch classes. In some cases, these are changes of inversion: **I–I<sup>6</sup>**, for example. In other cases, the root changes: **I–III** or **IV–II**, for example. What makes these progressions prolongations is that the function remains the same. **I–I<sup>6</sup>** prolongs tonic function (**T1–T3**), and **IV–II** prolongs pre-dominant function (**P4–P2**).

### Contrapuntal prolongation – passing chord

Many change-of-bass prolongations involve a skip of a third in the bass, such as **I–I<sup>6</sup>** (**T1–T3**). Just as in second-species counterpoint a melodic third from downbeat to downbeat invites the use of a weak-beat passing tone, a melodic third in the bass between these two chords invites the use of a *passing chord*.

The bass note of a passing chord will fill in the third with stepwise motion. The melody will also often contain passing motion.

A function is typically prolonged by contrapuntal chords belonging to the function that precedes it in the standard cycle. T is prolonged by D, D by P, and P by T.

A passing chord that prolongs the above **T1–T3** progression would then be a dominant chord (D precedes T) with scale-degree 2 in the bass (the passing tone between scale degrees 1 and 3): **D2**. 

<iframe src="https://trinket.io/embed/music/026277e656" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

Common **D2** chords are **V<sup>6/4</sup>**, **V<sup>4/3</sup>**, and **VII<sup>6</sup>**. Thus, a **I–I<sup>6</sup>** prolongation can involve those as passing chords. The following **T1 D2 T3** progression uses a **viiº6** to prolong tonic. Listen to this example, and then try to change the progression to a properly voiced **I V<sup>6/4</sup> I<sup>6</sup>** progression.

<iframe src="https://trinket.io/embed/music/e02e8af4b3" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

Note that while scale-degree 2 in the bass can support a **II** chord, **II** is pre-dominant, and so it is *not* used as a passing chord to prolong tonic.

### Contrapuntal prolongation – incomplete neighbor chord

In [second-species counterpoint](secondSpecies.html), variety could come by using a *substitution* in place of a passing tone. This leap of a fourth followed by step in the opposite direction still outlines a third from downbeat to downbeat, but offers a break from too much stepwise motion in the counterpoint.

In harmonic writing, the same effect is obtained by an *incomplete neighbor chord*. The bass follows the same incomplete-neighbor pattern as the second-species counterpoint, and the function of the contrapuntal chord is the same as its passing-chord counterpart. Thus instead of a passing motion of **T1 D2 T3**, a substitution pattern in the bass would produce **T1 D4 T3**. (In Roman numerals, that progression would almost invariably be **I V<sup>4/2</sup> I<sup>6</sup>**, as it is in the following example.)

<iframe src="https://trinket.io/embed/music/51a20e2c7a" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

### Contrapuntal prolongation – complete neighbor chord

Just as a *neighbor tone* in second- or third-species counterpoint could be used to ornament a single tone and return to it, a *neighbor chord* uses a neighbor-tone motion in the bass to prolong a function and return to the original bass pitch. The function of a neighbor chord follows the same principle as the passing or incomplete neighbor chord. Following are some examples of neighbor-chord prolongations:

- **T1 D7 T1**  
- **T3 D4 T3**  
- **P4 T3 P4**  
- **D7 P6 D7**

Here is a **T1 D7 T1** neighbor prolongation in strict keyboard style. What is the Roman numeral and figured bass for the **D7** chord? What is the least number of changes you can make to it in order to transform it into **T3 D4 T3**?

<iframe src="https://trinket.io/embed/music/e12906a55e" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

Just as third-species counterpoint has a *double neighbor* figure, harmonies can be prolonged by two chords using a double-neighbor figure in the bass. The most common double-neighbor prolongation is **T1 D2 D7 T1** (commonly **I V4/3 V6/5 I**).

<iframe src="https://trinket.io/embed/music/519c9f039d" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

### Contrapuntal prolongation - divider and embellishing chords ##

In second-species counterpoint, an *interval subdivision* divided a large leap between downbeats into two smaller leaps. Likewise, a *divider chord* takes a large leap between bass notes in a change-of-bass prolongation (or a simple octave leap in the bass) and divides it into two smaller leaps.

Divider chords almost always prolong tonic function, and can do so using either pre-dominant or dominant dividers. The most common divider-chord prolongations are:

- **T1 D5 T1** (**I V<sup>(7)</sup> I**), where the bass ascends or descends an octave between **T1** chords.  
- **T1 P4 T1** (**I IV I**), where the bass ascends or descends an octave between **T1** chords.  
- **T1 P6 T3** (**I IV<sup>6</sup> I<sup>6</sup>** or **I IV<sup>6</sup> III**), dubbed the *champagne progression* by theorist Gene Biringer, because it is "the progression you pull out when you want to impress a date." 

Following is a champagne progression. Which version is it (**I<sup>6</sup>** or **III**)? What one thing must change in order to form the other version? What default voice-leading rule is "broken" in this progression? (Note, because of rule conflicts, this progression will always break that rule, and it will always have these scale degrees in the melody.)

<iframe src="https://trinket.io/embed/music/6a403a3d21" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

In the case of **T1 D5 T1** and **T1 P4 T1**, the same harmonic progression can occur without the bass changing register. In other words, the bass leaps from *do* to *sol* or *fa*, but returns to the original bass note. Instead of dividing a large leap, the bass note of the intervening chord looks like an *embellishing tone* from third species. (In third-species counterpoint, an *embellishing tone* ornaments another tone by leaping to another consonance — usually a third or fourth away — and returning to the original tone.) Thus, what would otherwise be a *divider chord* is instead an *embellishing chord*. 

Following is a **T1 D5 T1** *divider* prolongation. What single change can make it an *embellishing chord* prolongation?

<iframe src="https://trinket.io/embed/music/a23ec68873" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

### Subsidiary harmonic progressions

The last type of prolongation is not contrapuntal, but instead involves weak versions of the typical **T–(P)–D–T** progression. When such a progression fails to produce a proper cadence — that is, it ends with contrapuntal chords such as **D7–T1** or **D4–T3**, or uses a "deceptive resolution" **D5–T6** (**V–VI**) in place of the cadential **D5–T1** — the progression is called a *subsidiary harmonic progression* (this term comes from Edward Aldwell & Carl Schachter; Steven Laitz calls the same progression an *embedded phrase model*). It is "subsidiary" (or "embedded") because instead of occupying the whole phrase, it is subsidiary to (or embedded in) a larger progression. 

These subsidiary progressions *always prolong tonic*. They are labeled in an analysis by following the initial T with a line:

> **T—————**

For instance, consider the following possible harmonic progression for a phrase:

<iframe src="https://trinket.io/embed/music/69e6b9acb9" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

The first progression through the **T–S–D–T** cycle does not produce a cadence when it returns to T. However, it cannot be said to be a contrapuntal prolongation because it follows the normal functional cycle perfectly. Thus, it is a subsidiary progression. 

[![](/images/harmony/subsidiaryProgression.png)](/images/harmony/subsidiaryProgression.png)

### Plagal progressions

As a rule, **T** is used for contrapuntal prolongation of **P**, **P** prolongs **D**, and **D** prolongs **T**. However, there are some common patterns in which **P** is used to prolong **T**.

The *champagne progression* (**I–IV<sup>6</sup>–I<sup>6</sup>** or **I–IV<sup>6</sup>–III**) is one. Another is the **P4** divider, as well as the related **P4** embellishing chord. All are described above.

One other common pattern is to use **IV** (**P**) as a complete or incomplete neighbor to **I<sup>6</sup>** (**T**). Common progressions include **I IV I<sup>6</sup>** and **I<sup>6</sup> IV I<sup>6</sup>**.

<iframe src="https://trinket.io/embed/music/480c1acf9b" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

Also common is a *change-of-figure* prolongation of **T1**: <strong>I–IV<sup>6/4</sup>–I</strong>. The <strong>IV<sup>6/4</sup></strong> can be considered an **P** chord, but it is often more appropriate simply to consider the sixth and fourth above the bass in that chord to be neighbor tones to the fifth and third. Simply label such a progression **T———** underneath the Roman numerals.

<iframe src="https://trinket.io/embed/music/1e440d4768" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>

### Prolonging a progression

Occasionally, a contrapuntal chord is used not to prolong a single function, but to connect chords of different functions — in other words, to prolong a progression.

The most common occurrence is when a bass line moves down by step from *do* to *sol*, which is especially common in minor. The bass line *do*–*te*–*le*–*sol* is harmonized by **T1 D7 P6 D5** (usually **i v<sup>6</sup> iv<sup>6</sup> V** — the chord qualities are important in this progression, called the "lament"). In this progression, the **P6** is a functional pre-dominant leading to the cadential **D5**. The **D7** chord, then, is simply a passing chord that connects **T1** with **P6**. To notate this, draw and arrow between **T** and **P** underneath the Roman numeral analysis. 

<iframe src="https://trinket.io/embed/music/3b6de8a510" width="100%" height="350" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>
