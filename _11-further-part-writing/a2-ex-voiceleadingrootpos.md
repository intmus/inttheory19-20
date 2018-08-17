---
layout: chapter
title: Examples 11a - Voice-leading for Root Position Triads and Seventh Chords
abc: true
---

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

**Circle-of-fifths progressions work because the voice-leading taps into the primary functions of diatonic harmony. If you review Unit 7a, you will remember that we created the harmonic flow chart by simply following good voice-leading between chords that have roots separated by a descending P5/ascending P4. Admittedly, long strings of root-position chords create unmelodic bass lines, but they still represent the strongest voicing for many sonorities. Try harmonizing the following chord progression. Write the soprano line from the given first pitch, and then fill in the inner voices following the guidelines above. (If you are struggling, it is often helpful to establish your ending and then work backward.)**

{% capture ex1 %}X:1
T:Circle-of-fifths triadic progression
M:4/4
L:1
K:C
V:1
c| x| x| x| x|]
V:2 clef=bass
[C,]| [A,,]|[D,]| [G,,]| [C,]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**Now that you have completed a harmonization, make sure to double-check it for part-writing errors. If you successfully completed it, try changing your melody and trying again.**

## Adding the seventh

**As a theory teacher, I often feel that I spend more time talking about the exceptions to rules than the actual rule itself. Luckily, turning a triad into a seventh chord creates one of the least broken rules: *Typically, the seventh of a chord resolves down by step.* There will be instances where you are forced to break this rule (e.g. pre-determined melodies, sequences, etc.), but generally, it will hold true. Try adding the following two seventh chords to the basic circle-of-fifths progression while following this rule.**

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

## Exploring options

**Of course, there are multiple chords in our circle-of-fifths progressions that have root movement by intervals other than 4ths and 5ths. Try harmonizing the following short chord progressions while observing our guidelines. Keep track of what types of root movement create the most issues while developing at least two possibilities for each of the progressions**

{% capture ex3 %}X:3
T:Short chord progressions
T:Treat each measure as a separate progression
M:4/4
L:1/4
K:C
V:1
cxxx|| cxxx|| cxxx|| cxxx|]
V:2 clef=bass
[C,] [F,,] [G,,] [C,]|| [C,] [F,,] [G,,] [A,,]|| [C,] [D,] [F,] [G,]|| [C,] [D,] [G,,] [C,]|]
w:C:I IV V7 I I IV V vi I ii IV V I ii7 V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Function over form (Part 1)

**When you were harmonizing these short chord progressions, which chord progression presented the most issues? For most, it will likely be when the progressions that have root-movement by 2nd, particularly a progression IV-V-vi. Let's start by isolating a common example of this movement, V moving to vi. In this progression, the V is acting according to its standard dominant function, but the vi chord has replaced the I chord in the position where a tonic function should occur. This progression represents a *functional substitution* in which vi is now acting as the tonic function. (This concept has application within the dominant and pre-dominant functions as well, but we need to explore first-inversion chords in the next topic, 11b, before we are ready for that discussion):**
- When V goes to vi, the vi chord is replacing the tonic function and therefore functions as a I<sup>sub6</sup>

**From a practical perspective, a *functional substitution* can inform your voice-leading. When a root-position V chord precedes a root-position vi chord, we must choose to prioritize either our *doubling* conventions or our *part-writing conventions*. With this in mind, harmonize the following two progressions; first with the standard tonic function (i.e. V to I) and then with the functional substitution (i.e. V to vi.) How does the standard function influence your decision on which conventions to employ on the function substitution.**

{% capture ex4 %}X:4
T:Using a functional substitution for a deceptive cadence
M:3/4
L:1/4
Q:1/4=60
K:C
V:1
[cE][B][c]| ] [cE][B][c]|]
V:2 clef=bass
[C,G,] [G,,] [C,]| [C,G,] [G,,] [A,,]|]
w:C:I V I I V vi{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

**Because the vi chord acts as a replacement for a I chord, we double the scale degree that works best for a I chord, `do`, rather than the standard doubling of the root, `la` or fifth, `mi`. In this progression, it is correct to break standard convention and double the chordal third of the vi chord.**

## Root movement by 2nd

**The other difficult resolution in the previous example was when the root position IV chord moved to the V chord. We do not have a *functional substitution* to provide a doubling exception here, so instead you must be careful about how you resolve the voices. Harmonize the following progression without altering the given pitches, and pay particular attention to the direction that the upper voices resolve as you avoid part-writing errors.**

{% capture ex5 %}X:5
T:Root movement by 2nd
M:4/4
L:1/4
K:C
V:1
[cE] [c] xx|]
V:2 clef=bass
[C,G,] [F,,] [G,,] [C,]|]
w:C:I IV V I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

## Common exceptions

**There are some commonly used exceptions to our general part-writing conventions. For example, when a chord progression has a root that moves down by P5, we expect the chordal third to resolve up by step to the root of the following chord. However, if you need to change the texture of your part-writing to be more or less compact, you may choose to have the chordal third leap to the following chordal third which changes the entire voicing possibilities of the two chords. (Note that you can only use this on the leading tone if it is in an inner voice.) Use this method to fill in the inner voices in the following example to change the voicing of the final chord.**

{% capture ex6 %}X:6
T:Chordal third to chordal third
M:4/4
L:1/4
K:C
V:1
[eG] [d] [c2]|]
V:2 clef=bass
[C,C] [G,,] [C,2]|]
w:C:I V I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

**Another common exception is called the *frustrated leading tone*. While it is not ideal, if the leading-tone is in an inner voice, you can choose to have it resolve by skipping downward to the root of the tonic chord. This can solve doubling issues if you are trying to fix an incomplete triad by adding the chordal fifth. Try it in the tenor voice on the following two progressions. Notice that this allows you to create a deceptive cadence without having to double the chordal third of the vi chord.**

{% capture ex7 %}X:7
T:Frustrating a leading tone
M:3/4
L:1/4
Q:1/4=60
K:C
V:1
[eG] [d] [c]|| [eG] [d] [c]|]
V:2 clef=bass
[C,C] [G,,] [C,]|| [C,C] [G,,] [A,,]|]
w:C:I V7 I I V7 vi{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}