# Insertion Sort Algorithm in C++ 🧑‍💻✨

This repository contains a simple implementation of the **Insertion Sort** algorithm in C++. Insertion sort is like sorting your playing cards 🃏 one by one in the correct order.

## How Insertion Sort Works 🔍

- Start from the second element and compare it with the elements before it.
- Shift all larger elements one position to the right 👉 to make space.
- Insert the current element at its correct position 🎯 in the sorted part.
- Repeat until the whole array is sorted ✅.

### Example:
Array before sorting: `[12, 11, 13, 5, 6]`

Steps:
- Compare 11 and 12, insert 11 before 12 → `[11, 12, 13, 5, 6]`
- 13 > 12, no change → `[11, 12, 13, 5, 6]`
- Insert 5 at correct position → `[5, 11, 12, 13, 6]`
- Insert 6 at correct position → `[5, 6, 11, 12, 13]`

## Code Example 💻

