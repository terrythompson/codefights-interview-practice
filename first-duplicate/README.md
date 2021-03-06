First Duplicate
-----

Given an array `a` that contains only numbers in the range from `1` to `a.length`, find the first duplicate number for which the second occurrence has the minimal index. In other words, if there are more than one duplicated numbers, return the number for which the second occurrence has a smaller index than the second occurrence of the other numbers. If there are no such elements, return `-1`.

##### Examples

* For `a = [2, 3, 3, 1, 5, 2]`, the output should be `firstDuplicate(a) = 3`. <br>There are two duplicates: numbers `2` and `3`. The second occurrence of `3` has a smaller index than the second occurrence of `2`, so the answer is `3`.

* For `a = [2, 4, 3, 5, 1]`, the output should be `firstDuplicate(a) = -1`.
