---
layout: chapter
title: Lesson 4b - Compound Meters
abc: true
---

Today's topic is the second classification of regular meters: *compound* meters.

As a quick review, there are a few critical terms necessary for discussing these meters. *Meter* is the manner in which we organize strong and weak pulses in music over time, and it is from this grouping that we determine the length of each *measure*. At its most basic, meter tells us two things:
- how we divide the meter into regular or irregular pulses called *beats*
- how many of these *beats* are in the measure

If we imagine meter as a hierarchy, *beats* are the highest level. Beats are then divided into *divisions*, and *divisions* can be further divided into *subdivisions*. A *regular* meter is one in which every *beat* is the same length.

Finally, do remember that meter is somewhat subjective and can be greatly altered by many factors, especially tempo. We will discuss this in the next topic, but where one listener might listen to a piece with four quarter-notes per measure and feel that the quarter notes are the beat, another listener may listen to the same piece and hear the beat in a slow two with the half-note as the beat.

## Goals

Using the following examples, determine:
- the defining characteristic of all *compound* meters
- what the top and bottom numbers mean in a compound time signature
- what *duple*, *triple*, and *quadruple* mean when describing a compound meter
- "theoretically ideal" beaming in compound meters 
- a list of common meters in *compound duple*, *compound triple*, and *compound quadruple*
- the common beat-counting system that we'll be using in this course (written in the "Compound Quadruple" example)
- how to decide whether 3/4 (or 3/8, 3/16, etc.) is a simple or compound meter

{% capture ex1 %}X:1
T:Common examples of compound duple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:6/8
L:1/8
K:C
G3 GGG | G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:6/4][L:1/4] G3 GGG | G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:6/16][L:1/16] G3 GGG | G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:6/32][L:1/32] G3 GGG | G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

