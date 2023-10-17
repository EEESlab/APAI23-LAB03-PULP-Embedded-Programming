# APAI-LAB02: Basics of Embedded Programming on PULP

## Summary:
The target device for the lab sessions is the multi-core [PULP](https://github.com/pulp-platform/pulp) platform.
The PULP Virtual Platform simulator GVSOC, which is included within the [PULP SDK](https://github.com/pulp-platform/pulp-sdk), will be used during the class.

- **Subject(s)**: hello-world, vector sum, matrix-vector mul, profiling code execution;
- **Programming Language**: C;
- **Lab duration**: 3h
- **Objective**: Embedded programming & profiling. You will learn basics of embedded programming, the pulp architecture, basic operations (sum & matmul), and how to profile your code execution (MAC, cycles) !


## How to deliver the assignment:

Instructions:
* Use Virtuale, upload only the assignment file named as follows: LAB#_APAI_yourname.ipynb


## Assignment DEADLINE: 19/10/2023 (at 16:00)


## Quickstart
### How to clone the code



### How to access the server

1. Open a browser and paste this link:
`https://compute.eees.dei.unibo.it:8443/guacamole`

2. access with your credentials
3. open a new terminal
4. clone this repository and go to your working directory.
```
git clone https://github.com/EEESlab/APAI23-LAB03-PULP-Embedded-Programming
cd APAI23-LAB03-PULP-Embedded-Programming
```
5. open the folder with visual studio code
6. start working !


### How to run the code
to run the code enter in a terminal
`make clean all run`

DO NOT FORGET: on every new terminal you open, you must do `module load pulp-sdk` once. Then you can do `make clean all run`
