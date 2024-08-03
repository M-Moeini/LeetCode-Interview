# Solving 150 LeetCode Interview Questions

## Overview

This repository is dedicated to solving 150 popular LeetCode interview questions. The goal is to provide clear, efficient, and well-documented solutions to help others prepare for technical interviews.

## Structure

The repository is organized into the following sections:

1. **Array**
2. **String**
3. **Linked List**
4. **Stack and Queue**
5. **Tree**
6. **Graph**
7. **Dynamic Programming**
8. **Backtracking**
9. **Sorting and Searching**
10. **Design**
11. **Math**
12. **Other Topics**

Each section contains solutions to problems related to that specific topic.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/leetcode-interview-questions.git
   cd leetcode-interview-questions

## Solutions

Each solution is provided in a Markdown file and includes:

- **Problem Description**: A brief description of the problem.
- **Approach**: Explanation of the approach used to solve the problem.
- **Complexity Analysis**: Time and space complexity of the solution.
- **Code**: The actual code implementation in Python.

## Example

Here is an example structure for a solution file:

### Problem 1: Two Sum

**Description**: Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`.

**Approach**:

- Use a dictionary to store the difference between the target and each element as we iterate through the array.
- Check if the current element exists in the dictionary.

**Complexity Analysis**:

- Time Complexity: O(n)
- Space Complexity: O(n)

**Code**:
```python
def two_sum(nums, target):
    num_dict = {}
    for i, num in enumerate(nums):
        if target - num in num_dict:
            return [num_dict[target - num], i]
        num_dict[num] = i

## Contribution

Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

## Contact

Mahdi Moeini  
Email: [mmoeini@mun.ca](mailto:mmoeini@mun.ca)  
LinkedIn: [linkedin.com/in/mmoeini](https://linkedin.com/in/mmoeini)  
GitHub: [m-moeini.github.io](https://m-moeini.github.io)
