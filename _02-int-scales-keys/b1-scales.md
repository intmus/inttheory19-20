---
layout: chapter
title: Lesson 2b - Scales and Scale Degrees - Diatonic, Pentatonic, and Chromatic
abc: true
---

<!--  MUST ADD MODES BEFORE NEXT YEAR IN ORDER TO PREPARE MODE MIXTURE -->

In this course, we will be studying many styles of music, but all of these will have roots in the harmonic and melodic practices of the common practice period. The common practice period is generally considered to include Western art music from the Renaissance through the Romantic eras, but any music that that grew out of this tradition--including almost all popular music today--can be analyzed using the tools we will study for common practice harmony.

## Scales

Whereas intervals are the basic building blocks of all music, *scales* represent the next step up the complexity ladder. Whenever you group any number of pitches, you create a *collection*. However, when you order a collection from top to bottom, you create a scale. A scale is a collection of pitches with a defined intervallic pattern when organized in a ascending or descending form--in short, a series of intervals--and can encompass any tuning system or style of composition.

We will explore some extended scales later in this course, but certain scales are at the core of all common practice harmony, and as a music student, you are likely already familiar with these: *major, minor, pentatonic, and chromatic*.

### Goals for this topic:

Using the examples below, create definitions and/or simple explanations for:
- the intervallic pattern of the *major* scale and all forms of *minor* scales
- how major and minor *pentatonic* scales relate to the major and minor scales
- why *natural, melodic,* and *harmonic* minors are named as they are
- the names for each scale degree (i.e. tonic) as well as the corresponding numeral notation
    - how the names for each scale degree are derived (e.g. How are dominant and subdominant scale degrees related?)
- the Latin spelling for every solfege

### Important notes

The following examples demonstrate how the tune of *Happy Birthday* would be written if only using the notes from a particular scale. In all examples, scale degrees are numbered below each pitch as well as solfege using movable "do". Additionally,scale degrees are named above the pitches for the examples in major and melodic minor. When determining your pitch collections, pay particular attention to the differences of the sixth and seventh scale degrees.

### Major

(Because ABC notation does not support scale degrees, I have placed a `^` in front of each scale degree. In normal scale degree notation, the `^` would appear *above* the numeral for each scale degree, not before it.)

