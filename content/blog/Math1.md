---
external: false
draft: false
title: "Elegant Maths: Three Selected Puzzles"
description: "Maths doesn't have to be calculus and quadratics!"
date: 2023-10-05
---
 
Mathematics feels like a lost love to me.
 
I miss the days of spending hours upon hours on a difficult assignment in my undergraduate days. Nothing could beat the satisfaction of cracking and writing up a proof and submitting it just in the nick of time.
 
With all its complexities and technicalities, most of which have been long lost to me, the beauty in mathematics lies in its deceptive simplicity.
 
Like a clear melody piercing through a cacophonous orchestra, solutions may reveal themselves in elementary but elegant ways, relying solely on logic.
 
I have curated three such puzzles today - hopefully they bring a smile to your face too.
 
 
## The Mutilated Chessboard

The **mutilated chessboard problem** has a rich history when it comes to the study of logical reasoning. Philosopher Max Black first proposed the problem in his book _'Critical Thinking'_ (1946), designed as a test case for creative insight.

![Chess1](/images/puzzle1/mutilatedboard.png)
 
The problem is as follows:
 
> Suppose a standard 8×8 chessboard has two diagonally opposite corners removed, leaving 62 squares. Is it possible to place 31 dominoes of size 2×1 so as to cover all of these squares?
 
I encourage you to spend at least 5 minutes on this puzzle. It is certainly very satisfying if you can uncover the simple logic behind it.
 
### Solution
 
It is very natural, given the question has not made it clear whether the problem is solvable or not, to attempt to find a _single feasible tiling._
 
You may have deduced after some attempts (or perhaps immediately if you are a whiz), that the puzzle is impossible to complete.
 
A domino that covers two squares will always cover one red and one black square. But any pair of opposite squares will always have the same colour on a chessboard (red in the diagram above), and thus if they are removed, you will be left with too many black squares!
 
This proves it impossible to tile the dominoes to cover every square, without having to picture a single arrangement of dominoes.
 
This problem for me provides some insight into the nature of mathematical proofs - to prove something **possible** requires the discovery of one satisfactory arrangement. Yet to prove something **impossible** requires proving the non-feasibility of every single arrangement, or to demonstrate some fundamental impossibility of the set-up.
 
 
## The Odd Pawns
 
We return to the chessboard for the next puzzle.

![Chess2](/images/puzzle1/puzzle1.png)
 
There is a square chessboard with an odd number of squares on each side (3x3, 5x5...).
 
Each square has a pawn on it initially. All the pawns are then removed.
 
> Is it possible to place each pawn on the board again so that it’s put on a neighbouring square to the one previously occupied by it (neighbouring means sharing a side)?
 
This time, I will tell you that it is in fact **impossible**. How do you approach it?
 
### Solution
 
This time you may have set out to query the fundamental basis of the puzzle rather than testing out every possible configuration.
 
The solution once again uses simple logic. 

Chessboards are made of **alternating coloured squares**. For each pawn to now be on a neighbouring square, would mean it has switched colours.
 
Since the chessboard has an odd number of squares on each side, the total number of squares is also odd (the product of two odd numbers is odd).
 
As such, there will always be an **unequal number of squares** of either colour.

Hence not every pawn will be able to swap colours, and thus cannot be repositioned on a neighbouring square.
 

## Ramen Chemistry
 
The final puzzle has a bit more meat in it, or perhaps I should say broth…
 
I had actually thought of this problem independently over a couple of bowls of ramen with my lovely girlfriend. 

Of course, given that we have been around for hundreds of thousands of years, this puzzle of course has existed as early as 1896, and is referred to as the _'Water and Wine'_ mixing problem
 
As an aside, you may be surprised to find out there are a significant number of mathematical theorems and problems named after common food items and meals.
 
**A smorgasbord of examples:**
- ["The ham sandwich theorem"](https://en.wikipedia.org/wiki/Ham_sandwich_theorem)
- ["Hamburger moment problem"](https://en.wikipedia.org/wiki/Hamburger_moment_problem)
- ["No free lunch theorem"](https://en.wikipedia.org/wiki/No_free_lunch_theorem)
- ["Pizza theorem"](https://en.wikipedia.org/wiki/Pizza_theorem)
- ["Potato paradox"](https://en.wikipedia.org/wiki/Potato_paradox)
 
For those whose highschool trauma have lead to them finding maths somewhat unpalatable - I find it humorous to picture a gaggle of maths professors gathered around the lunch table during their tea break, contemplating the most efficient way to slice a cheesecake (incidentally this problem exists and is known as the ["_'Fair cake-cutting' problem_](https://en.wikipedia.org/wiki/Fair_cake-cutting)).

![ramen](/images/puzzle1/ramen.jpg)

Back to the question at hand - I had ordered a particularly spicy bowl of ramen and she had opted for a milder soup base.
 
The first bowl was too spicy for her to consume straight, so I transferred one spoonful of my broth to her bowl to share the love. Wanting to try some of the yuzu truffle soup, I then moved the same quantity of her broth (now containing one of my spicy spoonfuls), back into the original bowl.
 
Never missing an opportunity to be an obnoxious dinner companion, I proposed the following question: 

> After this series of soup transfers, which bowl of soup is purer - i.e. contains the greater concentration of 'original soup'?
### Solution
 
When attempting to solve this problem, the budding chemists amongst you may have assigned some numerical quantities for volume and concentration to the soups. 

You may have then applied some stoichiometric calculations to determine the moles of soup exchanged with each soup spoon transfer.
 
While this is a very rational approach, as per the theme of this article, there is a **more elegant** answer!
 
An barrier to the solution is that volume and concentration are an inherently challenging unit to work with.
 
Let's simplify the problem to a bowl of 100 red marbles (bowl 1) and 100 white marbles (bowl 2).
 
A few assumptions have been made here:
1. Each bowl of soup is made up of 1 "type" of molecule - we have represented these with the red marbles and white marbles. This is not necessarily detached from real life; all the components of the broth can be arbitrarily subdivided to make this true.
2. The volume occupied by one molecule of soup A is equivalent to that of soup B
3. The number of molecules in each bowl is equivalent (this is implicitly evident as a result of the first two assumptions).
 

**An example**
 
|   **Soup 1**  | **Soup 2**   | 
| --------- | -------- |
| **100 Red**   | **100 White**|
| Move 10 Red ---> |        |
| **90 Red** | **100 White 10 Red** |
| | <--- Move mixture (e.g. 9 White 1 Red) |
| **91 Red 9 White** | **91 White 9 Red** |
| Move mixture (8 Red 2 White) ---> |        |
| **83 Red 7 White** | **93 White 17 Red** |
| | <--- Move mixture (7 White 3 Red) |
| **86 Red 14 White** | **86 White 14 Red** |

 
 
You might have noticed something after every two transfers - the ratios appear to be equal! You can repeat this as many times as you want to test this finding. 
 
On further exploration, the reasoning behind this equalisation becomes evident. If X number of red marbles have been moved to the other bowl, in order to maintain the same total number of marbles, X white marbles must have been displaced to the first bowl. This is independent of how many marbles are transferred with each spoonful.
 
This simple equilibrium means that the concentration of the bowls **must always be equal** after an even number of moves!
 
## Conclusion

Hopefully these puzzles have demonstrated some of the artistry in mathematical puzzles, there is a certain beauty in that they require nothing but elementary reasoning, yet are difficult enough to stump the most seasoned logicians.
 
**I hope you have enjoyed!**
 


