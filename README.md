# DSA_Leetcode_problems
Solving DSA problems from LeetCode in Java to prepare for coding interviews and improve logic building.


**#TwoSum**

**Problem Explanation:**

This Java solution finds two numbers in the array that add up to a given target and returns their indices. It uses a HashMap to store the numbers we've seen so far, along with their indices. For each number in the array, we calculate the complement (i.e., target - current number). If the complement is already in the map, it means we've found the pair that adds up to the target, so we return the indices. If not, we add the current number and its index to the map. This approach only requires one pass through the array, making it very efficient with a time complexity of O(n) and space complexity of O(n).

**Example:**
**Input:**
nums = [3, 2, 4]
target = 6
**Output:**
[1,2] indices


**Problem Explanation:**

**#LongestCommonPrefix**

This Java solution finds the longest common prefix shared by all strings in a given array. It starts by assuming the first string as the prefix, then compares it with each remaining string. If a string doesn't start with the current prefix, the prefix is shortened one character at a time until it matches or becomes empty. This process continues until all strings have been checked. The final result is the longest starting substring common to all strings. This approach is easy to understand and efficient for solving prefix-related string problems.The time complexity is O(S), with S being the total characters in all strings, as each character is checked at most once. Space complexity is O(1).

**Example:**
**Input:** ["flower", "flow", "flight"]
**Output:** "fl"
All three words start with "fl", so the longest common prefix is "fl".

