Overview
This repository contains solutions for two coding challenges and an implementation of an interactive photo gallery based on provided Figma designs.

Coding Challenge 1: Array Manipulation
Problem Statement:
Given an array of integers and a target sum, determine if there exists a contiguous subarray within the array that sums up to the target. Return true if such a subarray exists, otherwise return false.

Example:

Input: arr = [4, 2, 7, 1, 9, 5], target = 17
Output: true
Explanation: The subarray [7, 1, 9] sums up to 17.
Constraints:

The array will contain between 1 and 100,000 elements.
The elements in the array and the target sum will be between -1,000,000,000 and 1,000,000,000.
Complexity Requirements:

Expected Time Complexity: O(n), where n is the length of the array.
Expected Space Complexity: O(1).
Coding Challenge 2: String Transformation
Problem Statement:
Given a string, transform it based on the following rules:

If the length of the string is divisible by 3, reverse the entire string.
If the length of the string is divisible by 5, replace each character with its ASCII code.
If the length of the string is divisible by both 3 and 5 (i.e., divisible by 15), perform both operations in the order specified above.
Examples:

Input: "Hamburger"

Output: "regrubmaH"
Explanation: The length of the string is 9, which is divisible by 3 but not by 5 or 15. Therefore, the string is reversed.
Input: "Pizza"

Input: "Chocolate Chip Cookie"

Output: "eikooCpihCetalocohC"
Explanation: The length of the string is 21, which is divisible by 3 but not by 5 or 15. Therefore, the string is reversed.
Constraints:

The string will only contain alphanumeric characters and spaces.
The length of the string will be between 1 and 1000.
Complexity Requirements:

Expected Time Complexity: O(n), where n is the length of the string.
Expected Space Complexity: O(n), where n is the length of the string.
Interactive Photo Gallery
Features:

Responsive design that works seamlessly on both desktop and mobile devices.
Image thumbnail navigation.
Full-size image viewing.
Hover interactions displaying image titles.