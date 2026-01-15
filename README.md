# Assignment 1

![Assignment 1](https://github.com/PGE383-HPC/assignment1/actions/workflows/main.yml/badge.svg)

The aim of this assignment is to get familiarized with git, basic Unix commands, and the assignment submission process.  I've recorded a YouTube video that walks you through this process for the this first assignment.  The assignment submission process is the same for all assignments so you might find it to be a useful reference in the future as well:

https://youtu.be/FU-l1_cIGVo

**Note:** The testing procedure has changed since recording this video, please refer to the command below to test the solution.

## Instructions

 1. Open the assignment in a Github Codespace.

 2. In the using the file browser or the Terminal command window, create a new text file `solution.txt`.

 3. Open the new file `solution.txt` with a text editor and enter the following text **exactly as it appears**: `Hello, World!`.

 4. Commit the new file to the repository and push assignment1 and the changes you made back to [github.com](http://github.com).

 ## Testing

If you would like to check to see if your solution is correct, in the Terminal command window run the following command

 ```bash
 julia --project -e "using Pkg; Pkg.test()"
 ```

 The output will indicate which tests passed and/or failed.
