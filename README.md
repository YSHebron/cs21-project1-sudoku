# **CS 21 Project 1: Sudoku Solvers**

## Description
For this project, our goal was to create a 4x4 and 9x9 Sudoku solver using MIPS32 Assembly. Main languages used were C and 32-bit MIPS.

Our approach is as follows:
- First, we noted Sudoku's goal state(s) and constraints (row, column, and box).
- Next, we wrote C Sudoku solver programs as basis (see `"C Files\"`).
- Finally, we translated these C programs to MIPS32.

Key ideas here are **backtracking** and **search space optimization**.
Full documentation and Assembly files for the `4x4solver.asm` and `9x9solver.asm` sudoku solvers can be found in `"For Submission\"`.

### **Quick Links**
- See `CS21_Project1_Specs.pdf` for full specifications. Please [email](yshebron@up.edu.ph) me for access. Promising quick response.
- Project Documentation in `For Submission\Documentation.pdf`.
- Link to Video Documentation [here](https://drive.google.com/file/d/1k-E8vXAQEqSiizUXigCTDUmzAVF_FHYs/view?usp=sharing).

## **Requirements**
- Windows XP or higher.
- Java Runtime Environment (JRE), Java 9 or higher. Latest Java SE recommended. Download [here](https://www.oracle.com/java/technologies/javase-downloads.html).
- MARS v4.5. A Java program for teaching, compiling, and running MIPS32 Assembly. Download [here](http://courses.missouristate.edu/kenvollmar/mars/download.htm).

Note: There is already a packaged `mars.jar` file in `"For Submission\"`.

## **Running the Program**
The sudoku solvers can be run in two ways.

1. **Through the MARS GUI.** In the menu bar, click File>Open, then navigate to the sudoku solver assembly files. Afterwards, in the toolbar, click Assemble (tool and wrench icon) then click Run (play icon). In the lower left, the execution pane will be visible through which you can paste test cases such as those found in the included 4x4.txt and 9x9.txt files in `"For Submission\"`. Note that inputting test cases through the MARS GUI can only be done line-by-line.
2. **Through cmd.** Open your command line, `cd` to `"For Submission\"` (where `mars.jar` already exists), then run `java -jar mars.jar <file_name>`. File name could be `4x4solver.asm` or `9x9solver.asm`. You may now input your valid test cases to the cmd. 
## **Sample I/O**
For the 4x4 solver, an input is formatted as:
```
1000
0001
0400
0020
```

Which outputs:
```
1342
4231
2413
3124
```

For the 9x9 solver, an input is formatted as:
```
005800009
210000050
070900600
000201035
000000000
780405000
004006020
030000061
600003500
```
Which outputs:
```
465812379
219367458
378954612
946271835
523698147
781435296
154786923
832549761
697123584
```
---
Yenzy Urson S. Hebron \<yshebron@up.edu.ph\>

University of the Philippines Diliman

2nd Semester A.Y. 2021-2022

© Course Materials by Sir Wilson Tan and Sir Ivan Carlo Balingit
