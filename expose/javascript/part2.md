1: At line 12, `console.log(i)` will print 3 because `i` is visible after the loop and since the loop 
   iterates until the end of `prices.length`, which is 3, `i` will equal 3 and hence be printed out on line 12.
2: At line 13, `console.log(discountedPrice)` will print out 150 because `discountedPrice` is declared using `var` meaning that it is visible after the loop and the last iteration of the loop is when `i` equals 2. so if you plug in 2, you'll get that `discountedPrice` = 300 * (1 - 0.5) which is 150.
3: At line 14, `console.log(finalPrice)` will print out 150. Since `finalPrice` is declared using `var`, it is still visible after the for loop and the last iteration of the loop is when `i` is equal to 2, indicating that when you plug in 2, you'll get that `finalPrice` = `Math.round(150 * 100)/100` which is just 150.
4: This function will return an array called `discounted` that contains the discounted prices of the original prices that are discounted through the given discount parameter. This array will contain `[50, 100, 150]` and this will be printed because since all of the variables in the function are declared using `var` the values will all update and you'll get the discounted list values.
5: At line 12, `console.log(i)` will print out an error stating that i is not defined because `i` is defined in the the scope of the for loop through the declaration `let`. Since the print statement is outside of that code block, an error will be printed.
6: At line 13, `console.log(discountedPrice)` will print out an error stating that `discountedPrice` is not defined as it is defined within the scope of the for loop through the use of `let`. Since the print statement is outside the scope of the block, an error will be printed. 
7: At line 14, `console.log(finalPrice)` will print out `finalPrice` which was last updated by the for loop at its final iteration of 2. So if we plug in 2, we get that `finalPrice` = `Math.round(150 * 100)/100` which is just 150.
8: This function will return an array called `discounted` that contains the discounted prices of the original prices that are discounted through the given discount parameter. This array will contain `[50, 100, 150]` and this will be printed because since all of the variables in the function are declared using `let` the values will all update accordingly and you'll get the discounted list values.
9: Line 11 will print out an error stating that i is not defined because `i` is defined in the the scope of the for loop through the declaration `let`. Since the print statement is outside of that code block, an error will be printed.
10: Line 12 will print out the `const length` which is equal to the length of the parameter `prices`. Since the length of `prices` is 3, line 12 will print out 3.
11: This function will return an array called `discounted` that contains the discounted prices of the original prices that are discounted through the given discount parameter. This array will contain `[50, 100, 150]` and this will be printed because the `const` discountedPrice is redeclared within the variable in each iteration so it will not cause any errors and arrays are also mutable as long as it is not directly reassigned to another value, so this function will not error in any way. Hence the function will return `discountPrices` which contains all the new discounted price values.
12: Object
A. `student.name`
B. `student['Grad Year']`
C. `student.greeting()`
D. `student['Favorite Teacher'].name`
E. `student.courseLoad[0]`
13: Arithmetic
A. output: `'32'`, if an operand is a string and the binary `+` is used, the other is converted to a string as well which is why we get `'32'`.
B. output: `1`, if an operand is a string and any other operator other than `+` is used, the strings are converted to numbers which is why we get `1`.
C. output: `3`, if `null` is performed in a numeric conversion, it takes on the value `0` so `3 + null` would give you 3
D. output: `'3null'` if an operand is a string and the binary `+` is used, the other is converted to a string as well which is why we get `'3null'`
E. output: `4`, if `true` is performed in a numeric conversion, it takes on the value `1` so `3 + 1` would give you 4
F. output: `0`, if `false` and `null` are performed in a numeric conversion, `false` and `null` both take on the value 0 so 0 + 0 is 0.
G. output: `'3undefined'`, if an operand is a string and the binary `+` is used, the other is converted to a string as well which is why we get `'3undefined'`. 
H. output: `NaN`, if `undefined` is performed in a numeric conversion, it takes on the value `NaN` so `3 + undefined` would give you `NaN`
14: Comparison
A. output: `true`, When comparing values of different types, the values are converted to numbers and 2 > 1 so we get `true`
B. output: `false`, When comparing two strings, we evaluate them letter-by-letter lexographically and so when we compare, we get `2 < 1` which is `false`.  
C. output: `true`, When using `==`, we have a looser comparison with a type conversion so `2 =='2'` will evaluate to `true`.
D. output: `false`, When using `===`, we have a stricter comparison without type conversion so `2 ==='2'` will evaluate to `false`.
E. output: `false`, When comparing values of different types, the values are converted to numbers so `true` becomes 1 and 1 == 2 so we get `false` 
F. output: `true`, When comparing a value that uses the `Boolean()` conversion, it will evaluate to a boolean value and since the value of `Boolean(2)` evaluates to true, `true === true` is `true`.
15: The difference between `==` and `===` is that `===` denotes a stricter comparison without type conversion whereas `==` is a looser type comparison with type conversion. So when using `===` if the two operands are different types, the value `false` will be immeadiately returned without any type conversion. This is useful for when wanting to differentiate between values such as `1` and `true` (number v.s. Boolean)
16: see file `part2-question16.js` 
17: The result will be an array that is `[2,4,6]`. The function `modifyArray` takes in two parameters: an array and a callback function that call the function we want to use in our program at a later time. We then iterate through the new array and push in values of the given array that will be modified using our callback function. So since we call on the `doSomething` function, each value in the array that we iterate over is multiplied by 2 and is then pushed into the `newArr`. This will then return the `newArr` which holds values modified by our callback function which is `[2,4,6]`
18: see part2-question18.js
19: The output of this code is: 
1
4
3
2