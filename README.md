# The-prisoner-coin-flipping-puzzle-tidy-simulation-in-R

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
======================

I love 538’s Riddler column, and I’ve enjoyed solving the May 1st puzzle. I’ll quote:

    You are locked in the dungeon of a faraway castle with three fellow prisoners (i.e., there are four prisoners in total), each in a separate cell with no means of communication. But it just so happens that all of you are logicians (of course)….

    Each prisoner will be given a fair coin, which can either be fairly flipped one time or returned to the guards without being flipped. If all flipped coins come up heads, you will all be set free! But if any of the flipped coins comes up tails, or if no one chooses to flip a coin, you will all be doomed to spend the rest of your lives in the castle’s dungeon.

    The only tools you and your fellow prisoners have to aid you are random number generators, which will give each prisoner a random number, uniformly and independently chosen between zero and one.

    What are your chances of being released?

I’ll solve this with tidy simulation in R, in particular using one of my favorite functions, tidyr’s crossing(). In an appendix, I’ll show how to get a closed form solution for .


Wiki to Binomial Distribution: https://en.wikipedia.org/wiki/Binomial_distribution
