# Extension of the Key Signature Values Technique
I want to write here a more "straightforward" way of memorizing key signatures.

First, give the site here a read:
https://www.musictheory.net/lessons/25

Basically we want to give each key signature a value. 0 indicates no key modification. +1 means add 1 sharp (starting from F#) and -1 means add 1 flat (starting from Bb)

So if we create a table for each key signature, we can memorize the following and do some modulo calculation.

## Major Key
First, let's memorize the Major key signature values, it's recommended to just memorize the ones for the black keys too:
Major keys
| Keys | Key Signature Values|
|------|---------------------|
| C, D, E, F, G, A, B (White keys) | 0, 2, 4, -1, 1, 3, 5 |
| Db, Eb, Gb, Ab, Bb (Black keys)  | -5, -3, -6, -4, -2 |

## Minor key
To convert from major key, simply -3 to key signature value.
If the number exceeds 12, then do a 12 - x to flip the value.

ie C major = 0, so C minor = 0 - 3 = -3

I usually just straight up memorize the the black key ones since it requires an extra 12-x calculation. 
The white key ones can be quickly derived using the x-3 method.

| Keys | Key Signature Values|
|------|---------------------|
| C, D, E, F, G, A, B (White keys) | -3, -1, 1, -4, -2, 0, 2 |
| C#, D#, F#, G#, Bb (Black keys)  | 4, 6, 3, 5, -5 |

## Modes
### Quick prelude
I want to quickly first point out that it's easy to get confused with how modes work because books have a habit of teaching "when using the white keys, if you start from D, it's D dorian, if you start from E, it's E phrygian"
I need you to forget that for a moment.

I want you to think it in terms of scales.
So instead of say G mixolydian, I want you to think of something arbitrary instead, like C Mixolydian.
C Mixolydian has 1 flat. If you just play the scale (C, D, E, F, G, A, Bb), it won't sound like a scale since you might not be familliar with it.

But a lot of bluesy songs / jazz songs use this. Even some video game soundtracks use this. That funky feeling you hear in songs is actually Mixolydian popping in!
So instead of playing scales, I want you to try something different, let's build a 7th chord from this scale. 

C, E, G, Bb

Why, that's a Dominant seventh chord, used regularly in blues!
Now let's listen to a soundtrack that uses this.

Final Fantasy 8 - Timber owls
https://www.youtube.com/watch?v=5bJmW1tKzN4

The first 3 notes is mixolydian already. In fact, the whole song is in mixolydian. THAT is what modes are. They are scales. They aren't "starting notes from another position in a scale". They are scales with one or more notes altered from the "major" scale.


### The actual tutorial on finding mode key signatures
Since minor key is just Aeolian mode of Major, we can actually apply the same math to the other modes.

We just have to find the difference for each key signature value.

If we use A major to minor as an example, we can see A goes from 3 to 0, so to convert from major to minor, we simply need to -3.
Repeat this process for each white keys and we get the following:

- Lydian (F): +1
- Ionian (C): 0
- Mixolydian (G): -1
- Dorian (D): -2
- Aeolian (A): -3
- Phrygian (E): -4
- Locrian (B): -5

So a G in each mode will have the following:
- G Lydian: 2
- G Ionian: 1
- G Mixolydian: 0
- G Dorian: -1
- G Aeolian: -2
- G Phrygian: -3
- G Locrian: -4


It's easier to split these into two based on their thirds and calculate from there.

Lydian, Ionian and Mixolydian are major keys because they have a major third.
Dorian, Aeolian, Phrygian and Locrian are minor keys because they have a minor third.

So let's group them up

Calculation from major scale:
- Lydian: +1
- Ionian: 0
- Mixolydian: -1

Example: 
C Lydian = C major (0) + 1 = 1

Calculation from minor scale
- Dorian: +1
- Aeolian: 0
- Phrygian: -1
- Locrian: -2

C Dorian = C Minor (-3) +1 = -2

