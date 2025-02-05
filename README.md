# Objective-C Memory Management Bugs

This repository demonstrates common memory management issues in Objective-C, specifically memory leaks due to improper object ownership and circular references. It also shows how to solve these problems using proper memory management techniques.

## Bug Description
The `bug.m` file contains code that showcases several memory management problems. These include:

* **Memory Leaks:** Objects are created but not properly released, leading to memory leaks.
* **Circular References:** Objects retain each other, preventing deallocation, even when no longer directly accessible.
* **Delegate Issues:** Incorrect delegate handling can cause crashes or unexpected behavior.

## Solution
The `bugSolution.m` file provides corrected code that addresses these memory management issues. It demonstrates proper use of `retain`/`release` (or ARC equivalents) to prevent memory leaks and handles circular references and delegates correctly.