{% capture ex1 %}X: 1
%%staffsep 100%
T:Happy Birthday in G major
M:3/4
L:1/4
Q:1/4=90
K:G
"dominant"D/2>D/2| "submediant"E D "tonic"G| "leading tone"F2 D/2>D/2| E D "supertonic"A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol la sol do ti sol sol la sol re do sol sol
d "mediant"B G| F E "subdominant"c/2>c/2| B G A| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol mi do ti la fa fa mi do re do{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Minor scales

There are three forms of the minor scale, and each has a specific role. As you listen to these three melodies, only one of them will sound as if it has no surprising pitches. Once you have found the example that doesn't have a "surprise moment, consider the name of the mode. Does it give you some insight into why it sounds best playing this melody?

### Natural minor

{% capture ex2 %}X:2
%%staffsep 75%
T:Happy Birthday in G natural minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
D/2>D/2| E D G| F2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do te sol sol le sol re do sol sol
d B G| F E c/2>c/2| B G A| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol me do te le fa fa me do re do{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

### Harmonic minor

{% capture ex3 %}X:3
%%staffsep 75%
T:Happy Birthday in E harmonic minor
T:using the relative minor to G major
M:3/4
L:1/4
Q:1/4=90
K:G
B,/2>B,/2| C B, E| ^D2 B,/2>B,/2| C B, F| E2 B,/2>B,/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
B G E| ^D C A/2>A/2| G E F| E2|]
w:^5 ^3 ^1 ^#7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol me do ti le fa fa me do re do{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

### Melodic minor

When first determining your basic rules for melodic minor, you may want to choose to ignore 'le' in measure 6. That pitch serves a harmonic goal as part of a *cadence*, rather than a melodic function.

{% capture ex4 %}X:4
%%staffsep 100%
T:Happy Birthday in G melodic minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
"dominant"D/2>D/2| "submediant"E D "tonic"G| "leading tone"^F2 D/2>D/2| E D "supertonic"A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
d "mediant"B G| "subtonic"F HE "subdominant"c/2>c/2| B G A/4D/4"raised submediant"=E/4^F/4| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^5 ^#6 ^#7 ^1
w:sol me do te le fa fa me do re sol la ti do{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

### Major pentatonic

This is more of a teaching example rather than an actual modal shift, because the major scale and major pentatonic scales do not share the same type of relationship that the major and minor scales have. Certain scale degrees do not exist in the pentatonic scale, so it requires some "artistic license" to translate any tune that utilizes all seven scale degrees.

{% capture ex5 %}X:5
%%staffsep 75%
T:Happy Birthday in G major pentatonic
M:3/4
L:1/4
Q:1/4=90
K:G
D/2>D/2| E D G| D2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^5 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol la sol do sol sol sol la sol re do sol sol
d B G| D E d/2>d/2| B G A| G2|]
w:^5 ^3 ^1 ^5 ^6 ^5 ^5 ^3 ^1 ^2 ^1
w:sol mi do sol la sol sol mi do re do{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

### Minor pentatonic

We must also apply the same restrictions to the minor pentatonic scale. These scales do not correlate directly to their seven-note counterparts, so this is more of a re-imagining of Happy Birthday.

{% capture ex6 %}X:6
%%staffsep 75%
T:Happy Birthday in G minor pentatonic
M:3/4
L:1/4
Q:1/4=75
K:Bb
D/2>D/2| F D G| D2 D/2>D/2| F D B| G2 D/2>D/2|
w:^5 ^5 ^7 ^5 ^1 ^5 ^5 ^5 ^7 ^5 ^3 ^1 ^5 ^5
w:sol sol te sol do sol sol sol te sol me do sol sol
d c B| G HF c/2>c/2| B G F| G2|]
w:^5 ^4 ^3 ^1 ^7 ^4 ^4 ^3 ^1 ^7 ^1
w:sol fa me do te fa fa me do te do{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

### Chromatic scale

This final example is a heavily ornamented version of *Happy Birthday* that demonstrates every possible solfege as well as the correct resolution for all chromatic tones. This arrangement is still technically in G major, because strictly speaking, the chromatic scale is a collection of pitches and does not necessarily center around one tone. (Note that because ABC notation has no way to represent scale degrees, I was forced to omit the `^` that would normally appear above each scale degree and to use a `b` to represent a flat and a `#` to represent a sharp. Please forgive the misuses.)

{% capture ex7 %}X:7
%%staffsep 75%
T:Happy Birthday in G major (a la R. Strauss)
T:decorated to demonstrate all possible scale degrees and solfege
M:3/4
L:1/4
Q:1/4=75
K:G
"5"D/2>"#5"^D/2| "6"E/2"b6"_E/2 "5"D "1"G/2"#6"^E/2| "7"F2 (3"5"D/2"#4"^C/2"5"D/2| "6"E "5"=D "2"A/2"7"^F/2| "1"G2 "5"D/2>"5"D/2|
w:sol si la le sol do li ti sol fi sol la sol re ti do sol sol
"5"d/2"b5"_d/4"4"c/4 "3"B/2"b3"_B/4"2"A/4 "1"G| "7"F/2"b6"=F/2 "6"HE "4"c/2>"4"c/2| (3"3"B/2"#2"^A/2"3"B/2 "1"G/2"#1"^G/2 "2"=A/2"b2"_A/2| "1"G2|]
w:sol se fa me me re do ti te la fa fa mi ri mi do di re ra do{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

## Conclusions

Upon hearing a scale, most non-musicians recognize an obvious building block for creating music, even though they cannot articulate why. In my opinion, the simplest definition of music is "organized sound", and a scale represents an easily understood arrangement of pitches. 

This definition also provides a launching point for discussing pitch collections and scales. If we accept that music is "organized sound", then the method used to organize it will define any *style* of composition. For this course, we will be studying *tonal* music, because *tonal* describes the organizational method of this music.

Tonal music is organized around a central tone called the *tonic*.

Once we have chosen a central pitch around which we build a tonality, every pitch in the tonality is defined by its relationship to that pitch. It is these intervallic relationships that create pitch collections, and we can further categorize them by studying their commonalities and differences. 

### Diatonic music

For the majority of this course, we will be discussing *diatonic* music which is a subset of tonal music. The term *diatonic* can have a variety of meanings depending on context, but for this course, we will be using this term to refer to music that:
- is built around a tonic pitch
- includes all seven pitch names (i.e. letters)
- has a specific order of intervals that create a scale

Put simply, our musical hierarchy is:

- *Music* - organized sound
    - *Tonal music* - music organized around a central pitch
        - *Diatonic music* - tonal music that uses all seven letter names only once and follows a specific order of intervals
            - *Diatonic scale* - a ascending (or descending) ordering of all seven pitches in a diatonic pitch collection, contained within one octave

### Intervallic patterns

In diatonic music, each scale has seven pitches. All seven letters can be used once, and no letter can be used more than once. This creates a series of 2nds that create our scale.

Major scales have an intervallic pattern of:

*(W = whole-step, H = half-step, A = augmented 2nd)*

W - W - H - W - W - W - H

Natural minor scales have an intervallic pattern of:

W - H - W - W - H - W - W

Harmonic minor scales have an intervallic pattern of:

W - H - W - W - H - A - H

Melodic minor scales have both an ascending and descending form. The intervallic pattern for descending melodic minor is identical to a descending natural minor scale. (The necessity of this seemingly redundant pattern is discussed below under "Why we *need* three minor scales".) The intervallic pattern for 4ascending melodic minor is:

W - H - W - W - W - W - H

### Labeling scale degrees

When discussing scales, it is helpful to have a method that refers to pitches without referencing a specific key. For example, the first "Happy Birthday" example on the previous page is written in G major, but there are eleven other tonics around which we could structure that melody's intervallic structure. In order to reference the interval pattern rather than the actual pitches, we use *scale degrees*. 

One common way to communicate pitches of the scale is to use scale degree numbers. We denote these by placing a caret `^` above the scale degree number. For example, the pitch that is a fifth above the tonic would be called fifth scale degree and would be written as `^5`, although the caret would be above the numeral, not to the side.

A second common way to describe scale degrees is to use *solfege syllables*. In this system, each scale degree is assigned a single-syllable Latin word, and this can be helpful when sight-singing. The chart below shows all seven base solfege syllables and how each can be altered for raised and lowered pitches. If a solfege symbol is marked as "N/A", this alteration is non-functional in tonal harmony.

Scale degree | Solfege syllable | Raised | Lowered
 --- | --- | --- | ---
 ^1 | do | di | N/A
 ^2 | re | ri | ra
 ^3 | mi | N/A | me
 ^4 | fa | fi | N/A
 ^5 | sol | si | se
 ^6 | la | li | le
 ^7 | ti | N/A | te

A final method for labeling scale degrees is to use the names of the functions of each pitch as it relates to tonic. These names evolved over centuries of theory treatises from scholars such as Rameau, Riemann, Secther, Schoenberg, and Schenker. We will not use these names often in this course, but knowing them can help understand harmonic function when that concept is introduced.

They are:
1. Tonic 
2. Supertonic
3. Mediant
4. Subdominant
5. Dominant
6. Submediant
7. Leading-tone/Subtonic

Notice the relationship between any term and its counterpart as denoted by the prefix `sub`. The dominant is a fifth above the tonic; the subdominant is a fifth below the tonic. The mediant is a third above the tonic; the submediant is a third below the tonic. 

The supertonic is a 2nd above the tonic, but because of the importance and function of the leading-tone, its scale degree name changes to reflect the difference between a major 2nd below the tonic versus the minor 2nd below the tonic. If the 2nd below the tonic is a whole-step, we call it the subtonic. If the 2nd below the tonic is a half-step, we call it the leading tone. This is true in both major and minor.

### Tonal centers and modes

We consider a key to be defined by its tonic, so if two scales share a tonic, they are considered to be the same key but different *modes* of each other. For example, G major and G minor are the same key, but different modes. This is confusing for many students, because they have always associated their concept of a key with its key signature.

### Why we need three minor scales

Most intermediate music students understand that they must learn different forms of the minor scale, but they do not often give much thought as to why. 

Natural minor is the most obvious. It uses all of the naturally occurring notes from the key signature.

We will discuss the role of harmonic minor more when we begin analyzing chords, but as the name implies, it is a form of minor that emphasizes the most common scale degrees from a harmonic standpoint.

The "Happy Birthday" examples above are perfect for exploring the importance of melodic minor. By keeping the interval sizes from "Happy Birthday" but changing the pitches to fit the various forms of minor, you can hear three similar but distinct versions of "Happy Birthday". When a student first listens to the natural minor version, they often feel that the first `te` does not work with the rest of the tune, and in the harmonic minor version, the augmented 2nd that occurs between `ti` and `le` is jarring. On the other hand, the melodic minor version sounds entirely correct (although some may not like the darker tone of a traditionally "happy" song.)

This easily highlights the role of melodic minor -- to create melodies in minor. By having both an ascending and descending version, we can resolve the sixth and seventh scale degrees upward and downward by relying on the tendency of those scale degrees. `Te` and `le` both have a strong downward pull and almost always resolve downward. `Ti` and `la` both have a strong upward pull and tend to resolve upward. These are general rules and are occasionally broken, but I encourage you to play with the example below to hear how "strange" the piece becomes if you do not allow the sixth and seventh scale degrees to account for their resolutions. (Try putting `la` in for every sixth scale degree for the most obviously jarring version.)

{% capture ex8 %}X:8
%%staffsep 100%
T:Happy Birthday in G melodic minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
D/2>D/2| E D G| ^F2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
d B G| F HE c/2>c/2| B G A/4D/4=E/4^F/4| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^5 ^#6 ^#7 ^1
w:sol me do te le fa fa me do re sol la ti do{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}

### Pentatonic Scales

The pentatonic scale is a nearly universal sonority as demonstrated by Bobby McFerrin in the following clip.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ne6tB2KiZuk" frameborder="0" allowfullscreen></iframe>

Neither the major or minor form of the pentatonic scale relates strongly to the harmonic functions that we will study in this course, but their prominence in world and folk musics makes them an important part of our musical heritage. This alone justifies familarity with these colors.

Major and minor pentatonic scales have a simple relationship to their major and minor counterparts. The major pentatonic scale uses the first, second, third, fifth, and sixth scale degrees of the major scale. The minor pentatonic scale uses the first, third, fourth, fifth, and seventh scale degrees of the minor scale. 

Even though they do not function diatonically, there are two general concepts of harmony in pentatonic scales.
1. The tonic and dominant scale degrees still function as the primary harmonic "poles" in a pentatonic scale.
2. The lack of a leading tone in both forms is the primary reason that these do not function similarly to diatonic harmony. That being said, `la` in major pentatonic scales and `te` in minor pentatonic scales can take on a similar function by pulling toward the tonic in a melody. 

### Chromatic scale

The chromatic scale is not a tonality, because it has no tonic. It is however, the aggregate pitch collection and functions as a useful way to familiarize a musician with all twelve pitch-classes.

The final "Happy Birthday" version above uses every possible scale degree in order to demonstrate resolution in a diatonic key, but it is not a "chromatic" tonality. That example is still in G major, but it is heavily embellished using chromatic tones.

Of particular note, the example demonstrates the importance of considering resolution when choosing which chromatic pitch to use. Generally, if a pitch is raised, it should resolve upward; if a pitch is lowered, it should resolve downward. For example, `li` and `te` are enharmonically equivalent, but they function differently because their accidentals imply specific resolutions. `Li` should resolve to `ti`, but `te` should resolve to `la`. This is not only important in simplifying notation for harmonic analysis, but it also makes it easier for performers when reading heavily chromatic music.

### Putting it all together

If we were to put attach all of these ideas to staff notation, we get:

{% capture ex9 %}X:9
%%staffsep 100%
T:Major scales
M:4/4
L:1/8
K:G
"Major" G A B c d e f||
w:do re mi fa sol la ti 
w:^1 ^2 ^3 ^4 ^5 ^6 ^7
w:tonic supertonic mediant subdominant dominant submediant leading~tone
"Pentatonic" G A B d e ||
w:^1 ^2 ^3 ^5 ^6
w:do re mi sol la{% endcapture %}
{% include abc-example.html number="9" abc=ex9 %}

{% capture ex10 %}X:10
%%staffsep 100%
T:Minor scales
M:4/4
L:1/8
Q:1/8=60
K:Bb
"Natural" G A B c d e f||
w:do re me fa sol le te
w:^1 ^2 ^3 ^4 ^5 ^6 ^7
w:tonic supertonic mediant subdominant dominant submediant subtonic
"Harmonic" G A B c d e ^f|| 
w:do re me fa sol le ti
w:^1 ^2 ^3 ^4 ^5 ^6 ^#7
"Ascending Melodic" G A B c d =e ^f| "Descending Melodic" g =f _e d c B A||
w:^1 ^2 ^3 ^4 ^5 ^#6 ^#7 ^1 ^7 ^6 ^5 ^4 ^3 ^2 
w:do re me fa sol la ti do te le sol fa me re do 
"Pentatonic" G B c d f ||
w:^1 ^3 ^4 ^5 ^7 
w: do me fa sol te{% endcapture %}
{% include abc-example.html number="10" abc=ex10 %}
