#  Jigsaw loop
The Jigsaw loop is a loop that starts with Jaws / PCO variant to achieve a 100% setup rate.

Jigsaw loop is a great learning tool for learning how to work with Perfect Clears. The simplified version will teach and help you grasp the following:
- Looping (1st PC -> 2nd PC -> DPC)
- S/Z DPC
- Recovery

Though you will need to do some analyzing in your spare time and why this is the case.

This page expands beyond the "Ultimate Simplified Jigsaw PC Loop". If you haven't learned that, go read up and learn that first!
https://torchlight.github.io/tetnotes/simplified-jigsaw.html

This page aims to help you learn to perform the 1st and 2nd PC too! So you will also be learning the following:
- Saving T for 2nd PC
- Getting familliar with 2nd PC setups.

## 1st PC
Setup Phase:
    - The correct build direction can be determined by the first S/Z that arrives. Place it such that it is horizontal and pointing towards the middle of the field.
        - This will allow you to start the loop 100% of the time.

Solve phase:
    - Solutions from MetallicLurker's doc: https://docs.google.com/document/d/13EGXMdc4s_zRhp9VFD7Wq8VhLhAj_6MA4Cge0pvo0m8/edit?tab=t.0#heading=h.i9k2ip5co7ul
    - Beginner Path:
        - You might be tempted to go always go for the solve, but this isn't always a good idea (Spending T on first PC), at least while learning.
        - First, check if you can get the lucky 10% solve you would usually get in the main loop (without the tub recovery setup). (JSO / LZO) depending on direction
        - Otherwise, look for another way to PC
            - There are around 12 setups for 2nd PC, and you will easily get overwhelmed if you are forced to learn all of them at once.
            - Instead, let's try to find a solve that saves the T piece during 1st PC (ie: Good solve). If not, just continue the main loop.
                - The save T piece 2nd PC setups generally has simpler setups and solutions.
            - Hint1: Both Jaws and PCO are in a column parity imbalanced state.
                - that means you need to put in an odd number of column parity pieces. (J/L/Vert T)
            - Hint2: You will typically be able to solve if you have a heart combination available, even more so if you have both O + SZ to form the heart.
            - Hint3: Let's observe the solutions and categorize them! We can quickly go to the next step if we dont see any of the following combinations..
                - Jaws (SZJ start): 
                    - If T is placed in the usual orientation (vertically, just like in our regular Jigsaw)..
                        - You will always need a pair or LS / LZ / JS / JZ pair. (ie one squarey J/L piece, one zigzaggy S/Z piece)
                        - You will likely be able to solve if the fourth piece is an I or O piece.
                    - Unique solution: If T is placed horizontally:
                        - You will always need an LJ pair (not including that one case with IZO)
                    - Rare solution: This is only one solution
                        - It uses s symmetrical set: IO + LJ.
                - PCO Variant (TSZ start):
                    - If L is placed "normally" as in our loop (ie vertically to form a nice box)
                        - You will always need a pair or LS / LZ / JS / JZ pair. (ie one squarey piece, one zigzaggy piece, just like Jaws)
                        - You will likely be able to solve if the fourth piece is an I or O piece. (Are you seeing a repeating pattern here?)
                    - Unique solution: The L is placed horizontally.
                        - You will always need an I piece.
                        - The remaining slot can be solved with any 2-piece Heart combination \<3
                    - Rare solution: This is only one solution:
                        - You will place the I piece first. Then slap in TZO.
            - If we observe that pattern from hint 3, we can make the following conclusions:
                - Most solves use Heart (So we will be left with )
                - Solving using the usual orientation with either setup with result in Have T, 



## 2nd PC
Setup Phase:
    - Beginner Path:
        - Lucky JSO / LZO:
            - If you got lucky and rolled a JZO / LZO, you can continue building Step 2 and always get your tub + horizontal I piece.
            - If you don't want to do SZ DPC and want to learn 3rd PC with extra O, try and build the 3x4 box in this step using JZL / JSL instead of JOL box.

        - 2nd PC Setups:
            - If you've been following the instruction from the previous step and saved the T for the solve, you should now have at least 1 T piece among your 4 pieces.
            - You can now check https://tetris.johnbeak.cz/2nd/minimal.php for 2nd PCs. Thanks to PC theory, we now know that we only need to learn 4 setups (vs 12)!
            - Anyway, if you didn't get the lucky LSO solve, then your remaining pieces will almost always be the anti-matching pair J+Z / L+S (Anti-matching here means that usually JSJ / LZL forms a box, so JS and LZ are "matching") 
            - Also, your remaining 4 pieces will likely include an I piece in it due a large majority of the solves from 1st PC using an O piece.
            - Therefore, we can now train specific scenarios for 2nd PC in tools like Himitsu Confidential's usermodes.
            - The most common residues will be the following:
                1. TI + ...
                    - Matched Heart: JZ / LS (Tub + Vertical I 2nd)
                    - Mismatched heart: JS / LZ (Broken Tub 2nd)
                    - O + Z/S (Mount, hold O 2nd) 
                2. TO + ...
                    - Matched Hearts: JZ / LS (Heart + PCO 2nd)
                    - Mismatched heart: JS / LZ (Heart + PCO 2nd)
                        - You can memorize just the solution here for now:https://docs.google.com/document/d/12AF4o6d7acQRlyKLg-071TkYh8ZiYMpQkFS3zVCeRZY/edit?tab=t.0#heading=h.z3hg94crfao6
                        - Basically: 2x TLZ Congruent
                3. T + L/J +...
                    - SZ (Tub + Vertical I 2nd)
            - An easy way to remember is TI = Tub series, TO = Heart series.
            

## 3rd PC / DPC
From this point on, can either go for DPC / Freestyle for 7 PCs, glhf!
- Theoretically, most people die inside if they get S/Z for the 3rd PC. So they go for DPC.
- Either way, try and freestyle up to 7th PC if you'd like if you're practicing! The freestyle pc tips can be found in PC_Tips.md
- By the way, O 3rd PC is a favourite because you just stack 2x O pieces on top of each other (AKA Braindead)