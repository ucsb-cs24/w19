---
num: pa02-checkpoint
ready: false
desc: "Linked-list implementation of a card game"
assigned: 2019-01-25 09:00:00.00-8
due: 2019-02-01 23:59:00.00-8
---

<div markdown="1">

# Introduction

* The first thing you need to do for the checkpoint is read the description for the project here: [https://ucsb-cs24.github.io/w19/pa/pa02/](https://ucsb-cs24.github.io/w19/pa/pa02). Though you don't need to have all of this implemented by the checkpoint, it is essential that you have a good idea where this project is going so that you are able to make good design decisions. 

# Instructions

For the checkpoint, you must implement your linked list to store card hands (though it does not need to have the full game functionality yet). You must also have an outline of how you plan to complete the rest of the project in the form of a main function (potentially just psuedo-code) and function stubs for your card class (more details on this later).

## Linked List Implementation

This portion requires you to define and implement the basics of your card class. You need to complete the portion of your code required to be able to read each player's cards from a file, store them in linked lists, and print each players hand. 

## Example

Contents of `alice_cards.txt`:

```
h 3
s 2
c a
c 3
h 9
s a
```

Contents of `bob_cards.txt`:

```
c 2
s a
d j
h 9
c 3
```

Correct output after running `make && ./game alice_cards.txt bob_cards.txt`:

```
Alice's cards:
h 3
s 2
c a
c 3
h 9
s a

Bob's cards:
c 2
s a
d j
h 9
c 3
```

## Design Approach

* The goal of this portion is to get you thinking about how you plan on completing the rest of the assignment before jumping into coding it as well as to allow us to give you some initial feedback on your approach. Make sure you've read the entire project description carefully and spend some time thinking about what functionality your card list needs to have as well as how you will leverage this to code the game. 

* Create stubs for class functions you will need (you must ensure that your `cards.h` and `cards.cpp` files still compile so your linked list implementation will work). 

* Create a `main2.cpp` which details how you will use your card class to run the game. This can either be in code which makes calls to the stubs you've defined or psuedo-code which details how you will use these functions once they are fully defined. This `main2.cpp` is the start of your main for the final turn in for this project. 

* Your main focus when completing this section should be to clarify your thoughts on your code structure for this project and communicate that with your mentor through the stubs you declare in your card class and your `main2.cpp'

# Submission instructions 

You must submit exactly five files with the names: Makefile, main.cpp, cards.cpp, cards.h, main2.cpp

Submit these files to PA02-Checkpoint on gradescope. You should score 100% if you have completed the linked list implementation portion of this project. The rest of the points for this checkpoint will be given by your mentor who will check that you have completed the design approach portion of this project and your code style. 


Created by Jack Alexander, Jinjin Shao, Sierra Schwellenbach, and Diba Mirza
