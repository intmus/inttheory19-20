---
layout: chapter
title: 23a Lesson - Basic PC Set Manipulation
abc: true
---

# Class discussion
## Basic PC Set Manipulation

Vocabulary:
1. Atonal music: music without a tonal center or key
2. Twelve-tone music: music that doesn't value any pitch over another; all pitches are of equal importance
3. Serial music: music created from a mathematical process
4. Pitch class: a note and all of its enharmonic equivilants
5. Interger notation: numbers assigned to each pitch class
  - fixed zero interger notation: a system of interget notation where C is always 0, and every pitch class interger is assigned according to that.
  - movable zero interger notation: a system of interger notation where 0 is set to whatever pitch class a musical example somewhat revolves around
6. PC Collection: a scale for a non-diatonic group of pitches
7. PC Set: a group of pitches in order
  - a PC set can be a PC collection, but a PC collection CANNOT be a PC set.


How is manipulating a pitch class set helpful as a musician?
- playing atonal music
- **looking for a pattern for our ears to cling to**

A chord with two tones is a dyad. 
When analyzing atonal music, parentheses and commas versus brackets and commas mean different things. 

### Mod 12 Arithmetic
In music we use 12 because there are 12 pitches.
We want to always get our final number between 0 and 11. 
Sometimes you have to subtract 12 to get to a number between 0 and 11, because for set theory analysis, all octaves are considered of equal importance.
- C + P4 = F
- this is the same, but with interger notation 0 + 5 = 5

#### More Examples
- Gb + m3 = Bbb / 6 + 3 = 9
- A + P5 = E / 9 + 7 = 16 (4 for the octave equivalent)

Wherever you set zero, integer notation tells you how many half-steps you move. 
We typically use fixed zero, so if you're good at your intervals in C major, you will be able to short cut this.

Why do we have movable do?
-transposition

Fixed zero is what we normally use: so integer notation is centered around C at 0. 
Enharmonic Equivalency exists between pitch-classes that share the same tone but have different possible pitch names.
- for example, Db and C# are the same tone. 

### Normal Form (Normal order)
The formula is Tn()=()
  - the parenthesis contain numbers
T: transpose by
n: the number you are altering the following pitch-classes by
- ex: T5(0,5,8) = (7,0,3)
  - you take n and add it to the given intergers
  
Take a Cmaj7, spelled ECGB. 
Put it in closed position, but maintain the inversion. 
That is spelled EGBC (4,7,e,0)
That is how you find normal form, where the pitches are in an order as condensed as possible.

## How to find normal order:
 1. Put the pitch-classes on the clock and find the smallest distance between the pitches.
 2. Notate the numbers on a staff and find the closed position, then re-notate them into interger notation. 
  - Ex: (1,7,t)
  - normal form: (7,t,1)

Permutations: we have all the different arrangements possible listed.
- 17t, 1t7, t71, t17, 71t, 7t1
  - automatically we can aliminate some of these, because they have to be in (clockwise) ascending form
  - 17t, t17, 7t1
    - the order with the smallest interval is 7t1. So we write it in brackets as [7,t,1]
 **Brackets identify normal form**
 
 What is the relationship between these two pc sets?
(3,7,0)
(2,5,9)
They don't have obvious intervalic relationships
BUT, the first set isn't in normal form.
(3,7,0) to [0,3,7].
[0,3,7] and [2,5,9]. 
Both have intervalic relationships of 3 between the first and second interger, and 4 between the second and third interger.
- a shortcut to find normal form is to subtract the third interger from the first interger
  - the options for (3,7,0) are 0,3,7; 3,7,0; and 7,0,3.
  - the intervals between the outside intervals determine the normal form, you want the smallest interval.
  - (0,3,7) has 7, (3,7,0) has 9, and (7,0,3) has 8; our normal order is [0,3,7]. 
  
