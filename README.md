# Response-Surface-Methodology-Experimental-Design
Experimental Design: minimize the browsing time of Netflix using Response Surface Methodology (RSM)

---

In this project, our main objective is to minimize the browsing time of Netflix. The average browsing time is
our metric of interest. The data we used in the experiment were generated using a response surface simulator.
Our main goal is to build a second-order model to optimize the response. Before that, we need to abandon
the non-significant factors and make sure we are exploring in the region meeting the requirement of convexity.
We explored four relevant factors: Tile Size, Match Score, Preview Length, and Preview Type. 

First, we did a 24−1
fractional factorial experiment to do the factor screening. Among all the factors, Tile Size can be
considered as non-significant, that is, the change in tile size won’t significantly influence the browse time. We
ignored that factor in the subsequent experimentation.

Since the factor Preview Type is categorical, we did the experimentation respectively in both levels.
To find the vicinity of optimum, we used the Method of Steepest Descent. It is hard to reach the ideal region
for the first time, so we had to use intermediate two-level designs to reorient toward the optimum in both
levels.

Then we conducted the central composite design use a second-order response surface model to identify the
location of the optimum. Among these two candidate surfaces, the one with preview type is teaser/trailer
(TT) has the most optimal optimum.
