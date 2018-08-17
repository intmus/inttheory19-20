---
layout: chapter
title: 23e Examples - Serialism and Tone Rows
abc: true
---

For many people, the terms *tone row* and *matrix* are synonymous with post-tonal theory, but to this point, we haven't even mentioned them. (If you have never heard of either of these terms, don't worry. We'll get there.)

We haven't discussed them yet, because if you understand set theory, you will have no problem understanding what a tone row is and how we use them in analysis.

## Starting small

First, we need to reaffirm your understanding of set classes. To do this, let's start by writing out each unique, normal-form pc set represented in the set class of (013). What factors increase the number of unique pc sets? What limits the number of pc sets?

Before you began, you probably realized that there would be twenty-four possibilities. Because each of the pc sets will be in normal form, we know that there is only *one* pc set for each possible starting pitch. We can represent these using transposition notation.
- T<sub>0</sub>[0,1,3] = [0,1,3]
- T<sub>1</sub>[0,1,3] = [1,2,4]
- T<sub>2</sub>[0,1,3] = [2,3,5]
- T<sub>3</sub>[0,1,3] = [3,4,6]
- T<sub>4</sub>[0,1,3] = [4,5,7]
- T<sub>5</sub>[0,1,3] = [5,6,8]
- T<sub>6</sub>[0,1,3] = [6,7,9]
- T<sub>7</sub>[0,1,3] = [7,8,t]
- T<sub>8</sub>[0,1,3] = [8,9,e]
- T<sub>9</sub>[0,1,3] = [9,t,0]
- T<sub>t</sub>[0,1,3] = [t,e,1]
- T<sub>e</sub>[0,1,3] = [e,0,2]

There are a further twelve unique pc sets that result from inverting our prime form pc set. Of course, for each of these, you should normalize the pc set after inversion.
- T<sub>0</sub>I[0,1,3] = [9,e,0]
- T<sub>1</sub>I[0,1,3] = [t,0,1]
- T<sub>2</sub>I[0,1,3] = [e,1,2]
- T<sub>3</sub>I[0,1,3] = [0,2,3]
- T<sub>4</sub>I[0,1,3] = [1,3,4]
- T<sub>5</sub>I[0,1,3] = [2,4,5]
- T<sub>6</sub>I[0,1,3] = [3,5,6]
- T<sub>7</sub>I[0,1,3] = [4,6,7]
- T<sub>8</sub>I[0,1,3] = [5,7,8]
- T<sub>9</sub>I[0,1,3] = [6,8,9]
- T<sub>t</sub>I[0,1,3] = [7,9,t]
- T<sub>e</sub>I[0,1,3] = [8,t,e]

Each one of these twenty-four pc sets contains a unique collection of pitch classes. Without using the word "inversion", how would you describe the relationship between T<sub>0</sub> and T<sub>0</sub>I? 

## Visually representing a set class

In the above example, you could describe T<sub>0</sub> and T<sub>0</sub>I as the reverse order of the same *intervals*, but the only obvious correlation between the actual *pitch classes* is that both of the pc sets contain 0 -- which happens to be the interval of transposition for those two sets. (The interval of transposition is the "0" in T<sub>0</sub>.) If you look at each pair of transposed and inverted pc sets, you will notice the same thing; they always share the interval of transposition. If you wanted to represent this visually, you could plot each transposition and inversion on a chart in which this pivot pitch for each transposition became a center pitch and had the inversion and transposition branching out. Look at our trichord charted this way below.

