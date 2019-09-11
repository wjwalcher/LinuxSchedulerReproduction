### CPSC 508 Assignment 1 - Research Reproduction
---
This repo contains a research reproduction of the paper _The Linux Scheduler: a Decade of Wasted Cores by Lozi et. al_.

---
##### Crtitique
We begin by writing a critique of the paper itself, focusing on the methodologies employed. 
The critique answers (at least) the basic questions of:
- What is the purpose of the paper?
- What is the hypothesis that the authors are testing?
- What is the experimental setup?
- What is good/bad about the experimental setup?
- How well was the research carried out? What results are presented?
- Do we believe the results? Why/Why not?
- What things might we have done differently?
- What lessons did we learn from reading this paper critically?

The resulting critique is located in the file ```critique.txt```

---
##### Reproduction
There are two folders, ```scheduler_buggy``` and ```scheduler_fixed```.
Each one contains a Dockerfile of a Linux image, preloaded with the benchmark tools provided by the authors of the paper (which can be found [here](https://github.com/jplozi/wastedcores)).

---
##### Critique addendum
The file ```addendum.txt``` contains the final discussion of our results as well as how we found they differed from those published, along with commentary on the overall reproducibility of the results presented.
