# APAI-LAB03: Basics of Embedded Programming on PULP

## Summary:
The target device for the lab sessions is the multi-core [PULP](https://github.com/pulp-platform/pulp) platform.
The PULP Virtual Platform simulator GVSOC, which is included within the [PULP SDK](https://github.com/pulp-platform/pulp-sdk), will be used during the class.

- **Subject(s)**: hello-world, vector sum, matrix-vector mul, profiling code execution;
- **Programming Language**: C;
- **Lab duration**: 3h
- **Objective**: Embedded programming & profiling. You will learn basics of embedded programming, the pulp architecture, basic operations (sum & matmul), and how to profile your code execution (MAC, cycles) !


## How to deliver the assignment:

Use Virtuale, upload only the assignment file named as follows: LAB#_APAI_yourname.ipynb


**Assignment DEADLINE: 26/10/2023 (at 16:00)**

___

## Quickstart

#### How to access the server

1. Open a browser and paste this link:
`https://compute.eees.dei.unibo.it:8443/guacamole`

2. access with your credentials. We distribute credentials by hand.
3. open a new terminal
4. clone this repository and go to your working directory.
```
git clone https://github.com/EEESlab/APAI23-LAB03-PULP-Embedded-Programming
cd APAI23-LAB03-PULP-Embedded-Programming
```
5. open the folder with visual studio code
6. start working !


#### How to run the code
**[DO NOT FORGET]** Every time you open a new terminal run:

`module load pulp-sdk`

To run the code enter in a terminal

`make clean all run`
