---
layout: chapter
title: 8a Lesson - The Overtone Series
abc: true
---

# Class discussion

The *overtone series*, often referred to as the *harmonic series*, is a series of intervals built off of a pitch. There are two ways to label the overtone series. 
- Label the the first pitch of an overtone series the **fundamental** and every pitch above it is then numbered as an **overtone**.
  - Fundamental, 1st overtone, 2nd overtone, etc.
- Label each pitch as a numbered **partial**.
  - 1st partial, 2nd partial, 3rd partial, etc.

The overtone series built off of `C2` would be:

{% capture ex1 %}X:1
T:The overtone series
T:Labeled as a fundamental with numbered overtones
M:2/2
L:1/2
K:C
V:1
x x x x E G _B c d e ^f g|]
w: _ _ _ _ 4th 5th 6th 7th 8th 9th 10th 11th
V:2 clef=bass
C,,C,G,C x x x x x x x x|]
w:fund. 1st 2nd 3rd{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

{% capture ex2 %}X:2
T:The overtone series
T:Labeled as partials
M:2/2
L:1/2
K:C
V:1
x x x x E G _B c d e ^f g|]
w: _ _ _ _ 5th 6th 7th 8th 9th 10th 11th 12th
V:2 clef=bass
C,,C,G,C x x x x x x x x|]
w:1st 2nd 3rd 4th{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

The overtone series occurs naturally and can be explained mathematically, so it is one of the few objective ways in which we can discuss the origin of music. Any interval can be viewed as a ratio comparing the frequncies of the two pitches that create the interval. The simplest ratio, other than 1:1, is 2:1. For example, `C2` has a frequency of about 65.4 hertz (hz = vibrations per second), and `C3` has a frequency of about 130.8: a ratio of 2:1. When we hear two frequencies that have a 2:1 ratio, our brains interpret this as "the same pitch separated by an octave" -- an elegant solution to interpreting a physical phenomenon. This example demonstrates that all concepts associated with music, such as pitches, dividing octaves, intonation, etc., are human creations trying to organize and interpret the physical phenomenon of soundwaves entering our ear.

The overtone series orders intervals by decreasing size but increasing complexity. The first interval of the overtone series, a P8, is the "simplest" interval of 2:1. As the overtone series moves upward, each interval becomes smaller but more complex. A P5 has a ratio of 3:2, a P4 has a ratio of 4:3, a M3 has a ratio of 5:4, and onward. 

## Concepts derived from the overtone series

The overtone series is notable because:
- The overtone series is present above every note played by a standard musical instrument or the human voice.
  - When a person sings a pitch, we hear the fundamental as the pitch name, but the strength of each overtone above that fundamental determines many qualities that we associate with the pitch such as timbre.
- The overtone series is the basis for intonation.
  - Using the ratios from the overtone series, we can determine what is "in tune". For example, an octave is a frequency that is exactly twice as high as the given pitch, and a true P5 is a frequency that is 1.5 times higher than the given pitch.
  - Fixed pitch instruments (e.g. piano) use a system of *equal temperament* to play in all twelve keys without having to re-tune the instrument every time the key changes. This means that we intentionally tune these instruments "out of tune" when compared to the overtone series ratios, because being always slightly out-of-tune is a far better compromise than being perfectly in-tune sometimes and grossly out-of-tune at others.
- The overtone series defines why the octave is divided into 12 parts, because it is from the overtone series that we derive the circle-of-fifths. Please refer to the discussion of the circle-of-fifths and tonality in Lesson 2c. 
- The overtone series provides a visual example of why we find certain intervals more consonant or dissonant. 
  - We hear simpler ratios of intervals as consonant and complex ratios as dissonant. So intervals at the beginning of the overtone series represent consonant intervals, but as the intervals decrease in size as the overtone series moves upward, the ratios become more complex and therefore more dissonant.
- The overtone series provides a good foundation for voicing chords.
  - Idealized voicing for chords often mimic the overtone series by placing each voice along the overtone series of the lowest voice.

## Remembering the overtone series

There are many ways to remember the overtone series.
- The first is to remember the intervals. This is easy at the beginning of the series, but becomes repetitive and easy to mess up as the series ascends.
  - P8-P5-P4-M3-m3-m3-M2-M2-M2-M2-m2.
- You can also think of them as a sequence of scale degrees above the fundamental.
  - 1 - 1 - 5 - 1 - 3 - 5 - b7 - 1 - 2 - 3 - #4 - 5
- And for some, it is easier to divide the series into groupings. For example, when looking at the first 12 partials
  - The first four pitches are a tripled fundamental and one fifth. 
  - The second set of four pitches is a first inversion dominant triad built off of the fundamental. 
  - The final three pitches represent `re-mi-fi-sol` or the beginning of the Lydian mode of the fundamental.

When looking at this final method for remembering the first 12 pitches of the overtone series, I find it fascinating that each group of four pitches implies a different key area:
- The first four pitches strongly imply a key that uses the fundamental as tonic.
- The next 4 partials imply a key with a tonic based on the *subdominant* of the fundamental, because the dominant seventh chord would be a V chord in the key of the subdominant.
- The third set of four paritals imply a key with a tonic based on the *dominant* of the fundamental as demonstrated by thinking of this pattern as `sol-la-ti-do` in the key of the dominant.