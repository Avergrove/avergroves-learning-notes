#  Jigsaw loop

|||
|---|---|
|![Jaws](/img/tetris/pc/jigsaw_pc/jigsaw_jaws.png)|![PCO](/img/tetris/pc/jigsaw_pc/jigsaw_pco.png)|
|Jaws|PCO Variant|

The Jigsaw loop is a loop that starts with Jaws / PCO variant to achieve a 100% setup rate.

Jigsaw loop is a great learning tool for learning how to work with Perfect Clears. The simplified version will teach and help you grasp the following:
- Looping (1st PC -> 2nd PC -> DPC)
- S/Z DPC
- Recovery (Tub recovery, S/Z DPC Recovery)

Though you will need to do some analyzing in your spare time and why this is the case.

This page expands beyond the "Ultimate Simplified Jigsaw PC Loop". If you haven't learned that, go read up and learn that first!
https://torchlight.github.io/tetnotes/simplified-jigsaw.html

The main purpose of this page is not to help you solve the jigsaw 1st and 2nd PC (there's already plenty of resource for those!), but ***rather to help you "gently" dip your toes into 2nd PC step by step and avoid getting overwhelmed.***

This page aims to help you learn to perform the 1st and 2nd PC too! So you will also be learning the following:
- Saving T for 2nd PC
- Getting familliar with 2nd PC setups.
- Column parity.

- Because ML already has a page showing an overview of the solves on Jigsaw (which is fantastic, actually, go give it a look!), this page will instead focus on how to categorize solutions together and learn how to practice them!
    - https://docs.google.com/document/d/13EGXMdc4s_zRhp9VFD7Wq8VhLhAj_6MA4Cge0pvo0m8/edit?tab=t.0#heading=h.i9k2ip5co7ul

### Procedure
Let's first talk about the procedure on how to analyze it, and later talk about the theory behind it!

#### 1st PC
- Setup Phase:
    - Jigsaw loop is a two-setup opener. It has a 100% build rate, but you will need to pay attention to the dependencies!
    - To figure out the correct build direction, we need to search for dependencies. 
        - From the image at the top, we can see that Z is a dependency of S. So we must first place S.
        - The T piece can't be placed with Z is comes before S, so we must first place S.
    - The correct build direction can be determined by the first S/Z that arrives. Place it such that it is horizontal and pointing towards the middle of the field.
        - This will allow you to start the loop 100% of the time.

- Solve phase:
    - Beginner Path:
        - You might be tempted to go always go for the solve, but this isn't always a good idea (Spending T on first PC), at least while learning.
        - First, check if you can get the lucky 10% solve you would usually get in the main loop (without the tub recovery setup). (JSO / LZO) depending on direction
            
            |||
            |---|---|
            |![Jaws Lucky solution](/img/tetris/pc/jigsaw_pc/lucky_solve_1.png)|![PCO Variant lucky solution](/img/tetris/pc/jigsaw_pc/lucky_solve_2.png)|
            |Jaws|PCO Variant|

        - Otherwise, look for another way to PC
            - There are around a total of 12 minimal setups for 2nd PC, and you will easily get overwhelmed if you are forced to learn all of them at once.
            - **Instead, let's try to find a solve that saves the T piece during 1st PC (ie: Good solve). If not, just continue the main loop.**
                - The save T piece 2nd PC setups generally has simpler setups and solutions.
            - Hint1: Both Jaws and PCO are in a column parity imbalanced state.
                - that means you need to put in an odd number of column parity pieces. (J/L/Vert T)
            - Hint2: You will typically be able to solve if you have a heart combination available, even more so if you have both O + SZ to form the heart.
            - Hint3: Let's observe the solutions and categorize them! We can quickly go to the next step if we dont see any of the following combinations..
                - First, let's check the solutions on MetallicLurker's doc and categorize the solutions: https://docs.google.com/document/d/13EGXMdc4s_zRhp9VFD7Wq8VhLhAj_6MA4Cge0pvo0m8/edit?tab=t.0#heading=h.i9k2ip5co7ul
                - Jaws (SZJ start): 
                    - If T is placed in the usual orientation (vertically, just like in our regular Jigsaw)..
                        - You will always need a LS / LZ / JS / JZ **pair**. (ie one squarey J/L piece, one zigzaggy S/Z piece)
                        - You will likely be able to solve if the fourth piece is an I or O piece.
                    - Unique solution: If T is placed horizontally:
                        - You will always need an LJ pair 
                        - Alternatively, you will need IO + Z
                    - Rare solution: This is only one solution
                        - It uses s symmetrical set: IO + LJ.
                - PCO Variant (TSZ start):
                    - If L is placed "normally" as in our loop (ie vertically to form a nice box)
                        - You will always need a pair or LS / LZ / JS / JZ pair. (ie one squarey piece, one zigzaggy piece, just like Jaws)
                        - You will likely be able to solve if the fourth piece is an I or O piece. (Are you seeing a repeating pattern here?)
                    - Unique solution: The L is placed horizontally.
                        - You will always need an I piece.
                        - ![horizontal L Placement](/img/tetris/pc/jigsaw_pc/PCO_hori_L.png)
                        - The remaining slot can be solved with any 2-piece Heart combination \<3
                    - Rare solution: This is only one solution:
                        - You will place the I piece first. Then slap in TZO.
            - If we observe that pattern from hint 3, we can make the following conclusions:
                - Most solves use Heart (So we will be left with Save T, odd L/J for 2nd PC setups)
                - This is important because these setups are usually easier to solve, especially we are just starting to learn 2nd PCs.



#### 2nd PC
- Setup Phase:
    - Beginner Path:
        - Lucky JSO / LZO:
            - If you got lucky and rolled a JZO / LZO, you can continue building Step 2 and always get your tub + horizontal I piece.
            - If you don't want to do SZ DPC and want to learn 3rd PC with extra O, try and build the 3x4 box in this step using JZL / JSL instead of JOL box.

        - 2nd PC Setups:
            - If you've been following the instruction from the previous step (as in 1st PC, not "Lucky JSO / LZO") and saved the T for the solve, you should now have at least 1 T piece among your 4 pieces.
            - You can now check https://tetris.johnbeak.cz/2nd/minimal.php for 2nd PCs. Thanks to PC theory, we now know that we only need to learn 4 + 1 setups (vs 12)!
            - Anyway, if you didn't get the lucky LSO solve, then your remaining pieces will almost always be the anti-matching pair J+Z / L+S (Anti-matching here means that usually JSJ / LZL forms a box, so JS and LZ are "matching") 
            - Also, your remaining 4 pieces will likely include an I piece in it due a large majority of the solves from 1st PC using an O piece.
            - Therefore, we can now train specific scenarios for 2nd PC in tools like Himitsu Confidential's usermodes.
            - The most common residues will be the following:
                1. TI + ...
                    - Matched Heart: JZ / LS (Tub + Vertical I 2nd)
                    - Mismatched heart: JS / LZ (Tub + Vertical I 2nd / broken tub 2nd)
                    - O + Z/S (Mount, hold O 2nd, it's kind of rare because using LJ during 1st PC is rare.)
                2. TO + ...
                    - Matched Hearts: JZ / LS (Heart + PCO 2nd)
                    - Mismatched heart: JS / LZ (Factory 2nd, else Heart + PCO 2nd)
                3. T + L/J +...
                    - SZ (Tub + Vertical I 2nd)
                - Categorization: 
                    - An easy way to remember is TI = Tub series, TO = Heart series solves.
                    - Broken tub is used if vertical I tub can't be constructed (dependency is out of order)
            - Here are some 2nd PC usermodes you can use to practice so you can memorize them rapidly without having to swap between setups every loop:
                - Tub + Vertical I 2nd / Broken Tub 2nd:
                    - TI + JZ: https://tinyurl.com/nneyrphn
                    - TI + LS: https://tinyurl.com/mrf49c9h
                - Factory 2nd: 
                    - TO + JS: https://tinyurl.com/2sb7vhfz
                    - TO + LZ: https://tinyurl.com/p4na9j29
                        - Can also practice Heart + PCO 2nd with.
                - Heart + PCO 2nd:
                    - TO + JZ: https://tinyurl.com/yc6bx5zu
                    - TO + LS: https://tinyurl.com/2sanzvpu
                - Mound: 
                    - TIO + S: https://tinyurl.com/2tv238pd
                    - TIO + Z:  https://tinyurl.com/2uevv86f

#### 3rd PC / DPC
From this point on, you can either go for DPC to practice the basic 1-2-DPC loop, or Freestyle for 7 PCs, glhf!
- Theoretically, most people die inside if they get S/Z for the 3rd PC (Because solving it is painful), so if you are learning to consecutive PC, go for a save O back in 2nd PC! Because lots of solutions there involves heart shapes, there is a likely chance you can swap an O out for an SZ.
- Either way, try and freestyle up to 7th PC if you'd like if you're practicing! The freestyle pc tips can be found in PC_Tips.md

## Theory
### Column Parity and why solutions have even / odd J/L pair counts.
If you've been solving the (regular) PCO setup or Jigsaw for a while now, you may start noticing a pattern. 

- You might have told yourself something like the following before:
    - "Okay, if I place a T piece in the solution, then I need to do a floating line clear"
    - "If I drop a vertical T piece here, this hole can be symmetrical, I just need two symmetrically pair to solve this, like I+O, or S+Z, or L+J"

- Well, the reason answers both of those question boils down to the following (important) concepts
    - Parity
    - Column parity

- Parity is something you may have heard before while playing versus. Now let's put a checkerboa-
    - Well, actually, if you're reading this, you probably know about it already. Basically a T-piece is the only piece that can affect the board parity, while floating line clears *might* shift pairty, depending on the lines above the clear.

- Column parity is a similar concept to parity, but instead of laying a checkerboard on the tetris matrix, we lay vertical lines onto the field. This gives us two interesting facts:
    - The J, L, and vertical T piece can alter column parity!
    - Column parity is *not* affected by line clears! When you clear a line, blocks simply fall down, not sideways.

![Intro to Perfect Clear Theory](/img/tetris/pc/intro_to_pc_column_parity.png)

#### Why column parity matters
- If you've been reading the <a href="https://docs.google.com/document/d/1udtq235q2SdoFYwMZNu-GRYR-4dCYMkp0E8_Hw1XTyg/edit?tab=t.0#heading=h.z6ne0og04bp5">"Introduction to PC Theory"</a> recommended at the start, you might see the following:
***The column parity rule states that the number of L pieces, J pieces, and “vertical” T pieces together must sum to an even number for any PC.***
- This is a very important point, if we count the number of L and J pieces in the current PC (4L), we can rule out a large number of solutions that wouldn't work in advance, and help reduce mental power needed!
    - In the case of jigsaw just like during the solve above, you will notice that I pointed out things like "You will need an LJ pair", "You will need one L/J", this is because can see this in advance based on what we already place on the board.
    - This rule explains why some of the setups work better than the others; When you are forced to place an odd number of column parity pieces, you might get unlucky and end up not being able to solve because ytou ran out of column parity pieces.
    - Because column parity imbalance can't be resolved by floating line clears (as compared to checkerboard parity), it's important that we pay attention to the number of pieces we have available before solving!
- So once you've gotten familliar with column parity in Jigsaw, let's try and extend this knowledge to consecutive PC.

### What's a "Heart" and why is it mentioned a lot?

Hearts are two-piece setups that look like a heart when rotated 45 degrees.

This is a heart:
![Heart](/img/tetris/heart.png)
![Many Hearts](/img/tetris/many_hearts.png)

A heart is effectively a 3x3 box with one block chopped out. 

The main reason it's interesting is that there's a lot of ways to make these, using any two from involving L/J + SZO!

It's also the fundamental building unit for 6-3 stacking, so make sure you learn them!

Hearts are interesting because they can help you build rectangles, nice shapes that will enclose pesky S/Z pieces. The 1x hole in the corner also becomes a foundation for many other combinations