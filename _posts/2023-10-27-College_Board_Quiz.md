---
toc: true
comments: true
layout: post
title: College Board Quiz Notes
description: Notes and corrections for College Board quiz (2018 Practice MCQ)
type: tangibles
courses: { compsci: {week: 11} }
---

## Quiz Notes
- Citizen science: experiment/research completed with participation from general public
- Boolean value: true or false
- Internet Engineering Task Force (IETF):
    - Main goal: to make the internet work better
    - Roles: devloping standards and protocols for internet communication
- Iterative vs. incremental: similar but its like continuous work vs progress through small sections
    - Benefit: helps identify errors as code is added
    - Agile method uses both
- order in which variables are defined/changed and displayed matter (it affects what is displayed)
- Every device connected to the internet has an IP (Internect protocol) address
- Digital divide: gap between people who have access to internet and people who don't
    - Ways to reduce: providing free education/training on how to use computing devices, free/low cost computing devices, networks/infrastructure to people in remote areas
- Go back to question 23 after submission (unsure of my answer)
- Byte pair: data encoding technique; looks for pairs of characters that appear in the string more than once and replaces each instance of that pair with a corresponding character that does not appear in the string; saves a list containing the mapping of character pairs to their corresponding replacement characters
    - Example of a lossless transformation (string can be restored to original version)
- Review binary
- Benefits of open standards and protocols for internet communication:
    - allow different manufacturers/developers to build hard/software that can communicate with hard/software on the rest of the network
- Overflow error: when the data type used to store data was not large enough to hold the data
    - Ex. if data type is 1 byte and stored data is greater than 256
- NAND gate: type of logic gate; produces "false" output when both inputs are "true"
- Public key cryptography: method of encrypting/signing data
    - Public key is available for anyone to use
    - data encrypted with public key can only be decrypted with private key
- Symmetric encryption: only one key is used to encrypt and decrypt data
- Concat: concatenate function; used to join 2 or more text strings into one string; returns a single string consisting of str1 followed by str2
    - Ex. Concat("key", "board") returns "keyboard"
- Substring: function that extracts a substring stargin from a position in an input string with a given length; returns a substring of consecutive characters from str, starting with the character at position stat and containing length characters
    - Ex. Substring("delivery", 3, 4) return "live"
- Crowdsourcing: practice of obtaining info or input into a task/project by enlisting the services of a large number of people
- Abstraction: process of removing characteristics from something to reduce it so a set of essential elements
- Cloud computing: delivery of computing services

## Corrections
Score: 64/66

Question 30: Video-streaming service by genre (approximate the amount of time it takes the program to execute)
- Skill 1.D: Evaluate solution options 
- 3.17  daily videos
- My answer: 1 hour
- Correct answer: 5 hours
- The answer I chose is incorrect because it assumes that the Analysis procedure is only called once. The procedure is actually called for each genre in the list (comedy, drama, mystery, and romance) meaning it runs 4 times (1 hour per). Plus any other actions in the program, which could add an hour, resulting in the answer: 5 hours.

Question 31: Comparing loop algorithms with robots
- Skill 1.D: Evaluate solution options 
- 3.9 daily videos
- My answer was incorrect because Program I also moves the robot correctly to the gray square because it is repeated 4 times until the robot gets to the finish box. I think when I was doing this problem, I mixed up the commands and wasn't able to reach the goal, which made me get the wrong answer.