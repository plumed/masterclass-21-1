#  PLUMED Masterclass 21.1: PLUMED syntax and analysis

This lesson was given as part of the PLUMED masterclass series in 2021.  It includes:

* A video that explain the theory covered and a second video which shows you how the exercises should be completed.
* A series of exercises that you should try to complete yourself.
* Some supplementary python notebooks that provide further background information on the exercise.

The flow chart shown below indicates the order in which you should consult the resources.  You can click on the nodes to access the various resources.  Follow the thick black lines for the best results.  The resources that are connected by dashed lines are supplmentary resources that you may find useful when completing the exercise. 

This lesson was the first masterclass in the 2021 series.  

```mermaid
flowchart LR;
  A[Lecture I] ==> B[Instructions];
  A -.-> C[using pandas];
  B ==> D[Lecture II];
  C -.-> D;
  D --> E[solution];
  click A "video1" "A lecture that was given on January 18th 2021 as part of the plumed masterclass series that introduces you to the exercises in this lesson"
  click B "INSTRUCTIONS.md" "The instructions for the exercises";
  click C "notebooks/plumed-pandas.ipynb" "A python notebook file that illustrates how you can use pandas to read in COLVAR files that are generated with PLUMED" 
  click D "video2" "A lecture that was given on January 25th 2021 as part of the plumed masterclass series that goes through the solutions to the exercises in the lesson" 
  click E "notebooks/solution.ipynb" "A python notebook file that provides a complete set of solutions to the exercises";
```
