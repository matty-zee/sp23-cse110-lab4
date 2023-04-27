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
13. a. 32. `'3'` is a string and `2` is an integer so they are concatenated. 
- b. 