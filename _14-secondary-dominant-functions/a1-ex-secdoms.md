---
layout: chapter
title: 14a Examples - Secondary Dominant Chords
abc: true
---

## Secondary dominant chords

As we begin chromatic harmony, remember that all tonal harmony relates back to the fundamentals of the diatonic harmony that we have explored thus far. Secondary dominant chords share possibly the closest relationship to diatonic progressions and are an obvious extension of circle-of-fifths progressions.

To begin, harmonize the following progression in four-part harmony. Because it is full of root position triads, you will need to use multiple incomplete chords to avoid voice-leading errors.

{% capture ex1 %}X:1
T:A standard progression
M:4/4
L:1/2
K:C
V:1
[cE] [c]| [d] [d]| [c2]|]
V:2 clef=bass
[C,G,] [A,,]| [D,] [G,,]| [C,2]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

In Unit 7, we discussed the evolution of the circle-of-fifths progression, and in that process, we saw that the circle-of-fifths progressions are strong because the voice-leading closely mirrors are a series of V-I progressions. With that in mind, let's zoom in on the middle measure of the ii-V-I progression that you completed above. (This will work for any voicing that you chose, but I have inserted the voicing that I used.) On the staff below, I have isolated the ii and V chords in the first two measures. In the second two measures, all of the voices are the same, but I have altered the key signature to that of the key of the V chord -- in this case, G Major. Analyze the harmony now in G major, and make sure to consider the new key signature. What progression have we created? 

{% capture ex2 %}X:2
T:Altering ii-V
M:4/4
L:1/2
K:C
V:1
[dF] [dG]|| [K:G] [dF] [dG]||
V:2 clef=bass
[K:C] [D,A,] [G,,B,]|| [K:G] [D,A,] [G,,B,]||
w:C:ii V G:? ?{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

As you can see, these two progressions are identical with the exception of one accidental. The ii-V progression in C major has a weaker pull than the V-I progression in G major, but they are functionally similar. Therefore, we could strengthen the ii-V progression in C major by adding one accidental to the ii chord to have it mimic the dominant chord in a secondary key. To try this, take your completed progression from the first example above and alter the one pitch necessary in the ii chord to "borrow" the dominant chord from G major. (I have provided you with my voicing if you deleted yours.)

{% capture ex3 %}X:3
T:Changing ii into a dominant chord
M:4/4
L:1/2
K:C
V:1
[cE] [cE]| [dF] [dG]| [c2E]|]
V:2 clef=bass
[C,G,] [A,,A,]| [D,A,] [G,,B,]| [C2C,2]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Tonicization and secondary function

In this case, the progression is momentarily acting as if a non-tonic chord -- in this case, the V chord -- *has become* the tonic. We call this *tonicization*. It is the process of borrowing the dominant function from a non-tonic chord's key to provide emphasis and prolong a chord's function. 

Tonicization is a *secondary function*. When studying function in diatonic contexts we discussed the primary functions of tonic, dominant, and pre-dominant, as well as alternate functions such as cadential, passing, pedal, and arpeggiated. Secondary function is yet another category of functions in which the primary functions--i.e. the tonic and dominant relationship--*of a second key* are used in our original key. 

{% capture ex5 %}X:5
T:Changing ii7 into a dominant seventh chord
M:4/4
L:1/2
K:C
V:1
[cE] [cE]| [d^F] [BG]| [c2E]|]
V:2 clef=bass
[C,G,] [A,,A,]| [D,C] [G,,B,]| [C,2C]|]
w:C:I vi V7/V V I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

## Labeling secondary dominant chords

In the example above, the ii chord becomes a major chord once the sharp is added, so it is no longer a ii chord. To denote this in our Roman numerals, we use two Roman numerals separated by a slash: V/V. We read this as "five of five". In this labeling, the Roman numeral before the backslash is the chord's function as if it were *in the key of* the Roman numeral after the slash. In our example above, the D minor chord becomes a D major chord, so it now acts as the V chord in the key of G major: a "five of five".

One important note, standard practice for secondary function chords allows you to tonicize any chord that is *not* a diminished triad. This means that vii<sup>o</sup> in major and minor as well as ii<sup>o</sup> in minor should not be tonicized.

Because we label secondary functions in Roman numerals using slashes, students often confuse the function of the slash with leadsheet symbols. In leadsheet symbols, a slash denotes an inversion to the chord by denoting which pitch is in the bass voice, where in Roman numerals, we use *inversion figures* to denote the bass note. A slash in Roman numerals implies a secondary function and tells you what key is being tonicized. While both systems are useful for theorists, you must be careful not to let the nomenclature mix together.

## Secondary dominant seventh chords

In our progression above, what would happen if we had decided to use a ii<sup>7</sup> chord instead of a ii chord? Try it on the following staff. Start by harmonizing the ii<sup>7</sup>-V-I progression below while making sure that you resolve your chordal thirds and sevenths correctly. Once you have a voicing that you like, alter the ii<sup>7</sup> chord using accidentals to create a V<sup>7</sup> in the key of G major -- a V<sup>7</sup>/V (read: "five seven of five")

{% capture ex4 %}X:4
T:Changing ii into a dominant seventh chord
M:4/4
L:1/2
K:C
V:1
[cE] [c]| [d] [d]| [c2]|]
V:2 clef=bass
[C,G,] [A,,]| [D,] [G,,]| [C,2]|]
w:C:I vi ii7 V I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

### Conclusion

When you alter the ii<sup>7</sup> chord in the same way that you altered the ii triad to create a secondary dominant, you create a secondary dominant seventh chord--in this case, a V<sup>7</sup>/V.

There are many possibilities for using these beyond tonicizing V chords, because any major or minor triad can be tonicized by a secondary dominant seventh chord. Instead of altering the ii chord in the above progressions, try altering the vi chord. What chord will it tonicize? Which accidentals will need to be borrowed? What will you call it once you have altered it? We will fully examine these ideas in Unit 15.