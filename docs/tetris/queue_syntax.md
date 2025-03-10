# Queue Syntax
If you are working with user modes on Himitsu Confidential, you might be interested in queue syntax! This is the thingy you put in the input box!
It's generally similar to Regex but not really.

- Pieces / groups are separated by comma.
    - General order: `S, Z, T` Just means give SZT in order
    - Wildcard: `*` just means any piece. It's only one piece (unintended reference), though.
        - Internally, this seem to get replaced into IOSZJTL.
    - 3x Wildcard: `*,*,*`. Give me 3 of any piece.
    - Bag: `[SZT]` Give one piece among IOSZ.
    - 3x Bag `[SZT], [IO], [JL]` Draw randomly from an SZT bag, then from an IO bag, then from a JL bag. 
    - Any order: `!`, typically used after a bag or wildcard to expand and expend each piece from a bag. It's kind of like factorial expansion. Has no use by itself.
    - One bag: `[*]!` - One full bag in a random order.



## The Sfinder bot
>minimals v115@ngB8GeD8FeG8CeG8BeI8AeI8AeD8JeAgH *p7 7



>allspin_sol_finder v115@fgQ4zhywB8R4RpBtwwD8Q4Rpg0BtG8i0G8hlI8glI8?glD8JeAgWaA28/DBxngHBFbcRASUD6AZRaHBQecRAylAAAf?gRpzhR4B8RpwwBtR4D8ywi0G8Btg0G8hlI8glI8glD8JeAA?PaAVEYHBzngHBFbcRASEBVBVIaHBQecRAylAAAfgi0RpywB?8Btg0RpQ4wwD8BthlR4G8glwhQ4G8glwhI8whI8whD8JeAA?PaAV+vKBwngHBFbcRASEROBVLaHBQecRAylAAAfgRpBtzhB?8RpwwBtR4D8ywi0G8R4g0G8hlI8glI8glD8JeAAPaA0Fg2A?1ngHBFbcRASEJEBXLaHBQecRAylAAAfgRpg0glzhB8Rpg0g?lywD8h0hlwwAtG8Q4BtG8R4I8Q4I8AtD8JeAAPaAU7XHBwn?gHBFbcRASEB6AULaHBQecRAylAAAfgRpR4zhB8RpywAtg0D?8R4wwBtg0G8Ath0G8hlI8glI8glD8JeAAPaAy8f2A2ngHBF?bcRAS0+5AWLaHBQecRAylAAA OJIZLTS 7

- Please copy paste only one board.. not all 6 of them. Use this instead
>allspin_sol_finder v115@ngB8GeD8FeG8CeG8BeI8AeI8AeD8JeAgH OJIZLTS 7


