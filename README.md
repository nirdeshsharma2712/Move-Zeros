# 📊 LeetCode Problem: Move Zeroes

## 🧩 Problem Statement

Given an integer array `nums`, move all `0's` to the end of it while maintaining the relative order of the **non-zero elements**.

> **Note :**
> - Note that you must do this in-place without making a copy of the array


## 🧠 Approach: Two-Pointer Swap

- Use a pointer `j` to track the position for the **next non-zero**.
  
- Traverse the array:

> - If `nums[i] ≠ 0 → swap nums[i]` with `nums[j]`, then `j++`.



## ✅ Example Walkthrough

### Example 1

##### Input: nums = [0,1,0,3,12]
##### Output: [1,3,12,0,0]


### Example 2

##### Input: nums = [0]
##### Output: [0]


## 🛠️ Constraints

- `1 <= nums.length <= 10^ 4`
- `2^31 <= nums[i] <= 2^31 - 1`