Inv pc set | inv pc 1 | inv pc 2 | **common pc** | tran pc 2 | tran pc 3 | Tran pc set
--- | --- | --- | --- | --- | --- | ---
T<sub>0</sub>I | 9 | e | 0 | 1 | 3 | T<sub>0</sub>
T<sub>1</sub>I | t | 0 | 1 | 2 | 4 | T<sub>1</sub>
T<sub>2</sub>I | e | 1 | 2 | 3 | 5 | T<sub>2</sub>
T<sub>3</sub>I | 0 | 2 | 3 | 4 | 6 | T<sub>3</sub>
T<sub>4</sub>I | 1 | 3 | 4 | 5 | 7 | T<sub>4</sub>
T<sub>1</sub>I | 2 | 4 | 5 | 6 | 8 | T<sub>5</sub>
T<sub>6</sub>I | 3 | 5 | 6 | 7 | 9 | T<sub>6</sub>
T<sub>7</sub>I | 4 | 6 | 7 | 8 | t | T<sub>7</sub>
T<sub>8</sub>I | 5 | 7 | 8 | 9 | e | T<sub>8</sub>
T<sub>9</sub>I | 6 | 8 | 9 | t | 0 | T<sub>9</sub>
T<sub>t</sub>I | 7 | 9 | t | e | 1 | T<sub>t</sub>
T<sub>e</sub>I | 8 | t | e | 0 | 2 | T<sub>e</sub>

Here, the "common pc" column shows the pitch class that is common to both the inversion and the transposition pc sets. (Note that to create this chart, the inverted form of the pc set is written in descending form rather than ascending form, so you must read it backwards to find its normal form.) You can make a chart like this for any pc set, and you can see how helpful this would be if you were analyzing a piece of music that had this trichord present. Rather than only looking for intervallic patterns, you could quickly refer to your chart to identify whether a specific trichord belongs to this set class.

## Expanding the set

What if we were to expand this technique? What would the above chart look like for a pc set with all twelve pitch classes? Before we explore that, let's set some ground rules. If you were to use normal form, there is technically only one prime form for an aggregate pitch set: (0123456789te). However, if we treat the intervallic pattern as a fixed part of the pc set -- meaning we do *not* put the pc set into normal form -- then we can create nearly a million different distinct combinations of all twelve pitch classes.

With this in mind, try creating the first two lines of the above graph (that would be T<sub>0</sub>/T<sub>0</sub>I and T<sub>1</sub>/T<sub>1</sub>I) for the following pc set:
T<sub>0</sub> = (0,2,4,6,8,t,1,3,5,7,9,e)

What do you notice as you work through this? Can you think of different methods for creating T<sub>1</sub>I rather than just mirroring T<sub>1</sub>? While the chart above was not too unwiedly for addressing all possible variations on a trichord, can you think of a way to create a chart that shows every combination (transposed and inverted) of an aggregate pc set that would take less space than the clunky chart above?

## Developing a matrix

The answer to the pc set would take up too much screen for me to succinctly write in a table here, but in plain text the order would be:
- T<sub>0</sub>I 1 3 5 7 9 e 2 4 6 8 t **0** 2 4 6 8 t 1 3 5 7 9 e T<sub>0</sub>
- T<sub>1</sub>I 2 4 6 8 t 0 3 5 7 9 e **1** 3 5 7 9 e 2 4 6 8 t 0 T<sub>1</sub>

What if rather than writing T<sub>0</sub> and T<sub>0</sub>I in a straight line, we rotated the inversion pc set, T<sub>0</sub>I, downward at 90 degree angle to create a verical column? This would create the outline for a 12 by 12 grid with T<sub>0</sub> as the top row and T<sub>0</sub>I as the first column.

-- | T<sub>0</sub>I |  |  |  |  |  |  |  |  |  |  
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
T<sub>0</sub> | 0 | 2 | 4 | 6 | 8 | t | 1 | 3 | 5 | 7 | 9 | e
-- | t |  |  |  |  |  |  |  |  |  |  |  
-- | 8 |  |  |  |  |  |  |  |  |  |  |  
-- | 6 |  |  |  |  |  |  |  |  |  |  |  
-- | 4 |  |  |  |  |  |  |  |  |  |  |  
-- | 2 |  |  |  |  |  |  |  |  |  |  |  
-- | e |  |  |  |  |  |  |  |  |  |  |  
-- | 9 |  |  |  |  |  |  |  |  |  |  |  
-- | 7 |  |  |  |  |  |  |  |  |  |  |  
-- | 5 |  |  |  |  |  |  |  |  |  |  |  
-- | 3 |  |  |  |  |  |  |  |  |  |  |  
-- | 1 |  |  |  |  |  |  |  |  |  |  |  

