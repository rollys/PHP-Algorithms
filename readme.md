# PHP Algorithms

Here I will add a handful of algorithms from many fields I find useful and interesting.

## Euclidean (aka GCD)

GCD stands for Greatest Common Divisor.  
Given 2 natural numbers, find their greatest common divisor that divides both of them without leaving any reminder.  
> Time Complexity: O(log min(a, b))

## Euclidean Extended (aka GCD Extended)

Same as the Euclidean algorithm but this algorithm also brings us 2 numbers `x,y` that satisfy the following equation:  
`gcd(a, b) = ax + by = d`  
> Time Complexity: O(log min(a, b))

## Kadane (aka Maximum Subarray Problem)

Named after [Joseph Born Kadane](https://en.wikipedia.org/wiki/Joseph_Born_Kadane).  
Finding the contiguous subarray within a one-dimensional array.
> Time Complexity: O(n)

## Binary Search

Finds the position (index) of a target value within a sorted array.  
> Time Complexity: O(log n)

## Insertion Sort

Simple sorting algorithm.  
> Time Complexity: O(n^2)

## String Sum

Given 2 big natural numbers, sum them together.  
> Time Complexity: O(max(|str1|, |str2|))

## Is Prime (Simple Version)

Given a integer number, check if the number is prime or not.  
> Time Complexity: O(sqrt(n))

## KMP (Knuth–Morris–Pratt string-searching)

Given a word of size `m` and a text of size `n`, searches for all occurrences of a word within a text.  
> Time Complexity: O(n+m)

## Modular Exponentiation

Efficient way to compute (x ^ n) % m.  
> Time Complexity: O(log n)

## Modular Multiplicative Inverse

Given a and m, finds x such that: `(a * x) mod m = 1`
> Time Complexity: O(log min(a, m))

## License

All algorithms are licensed under the [MIT license](https://opensource.org/licenses/MIT).


Have fun!
