# DSA_Leetcode_problems
Solving DSA problems from LeetCode in Java to prepare for coding interviews and improve logic building.


**#TwoSum**
This Java solution finds two numbers in the array that add up to a given target and returns their indices. It uses a HashMap to store the numbers we've seen so far, along with their indices. For each number in the array, we calculate the complement (i.e., target - current number). If the complement is already in the map, it means we've found the pair that adds up to the target, so we return the indices. If not, we add the current number and its index to the map. This approach only requires one pass through the array, making it very efficient with a time complexity of O(n) and space complexity of O(n).

**Example:**
Input:
nums = [3, 2, 4]
target = 6
Output: [1,2] indices
