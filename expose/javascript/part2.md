# Part 2

## Question 1
The code will return `3`. At line 12 `console.log(i)` will print the value of `i` after the loop has completed. `i` is declared with `var`, therefore there would not be any errors. Given the prices array `[100, 200, 300]` passed to the `discountPrices` function, `i` will be `3` when the loop terminates.

## Question 2
The code will print `150`. Given the prices and the discount of `0.5` the loop will calculate it by `300 * (1-0.5)`. The variable `discountedPrice` is declared with `var` inside the loop and we know that `var` doesn’t have block scope therefore it won’t cause an error.

## Question 3
The code will print `150`. `console.log(finalPrice)` will print the value of `finalPrice` to the console which is `150`.

## Question 4
The `discountPrices` function is called with an array `[100, 200, 300]` and a discount of `0.5` (50%). Therefore, the function will return `[50, 100, 150]`.

## Question 5
Code will cause an error. This error occurs because of the block scoping rules that `let` has. The variable `i` only exists within the `for` loop block.

## Question 6
At line 13 code will cause an error because `discountedPrice` is not accessible outside the loop. Variables declared with `let` are block-scoped, which means they are only accessible within the block where `let` was used. Since `discountedPrice` is declared within the `for` loop, it cannot be accessed outside of it.

## Question 7
The code will print `150`. The `finalPrice` will hold the discounted price of the last item in the array, which is `300` then the discount calculation would be `300 * (1 - 0.5)`, which equals `150`. The `Math.round` method will not change the value since `150` does not have any decimal places to round off. Therefore, the `console.log(finalPrice)` will output `150` to the console.

## Question 8
The function will return the array `[50, 100, 150]`. There is no error in this code and inside the loop we’ll have the following calculations: `100 * (1 - 0.5) = 50`; `200* (1 - 0.5) = 100`; `300 * (1 - 0.5) = 150`.

## Question 9
The code will cause an error because `i` is not accessible outside the `for` loop and trying to log it to the console after the loop has completed causes an error. Variables declared with `let` are block-scoped and thus the error occurs.

## Question 10
The code will print `3` because `length` is equal to `prices.length`. `prices` is an array passed to the `discountPrices` function and we know that `length` will be the number of elements in the `prices` array. Given the call `discountPrices([100, 200, 300], 0.5);` length will be `3`, and that's what will be logged to the console.

## Question 11
The function will return the following array: `[50, 100, 150]`. There are no errors in this code because each variable is properly scoped and the return statement is correctly returning the discounted array, which is the outcome of this function.
## Question 12
- A. `student.name;`
- B. `student['Grad Year'];`
- C. `student.greeting();`
- D. `student['Favorite Teacher'].name;`
- E. `student.courseLoad[0];`

## Question 13
- A. `'32'` (2 was converted in string)
- B. `1` (converts the string 3 to a number)
- C. `3` (null is considered as 0 in numeric operations)
- D. `'3null'` (+ will convert null to string)
- E. `4` (true is converted to 1)
- F. `0` (both false and null are 0 in numeric operations)
- G. `'3undefined'` (undefined is converted in to string)
- H. `NaN` (Not-a-Number because undefined cannot be converted to an integer)

## Question 14
- A. `true` (string is converted to a number)
- B. `false` ('2' is considered greater than '1')
- C. `true` (`==` converts both operands to the same type, thus converting '2' to a number)
- D. `false` (`===` doesn't perform type conversion, types are different thus false)
- E. `false` ('true' is converted to 1 before the comparison)
- F. `true` (any non-zero number is true)

## Question 15
- The `==` operator or the "loose equality" operator converts the operands to the same type in JS before making the comparison.
- The `===` operator is known as the "strict equality" operator and doesn't perform any type conversion. If the operands are of different types, the comparison will be false. Only if both the type and the value are the same, it will return true.

## Question 17
If we call `modifyArray([1,2,3], doSomething)` the result will be `[2, 4, 6]`. This is because `modifyArray` takes each element of the input array `[1, 2, 3]` and applies `doSomething` to it. `doSomething` function multiplies each number by `2`.

## Question 19
1
4
3
2