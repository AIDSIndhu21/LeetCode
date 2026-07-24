# DAY 1
    PROBLEM TITLE: TWO SUM
    PROBLEM EXPLANATION:
        This solution uses a nested loop approach to check every possible pair of elements in the array:
            >>Outer Loop (`i`): Iterates through each element from index `0` to `n-1`.
            >>Inner Loop (`j`): Iterates through subsequent elements starting from index `i + 1` to avoid checking the same pair or using an element twice.
            >>Check Sum: Checks if `nums[i] + nums[j] == target`. If true, returns `[i, j]`.

----------------------------------------------------------------------------------------------------
# DAY 2
    PROBLEM TITLE:REVERSE STRING
    PROBLEM EXPLANATION:
            >>Solved using python lists built-in function > .reverse()
 ---------------------------------------------------------------------------------------------------
 # DAY 3
    PROBLEM TITLE:FIZZ BUZZ
    PROBLEM EXPLANATION:
            >>Initialized an empty list.
            >>Loop form 1 to n+1.
            >>Used if elif and else for Fizzbuzz condition.
                APPENDS
                    ~FizzBuzz if i%3==0 and i%5==0
                    ~Fizz if only i%3==0
                    ~Buzz if only i%5==0
                    ~Else Number itself 
            >>Appended the result to empty list and displayed.         
---------------------------------------------------------------------------------------------------
# DAY 4
    PROBLEM TITLE:Reverse Words in a String
    PROBLEM EXPLANATION:
            >>Split the string using .split()
            >>Using slicing method reversed the string and joined and displayed the reversed string.
----------------------------------------------------------------------------------------------------

# DAY 5
    PROBLEM TITLE:ADD BINARY
    PROBLEM EXPALNATION:
            >>Adding two binary strings by specifing it as int and '+' operator is used.
            >>The specification 'int(a,2)' will allows to read the number as binary if ',2' is not specified the number will read as decimal.
            >>Using [2:] is used for doesnt considering first two numbers.
            >>Using 'bin()' the addition result is returned as binary.