#### Ex: (0,5,7)
- the pc set options with the smallest interval are (0,5,7) and (5,7,0)
- because the interval between the two outside intergers are both 7, we have to look to the interval between the first and second intergers.
- the interval between the first two intergers in (0,5,7) is 5, while the interval between the first two intergers in (5,7,0) is 2, so [5,7,0] is our normal form. 
    
 Normal form: The arrangement of pitches in ascending order that have the smallest interval between them
 
 #### Ex: (2,3,5,8,e)
 Options in ascending order:
 - (2,3,5,8,e); (3,5,8,e,2); (5,8,e,2,3); (8,e,2,3,5); and (e,2,3,5,8).
 
 Intervals between:
 - (2,3,5,8,e) 9 6 3
 - (3,5,8,e,2) 11
 - (5,8,e,2,3) 10
 - (8,e,2,3,5) 9 7
 - (e,2,3,5,8) 9 6 4
  - Our normal form is [2,3,5,8,e]
  
# Further reading

## From *Open Music Theory*

### Transposition

In post-tonal music, transposition is often associated with motion: Take a chord, motive, melody, and when it is transposed, the aural effect is of *moving* that chord, motive, or melody in some direction. That’s the effect here, in two disconnected passages from Debussy's, *La cathédrale engloutie*:

[![](/images/postTonal/transposition.png)](/images/postTonal/transposition.png)

The opening motive — comprising the notes B, D, E, or {11, 2, 4} — is transposed four semitones higher in m. 18, representing the cathedral’s slow ascent above the water. Transposing something preserves its intervallic content, and not only that, it preserves the specific arrangement of that thing’s intervals. When we hear the passage at m. 18 above, we recognize its relationship to the passage in m. 1 because the same intervals return, but starting on a different pitch.

Transposition is an operation — something that is *done* to a pitch, pitch class, or collection of these things — or alternatively a *measurement* — representing the distance between things. We represent it as *Tn*, where *n* represents the ordered pitch-class interval between the two things. To transpose something by *Tn*, add *n* to every element in that thing (mod 12). Given the collection of pitch classes in m. 1 above and transposition by *T4*:

[![](/images/postTonal/t4.png)](/images/postTonal/t4.png)

The result is the pitch classes in m. 18. *T4* {11, 2, 4} = {3, 6, 8}.

Alternatively, to determine the transpositional relationship *between* two things, subtract the first thing from the second. If the numbers that result are all the same, the two things are related by that *Tn*.

[![](/images/postTonal/t4Measurement.png)](/images/postTonal/t4Measurement.png)

This is how I arrived at the *T4* arrow label in the musical example above, by “subtracting” the pitch class integers of m. 1 from the pitch-class integers in m. 18.

### Normal Form

Normal order (sometimes called normal form) has a lot in common with the concept of triad “root position.” Among other things, root position is a standard way to order the pitch-classes of triads and seventh chords so that we can classify and compare them easily. Normal order does the same, but in a more generalized way so as to apply to chords containing a variety of notes and intervals.

Normal order is the most compressed way to write a given collection of pitch classes. Often, you’ll be able to determine normal order intuitively using a keyboard or a clockface, but it’s good to learn a process that will always give you the correct answer.

1. Write as a collection of pitch classes (eliminating duplicates) in ascending order and within a single octave. There are many possible answers.
2. Duplicate the first pitch class at the end. 
3. Find the largest ordered pitch-class interval between adjacent pitch classes.
4. Rewrite the collection beginning with the pitch class to the right of the largest interval and write your answer in square brackets.

For example, given {G-sharp4, A2, D-sharp3, A4}:

1. *Write as a collection of pitch classes (eliminating duplicates) in ascending order and within a single octave.* {8,9,3}
2. *Duplicate the first pitch class at the end.* {8,9,3,8}
3. *Find the largest ordered pitch-class interval between adjacent pitch classes.* In this case, the largest interval is between "9" and "3."
4. *Rewrite the collection beginning with the pitch class to the right of the largest interval and write your answer in square brackets.* [3,8,9]

Occasionally you’ll have a tie in step 3. In these cases, write the ordering implied by each tie and calculate the interval from the first to the penultimate pitch class. The ordering with the smallest interval is the normal order.
