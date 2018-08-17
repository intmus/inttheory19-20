---
layout: chapter
title: 16b Examples - Pivot chords
abc: true
---

## The benefit of using leadsheet symbols in analysis

As we leave strict diatonic function and begin to explore chromatic alterations, one of the most difficult challenges in analysis is discerning what tonic is implied at any given moment. Roman numeral analysis shows function -- tonic, dominant, etc., -- but a chord's function is determined by its relationship to tonic. Simply put, you cannot write a Roman numeral if you do not know your tonic.

Leadsheet notation solves this issue by providing a way to begin analyzing music that is independent of key or tonic. An F major chord could be a I chord in F major, a IV chord in C major, a III chord in D-flat major, and many others, but it will always be an F major chord. Leadsheet notation does not rely on any pre-existing knowledge of the piece, so I strongly urge you to begin analyzing music by writing the leadsheet symbols first. This will allow you to look for patterns within chord progressions rather than having to repeatedly analyze the same chord only to change each time that you discover something new.

## Simple modulations and common chords

The simplest modulation is one that uses the expectations of the listener and produces modulations through slight changes. Analyze the following excerpt from a Haydn piano sonata using leadsheet symbols. Even though there is only one altered note, it clearly ends in a different key than the beginning. To begin understanding how this modulation works, ask these key questions:
1. Where do you first *hear* something changing?
2. How is the change prepared?
3. What harmonies transition into and out of the modulation? 

Once you have answered these, create Roman numerals for *both beginning key and ending key*. (This will require secondary function chords.) When looking at the Roman numeral progressions, you can see where the progressions function diatonically and where they emphasize non-tonic chords such as the subdominant.

{% capture ex1 %}X:1
T:Haydn - Piano Sonata in G Major, mvt. 3
M:4/4
L:1/8
K:G
Q:1/4=65
V:1
d| d>e/2f/4 gg g2 fe| e/2d/2c/2B/2 d/2c/2B/2A/2 BG zd|
d>e/2f/4 gb b2 ag| g/2f/2e/2d/2 e2 d2 z:|]
V:2 clef=bass
z| zG, B,C DD, DC| B,G, A,D, G,D,/2B,,/2 G,,2|
w:G:
zG, B,G, zG ^CE| DF, G,A, D,A,, D,,:|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Common chords between keys

When a modulation centers around a common chord between two keys, we call this a *common chord pivot modulation*. To better understand why closely-related keys create smoother modulations, it is helpful to look at the number of common chords between the two keys. In the following chart, I have listed each chord from C major and G major, but I have aligned them by root rather than by scale degree.

C major | Chord | Chord | G major
 --- | --- | --- | ---
 I | **C maj** | **C maj** | IV
 ii | D min | D maj | V
 iii | **E min** | **E min** | vi
 IV | F maj | F#<sup>o</sup> | vii<sup>o</sup>
 V | **G maj** | **G maj** | I
 vi | **A min** | **A min** | ii
 vii<sup>o</sup> | B<sup>o</sup> | B min | iii

You can see that the two keys share four common chords (highlighted in bold), so writing a smooth progression in both keys is fairly easy because it can rely on multiple common chords. Try creating a table like this for distantly-related keys such as C major and E major. What about G major and F minor?

## Pivot chords and modulation points

The *pivot chord* of a pivot chord modulation is more than just a chord that is common to both keys. A pivot chord smoothly transitions from one key to another because it is part of a functional progression in *both* the old and the new keys. The simpler the pivot's progression, the less-jarring the modulation.

In the previous topic, we listened to an excerpt from the third movement of the second movement of Tchaikovsky's Symphony No. 5. Analyze this piece beginning with leadsheet symbols, then add Roman numerals from the beginning until you get to the *modulation point* -- the place where you first hear the modulation. 

**Common chord pivots occur *right before you hear* the modulation point.** 

To show a modulation:
- Draw a bracket that provides an area on top and bottom. Your bracket needs to have more than one line, otherwise it resemble a slash and therefore a secondary function.
- On the top part of the bracket, show the Roman numeral for the pivot chord in the original key.
- On the bottom part of the bracket, name the new key (using an upper/lower case letter followed by a colon) as well as the Roman numeral for the pivot chord in this new key. 

{% capture ex2 %}X:2
T:Tchaikovsky - Symphony No. 5, Mvt. II
T:reduction
M:12/8
L:1/8
K:D
Q:1/8=90
V:1
z6 z3 DCB,| D3 C6 A,B,C| E3 D6 DEF| G3 G2G G3-G2G|G3 F3 z3 DCB,|
D3 C6 A,B,C| E3 D6 DEF| ^G3 G2 G G3-G2 G| ^GBA A6 z3|]
V:2 clef=bass
[A,6E,A,,C,,] [A,6F,A,,D,,]| [A,6G,A,,E,,] [A,6E,A,,G,,]| [A,6A,,F,,] [A,6DF,A,,D,,]| [G,6DE,B,,E,,B,,,] [A,3DA,,,A,,E,,][A,3CA,,,A,,E,,]| [A,6DD,A,,E,,] [F,,6]|
w:D:
[A,6G,A,,E,,] [A,6E,A,,G,,]| [A,6A,,F,,] [A,6DF,A,,D,,]| [F,6FB,D,B,,B,,,] [F,3FB,D,D,,][^G,3^ECC,C,,]| [F,9FCC,F,,] z3|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

What makes this modulation work so well? More specifically, how strong is the progression before and after the pivot chord?