# Experiment 70: Generics (Max Element)

## Problem Statement
Write a generic method `findMax(T[] array)` that takes an array of any type (that implements `Comparable`) and returns the maximum element. Demonstrate this with an `Integer` array and a `String` array.

## Input Format
* **Line 1:** An integer $N$ (size of the integer array).
* **Line 2:** $N$ space-separated integers.
* **Line 3:** An integer $M$ (size of the string array).
* **Line 4:** $M$ space-separated strings.

## Output Format
* `Max Integer: [val]`
* `Max String: [val]`

## Example 1

**Input:**
```text
3
10 50 20
3
Apple Orange Banana
```


**Output:**
```test
Max Integer: 50
Max String: Orange
```