{% capture ex2 %}X:2
T:Common examples of compound triple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:9/8
L:1/8
K:C
G3 GGG G2G| (2GG G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:9/4][L:1/4] G3 GGG G2G| (2GG G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:9/16][L:1/16] G3 GGG G2G| (2GG G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||
[M:9/32][L:1/32] G3 GGG G2G| (2GG G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2||{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

{% capture ex3 %}X:3
T:Common examples of compound quadruple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:12/8
L:1/8
K:C
G3 GGG G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2 G/2GGG/2 GGG||
w:1 2 la li 3 li 4 & 1 to la ta li ti 2 to la li ti 3 to ta ti 4 la li
[M:12/4][L:1/4] G3 GGG G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2 G/2GGG/2 GGG||
[M:12/16][L:1/16] G3 GGG G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2 G/2GGG/2 GGG||
[M:12/32][L:1/32] G3 GGG G2G (2GG|G/2G/2G/2G/2G/2G/2 G/2G/2GG/2G/2 G/2GGG/2 GGG||{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## The problem with 3

Use the MIDI player to listen to the following two examples. Even though they are identical excerpts, one thing has been altered in the second example. What was altered, and does it change your perception of whether the tune is simple or compound? Provide your final classifications for both examples.

{% capture ex4 %}X:4
T:Amelia's Waltz
M:3/4
K:D
Q:1/4=100
L:1/8
A,|"D"D3 E D2|"D"D2 F3 E|"Bm"D2 F2 BF|"F#m"A3 F A2|\
"G"B2 G3 B|"D"A2 F3 E|"Bm"D2 B,3 A,|"G"B,4 A,2 |
"D"D3 E D2|"D"D2 F3 E|"Bm"D2 F2 BF|"F#m"A3 F A2|\
"G"B3 c d2|"G"d2 e2 f2|"A"e2 B2 c2| "D"d6 ||{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

{% capture ex5 %}X:5
T:Amelia's Waltz
M:3/4
K:D
Q:1/4=180
L:1/8
A,|"D"D3 E D2|"D"D2 F3 E|"Bm"D2 F2 BF|"F#m"A3 F A2|\
"G"B2 G3 B|"D"A2 F3 E|"Bm"D2 B,3 A,|"G"B,4 A,2 |
"D"D3 E D2|"D"D2 F3 E|"Bm"D2 F2 BF|"F#m"A3 F A2|\
"G"B3 c d2|"G"d2 e2 f2|"A"e2 B2 c2| "D"d6 ||{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

## Conclusions

After a quick review of our general definitions from Overview, the class quickly worked through compound meters. *Compound meter* is a **regular** meter in which the beat is divided into three equal parts. This definition took a few tries to find its simplest form, because the students struggled to differentiate regular versus irregular meters. We will not be covering irregular meters until later in the course, so I asked them to consider the subjective nature of meters that will be discussed in the next topic, 4c - Metric Perception. After that discussion, we will see if this concept makes more sense.

For a *compound* time signature, the class suggested that:
- the top number is how many divisions are in the meter.
- the bottom number is the rhythmic value of the division.

These definitions actually took quite a few tries to reach. The students were somewhat careless with their use of the terms *beat, division*, and *subdivision*, but these three terms are the keys to separating compound from simple meters and their time signatures. In a simple meter, the top number is the number of *beats* in the measure, and the bottom number is the note value of the *beat*. Contrast that with compound meter time signatures. The top and bottom numbers represent entirely different concepts, and for compound meters, this requires a slight bit of math to find the actual number of beats. One student simplifed it to:
- To find the number of beats in a compound time signature, divide the top number by 3.

Of course, this highlights the primary problem with our time signature system. It requires the user to already understand the system by being able to differentiate between simple and compound meters, because the system is not uniform across all meters. This is why the pedagogical method of grouping meters by *simple* vs *compound* and then attaching a word to denote the number of beats (i.e. single, duple, triple, quadruple, etc.) is useful.

### Duple, Triple, and Quadruple:

The terms duple, triple, and quadruple refer to the number of beats in the measure. In compound time: 
- duple has 2 strong beats with 3 eighth notes per beat.
    - ex: 6/8
- triple has 3 strong beats with 3 eighth notes per beat.
    - ex: 9/8
- quadruple has 4 strong beats with 3 eighth notes per beat.
    - ex: 12/8

Within a given meter classification, there are many different time signatures. For example, in compound duple, there is 6/8, 6/16, 6/4, and many others.

 ### Differentiating between compound and simple meters

 The simplest method to differentiating is to memorize the standard groupings of all meters. That being said it is fairly easy to remember that if the top number of the time signature is a multiple of three, then that is a compound meter, assuming that the tempo does not become too slow or too fast.

### "Theoretically ideal" beaming in compound time

Like simple time, theoretically ideal beaming in compound time does not obscure beats. Unlike simple time, compound time is written this way in common practice with few exceptions and only one that is notable. Occasionally a compound meter will create hemiola -- a feel of two against three -- by having three consecutive groups of two divisions over two compound beats. The most common notation of this occurs in 6/8 when three quarter notes are placed in a row. If written using quarter notes rather than tying two eighth notes together, this will obscure the second beat. The tune "America" from *West Side Story* highlights this rhythm as its primary melodic motif. 

### Beat counting

As with simple meters, there are various systems for counting beats and their divisions. One of the most common systems condenses the method for counting beats in simple time to 1-&-a. The other most common counting method uses 1-la-li. For this course, we will use the -la-li method to help differentiate the counting from a simple meter.

The problem with both of these systems is that there is not a unique syllable for each subdivsion. Generally speaking, students are asked to insert "ta" between each of the division syllables creating 1-ta-la-ta-li-ta. This is adequate for practice aloud, but it is poor for specificity because there are three 'ta' syllables in each beat. For our class, we are going to try using:
1-to-la-ta-li-ti 

## Meters that have a '3' as the top number of the time signature

After listening to the two examples in 3/4, the class easily identified that the two examples were identical except for the tempo. In the slower example, every person in the class heard it in a simple triple meter with the quarter note as the beat. For the faster example, all but one student changed to hear it as a fast compound single meter with the dotted half note as the beat. Meters such as 3/8, 3/4, and 3/2 are all dependent on tempo as to whether they are a compound or simple meter. While a good rule of thumb is to consider these meters as simple until you have listened to the piece at tempo, 3/8 meters are commonly fast and conducted in one. Make sure to look at the tempo if determining a meter's classification when only looking at the score.