# Advent of Code 2024 solutions

Using [Enso](https://ensoanalytics.com).

## Solutions

### Day 1

A good warmer up. Second part got a bit tricky, but still faily easy. I used a lot of partial application with helper functions, that was nice.
I was underusing convenience methods on rows (like multiply) — I should think about it in the future.

![component graph with the solution for day1](https://github.com/vitvakatu/enso-advent-of-code/blob/master/Day1/Main.png)

### Day 2

The first part was relatively easy, I just created a lot of spaghetti components to check the invariants.
The second part took a lot of time, mainly because I didn’t want to implement “iterative” approach by removing elements from the list.
After several experiments I surrendered and started removing elements in a loop. It was suprisingly easy, thanks to Range abstraction and `drop ..By_Index`.

![component graph with part2 function for day2](https://github.com/vitvakatu/enso-advent-of-code/blob/master/Day1/Part2.png)

## License

This work by Ilya Bogdanov is marked with CC0 1.0. To view a copy of this license, visit https://creativecommons.org/publicdomain/zero/1.0/
