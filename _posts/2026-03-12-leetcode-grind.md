---
layout: post
title:  "my leetcode log: the fate I cannot avoid"
published: false
---

I know AI does better at Leetcode than me, but it's about showing up everyday.

I'm going to grind on Leetcode for the next couple months. My goal is to solve every Blind 75 questions on Neetcode thoroughly.


- **03/18/26 (1):** Long weekend. solved Valid Parentheses.
- **03/14/26 (2):** solved Valid Palindrome, Encode & Decode. Tackled threeSum.
    ```python
    def threeSum(self, nums: List[int]) -> List[List[int]]:
        output = []
        nums.sort()
        for i, a in enumerate(nums):
            if a > 0: break
            if i > 0 and a == nums[i-1]: continue
            l = i + 1
            r = len(nums) - 1
            while l < r:
                threeS = a + nums[l] + nums[r]
                if threeS > 0:
                    r -= 1
                elif threeS < 0:
                    l += 1
                else:
                    output.append([a, nums[l], nums[r]])
                    l += 1
                    r -= 1
                    while nums[l-1] == nums[l] and l < r:
                        l += 1
        return output
    ```
    - `if a > 0: break` for sorted array, if the first element is positive, the sum will always be positive.
    - `if i > 0 and a == nums[i-1]: continue` if we encounter the same number, we skip to the next number. No duplicates.
    - the last inner while loop checks for duplicates and finishes the loop.

- **03/13/26 (1):** solved Top K Frequent Elements and also resolved Contains
Duplicate and Two Sum in C++. I could maybe write about why bubble sort is
inefficient for most cases. Get really good at Binary Search, DFS, BFS, and Sliding. 
- **03/12/26 (4):** solved Contains Duplicate, Two Sum, Valid Anagram, Group Anagrams.