This grid is a called a *matrix*. We could then fill in each *row* of our matrix with the transpositions of the original pc set and each column with inversions. For example, where would the other two pc sets that we figured out in our original example, T<sub>1</sub> and T<sub>1</sub>I, fit in this grid? 

## Filling out the matrix

Because the top row is the original pc set and the column is its inversion, it makes sense to place the next pc sets, T<sub>1</sub> and T<sub>1</sub>I, in the row and column respectively that begin with the pitch class "1". It would look like this:

-- | T<sub>0</sub>I |  |  |  |  |  | T<sub>1</sub>I |  |  |  |  
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
T<sub>0</sub> | 0 | 2 | 4 | 6 | 8 | t | 1 | 3 | 5 | 7 | 9 | e
-- | t |  |  |  |  |  | e |  |  |  |  |  
-- | 8 |  |  |  |  |  | 9 |  |  |  |  |  
-- | 6 |  |  |  |  |  | 7 |  |  |  |  |  
-- | 4 |  |  |  |  |  | 5 |  |  |  |  |  
-- | 2 |  |  |  |  |  | 3 |  |  |  |  |  
-- | e |  |  |  |  |  | 0 |  |  |  |  |  
-- | 9 |  |  |  |  |  | t |  |  |  |  |  
-- | 7 |  |  |  |  |  | 8 |  |  |  |  |  
-- | 5 |  |  |  |  |  | 6 |  |  |  |  |  
-- | 3 |  |  |  |  |  | 4 |  |  |  |  |  
T<sub>1</sub> | 1 | 3 | 5 | 7 | 9 | e | 2 | 4 | 6 | 8 | t | 0 

Because we have done this correctly, you'll notice the pitch classes in the bottom row line up perfectly with the final pitch class from our new column. Why?

The great thing about this system is that once each of the transpositions is filled in correctly, each *column* will be a correctly transposed version of the inverted pc sets. Once filled in, a matrix such as this shows every transposition and inversion of any aggregate pc set.

## Serialism and 12-tone music

Before we go further, we should briefly define the genre of music most associated with set theory and matrices. (Although set theory can be used to study *any* type of music as long as it divides the octave into twelve pitches.) *Serialism* is any music in which some aspect of the composition is based on a pre-defined repeatable pattern; this can be the melodic intervals, harmonic intervals, harmonies, rhythm, or any other aspect of music that could be described in a series.

*12-tone music* is a sub-genre within serialism in which a fixed series of all twelve pitches is used to generate both the melodic and harmonic content of the piece. There are a variety of ways in which composers have employed this, but in its strictest form, all twelve pitches must be used before a pitch can be repeated. The series that determines the order of all twelve pitch classes is called a *tone row*, represented by our top row in the example above. To provide compositional variety, the tone row may be altered to any of its transpositions or inversions, and any of tone row may also be played in *retrograde* -- all pitches in reverse order. So from this, there are four forms of a tone row.
- Prime (P) - a tone row or any of its transpositions
- Retrograde (R) - any *prime* row played in reverse order
- Inversion (I) - the inversion of the original prime tone row and all its transpositions
- Retrograde inversion (RI) - any inverted row played in reverse order

Because any of these tone row orders can start on all twelve pitches, there are forty-eight possible arrangements of any tone row: twelve prime tone rows, twelve inverted tone rows, twelve inversion tone rows, and 12 retrograde inversion rows. We label these using the abbreviations above (P, R, I, and RI) followed by a subscript number to represent the transposition. (e.g. P<sub>5</sub> or RI<sub>6</sub>).

