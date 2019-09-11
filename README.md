### CPSC 508 Assignment 1 - Research Reproduction
---
This repo contains a research reproduction of the paper _The Linux Scheduler: a Decade of Wasted Cores by Lozi et. al_.

---
##### Crtitique
We begin by writing a critique of the paper itself, focusing on the methodologies employed. 
The critique should answer (at least) the basic questions of:
- [ ] What is the purpose of the paper?
- [ ] What is the hypothesis that the authors are testing?
- [ ] What is the experimental setup?
- [ ] What is good/bad about the experimental setup?
- [ ] How well was the research carried out? What results are presented?
- [ ] Do we believe the results? Why/Why not?
- [ ] What things might we have done differently?
- [ ] What lessons did we learn from reading this paper critically?

The resulting critique will be located in the file ```critique.txt```

---
##### Reproduction
There are two folders, ```scheduler_buggy``` and ```scheduler_fixed```.
Each one will somehow contain a Linux image [trying Qemu now], preloaded with the benchmark tools provided by the authors of the paper (which can be found [here](https://github.com/jplozi/wastedcores)).
The file ```reproduction.pdf``` should contain:
- [ ] A write-up of what experiment you are trying to reproduce (identify the corresponding tables/graphs from the original paper).
- [ ] A description of your experimental setup.
- [ ] A discussion of any assumptions you made and important information that the authors did not provide in their paper.
- [ ] A list of any tools and/or traces that you used.

The Overleaf Document we'll use for this PDF can be found [here](https://www.overleaf.com/6984225494pnzyrbrsyjtq).

---
##### Critique addendum
The file ```addendum.txt``` should contain the final discussion of our results as well as how we found they differed from those published, along with commentary on the overall reproducibility of the results presented.
