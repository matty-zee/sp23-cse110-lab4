1. 3 is printed. The for loop increments `i`  until it reaches 3 as `i < prices.length` is no longer true. 
2. 150 is printed. The last value that `discountedPrice` takes is the last value of the input list multiplied by 1 - discount.
3. 150 is printed. The last value that `finalPrice` takes is the last value of the input list multiplied by 1 - discount rounded to the nearest whole number.
4. [50,100,150]. This function iterates through an input list and applies the input discount to every value and rounds it to the nearest whole number. 
5. An error occurs. Since it defined with `let`, `i` has block scope and does not exist outside the for-loop.
6. An error occurs.  Since it defined with `let`, `discountedPrice` has block scope and does not exist outside the for-loop.
7. 150 is printed. Since is it defined with `let`, `finalPrice` has block scope which extends to the end of the `discountPrices` function. 
8. [50, 100, 150] is returned. This function iterates through an input list and applies the input discount to every value and rounds it to the nearest whole number. 
9. An error occurs. Since it defined with `let`, `i` has block scope and does not exist outside the for-loop.
10. 3 is printed. The length of `prices` is 3. 
11. [50, 100, 150] is returned. This function iterates through an input list and applies the input discount to every value within it but does not round to the nearest whole number. The `const` keyword only prevents a variable from being reassigned so modifying the assigned array is ok. 
12. a. `student.name` 
-  b. `student['Grad Year']`
-  c. `student.greeting()`
-  d. `student['Favorite Teacher'].name`
-  e. `student.courseLoad[0]`
13. a. '32'. `'3'` is a string and `2` is an integer so they are concatenated. 
- b. 1. `-` is iterpreted as an arithmetic operation.
- c. 3. `null`'s numerical value is 0.
- d. '3null'. Since `'3'` is a string, `+` is concatenation.
- e. 4. `true`'s numerial value is 1. 
- f. 0. `false` and `null`'s numerical values are both 0.
- g. `3undefined`. Since `'3'` is a string, `+` is concatenation.
- h. NaN. The result is undefined because `-` is interpreted as an arithmetic operation and subtracting undefined results in an undefined value. 
14. a. True. When comparing strings to numbers, strings are parsed as integers. If the string isn't a number, its integer value is NaN.
- b. False. 2 is compare to the numerical value of the first character of `'12'`, which is 1. 
- c. True. '2' is converted to a number. 
- d. False. `===` is strict comparison so it checks the value and type to see if LHS and RHS are the same. 
- e. False. The numerical value of `true` is 1. 
- f. True. LHS and RHS are both boolean and parsing any number greater than 0 as a boolean returns `true`. 
15. `==` only checks if values are the same after type converting when applicable. `===` does not do any type conversions and checks both sides values and types are the same. 
