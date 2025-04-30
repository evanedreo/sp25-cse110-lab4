1. 3
2. 100
3. 150
4. [50, 100, 150]
5. error (ReferenceError: i is not defined),let is block scoped, so i only exists inside the loop block. While line 12 is outside the loop block, therefore, accessing i causes a ReferenceError.
6. error (ReferenceError: discountedPrice is not defined). discountedPrice is declared using let (block scoped), therefore, it wont be able to be accessed outside the loop and line 13 is outside that block.
7. 150
8. [50, 100, 150]
9. error (ReferenceError: i is not defined)let is block scoped, so i only exists inside the loop block. While line 11 is outside the loop block, therefore, accessing i causes a ReferenceError.
10. 3
11. [50, 100, 150]
12. A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]
13. A. '3' + 2 → '32'
The + operator with a string makes everything a string, so '3' and 2 combine into '32'
B. '3' - 2 → 1
The - operator turns both values into numbers, so '3' becomes 3, and 3 - 2 = 1.
C. 3 + null → 3
null is treated as 0 in numeric operations, so this becomes 3 + 0 = 3.
D. '3' + null → '3null'
The + operator with a string turns everything into a string, so it combines '3' and 'null'.
E. true + 3 → 4
true is converted to 1, so the result is 1 + 3 = 4.
F. false + null → 0
false becomes 0, null becomes 0, so 0 + 0 = 0.
G. '3' + undefined → '3undefined'
String plus undefined becomes one long string: '3' + 'undefined'.
H. '3' - undefined → NaN
'3' turns into 3, but undefined can’t become a number, so the result is Not a Number (NaN).
14. A. '2' > 1 → true
The string '2' is turned into the number 2, and 2 > 1 is true.
B. '2' < '12' → false
Both are strings, so it compares alphabetically. Since '2' comes after '1', it’s false.
C. 2 == '2' → true
The double equals (==) allows type conversion, so '2' becomes 2, and 2 == 2 is true.
D. 2 === '2' → false
Triple equals (===) checks both type and value — 2 (number) is not equal to '2' (string).
E. true == 2 → false
true becomes 1, and 1 == 2 is false.
F. true === Boolean(2) → true
Boolean(2) returns true because 2 is truthy, and both sides are exactly true.
15. - == checks for equality of value, but allows type conversion 
- === checks for equality of both value and type, so no type conversion happens.
17. [2, 4, 6]
Explanation:
We are passing the doSomething function as a callback into modifyArray. Inside the function modifyArray, each element of the array [1, 2, 3] is passed to doSomething, which multiplies the number by Step by step:
doSomething(1) → 2
doSomething(2) → 4
doSomething(3) → 6
These values are stored in a new array, which is returned:
[2, 4, 6]
19. 1  
4  
3  
2
