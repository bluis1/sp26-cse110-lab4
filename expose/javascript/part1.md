# Part 1

## Question 1
Line 9 prints: `20` because `add` is true, so the code inside the `if` block runs. result starts at 0 and then becomes `10 + 10`, which is 20.

## Question 2
Line 13 prints: `20` because `var` has function scope, not block scope. Even though `result` was declared inside the `if` block, it can still be accessed later inside the same function.

## Question 3
You should not use `var` because it has function scope instead of block scope. This can cause variables to be accessible outside the block where you expected them to stay, which can lead to naming conflicts and bugs in testing later.

## Question 4
Line 9 prints: `20` because `add` is true, so the `if` block runs. Inside the block, `result` becomes `10 + 10`, which is 20.


## Question 5
Line 13 causes an error because `result` was declared with `let` inside the `if` block. `let` is block scoped, so `result` cannot be accessed outside that block.

## Question 6
Line 9 does not print anything because the code causes an error before it reaches line 9. `result` was declared with `const`, which is `0`, so it cannot be reassigned on line 7.

## Question 7
Line 13 doesn't print anything because the function already errors on line 7. Also, `const` is block-scoped like `let`, so `result` would not be accessible outside the `if` block anyway.