Using this terminology, complete the tone row matrix above by filling in each row and then labeling. Is it necessary to go in a particular order? What is the easiest way to fill it out. Knowing that we use P, I, R, and RI to label each direction of the matrix, how would you differentiate each tone row? Would retrograde tone rows be labeled by their starting pitch or their corresponding prime label?

## Completing our tone row matrix

The correctly completed tone row matrix for our original row would be:

-- | I<sub>0</sub> | I<sub>2</sub> | I<sub>4</sub> | I<sub>6</sub> | I<sub>8</sub> | I<sub>t</sub> | I<sub>1</sub> | I<sub>3</sub> | I<sub>5</sub> | I<sub>7</sub> | I<sub>9</sub> | I<sub>e</sub> | --
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
P<sub>0</sub> | 0 | 2 | 4 | 6 | 8 | t | 1 | 3 | 5 | 7 | 9 | e | R<sub>0</sub>
P<sub>t</sub> | t | 0 | 2 | 4 | 6 | 8 | e | 1 | 3 | 5 | 7 | 9 | R<sub>t</sub>
P<sub>8</sub> | 8 | t | 0 | 2 | 4 | 6 | 9 | e | 1 | 3 | 5 | 7 | R<sub>8</sub>
P<sub>6</sub> | 6 | 8 | t | 0 | 2 | 5 | 7 | 9 | e | 1 | 3 | 5 | R<sub>6</sub>
P<sub>4</sub> | 4 | 6 | 8 | t | 0 | 2 | 5 | 7 | 9 | e | 1 | 3 | R<sub>4</sub>
P<sub>2</sub> | 2 | 4 | 6 | 8 | t | 0 | 3 | 5 | 7 | 9 | e | 1 | R<sub>2</sub>
P<sub>3</sub> | e | 1 | 3 | 5 | 7 | 9 | 0 | 2 | 4 | 6 | 8 | t | R<sub>3</sub>
P<sub>9</sub> | 9 | e | 1 | 3 | 5 | 7 | t | 0 | 2 | 4 | 6 | 8 | R<sub>9</sub>
P<sub>7</sub> | 7 | 9 | e | 1 | 3 | 6 | 8 | t | 0 | 2 | 4 | 6 | R<sub>7</sub>
P<sub>5</sub> | 5 | 7 | 9 | e | 1 | 3 | 6 | 8 | t | 0 | 2 | 4 | R<sub>5</sub>
P<sub>3</sub> | 3 | 5 | 7 | 9 | e | 1 | 4 | 6 | 8 | t | 0 | 2 | R<sub>3</sub>
P<sub>1</sub> | 1 | 3 | 5 | 7 | 9 | e | 2 | 4 | 6 | 8 | t | 0 | R<sub>1</sub>
-- | RI<sub>0</sub> | RI<sub>2</sub> | RI<sub>4</sub> | RI<sub>6</sub> | RI<sub>8</sub> | RI<sub>t</sub> | RI<sub>1</sub> | RI<sub>3</sub> | RI<sub>5</sub> | RI<sub>7</sub> | RI<sub>9</sub> | RI<sub>9</sub> | --

## Properties of the matrix

Finally let's touch on some general important concepts and common mistakes that you will encounter when creating tone row matrices.

### Important concepts

- The most often used labeling method for tone row matrices is fixed-zero notation, but movable-zero is preferred by some. Either is possible, but make sure that you are consistent in your application and clearly state which method you are using in any analysis.
    - In fixed-zero, 0 will always be the pitch class that includes C.
    - In movable-zero, the analyst chooses a primary pitch to designate as 0 based on the important features of the piece (e.g. it is often the first pitch class of the piece) and then determines each other pitch class's number based on the intervallic relationship to the designated 0 pitch class.
