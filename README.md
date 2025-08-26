# CS50 Problem Set 3 — Sort

![CS50](https://img.shields.io/badge/CS50-Harvard-red)
![Analysis](https://img.shields.io/badge/assignment-analysis-blue)

## 📌 Overview
This repository contains my analysis for CS50 Problem Set 3: **Sort**.  
The assignment provides three compiled C programs (`sort1`, `sort2`, `sort3`) and several input text files. The task was to identify which program implements:

- **Bubble Sort**  
- **Selection Sort**  
- **Merge Sort**  

The file `answers.txt` contains my results and detailed explanations, including timing evidence from testing.

---

## ⚙️ How to Run
To test the programs, navigate into the `sort` folder:

```bash
cd sort


Make sure the programs are executable:


chmod +x sort1 sort2 sort3

Run a sort on an input file:

./sort1 reversed10000.txt
./sort2 random5000.txt
./sort3 sorted10000.txt

To measure the runtime:

time ./sort1 reversed10000.txt

How I Determined the Sorting Algorithms


Bubble Sort

Very slow on reversed and large random inputs.

Runs much faster on already sorted input.

Matches the behavior of repeated adjacent swaps.

Selection Sort

Consistent speed across all input types (sorted, reversed, random).

Always scans the unsorted portion for the minimum value.

Merge Sort

Fastest across all input sizes.

Divides and conquers efficiently with O(n log n) complexity.

Tested each program on multiple input files.

Recorded timings and observations.

Correctly identified which sort algorithm each program implements.

Submitted via submit50 to CS50.



Notes

To reproduce, download the official PS3 distribution from CS50 and place it in the sort/ folder.

Timing results can vary slightly depending on system performance.

This repository focuses on analysis; no C source code was written for this problem set.


Author: Caroline Mildred Gomes
Course: CS50 Harvard University (edX)

