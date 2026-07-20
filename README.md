# LeetCode
--DAY 1--
    PROBLEM TITLE: TWO SUM
    PROBLEM EXPLANATION:
        This solution uses a nested loop approach to check every possible pair of elements in the array:
            >>Outer Loop (`i`): Iterates through each element from index `0` to `n-1`.
            >>Inner Loop (`j`): Iterates through subsequent elements starting from index `i + 1` to avoid checking the same pair or using an element twice.
            >>Check Sum: Checks if `nums[i] + nums[j] == target`. If true, returns `[i, j]`.

____________________________________________________________________________________________________
