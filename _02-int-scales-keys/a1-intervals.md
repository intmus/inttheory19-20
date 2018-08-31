---
layout: chapter
title: Lesson 2a - Identifying and Labeling Intervals
abc: true
---

Now that we have formalized our notation of the most basic level of music notation, a single pitch, we must find a method to measure the distance between two pitches. 

## **Intervals**

Any two-note combination is called a *dyad*, and the distance between the two pitches of a dyad is an *interval*. Intervals are the fundamental building blocks of melody and harmony. At their simplest, intervals need only measure the distance between two pitches, but there are many variables in music for which we must account.

### Goals for this topic

In the example below, each interval represents the concept stated at the beginning of its staff, but each measure *also* has an important relationship to the measures above and below it. Using these, develop a simple explanation for how we find each of the following:
- the *size* of the interval between two pitches as represented by a numeral
- the *quality* of the interval as represented by the labels *perfect, major, minor, diminshed, and augmented*
- which *sizes* can use which *qualities* as well as the hierarchy of *qualities* for each *size*
- *chromatic* versus *diatonic* intervals
- *simple* versus *compound* intervals and how this affects classifying of *quality* and *size*
- how the *size* and *quality* change when the upper and lower pitches of an interval are inverted

### Important concepts

- _**Qualities**_: P = perfect, M = major, m = minor, A = augmented, d = diminished
- _**Diatonic** intervals in the examples below_
  - Major 3rd from the harmonic intervals
  - Major 2nd from the melodic intervals
  - Major 6th from simple intervals
  - Perfect 15th and major 10th from the compound intervals
  - Minor 6th from the inversion pairs
- _**Chromatic** intervals in the examples below_
  - All other intervals

