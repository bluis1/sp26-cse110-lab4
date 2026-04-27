# DevTools Part 2

## What was the bug?
The bug was that `num1` and `num2` were being read from the input boxes using `.value`, which makes them strings. Because of that, JavaScript used `+` to combine the strings instead of adding numbers. For example, `2` and `3` became `"23"` instead of `5`.

## How would you fix it?
I would convert `num1` and `num2` into numbers before adding them.

```js
let result = Number(num1) + Number(num2);
```