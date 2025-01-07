# Fast chord to mode mapping
- If you are playing Jazz, chances are everyone talks about modes. The basic form is 251, and you see people saying D dorian, G mixolydian, C Ionian, but what if we just want to stick it to the key of C?

## Scenario 1: We only use diatonic chords
- Let's break down what scale we need to use based on the following
- A D min chord belongs to a minor scale. (D minor: -1 flat)
- A E min chord belongs to a minor scale (E minor: +1 sharp)
- A G dom chord belongs to a mixolydian scale (G mixolydian: 0 modification!)
- A A min chord belongs to a minor scale (A minor: 0 modification)
- Let's ignore B dim for now. Because it's complicated
- A C maj chord belongs to a major scale. (C major: 0 modification)

- So we can see that modifications really only range from -1 to 1.
- So in a major diatonic scale, we can safely play Lydian / Mixolydian
- The same applies for minor diatonic scale.

- Circling back, what about the B dim? It plays the following:
    - B, C#, D, E, F, G, Ab, Bb
    - We can ignore the C# since this causes a modification to our C key and is an avoid tone.
    - So we are left with B, C, D, E, F, G, Ab, Bb
    - Conveniently, this is Melodic / Harmonic Minor, so we can also use melodic / harmonic minor.

- To summarize, if our song sticks to only diatonic chords, we can happily jazz away in +-1 key signature, and use melodic / harmonic minor relative to major if needed.

## Scenario 2: We use borrowed chords
- WIP
- To experiment:
    - If we see a major chord, we attempt to use the Major modes (Lydian, Ionian, Mixolydian)
    - If we see a minor chord, we attempt to use the minor modes (Dorian, Aeolian, Phrygian, Locrian)
    - If we see a dominant chord... try to use Mixolydian neightbours (Ionian, Mixolydian, Dorian)
    - If we see a dim chord, .. yeah this aint working.

- But honestly, just synthesize your own scales and pay attention to the chord tones at this point.