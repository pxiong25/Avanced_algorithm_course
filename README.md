Warm - up Assignment (Indices)

Using C++ programming language (IDE: CLion), Integers and a target value are inputted to find the corresponding output (indices instead of arrays)

Example 1: 
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Output: Because nums[0] + nums[1] == 9, we return [0, 1].

Example 2: 
Input: nums = [3,2,4], target = 6
Output: [1,2]

Example 3: 
Input: nums = [3,3], target = 6
Output: [0,1]

Constraints:
2 <= nums.length <= 104
-109 <= nums[i] <= 109
-109 <= target <= 109 Only one valid answer exists.

Function: twoSum
  1. loops through the array (nums)
  2. Checks if the sum of two numbers equal the target
  3. Outputs the indices (0, 1, 2, etc.) of the numbers that equal the target

Main Function: 
  1. (main) function is to test the provided array (nums) and target values
  2. (twoSum) function is performed and renders result


