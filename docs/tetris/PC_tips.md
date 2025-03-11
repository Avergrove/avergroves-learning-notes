# PC Tips
It's highly recommended to read the Introduction to Perfect Clear Theory: https://docs.google.com/document/d/1udtq235q2SdoFYwMZNu-GRYR-4dCYMkp0E8_Hw1XTyg/edit?tab=t.0, it will give you an overview of PCing.

This page mostly discusses PCs in general.

- I think one of the most important point to notice in the document is column parity.
- "The sum of L/J and vertical T pieces must add up to an even number", which can help you determine whether a T piece needs to be horizontal or vertical.
- When learning minimals, it might help to group solutions together.
    - Lime DPC will probably be your first experience of this.

## Looping
- A PC loop is 14 lines. The more PCs you can squeeze into a loop, the more score you get.
- Most PCs will require mental brainpower.
- Naturally, this means two things:
    - 14L to one PC is straightforward, but you score less. (because you do just one PC per whole loop)
    - 7x consective PCs score the most. But you will be living in hell, but you will also look cool as hell.
    - So most people go for a balance among the two, usually opting TD openers the finish as 8L PC openers, getting 2 PCs.
    - The alternative is Jigsaw, it can potentially get 3 PCs in a loop!
    - The final form is 7x consecutive PC. It's painful but.. you can do it.

## Overarching PC facts

- Each PC is advanced by 1 for each 4L
    - 1st Pc -> 2nd Pc -> 3rd Pc -> 4th Pc -> 5th PC -> 6th PC -> 7th PC -> 1st (8th dupe) PC
- Each PC is advanced by 4 for each 2L PC.
    - 1st PC -> 5th Pc -> 2nd PC -> 6th PC -> 3rd PC -> 7th PC -> 4th PC -> 1st PC 
        - If you've played music already, this is basically the circular progression in reverse.

    - 1st, 3rd, 4th, 6th PC bag: You are guaranteed to have at least one of the pieces be duplicated.
    - 2nd, 5th, 7th PC bags: you are guaranteed one of 7 unique pieces. Which means you can make setups with dependencies.
    - 4th and 6th PC bags: You are guaranteed to have at least one of the 6 pieces having duplicates.

## PC Freestyling
- With the "duplicated" piece fact, we can now freestyle some PC setups.

General guidelines: 
- Spend your extra pieces on well known setups: jaws, box, etc.
- We want to get rid of extra SZO because those do not affect column parity and they are troublesome.
- Try placing only 4 pieces, then look for a solution. Unless you really, really can't, then only place another piece. Don't get addicted to solving high piece setups.
- We want to save the LJT for the solve if possible.
- Because we want to get rid of extra pieces from last bag, we need to pay attention to which first pieces visible should we get rid of:

| PC Count | Residue pieces |
| -------- | -------------- |
| 1st PC   | None!          |
| 2nd PC   | 4 pieces       |
| 3rd PC   | 1 piece        |
| 4th PC   | 5 pieces       |
| 5th PC   | 2 pieces       |
| 6th PC   | 6 pieces       |
| 7th PC   | 3 pieces       |

Pattern: Basically, +4 piece in modulo. or you can just remember the number 0415263.

- When setting up from freestyles, it's typically to solve so that the remaining space is compressed from left right or right to left, not from bottom to top as this accomodates more pieces orientations


### Setup Phase tips
- With that in mind..
    - Double SZ: Try and enclose S and Z using as little L/J pieces as possible. 
    - Double O: Just stack the two Os (AKA Braindead). With other pieces, build 4x4 box, jaws, etc.
    - double T: Spend one SZT to make a PCO pattern, save the T for the solve. Use the usual setups on the other side (4x4 box, jaws.)
    - Double I: The suggestion is to hold I but.. isn't two Is the same as double O?
    - Double LJ: Try and build the PCO opener.
    - More than one double pieces: Try and freestyle as above. Use the extra as solve. Also please try to spend the S/Z if possible.

### Free style solve Phase tips

- Notes 
    - 1: Boxes are always Column parity neutral. Basically you either need even number of J/Ls, or Odd number of J/Ls + 1x vertical T piece.
    - 2: T pieces are often interchangeable with J/L if they involve a line clear.

- Because you are now freestyling setups.. you now should learn freestyle solves, this would explain why solves on PC training sites tend to be boxes in nx4 size or PCO shapes.
- Because I pieces and 2x O pieces can be used to reduce the box width, we should learn to solve from lower width solutions.

- Your learned setups are still usable in solves! But here are some additional notes you might notice during your solves.
- 2x4 box:
    - Excluding the non-obvious ones:
        - The T piece is adaptable with J/L
        - J/L can be slid in with line clear direction swaps.

- 3x4 box:
    - Your knowledge from 6-3 stacking is still useful!
    - But now you want to augment it with middle single line clears.
        - The less obvious ones are..
            - T + S/Z + J/L
            - 2x T + S/Z. 
                - Place the T piece first according to which part of the S/Z is elevated.
            - SLT: It's like Jigsaw. The T sits on the S.
            - Thanks to line clears, JSJ boxes are entirely possible.
    - 
