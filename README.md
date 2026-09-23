#LeetCode 167 - Two Sum II: Input Array Is Sorted
#Problem
Given a sorted array numbers and a target value, find two numbers whose sum is equal to the target.
Return their 1-based indices.
#Approach
This solution uses the Two Pointer approach.
- Start left from the beginning.
- Start right from the end.
- If the sum is equal to the target, return the indices.
- If the sum is smaller, move left forward.
- If the sum is larger, move right backward.
#Example
Input:
numbers = [2,7,11,15], target = 9
Output:
[1,2]

#Complexity
- Time: O(n)
- Space: O(1)

#Language
Java

#LeetCode
Problem 167 - Two Sum II: Input Array Is Sorted
