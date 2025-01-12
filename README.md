# JavaScript Null Value Handling

This repository demonstrates a common error in JavaScript related to handling `null` values and how to fix it effectively. The code shows a function that adds two numbers but throws an error when null parameters are passed. The solution implements robust null checks to handle these scenarios gracefully.

## Bug Description
The initial `foo` function lacks explicit null checks, resulting in an error if `null` is passed as an argument. This highlights the importance of defensive programming in handling unexpected input. 

## Solution
The corrected `foo` function includes explicit checks for `null` values, returning `null` appropriately when either or both input parameters are `null`. This behavior is more reliable and avoids potential runtime errors.