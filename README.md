# Algorithmic Keyword Filter in C++

## 📝 Overview
This repository contains an optimized C++ solution designed to parse a stream of strings and efficiently filter specific keywords (`and`, `not`, `that`, `the`, `you`). 

## ⚡ Technical Highlights
* **I/O Optimization:** Utilizes `ios_base::sync_with_stdio(false);` and `cin.tie(nullptr);` to untie C++ streams from C standard streams. This significantly speeds up execution time when processing high-volume input.
* **Memory Efficiency:** Uses standard sequential string comparison within a streamlined `while` loop, preventing unnecessary memory allocation.

## 🚀 How It Works
The program reads the total count of words, iterates through each word dynamically, and increments a counter if a matching keyword is found. If at least one keyword matches, it outputs `Yes`; otherwise, it outputs `No`.
