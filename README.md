# leetcode169
Description

This C++ solution finds the majority element in an array using a sorting-based approach. The majority element is defined as the element that appears more than ⌊n/2⌋ times in the array of size n.

Algorithm

The solution leverages the mathematical property that when an array is sorted, the majority element (which occupies more than half of the array) will always be located at the middle position (n/2).

How It Works

Sort the Array: The input array is sorted in ascending order using the built-in sort() function

Return Middle Element: The element at index n/2 (where n is the array size) is returned as the majority element

Time Complexity:
O(n log n) - Dominated by the sorting operation

Space Complexity:
O(1) - Constant space (in-place sorting)

O(log n) - If considering the space used by the sorting algorithm's recursion stack

conclusion

The majority element problem requires finding the element that appears more than ⌊n/2⌋ times in an array of size n. We explored multiple approaches with the sorting method being particularly elegant and straightforward.

Example 1:

Input: nums = [3,2,3]
Output: 3
Example 2:

Input: nums = [2,2,1,1,1,2,2]
Output: 2

Constraints:
n == nums.length
1 <= n <= 5 * 104
-109 <= nums[i] <= 109
