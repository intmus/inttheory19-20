---
layout: chapter
title: 23c Examples - PC Set Prime Form
abc: true
---

Pitch-class integer notation and the two primary forms of manipulation -- transposition and inversion -- allow for a tremendous amount of flexibility in analysis. This flexibility comes with the drawback of making comparison difficult, because there is no guarantee that a pc set is in the same order. For this reason, we use normal form to ensure that our comparisons between pc sets are built in a consistent manner. This is also why you should always normalize a pc set after inverting it.

## How many are there?

If you were to group all of the unique transpositions and inversions of a pc set, how many permutations would there be? To explore these ideas, first write out all unique inversions and transpositions of the following prime form pc set. This set represents a typical pc set in that every transposition and inversion is unique.
- (014)

Because there are twelve possible starting pitches and for both the starting set and its inversion, there are typically twenty-four possible pc sets within a set class. And because we use normal form to represent each pc set within a set class, this means there is *only* one arrangement of the pc set for each starting pitch. (If every unique order of pitch classes was considered as well, there would be vastly more options depending on the cardinality of (i.e. the number of pitch classes within) a pc set.

## Set class

Theoretically, we can determine whether any two pc sets are related by transposition, inversion, or both. To try this, study the following four trichords. How are they related? What method(s) will you use to find the relationships? As you work through this, keep track of the manipulations you make to find compare them. Hint: It will be helpful to make sure that you are always working with the normal form.
- (2,9,6)
- (8,4,1)
- (e,2,7)
- (6,2,8)

For fairly simple trichords such as these, there are a variety of methods you could use to compare them. Some people will write them using traditional notation on a staff, yet others will attempt to visualize them on clock or number line. These visual methods may work to a degree for a simple trichord but fail on two accounts
- It is difficult to scale to larger, denser pc sets.
- It is difficult to see the relationship for anything other than transposition.

For these reasons, set theory has a system to reduce and compare any pc set into a group of all related pc sets. Any two pc sets that are related by transposition and/or inversion are considered to be part of the same *set class*. All of the trichords listed above belong to the same set class, and we can show this using simple manipulations.

If we put each of them into normal form, we get:
- [2,6,9]
- [1,4,8]
- [7,e,2]
- [2,6,8]

Just by doing this, it easy to use addition and subtraction to show that the first and third trichords are directly related by transposition:
- T<sub>5</sub>[2,6,9] = [7,e,2])

And the second and fourth are related in the same manner 
- T<sub>1</sub>[1,4,8] = [2,6,8]

Because an inverted pc set often has no common tones with its original pc set, it is more difficult to see inverted relationships. For this, it would be easier to create a "standard" around which we can examine all pc sets in normal form within a set class. For this, let's try reducing both sets above to begin with 0. If we do this the first pair of pc sets becomes [0,4,7] and the second pair becomes [0,3,7]. You can see that they are similar in that they both use pitch classes 0 and 7, but are they related by inversion? Let's try inverting one of them, normalizing it, and then reducing it to a normal form that begins on 0.

- [2,6,9] reduces to [0,4,7] (by transposing by -2)
- [0,4,7] inverts to [0,8,5]
- [0,8,5] normalizes to [5,8,0]
- [5,8,0] reduces to [0,3,7] (by transposing by -5)

Therefore, we can see that all four of our original trichords are related by transposition and inversion. Or we could also say that *they all belong to the same **set class**.*

## Prime form

The process that we just demonstrated is the actual method for finding a pc set's *prime form*. Prime form is the "most reduced" version of any pc set. It will always start with 0, and it is used to denote an entire *set class*--all possible transpositions and inversions of a given pc set.

In the above trichords, we had two possible prime forms [0,3,7] and [0,4,7]. These two trichords represent the reduced trichord of both inversions of this pc set. To determine which is prime form, we apply the same tie-breakers that we used when determining normal form: start by comparing the outermost intervals and then work your way inward. Both of these trichords have an outer interval of 7, but [0,3,7] has a smaller second interval (i.e. 0 to 3 is smaller than 0 to 4). Therefore, the prime form of **all** of the above trichords is:

(037)

Notice the notation of prime form. For this we use parentheses only with no commas. (All of the notation that we use for pc sets--unordered, normal, and prime forms--was standardized by Joseph Straus in his *Introduction to Post-tonal Theory*.)

## Finding prime form for any pc set

Now that you understand the goal of prime form -- finding one pc set to represent all transpositions and inversions -- let's try another one to see if we can develop a step-by-step process for finding prime form of any pc set. Try finding the prime form of the following tetrachord. Remember that you need to check the inversions as well.

(4,t,8,3)

Hopefully you came to the answer of (0157)

To find prime form, you:
1. Put the pc set into normal form.
2. Transpose that set to begin with 0.
    - Remember this pc set, because it will be one of two possible options at the end of the process
3. Invert your pc set.
    - You may use either the normal form of the original or the reduced version that begins with 0. They will get you to the same answer after Step 5.
4. Put the new pc set into normal form.
5. Transpose this new pc set to begin with 0.
6. Compare the two pc sets that begin with 0 using the tie-breaker system that we outlined for identifying normal form.
    - These are the final forms taken from steps 2 and 5.
    - You will always end with a pc set that begins with 0.
7. Notate your prime form using parentheses and no commas.

## Symmetrical set classes

What could reduce the number of pc sets within a set class? Write out all unique inversions and transpositions for the two following pc sets for examples that deviate from the standard possibility of twenty-four unique permutations. What causes these to have so many less pc sets in the set class?
- (048)
- (0158)

The number of pc sets in a set class can be reduced if the pc set is symmetrical: augmented triads, diminished seventh chords, the whole tone scale, and the octatonic scales are all symmetrical set classes with less than twenty-four unique pc sets, but there are many others that have symmetry reducing the number of pc sets in the set class.