- 4x4 box:
    - It's easier to look at what you have early in the queue and decide:
        - Symmetrical pieces:
            - LJ 
                - SZ: hold the Lj's hand together. Now twist those SZ in!
                - O: Same solution.
            - 2x (2x4) boxes
                - For example, duble TJ TJ.

        - Non Symmetrical:
            - JLZ
                - T in queue: Create an out of order JSL Box. Except put the S vertically. Now you can slot in the T.
             - O in queue: You can do a direction swap solve.

            - O
                - J + L + T/S/Z: Usually the O sits in the corner during a solve. The JLT will form a shape to support the O, single line clear.
                - STL: The hell is this solution. Drop S first, then floating O.

            - OI
                - Do you have 2x J/L piece?

            - Jigsaw shapes: LSZT
                - There are 2x vertical orientations.
                - One is to put SZ first
                - The other it to put JT first. (The T is floating on the J. funny vertical Z solve.)

            - I:
                - See if you can find any of the lower-width solutions (3x4, 2x4)

            - 2xJ:
                - .. S/Z + T: Try and build the groove, use vertical S/Z
                - 1x T + O: Both J will sit on each other.

            - 1xT:
                - .. ZLS: Hellish solution where you need to vertical T, L on top. Spin vertical S in and twist Z in.

            - 2xT:
                - Remember the column parity rule!
                - If J is upcoming, perpendicular Ts sitting on top of each other.
                - JZ: ***Shachiku train***

    - If you have 2x T piece, you can probably look for symmetrical pieces. (SZ, JL, O + I)
    - If you have 2x T piece, and there are no symmetric piece, then you need to put T pieces 90 degrees.
        - Example: TTIL
    - SZT + L/J has 2x vertically mirrored solutions.
        - Solution 1: The jaws you see in jigsaw.
        - Solution 2: The jaws you see in jigsaw.. flipped.
    - O can be used to flip direction for SZ pieces.
        - Example: JLOS. JL creates a groove for Z piece, but placing an O flips it to S!
    - I pieces can be used to convert a 4x4 solution into 3x4. Your 6-3 stacking technique will pay off here!
    - 2x4 boxes:
        - T works with J, L.
        - Need double O.
    - 3x4 Boxes:
        - The common setup is LZL, JSJ
    - 4x4 boxes:
        - On the flipside, the common setup is LSSL, JZZJ, reverted from 3x4 box.
        - If you get LZZL / JSSJ instead, you can't solve, you will need some other piece, like O.
    - If your leftover pieces are SZTIs... you can't solve a 4x4 box. Make a wider box. If you have more dupe pieces, you can spend them similarly to setup phase.



## Consecutive PC
Assuming we want to get the 10PC badge, we will need to learn consecutive PCs.
- In theory, you get 1x grace DPC if you get a fugly extra SZ on 3rd PC.. i think. Needs confirmation, I haven't gotten 10PC yet!

## 1st PC:
- There are 3 sets of setups you can learn:
    - PCO
    - Jigsaw Loop - Mostly for blitz only. (?)
    - 5-piece setup.

- PCO is often the first setup that is taught to beginners for good reason.
    - It's usable in versus, even if you don't get the PC! The field is nice and flat, and follow ups are straightforward with the well in the middle.
    - It teaches you twists moves.

- Jigsaw loop is a scoring method in Blitz. It usually involves performing a 2nd PC with tub then going for S/Z DPC.

- 5-piece setup: I'm currently learning and studying this. I will write more when I learn about it.

### 5-piece Setup.
- The main document by mL is here: https://docs.google.com/document/d/1aXMd-YK1qM50AgnRfN92eJ_lQvGBLUObUkHgqX7oMbk/edit?tab=t.0
- 5-piece setup is a set of 4 openers then you improvise on to get the PCO.
- These openers cover 92.063% bag possibilities. If you can't use it, use Jigsaw!
- Because these setups use less pieces than PCO (5 vs 6 piece), you have more possibilities, and therefore higher change to PC.. and higher lookahead difficulty.

- Setup 1: Start by focusing on "Jaws and TSZ + IO"
    - These two shapes should be familliar if you've worked with Jigsaw before! It's the SZ+L combination or SZ+T combination. Slap the I and O on the side.

- Setup 2: Centered 5p PCO and top-heavy 5p PCO
    - These are the PCO setups with one piece on top taken away. (without the I too.)

## 2nd PC:
### Save T Odd JL
- Factory 2nd:
    - This is fundamentally a 4x4 box to solve. There is an O slot and T slot that's set up for you already.

## 3rd PC:
- If you get SZ you probably just want to go for DPC.
- If you want to go for consecutive PC... try and build a giant box using your SZ pieces if possible. Basically, get rid of it similar to freestyle.

## 4th-6th PC:
- From this point onwards, PC is usually freestyled (!), see the Freestyle guidelines above.
- You can read four.lol but.. it's chaotic.
- You can also read on queue based setups but.. go learn freestyle first.

## 7th PC:
- Technically also freestyled. But you can use setups if you want.
- You're not going to memorize all those setups, aren't you?
- You have 3 pieces left from the last bag, you know what to do with them at this point if you are freestyling: get rid of it into a box!