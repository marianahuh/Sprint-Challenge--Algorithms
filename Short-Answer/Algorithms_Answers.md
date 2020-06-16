#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n) - The number of operations grows as n grows.

b) O(n^2) - There is an O(n) operation nested in an O(n) operation.

c) O(1) - The input of how many bunnies does not reflect on the run time. The number of operations is alway the same.

## Exercise II

A binary search approach would determine which 'f' floor will break the least amount of eggs.

First drop from the mid level of the building, if the egg breaks, go down to mid level below. Otherwise, if it doesn't break, go mid level higher from current floor until the egg breaks.
Continue the sequence unitl you reach 'f' floor that results in a broken egg minus one floor.

Runtime would be O(log n)
