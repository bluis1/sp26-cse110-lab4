# Part 2

## Question 1
Line 12 prints `3`. This is because `i` was declared with `var` inside the `for` loop, so it is function scoped. After the loop finishes, `i` has increased to 3, so it can still be accessed and printed outside the loop.

## Question 2
Line 13 prints `150`. This is because `discountedPrice` was declared with `var` inside the `for` loop, so it is function scoped and can still be accessed after the loop. On the last loop, the price is `300`, so `300 * (1 - 0.5)` becomes `150`.

## Question 3
Line 14 prints `150` because `finalPrice` was declared with `var` at the function level, so it can be accessed anywhere inside the function. During the last loop, `finalPrice` becomes `150`, so that final value is printed.

## Question 4
The function returns `[50, 100, 150]`. Each price is multiplied by `(1 - 0.5)`, so each original price gets cut in half. Those final prices are pushed into the `discounted` array, and then the array is returned.

## Question 5
Line 12 causes an error because `i` was declared with `let` inside the `for` loop. `let` is block scoped, so `i` only exists inside the loop and cannt be accessed after the loop ends.

## Question 6
Line 13 causes an error because `discountedPrice` was declared with `let` inside the `for` loop. Since `let` is block scoped, `discountedPrice` only exists inside the loop and can't be accessed after the loop ends.

## Question 7
Line 14 prints `150`. This is because `finalPrice` was declared with `let` outside the `for` loop but still inside the function. Since line 14 is in the same function scope, it can access `finalPrice`. After the last loop, `finalPrice` is `150`.

## Question 8
The function returns `[50, 100, 150]`. The `let` declarations do not cause an error here because nothing is accessed outside of its allowed scope. Each price is discounted by 50%, pushed into the `discounted` array, and then returned.

## Question 9
Line 11 causes an error because `i` was declared with `let` inside the `for` loop. Since `let` is block scoped, `i` only exists inside the loop and cannot be accessed after the loop ends.

## Question 10
Line 12 prints `3`. This is because `length` was declared with `const` near the top of the function, outside the `for` loop. Its value is `prices.length`, and the array has 3 items: `[100, 200, 300]`.

## Question 11
The function returns `[50, 100, 150]`. The `discounted` array is declared with `const`, but that only means the variable cannot be reassigned to a different array. The code can still use `.push()` to add values into the array.

## Question 12
A. student.name

B. student['Grad Year']

C. student.greeting()

D. student['Favorite Teacher'].name

E. student.courseLoad[0]

## Question 13
A. outputs `32` because `+` with a string does concatenation.

B. outputs `1` because `-` converts `3` into the number `3`.

C. outputs `3` because `null` becomes `0`.

D. outputs `"3null"` because `+` with a string does concatenation.

E. outputs `4` because `true` becomes `1`.

F. outputs `0` because both `false` and `null` become `0`

G. outputs `"3undefined"` because `undefined` becomes a string.

H. outputs `NaN` because `undefined` becomes `NaN`

## Question 14


## Question 15


## Question 16


## Question 17


## Question 18


## Question 19


## Question 20