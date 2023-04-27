1. 3 is printed. The for loop increments `i`  until it reaches 3 as `i < prices.length` is no longer true. 
2. 150 is printed. The last value that `discountedPrice` takes is the last value of the input list multiplied by 1 - discount.
3. 150 is printed. The last value that `finalPrice` takes is the last value of the input list multiplied by 1 - discount rounded to the nearest whole number.
4. [50,100,150]. This function iterates through an input list and applies the input discount to every value within it. 
5. An error occurs. Since it defined with `let`, `i` has block scope and does not exist outside the for-loop.
6. An error occurs.  Since it defined with `let`, `discountedPrice` has block scope and does not exist outside the for-loop.
7. 150 is printed. Since is it defined with `let`, `finalPrice` has block scope which extends to the end of the `discountPrices` function. 
8. 