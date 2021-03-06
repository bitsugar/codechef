---
languages_supported:
    - NA
title: CIEL8STR
category: NA
old_version: true
problem_code: CIEL8STR
tags:
    - NA
layout: problem
---
###  All submissions for this problem are available. 

Chef Ciel likes 8. Ciel's restaurant has many menus whose prices are multiples of 8. Now, Ciel has some digits written on a wooden board, and she'd like to cut the board to display prices in a new menu. In how many ways can Ciel choose consecutive digits from the board which denote integer multiples of 8?

In this problem, an integer must not have leading zeros. For example, 0, 8, 48, 1000 are integer multiples of 8, but 00, 5, 58, 01000 are not.

### Input

An input contains a string **S**, which denotes digits written on the wooden board.

### Output

Print the number of ways in which Ciel can choose consecutive digits which denote integer multiples of 8.

### Constraints

1 ≤ |**S**| ≤ 1000000 (106), where |**S**| means the length of **S**.
**S** doesn't contain non-digit charactors.

### Sample Input

`5858`### Sample Output

`2`### Output details

Ciel can choose 5, 8, 5, 8, 58, 85, 58, 585, 858 and 5858. Here, only 8 and 8 are multiples of 8.