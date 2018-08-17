---
layout: chapter
title: 11d Examples - Tonal Sequences
abc: true
---

## Melodic sequences

**We will begin studying sequences by looking at melodic sequences because they demonstrate the basic principles without the complications of multiple voices. Look at the following melodic patterns; each one is the beginning of a melodic sequence. Complete the pattern through the designated ending pitch and then discuss the repetition using the following terms:**
- ascending or descending
- diatonic or chromatic
- intervals of transposition
- length of pattern
- single or multiple parts within each repetition

{% capture ex1 %}X:1
T:Melodic sequences
M:2/2
L:1/8
Q:1/4=70
K:C
CDEC DEFD| x8| x8| x4c4||
cBcG BABF| AGAE x4| x8| x4C4||
cBcG B^AB^F| _BA_BF x4| x4G4||
c'gae fcdA| x6C2||
c'bc'g a^gae| fefc x4| x8| x4C4||
cBcG AGAE| dcdA BABF| x8| x8| g8||{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Harmonic sequences

**Sequences occur harmonically as well, and when they do, they can supplant standard function or inversion conventions. As mentioned on the previous page, sequences work because they establish a pattern for the listener and then fulfill this new goal. Look at the following example of a two voice pattern. The first bar establishes tonic, and then a sequence begins in the second measure. After listening to it, discuss with your classmates whether it *sounds* functional. If you were going to describe this to another person, how would you describe it? Once you finish your discussion, propose a harmonic progression that fits the melody.**

{% capture ex2 %}X:2
T:A two voice sequence
M:4/4
L:1/2
K:C
V:1
c f-| f e-| e d-| d c-| c B| c2|]
V:2 clef=bass
C, A,| G, G,| F, F,| E, E,| D, D,| C,2|]
w:C:{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**What progression did you create? Did it follow standard tonal conventions? There are multiple variations on the harmonic progression for this sequence, but I have suggested one below. Using my progression, try adding a third voice as an alto line. (Remember that the sequential pattern will not start until the second measure.) Does this new voice also follow a pattern that could be described by your classfication method?**

{% capture ex3 %}X:3
T:Harmonizing a two voice sequence
M:4/4
L:1/2
K:C
V:1
c f-| f e-| e d-| d c-| c B| c2|]
V:2 clef=bass
C, A,| G, G,| F, F,| E, E,| D, D,| C,2|]
w:C:I IV6 V7 I6/4 IVM7 viio6/4 iii7 vi6/4 ii7 V6/4 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

**The next example shows you my suggested alto voice. It provides the required missing chord tones for each chord in this progression.**

{% capture ex4 %}X:4
T:Filling in the sequence
M:4/4
L:1/2
K:C
V:1
[cE] [fc]| [Bf] [ec]| [Ae] [Bd]| [Gd] [Ac]| [cF] [GB]| [E2c2]|]
V:2 clef=bass
C, A,| G, G,| F, F,| E, E,| D, D,| C,2|]
w:C:I IV6 V7 I6/4 IVM7 viio6/4 iii7 vi6/4 ii7 V6/4 I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

**In your classification of the two-voice progression above, you likely described each line individually (e.g. descending diatonic 2nds that last one whole note), or you may have describe the intervals between the two lines for each measure (e.g. a diatonic 7th resolving to diatonic 6th, then repeating after transposing down a diatonic 2nd). Neither of these is sufficient, however, once we add a third voice.**

**Instead, we classify *harmonic* sequences by describing the movement of the *roots* of each chord. We do *not* label harmonic sequences by inversions or the bass line. If we were to identify sequences by bass lines, all sequences that created a particular style of bass line (e.g. descending by stepwise motion) would be grouped together, even if they shared no harmonic similarities. (You can see this concept in the next two examples below.) Taking this into account, the description of the sequence in the example above would be:**
- A diatonic harmonic sequence with root-movement by descending 5th that alternates between root-position seventh chords and second-inversion triads.