{% capture ex1 %}X:1
T:Intervals
M:1/4
L:1/4
K:C
V:1 name=Harmonic
[_BA]| [ce]| [_e_B]| [D_A]| [^dF]| [CB]| [^f^F]||
w: m2 M3 P4 d5 A6 M7 P8
V:2 name=Melodic
B/2A/2| c/2^e/2| e/2_B/2| _D/2_A/2| F/2_d/2| ^C/2B/2| f/2^F/2||
w:M2 _ A3 _ A4 _ P5 _ m6 _ m7 _ d8 
V:3 name=Simple
[_B^A]| [^c_e]| [_eB]| D/2^A/2| d/2F/2| [C__B]| [^fF]||
w: d2 d3 d4 A5 _ M6 _ d7 A8
V:4 name=Compound clef=bass
[^B,A,,]| [C,_E]| [_E_B,,]| _A,/2_D,,/2| F,,/2_D/2| ^B,/2C,,/2| [FF,,]||
w:A9 m10 P11 P12 _ m13 _ A14 _ P15||
V:5 name=Inversions
[_B,A]| [cE]| [_E_B]| [d_A]| [_df]| [Bc]| [^f^F]||
w: M7 m6 P5 A4 M3 m2 P8{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Conclusions

Our goal when measuring intervals is intrinsically tied to the tonal system that we use, diatonic harmony. The simplest way to measure the distance between two intervals would be to measure the distance by the shortest possible interval--in this case, a half-step (minor second). While easily understandable, this method does not relate to our concept of tonality. Instead, counting half-steps creates *interval-classes* in which intervals are considered equal regardless of the pitches. For example, the interval of `G` to `D-flat` has six half-steps which is identical to the interval from `G` to `C-sharp`. Both even use the same pitch-classes, however, any person familiar with diatonic harmony will immediately associate these two intervals with different key centers. (`G` to `D-flat` is strongly associated with the key of A-flat major/minor, whereas `C-sharp` to `G` likely implies D major/minor.) The context of these two intervals is critical in determining their function in tonal harmony, so we must use a system that differentiates between the two.

In a diatonic labeling system, every interval has a *size* and a *quality*. 

For example, in a minor second, labeled `m2`, the **m** indicates the *quality* of the interval and the **2** indicates the *size* of the interval.

### Interval size

Interval *size* can be determined by considering either:
- lines and spaces
- letter names

Both these methods will correctly identify interval size, although counting letter names yields results without requiring the presence (or visualization) of a staff. Do not forget that you must include the both letters when counting. (e.g. The ascending interval from A to C is a third, because you must count A (1), B (2), and C (3).)

This means that any interval that has the same two letters, regardless of accidentals or key signatures, will always have the same *size*. Using our previous example, the *size* of the interval between `G` and `D-flat` is a fifth. We can change the bottom note to any other `G` (`G-sharp, G-flat`, etc.) and the top note to any other `D` (`D-sharp, D-natural`, etc.), but the *size* of that interval will **always** be a fifth. Yet if we exchange the `D-flat` for its enharmonic equivalent, `C-sharp`, we alter the letters and turn the *size* of the interval into a fourth.

### Interval quality

- If you are completely unfamiliar with scales, you may want to skip one topic ahead to [scales]({{ site.baseurl }}/02-int-scales-keys/b1-scales.html), and then return to this after beginning to understand the construction of the major scale. For a method that does not rely on knowledge of major scales, you can also go to the [Further Reading]({{ site.baseurl }}/02-int-scales-keys/a2-intervals.html) of this topic to find a useful method from the writers of *Open Music Theory*.

Interval *quality* is difficult to examine without beginning to think about our concept of tonality and keys. One of the most common and straightforward methods for finding interval *quality* requires a strong familiarity with the twelve major scales:

**Please remember that each of the following steps only works if you consider `do` as the bottom pitch of the interval.**
1. When looking at an interval, consider the bottom pitch of the interval as `do` of a major scale.
1. If the top pitch of the interval is a note that naturally exists in that major scale, it is either a major or perfect interval. Whether major or perfect depends on the *size*.
  - Unisons, fourths, fifths, and octaves occur naturally as *perfect* intervals within the major scale.
  - Seconds, thirds, sixths, and sevenths occur naturally as *major* intervals within the major scale.
1. Any alteration from the basic major and perfect intervals can then be labeled by looking at the direction of alteration and the number of half-steps that the interval was altered.
  - If the original interval is *perfect*:
    - Raising the interval by a half-step creates an *augmented* interval.
    - Lowering the interval by a half-step creates a *diminished* interval.
  - If the original interval is *major*:
    - Raising the interval by a half-step creates an *augmented* interval.
    - Lowering the interval by a half-step creates a *minor* interval.
    - Lowering the interval by a 2 half-steps creates a *diminished* interval.

From this, our interval hierarchies were grouped as:
- Interval *sizes* of 1, 4, 5, and 8 can only have the *qualities* of perfect, augmented, or diminished.
- Interval *sizes* of 2, 3, 6, and 7 can only have the *qualities* of major, minor, augmented, or diminished.

Some examples using this method:
- `C` to `E`:
  - Counting the letter names confirmed that the *size* is a third (C, D, E = 3)
  - By using the lower pitch, `C`, as `do`, we know that the naturally occurring `E` in the key of C major is `E-natural`.
  - Because this is a third, we know that the naturally occurring note must use the *major* hierarchy, so therefore, `E-natural` would be a **major third *(M3)** above C.
- `D` to `G-sharp`
  - Counting the letter names confirmed that the *size* is a fourth (D, E, F, G = 4)
  - By using the lower pitch, `D`, as `do`, we know that the naturally occurring `G` in the key of D major is `G-natural`.
  - Because this is a fourth, we know that the naturally occurring note must use the *perfect* hierarchy, so therefore, `G-natural` would be a P4 above D.
  - Because `G-sharp` is one half-step above the *perfect* interval, we know that this interval is an **augmented fourth (A4)**.
- `F` to `E-double-flat`
  - Counting the letter names confirmed that the *size* is a seventh (F, G, A, B C, D, E = 7)
  - By using the lower pitch, `F`, as `do`, we know that the naturally occurring `E` in the key of F major is `E-natural`.
  - Because this is a seventh, we know that the naturally occurring note must use the *major* hierarchy, so therefore, `E-natural` would be a M7 above F.
  - Because `E-double-flat` is two half-steps below the *major* interval, we know that this interval is an **diminished seventh (d7)**.

Note that even though *perfect* intervals use a different hierarchy than *major/minor* intervals, but both hierarchies share the terms *diminished* and *augmented*. 

### Melodic vs. Harmonic

Melodic and harmonic intervals are one of the simplest concepts to understand, although the describing them can be problematic. At first, students often describe harmonic intervals as occurring "at the same time" while melodic intervals occur "at different times". While this is a simple explanation, we must be careful in how we apply the terms *interval* and *pitches*. The interval is the space between the two pitches, therefore, the interval cannot occur "at the same time" or "at different times". The pitches can occur simultaneously or consecutively, but the interval always exists as a fixed measurement. This is how we can label harmonic and melodic intervals using the same system.

I recommend that we think of intervals as existing on either a horizontal or vertical axis, because we can visualize axes (as in the plural of axis) easily on musical staff notation. If two pitches occur "at the same time", they will be aligned vertically on a staff. If two pitches occur consecutively, they will represent unique points on a horizontal line that runs parallel to the lines of the staff. This may seem overly technical, but it is an important distinction.

A final note: melodic intervals can have two modifiers attached to them, *ascending* or *descending*. Ascending intervals start with the lower of the two pitches, whereas descending intervals start on the the higher pitch. Harmonic intervals cannot be ascending or descending.
 
### Simple vs. Compound

Simple intervals include any interval that is equal to or smaller than an octave. Compound intervals are any interval larger than an octave.

To label compound intervals, we count letter names as we do for simple intervals. We can find a compound interval by adding 7 to any simple interval. For example, a 2nd becomes a 9th. A 4th becomes an 11th. An 8ve (octave) becomes a 15th.

Conversely, if we see a compound interval, we can find its simple equivalent by subtracting 7. A 12th is a 5th plus an octave. A 10th is a 3rd plus an octave.

You may ask why we don't add eight considering that we are adding an octave. The answer lies in how we find the *size* of intervals. When we find interval *size*, we count the letter names *and include the starting pitch*. When we add an octave, we have already used the top note so we are missing one letter. For example, a fifth from A to E includes the letters `A B C D E`. If we add an octave, the first `E` was already included in the first interval of the 5th, so we are only adding seven letters `F G A B C D E`.

### Chromatic vs. Diatonic

The difference between chromatic and diatonic is probably the most straightforward of the classifications. Simply put, *diatonic* intervals use only the notes of the given key signature, while *chromatic* intervals have accidentals that alter one of both of the pitches.

### Inversions

For this discussion, we are considering an inversion to be an interval in which one pitch is fixed and the other is displaced by an octave toward the fixed pitch.

To determine the *size* of an inverted interval, the first student pointed out that you could create a grid of size pairs, so:
- 4 inverts to 5
- 3 inverts to 6
- 2 inverts to 7
- 1 inverts to 8

Each of these pairs adds up to nine, so if you would prefer to not memorize this grid, you can find an inversion by simply subtracting the size from 9. For example, if there is a written 3rd, subtract 3 from 9 to find that the inversion of a 3rd is a 6th. Note that for compound intervals, you must use subtract from 16 or use negative numbers and absolute values. Because of this, it is easier to reduce compound intervals to a simple interval before inverting.

To find the qualities of inverted intervals, the students agreed that memorizing three pairs is the easiest method:
- diminished becomes augmented
- major becomes minor 
- perfect becomes perfect