# Part 1

## Question 1
Line 9 prints: `20` because `add` is true, so the code inside the `if` block runs. result starts at 0 and then becomes `10 + 10`, which is 20.

## Question 2
Line 13 prints: `20` because `var` has function scope, not block scope. Even though `result` was declared inside the `if` block, it can still be accessed later inside the same function.

## Question 3
You should not use `var` because it has function scope instead of block scope. This can cause variables to be accessible outside the block where you expected them to stay, which can lead to naming conflicts and bugs in testing later.

## Question 4
Line 9 prints:

## Question 5
Line 13 prints:

## Question 6
Line 9 prints:

## Question 7
Line 13 prints: