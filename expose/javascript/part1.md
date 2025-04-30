1. values added:  20
2. final result:  20
3. var ignores block boundaries (like if, for, while) and moves the variable to the top of the function. Therefore, this might cause bugs because the variable is still accessible outside the block where we declared it.
4. values added:  20
5. error, we used let to declare result. moreover, it only available inside of the if block. Where line 13 is outside of if block. Therefore, it causes an error
- ReferenceError: result is not defined.
6. error, result is initially declared as a const on line 5. Moreover, in line 6 we try to reassign result with result = num1 + num2;. However, const variables cannot be reassigned after their initial assignment.
- This will cause a TypeError, and the code stops running before reaching line 9.
7. error. Because the error occurs on line 6, the remaining of the code doesnt run and we will never reach line 13. Moreover, if even we are able to reach it, result is declared inside the if block and wouldn’t be accessible in line 13 and it would throw a ReferenceError.


