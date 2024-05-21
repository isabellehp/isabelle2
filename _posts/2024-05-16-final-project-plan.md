---
comments: true
layout: post
title: Final Project Plan
description: Plan for Isabelle and Chrissie's final project
courses: {'compsci': {'week': 34}}
type: tangibles
---

### Overview
Because our group spends a lot of time playing NYT games like the mini crossword together, we want to make a project related to that so it caters to our enjoyment. The mini crossword project will include a crossword grid, word bank, hints, user input, etc.

### Mini Crossword Puzzle

#### Loops (Algorithmic): 
Show specific example of building a List using List Comprehension. Show examples of processing a list using conventional and for each methods.
  - Use loops to iterate over rows and columns of the crossword grid
  - List comprehension to initialize and populate the crossword grid with blank squares and black squares.

#### Sorting / Searching (Algorithmic)
Show examples of sorting and searching using the backend of your project.. FYI, SQLAlchemy allows filtered selections and sorting. Additionally, you have sorting options discussed in tech talk.
  - Create a word bank/dictionary to store valid words for the crossword
  - Alphabetically sort the word bank for efficiency
  - Verify if a word entered by the user is valid?

#### Big(O)
Illustrate Space and Time complexity used in your Sorting / Searching algorithm.
- Time Complexity:
  - Analyze the time complexity of the word lookup algorithm, considering the size of the word bank and the search method used
- Space Complexity:
  - Analyze the space complexity of storing the crossword grid and word bank in memory.

#### 2D Iteration
Show examples of code that use 2D iteration. This can be anywhere in your code where you are using rows and columns.
  - Use 2D iteration to interact with the crossword grid.
  - Iterate over rows and columns to display the crossword and handle user input for filling in words.

#### Deployment (Full Stack)
A complete deployment illustration multiple people using and updating your Full Stack Web Application simultaneously.
  - Records of time it took to complete crosswords