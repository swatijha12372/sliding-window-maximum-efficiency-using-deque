# Sliding Window Maximum Using Deque

## 📌 Project Overview

This project implements the Sliding Window Maximum problem using a Deque in Java.

The goal is to find the maximum element in every contiguous window of size k efficiently.

## 🎯 Problem Statement

Given an array of integers and a window size k, find the maximum element in every contiguous window of size k.

### Example

Input:
[1, 3, -1, -3, 5, 3, 6, 7]

Window Size:
3

Output:
[3, 3, 5, 5, 6, 7]

## 💡 Approach

The solution uses a Monotonic Deque.

For every element:

1. Remove indices outside the current window.
2. Remove smaller elements from the back of the Deque.
3. Add the current element's index.
4. The front of the Deque contains the maximum element's index.
5. Store the maximum for each completed window.

## ⚡ Efficiency

Brute Force:
O(n × k)

Optimized Deque Approach:
O(n)

Space Complexity:
O(k)

## 🛠️ Technologies Used

- Java
- Data Structures & Algorithms
- Sliding Window
- Deque
- Monotonic Queue

## ▶️ How to Run

Compile:

javac SlidingWindowMaximum.java

Run:

java SlidingWindowMaximum

## 📤 Sample Output

Input: [1, 3, -1, -3, 5, 3, 6, 7]
Window Size: 3
Output: [3, 3, 5, 5, 6, 7]

## 📚 Key Learning

This project demonstrates how Sliding Window combined with a Monotonic Deque improves efficiency from O(n × k) to O(n).

## 👩‍💻 Author

Swati Jha

B.Tech Student | DSA & Web Development
