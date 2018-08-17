---
layout: chapter
title: Examples 10b - Part-writing Errors
abc: true
---

## Parallel perfect fifths and perfect octaves (PP5, PP8)

**Part-writing errors result from poor voice-leading. For example, look at the progression below and try to find our first major error: *parallel octaves*. Once you have found it, look to see if a voicing rule has been broken. If the voicing error is not fixed, is there any way to avoid the parallel octaves without incorrectly resolving a tendency tone?**

{% capture ex1 %}X:1
T:Parallel perfect octaves (PP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**Parallel octaves and fifths undermine the independence of lines, so you should always avoid them in this style. Listen to the following example, and try to locate the parallel perfect fifths aurally before you look through the parts.**

{% capture ex2 %}X:2
T:Parallel perfect fifths (PP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,A,] | [DG,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**Once you have identified the voice that contains the PP5s, try singing the upper of the two voices, and then listen to the example again. Do you have a difficult time differentiating the upper voice from the lower of these two voices?**

## Contrary perfect fifths and octaves (CP5, CP8)

**Our next part-writing error, *contrary perfect fifths and perfect octaves* are simply an attempt to cover up parallel perfect fifths and perfect octaves by displacing one voice by an octave. The next two examples attempt to fix the errors from the first two examples on this page by displacing one voice of the parallel perfect intervals. Identify these by comparing them to the previous example (i.e. P) Notice that it creates multiple voicing and spacing errors as well as nearly unsingable parts!**

{% capture ex3 %}X:3
T:Contrary perfect octaves (CP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C,]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}


{% capture ex4 %}X:4
T:Contrary perfect fifths (CP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,,A,] | [D,G,,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

## Unacceptable unequal fifths (UU5)

**The last two common part-writing errors have specific clauses tied to them that specify which voices are acceptable and unacceptable. The first, *unacceptable unequal fifths*, must occur between the bass voice and one of the upper voices. In the following example, find the *unacceptable unequal fifths* where a d5 moves to a P5. What is wrong with the voice-leading here?**

{% capture ex5 %}X:5
T:Unacceptable unequal fifths (UU5)
M:4/4
L:1/2
K:C
V:1
[cE] [Fd]| [dF] [cG]|]
V:2 clef=bass
[C,C] [D,A,] | [B,,G,] [E,C,]|]
w:C:I ii V6/5 I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

**Note that we will consider a P5 moving to a d5 as *acceptable* unequal fifths, because a P5 to a d5 does not require incorrect resolutions of tendency tones. There are some stricter versions of chorale part-writing that do not allow any form of unequal fifths.**

## Unacceptable similar fifths or octaves (US5, US8)

**The final common part-writing has many names, but we will use the term *unacceptable similar fifths or octaves*. This error can also be called "direct", "hidden", or "exposed". I prefer to use *similar* because it implies the motion like the other categories, but I also think that *exposed* does a fine job describing the effect. (I dislike the term *hidden* because students often confuse this with contrary fifths (or octaves), because the goal of contrary fifths is to "hide" parallel fifths.) *Unacceptable similar fifths or octaves* have the most restrictions. The conditions are:**
- They can only occur between the soprano and the bass voices.
- They require a skip of a third or more in the soprano voice.
- The two voices must move in similar (not parallel) motion.
- The second interval must be a P5 or P8.

**If any one of these conditions are not met, then there is not a part-writing error. Look at the following example to find an example of *similar octaves*. Once you have found it, look at the voice-leading around it. What does it do to spacing? Does it create more errors? Unacceptable similar octaves and fifths also often create melodies that imply different harmonies. To demonstrate, sing the melody alone. Do you hear it as C major or a different key?**

{% capture ex6 %}X:6
T:Similar octaves (S8)
M:4/4
L:1/2
K:C
V:1
[Ge] [AA]| [FA] [FB]| [c2E2]|]
V:2 clef=bass
[C,C] [CA,,]| [F,,C] [DG,,]| [C2C,2]|]
w:C:I vi IV V7 I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

**As a final demonstration of the difficulties that these part-writing errors create, try to fix each of the part-writing errors on this page. What do you have to change? Do you get to keep the harmony? Voice-leading? Voicing? In trying to fix it, do you just create further errors?**