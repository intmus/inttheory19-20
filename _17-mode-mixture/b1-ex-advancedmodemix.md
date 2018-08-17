---
layout: chapter
title: 17b Examples - Advanced mode mixture
abc: true
---

## Extending mode mixture

Please watch this wonderfully-made video on modal interchange -- another name for mode mixture -- created by Myles Yang for his Native Construct YouTube channel. In it, he demonstrates possible mode mixture beyond parallel major and minor modes. If you are not familiar with modes beyond major and minor (Ionian and Aeolian), please review Unit 2. You can also quiz yourself on modes at [musictheoryfundamentals.com](http://musictheoryfundamentals.com/MusicTheory/modes.php).

<iframe width="560" height="315" src="https://www.youtube.com/embed/1dRA28cdt5c?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

This video does a great job of explaining the concept of mode mixture, but as he mentioned near the end of the video, he is only "scratching the surface". Having watched the video, you probably feel that you understand the extended *concept* of mode mixture, but if you were asked to compose a progression and melody the incorporated mode mixture, do you feel that you would be able to implement it? Where would you start? In short, this video explains the "what is it?", but it does not begin to approach the "why it works?" or "how it works?".

To begin exploring this, use the score below to try voicing one of the progressions taken from the video. Take risks, and break the "rules" as you try this. You must use the chord progression below, but you may alter the bass and soprano lines if you would like. You may also add as many or as few of the pitches as you need. Are you able to make this progression sound as pleasing as it does in the video? If not, what are the factors making this difficult? From a technical viewpoint, is it lack of knowledge or is it the medium (MIDI keyboard)? From a musical viewpoint, what aspects make the biggest improvement when you alter them?

{% capture ex1 %}X:1
T:Sample mode mixture
M:4/4
L:1/2
Q:1/4=90
K:C
V:1
[e] [f]| [f] [f]| [e2]|]
V:2 clef=bass
[C,] [_B,,]| [F,,] [D,]| [C,2]|]
w:C:I bVII IVM7(#11) ii%7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Functional mode mixture

As you have hopefully come to realize, all tonal harmony -- even the chromatic alterations -- rely on voice-leading to create a sense of natural progression, and each harmony can be viewed through the lens of how it functions. From this, we derive primary harmonic functions such as tonic, dominant, and pre-dominant as well as embellishing functions such as passing, pedal, and cadential. Even the exceptions to these can be viewed as functional substitutions (e.g. deceptive progressions).

At its core, mode mixture borrows altered tones from parallel modes -- thus altering chord *qualities* -- but retains standard chord function. If a diatonic chord would have a pre-dominant function, altering an individual tone by a half-step will not alter the function. It creates color and often *strengthens* the voice-leading by changing whole-step resolutions into half-step resolutions. Moreover, if a chord functions as an embellishing chord such as a passing or pedal chord, then it will retain that function even if one or two pitches are borrowed from a parallel mode. 

Even seemingly inexplicable choices can be explained -- such as the ii<sup>&oslash;7</sup> from the chord progression above -- if you look at the voice-leading and compare it to standard diatonic function. For example:
1. The ii<sup>&oslash;7</sup> is inserted into the position where we would normally expect a dominant function.
2. If you compare the pitches within ii<sup>&oslash;7</sup> to the pitches of vii<sup>o7</sup>, you will realize that three of the pitches are the same (D, F, and A-flat) and the remaining pitch only changes by a half-step (B to C). In this progression, the C works best when it acts as an anticipation of the tonic chord, and this strengthens the voice-leading resolutions of ii<sup>&oslash;7</sup>. Therefore, the ii<sup>&oslash;7</sup> can be viewed as an altered dominant function chord.

With this in mind, look at the following reduction of an excerpt from Mahler's Symphony No. 2. How would you explain each of these borrowed chords? How do they function? Is this similar to the progression from above?

{% capture ex2 %}X:2
T:Mahler Symphony No. 2, Mvt. I
T:Simplified reduction
M:4/4
L:1/4
Q:1/4=60
K:C
V:1
[g3GEC] _B/2>_A/2| [g3GEC] _G/2>F/2| [g3GEC] _E/2>_D/2|
[g3GEC] _B,/2>_A,/2| [G2EC] z2| [G2EC] z2| [Eceg] [_E3c_eg]|]
V:2 clef=bass
(3C,/2G,,/2C,/2 (3C,/2G,,/2C,/2 C,/2z/2 [B,DF]| (3C,/2G,,/2C,/2 (3C,/2G,,/2C,/2 C,/2z/2 [_A,_D]| (3C,/2G,,/2C,/2 (3C,/2G,,/2C,/2 C,/2z/2 [_A,F,]|
(3C,/2G,,/2C,/2 (3C,/2G,,/2C,/2 C,/2z/2 [B,,D,F,]| (3C,/2G,,/2C,/2 (3C,/2G,,/2C,/2 [C,2E,G,]| (3C,/2G,,/2C,/2 (3C,/2G,,/2C,/2 [C,2E,G,]| [C,,4C,]|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Chromatic non-chord tones versus mode mixture

Analyze the following two chord progressions. What factors help you decide how to label each chord? Which tones are chromatic passing tones, and which create new harmonies?

{% capture ex3 %}X:3
T:Mode mixture or non-chord tones?
M:4/4
L:1/4
Q:1/4=60
K:C
V:1
[cE] [cF] [cF] [cE]|| 
GA A/2_A/2G|]
V:2 clef=bass
[C,G,] [C,A,] [C,_A,] [G,C,2]|| 
[C,E] [C,F] [C,F] [C,E]|]
w:C:{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

Chromatic passing tones often create harmonies that could be considered borrowed chords, but the determining factor should always be function. If the resulting borrowed chord does not sound as a defined function (e.g. tonic, dominant, pedal, etc.), then the pitch should be classified as a passing tone. If the chord operates as a functional substitution (tonic, dominant, pre-dominant), then it is better to label it as a borrowed chord. If each member of the chord functions solely for smooth voice-leading purposes, then it should be labeled as a borrowed chord with an alternate function such as a passing or pedal chord.