- In a tone row matrix, label each prime and inversion tone row by the abbreviation `P` or `I` respectively, followed by a subscript integer of the first pitch class for that row.
- However, label retrograde (R) and retrograde inversion (RI) rows by their corresponding prime (P) and inversion (I) rows. If you don't have a completed matrix available, but you know that a tone row is a R or RI form, you can just label it using the **last** pitch of the tone row, because that is the first pitch class of the corresponsding P or I row, and therefore the pitch that will be used to name that P or I row.
- There are various ways to arrange the prime and inversion tone rows in the matrix depending on which transposition of the tone row that you choose to place in the top level of the matrix.
    - The first layout is used to prioritize a specific iteration of the tone row. Typically, your original tone row will be taken from a piece of music. Many theorists prefer to format the matrix with the original tone row across the top *in its non-transposed iteration*. For example, if the first iteration of the row started on A-flat, the first row in the matrix would be that row. If you are using fixed-zero notation this would be labeled P<sub>8</sub>, but if you are using movable-zero, this would be labeled P<sub>0</sub>.
    - On the other hand, a matrix is only meant to be a useful tool for analysis, so it's primary role is to help you track all possible uses of the row. It is easier to create a matrix that starts on 0, because creating the first inverted row (I<sub>0</sub>) can be created using your standard fixed-zero inversions -- which you probably already have memorized. (i.e. 0 becomes 0, 1 becomes e, 2 becomes t, etc.) If using fixed-zero, though, it is rare that the piece will begin on pitch class 0 (C). Instead, you can simply transpose your entire tone row to start on 0, write this as the top left row of your matrix, and then create the matrix as we did above. Even though your rows will be in a different order, every row will be *labeled* identically to the other method because you are using fixed-zero notation. 
        - For example, if the first iteration of the row started on A-flat (pc 8 in fixed-zero), you would subtract 8 from that tone row to transpose the entire row to begin on pitch class 0. You can then place this as the top row of your matrix and build the matrix normally. All rows will be labeled correctly according to fixed-zero notation. To make sure that you remember which row is the original row, you will probably want to mark it in some way. I do this by circling the row label (e.g. P<sub>8</sub>) of the row that begins the piece.
- When done correctly, any tone row matrix will have a pitch class that extends diagonally from the top left cell of the matrix to the bottom right cell. In the correct chart above, you can see that the pitch class 0 is in the first cell and then connects diagonally across the entire matrix.

### Common mistakes

- The most common mistake when creating a matrix, other than simply mis-transposing, is the mislabeling of the tone rows. Remember that the labels for R and RI rows are based on their corresponding prime and inverted rows, NOT the starting pitch of the R or RI rows.
- When using a matrix to analyze a 12-tone piece of music, you will occasionally encounter tone row *elision*. Two rows are said to be elighted if the ending pitch class(es) of of one row are actually shared to become the beginning pitch class(es) of the next row. If you encounter a tone row that seems to have less than twelve pitch classes, this is likely the reason.
- If you use movable-zero, you will need to be careful in creating your first inverted row because you will not be inverting around C=0. Proponents of this method usually suggest inverting interval by interval away from the first pitch class. (e.g. If the first interval of the row is an *ascending* M3, then the first interval of your inverted row will be a *descending* M3. You will continue this process for each interval.)

## Technology is great...to a point

As with most things, some enterprising people have created a shortcut to all of this work. There are now free-to-use matrix calculators such as the 12-tone assistant at [this excellent website](http://in.music.sc.edu/fs/bain/software/tta-v2.4d/default.htm). These are great to speed up your analysis, but as a student, make sure that you understand the principles of why and how these work before becoming entirely reliant on them. Even when trying to use this website, you must understand exactly what output you are trying to achieve before you can choose the correct option.

Admittedly, it is unlikely that you will ever be required to create a tone row matrix without access to a calculator (unless you are taking a music theory exam.) But the tedium of transposing each of the rows by hand will help you notice patterns in the tone row and help you to remember the nuances of the tone row as you analyze. This often provides insight into the analysis that would be missed by those relying on a calculator to create the matrix.