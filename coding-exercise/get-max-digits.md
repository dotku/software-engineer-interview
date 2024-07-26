
Given an array of integers a, your task is to calculate the digits that occur the most number of times in the array. Return the array of these digits in ascending order.

Example

For a = [25, 2, 3, 57, 38, 41], the output should be solution(a) = [2, 3, 5].

Here are the number of times each digit appears in the array:

```
0 -> 0
1 -> 1
2 -> 2
3 -> 2
4 -> 1
5 -> 2
6 -> 0
7 -> 1
8 -> 1
```

The most number of times any number occurs in the array is 2, and the digits which appear 2 times are 2, 3 and 5. So the answer is [2, 3, 5].

Input/Output

[execution time limit] 4 seconds (js)

[memory limit] 1 GB

[input] array.integer a

An array of positive integers.

Guaranteed constraints:
1 ≤ a.length ≤ 103,
1 ≤ a[i] < 100.

[output] array.integer

The array of most frequently occurring digits, sorted in ascending order.

[JavaScript] Syntax Tips

```
// Prints help message to the console
// Returns a string
function helloWorld(name) {
    console.log("This prints to the console when you Run Tests");
    return "Hello, " + name;
}
```
