# Aim : To implement different searching techniques in C++.

Experiment 20 A: Linear Search

Experiment 20 B: Sequential Search

Experiment 20 C: Binary Search

# Theory :

# Linear Search :
This is the simplest search technique.

Mechanism: It checks every element in the list or array one by one, starting from the beginning, until the target element is found or the end of the list is reached.

# Sequential Search :

The sequential search algorithm works by examining every element in the list or array one by one, in sequence, until one of two conditions is met:

Success: The target element is found, and its index (position) is returned.

Failure: The algorithm reaches the end of the list, concluding that the target element is not present.

# Binary Search :

This is a much more efficient search technique based on a "divide and conquer" strategy.

Mechanism: It works by repeatedly dividing the search interval in half. It compares the target value to the middle element of the array. If the values are not equal, the half in which the target cannot lie is eliminated, and the search continues on the remaining half

# Algorithm

# 20 A – Linear Search

Start the program.

Input size and array elements.

Input the value to search.

Traverse the array:

If arr[i] == val, return index.

If not found, return -1.

End program.

# 20 B – Sequential Search

Start the program.

Input size and array elements.

Input the search key.

Traverse sequentially until found.

Print index if found, else print not found.

End program.

# 20 C – Binary Search

Start the program.

Input size and sorted array elements.

Input search value.

Set left = 0, right = size-1.

While left <= right:

Find mid = (left+right)/2.

If arr[mid] == val, return index.

Else if arr[mid] < val, search in right half.

Else search in left half.

Print result.

End program

# Conclusion :
Understood Linear Search, Sequential Search, and Binary Search.
Learned that linear/sequential are simple but less efficient.
Binary search is efficient but requires a sorted array.









