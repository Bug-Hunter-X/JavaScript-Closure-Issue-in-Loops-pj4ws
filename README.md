# JavaScript Closure Issue in Loops

This repository demonstrates a common issue with closures in JavaScript loops.  The code appears to correctly log the numbers 0-9, but due to how closures work with the loop variable `i`, it will instead log the number 10 ten times.  The solution shows how to correctly capture the variable value using an immediately invoked function expression (IIFE).