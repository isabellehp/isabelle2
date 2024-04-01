---
toc: false
comments: True
layout: post
title: CB MCQ Practice Corrections
description: Corrections for College Board quiz (2021 Practice MCQ)
type: tangibles
courses: { compsci: {week: 25} }
---

## Corrections
**Question 55**: Move element from end of list to beginning

A code segment is intended to transform the list utensils so that the last element of the list is moved to the beginning of the list.

For example, if utensils initially contains  ["fork", "spoon", "tongs", "spatula", "whisk"], it should contain ["whisk", "fork", "spoon", "tongs", "spatula"] after executing the code segment.

Which of the following code segments transforms the list as intended?

- My answer: A
   
    len = LENGTH(utensils)
    temp = utensils[len]
    REMOVE(utensils, len)
    APPEND(utensils, temp)
- Correct answer: C
    
    len = LENGTH(utensils)
    temp = utensils[len]
    REMOVE(utensils, len)
    INSERT(utensils, 1, temp)
- Explanation: The answer I chose is incorrect because it results in the same list as the original. The difference between A and C is that A appends temp to the end of the list whereas C inserts temp as the first element of the list.

**Question 68**: Error in remove duplicates code segment

The following code segment is intended to remove all duplicate elements in the list myList. The procedure does not work as intended.

j 
 LENGTH(myList)

REPEAT UNTIL(j = 1)

{

IF(myList[j] = myList[j - 1])

{

REMOVE(myList, j)

}

j 
 j - 1

}

For which of the following contents of myList will the procedure NOT produce the intended results?

Select two answers.

- My answer:
    - A: [10, 10, 20, 20, 10, 10]
    - B: [30, 30, 30, 10, 20, 20]
- Correct answer:
    - A: [10, 10, 20, 20, 10, 10]
    - C: [30, 50, 40, 10, 20, 40]
- Explanation: B is incorrect because the code will remove the sixth element (20), the third element (30), and the second element (30). This results in the list [30, 10, 20], which contains no duplicates, as intended. C is correct because the code will remove each element that is equal in value to the element immediately preceding it. This list does not contain any pairs of adjacent elements that are equal in value, so no elements will be removed even though the value 40 appears twice in the list.

**Question 70**: Remove nth character from oldStr

The following procedures are available for string manipulation.

| Procedure Call | Explanation |
| --- | --- |
| substring(str, start, end) | Returns a substring of consecutive characters of str starting with the character at position start and ending with the character at position end. The first character of str is considered position 1. For example, substring("delivery", 3, 6) returns "live". |
| concat(str1, str2) | Returns a single string consisting of str1 followed by str2. For example, concat("key", "board") returns "keyboard". |
| len(str) | Returns the number of characters in str. For example, len("key") returns 3. |

A programmer wants to create a new string by removing the character in position n of the string oldStr. For example, if oldStr is "best" and n is 3, then the new string should be "bet". Assume that 1 < n < len(oldStr).

Which of the following code segments can be used to create the desired new string and store it in newStr ?

Select two answers.

- My answer: 
    - A: left = substring(oldStr, 1, n - 1) right = substring(oldStr, n + 1, len(oldStr)) newStr = concat(left, right)
    - B: left = substring(oldStr, 1, n + 1) right = substring(oldStr, n + 1, len(oldStr)) newStr = concat(left, right)
- Correct answer: 
    - A: left = substring(oldStr, 1, n - 1) right = substring(oldStr, n + 1, len(oldStr)) newStr = concat(left, right)
    - C: newStr = substring(oldStr, 1, n - 1) new Str = concat(newStr, substring(oldStr, n + 1, len(oldStr)))
- Explanation: B is incorrect because the code makes left = "best", right = 
est", resulting in "bestest" not "bet". C is correct because it creates variable newStr = "be" and results in "bet" as wanted.
