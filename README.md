      -- DATA STRUCTURE AND ALGORITHM --

      TITLE: Tower Of Hanoi Game
      DESCRIPTION: This program is intended to show how stack is used
                   to build a game called Tower Of Hanoi.
                   (here I use arrays to implement stacks.)

      HOW DOES IT WORK?
         -program labels the pegs as A, B, and C.
         -By default, peg #A is the STARTING peg and peg #C is the ENDING peg.
         -The goal is to move all the disks off the starting peg and eventually
          get them all onto the ending peg.You may move only one disk at a time
          and you are not allowed to place a larger diameter disk on top of a smaller one.
         -you have to make as few moves as possible. The minimum number of moves required to
          solve a Tower of Hanoi puzzle is 2^n − 1, where n is the number of disks.
          (our program,however, uses 2^n+3 as a maximum move.)
         -The program counts your moves and announces your total when the game ends.
         -In the process you can use the other peg (in fact any of the 3 pegs) for temporary storage.
         -The game ends if and when you manage to move all the disks to the ending peg.

    February 2022