**The above sequence has only one interval and direction in its root movement pattern, a descending P5. As we saw in the final example of the melodic sequences above, though, it is also possible for harmonic sequences to have two or more parts within each repetition. Look at the example below, and classify it using our terms from above:**
- ascending or descending
- diatonic or chromatic
- intervals of transposition
- length of pattern
- single or multiple parts within each repetition

{% capture ex5 %}X:5
T:A multi-part sequence
M:4/4
L:1/2
K:C
V:1
[eG] [Bd]| [cE] [GB]| [AC] [EG]| [AF] [BD]:|
V:2 clef=bass
C G,| A, E,| F, C,| F, G,:|
w:C:I V vi iii IV I IV V{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

**Hopefully you were able to identify that the sequence only covers the first three measures, the final measure is simply a way to allow the pattern to repeat smoothly. For the sequence, there are two possibilities to describe it. You could consider each measure a pattern in which case you would say that this is a diatonic sequence that descends by 3rd. If you consider the pattern to be a half note, though, it has multiple parts. It is a diatonic sequence of triads that moves down by 4th and then up by 2nd. Either is correct, but the second version communicates a clearer picture of the pattern.**

**How does your description of the sequence change if we change some of the voices to alter the chords' inversions as in the example below?**

{% capture ex6 %}X:6
T:Using inversions to create a smooth bass line
M:4/4
L:1/2
K:C
V:1
[eG] [Gd]| [cE] [EB]| [AC] [CG]| [AF] [BD]:|
V:2 clef=bass
C B,| A, G,| F, E,| F, G,:|
w:C:I V6 vi iii6 IV I6 IV V{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

## Standard sequences

parallel 6th chords

**While any sequence that establishes a pattern and has clear voice-leading can function, there are common sequences that many composers have relied upon. We discussed the first of these in Unit 7a when exploring how voice-leading led to the standard circle-of-fifths progression. Now that we understand the structure of sequences, how would you describe this sequence?**

{% capture ex7 %}X:7
T:Circle of fifths sequence of triads
M:4/4
L:1
K:C
V:1
[GE]| [EG]| [EA]| [FA]| [BG]| [cG]|]
V:2 clef=bass
[C,C]| [E,B,]| [A,,C]| [D,D]| [G,,D]| [C,E]|]
w:C:I iii vi ii V I{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

**Sequences can also be used to explain how non-diatonic progressions function in a diatonic context. One common sequence occurs when first-inversion chords are used in succession to create a stepwise bass line. A *parallel 6 chord* is any sequence with repeated first-inversion triads. Notice that this does not create objectional parallel voices as long as the root of the chord stays above the chordal fifth. If these two voices are inverted, this will result in parallel perfect fifths.**

{% capture ex8 %}X:8
T:Parallel 6 chords
M:4/4
L:1/2
K:C
V:1
[eg] [gd]| [fc] [eB]| [dA] [cG]| [BF] [cE]|]
V:2 clef=bass
C B,| A, G,| F, E,| D, C,|]
w:C:I V6 IV6 iii6 ii6 I6 viio6 I{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}

**We also looked at one of the most commonly used sequences in this unit: the Pachelbel sequence.**

{% capture ex9 %}X:9
T:Pachelbel's sequence
M:4/4
L:1/2
K:C
V:1
[eG] [Bd]| [cE] [GB]| [AC] [EG]| [AF] [BD]:|
V:2 clef=bass
C G,| A, E,| F, C,| F, G,:|
w:C:I V vi iii IV I IV V{% endcapture %}
{% include abc-example.html number="9" abc=ex9 %}

**This sequence takes its name from the German Baroque composer, Johann Pachelbel, who composed a canon using this sequence as its foundation. Since then, the harmonic progression has become a common structure on which to build multiple styles of music. The comedian Rob Paravonian satired many of these takes in his now famous "Pachelbel Rant". (Caution: some strong language)**

<iframe width="560" height="315" src="https://www.youtube.com/embed/JdxkVQy7QLM" frameborder="0" allowfullscreen></iframe>