# AI Bootcamp
Name: Varshitha
Date: 6th sep 2026
Day 1:

1. Coding Problem:
   Approach:
   I first counted how many times each character occured in the string using a dictionary. I skipped spaces. After getting all the counts, I checked the string again from the beginning. If a character has a count of 1, I printed it and stopped because I need the first non-repeating character. If none of the characters has a count of 1, I printed that no non-repeating character was found.

## the code is available in "Day_1_Python.ipynb"
## test inputs
## Test Input 1:
programming

## Test Input 2:
aabbcdd

## Test Input 3:
aabbcc

## Outputs
## Output 1:
Enter a string: programming
First non-repeating character: p

**Output 2:**
Enter a string: aabbcdd
First non-repeating character: c

**Output 3:**
Enter a string: aabbcc
No non-repeating character found

2. Concept Question
| Data Structure | Ordered? | Duplicates? | Mutable? | Example                       |
| -------------- | -------- | ----------- | -------- | ----------------------------- |
| **List**       | Yes ✅    | Yes ✅       | Yes ✅    | `["Ravi", "Anil", "Ravi"]`    |
| **Tuple**      | Yes ✅    | Yes ✅       | No ❌     | `("Ravi", "Anil", "Ravi")`    |
| **Set**        | No ❌     | No ❌        | Yes ✅    | `{"Ravi", "Anil"}`            |
| **Dictionary** | Yes* ✅   | Keys: No ❌  | Yes ✅    | `{"name": "Ravi", "age": 20}` |
   
3. Debugging challenge
## what was the issue?
The issue was that the else was inside the loop, so it printed "Student not found" for every student who was not Kiran. 
## how did i fix it?
I fixed it by checking whether Kiran exists in the list using in. I also tried a loop without using range(len(students)) by directly taking each student from the list.

4. What I learnt today
 Today, I learned how to use dictionaries to count the occurrence of characters in a string and find the first non-repeating character. I also learned how to take input from the user and work with strings using loops. I learned the basic characteristics and differences between lists, tuples, sets, and dictionaries. In the debugging question, I learned that instead of going through the indexes using range(len()), I can directly go through the elements in a list and also use in to check if a particular value is present in the list.   

5. What I found difficult?
  I found the third question a little difficult because I initially wasn't sure how to fix the logic. I had to understand that instead of checking each student separately, I could directly check whether Kiran is present in the list and then print the appropriate result. 


