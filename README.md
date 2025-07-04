# EPI Judge

## Introduction

EPI Judge is meant to serve as a companion to our book Elements of Programming Interviews. Specifically, this project consists of the following:

- **Stub programs** for each problem in our book in Python, Java, and C++
- **Test-cases** that cover common corner-case and performance bugs
- A **framework** for running these tests on your implementation on your machine

## Running the judge from the command line

#### Java

Use the [`Makefile`](https://github.com/adnanaziz/EPIJudge/blob/master/epi_judge_java/Makefile). 

Compile and run a specific program:

    $ make <program_name> 
Example:

    $ make Anagrams
Compile and run the last program that you edited:

	$ make

## Tracking your progress

The file [index.html](https://github.com/adnanaziz/EPIJudge/blob/master/index.html) in the root of this project tracks your progress through the problems. Specifically, there's an expanding tab for each chapter. Click on it, and you will see your progress, e.g., as below. This file gets updated each time you execute a program. You can **use this file to map book problems to stub programs**.

<img src="https://i.imgur.com/xjf7Z32.png" width="600px"></img>
