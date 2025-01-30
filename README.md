# Type Error in TypeScript Function Parameter

This example demonstrates a common type error in TypeScript that occurs when passing an array of strings to a function expecting a single string.

## Bug

The function `greeter` expects a single string argument. However, the `user` variable is an array of strings. TypeScript correctly flags this as a type error, preventing the code from compiling.

## Solution

The solution is to modify the function to either accept an array of strings or to iterate over the array and call the function for each element.
