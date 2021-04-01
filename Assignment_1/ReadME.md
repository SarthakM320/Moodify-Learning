# Virus Replication Simulation 

## Installation of Packages

```bash
pip install numpy
```
We dont need to install random as it is already present in numpy module
```bash
from numpy.random import *
```

## What we have done in this:
In this project we have written a code to simulate the replication of Viruses. We were given the information that the first neighbours of a cell had a probability 0.25 of changing to one
and the second neighbours had a probability of 0.08 of changing to 1.


We had to initialize a 2D array of Dimensions 100x150 and intialise one element to 1. After that we had to swap 8 elements randomily to another 8 elements and then check for the neighbours 
around a elements having the value 1 and trying to convert others to 1's using the functions firstneighbours and second neighbours. THis procedure was repeated untill all the 
cells had the value 1.


After this we plotted the number of 1's after each iteration and the number of 1's added in each iteration.

Here are the pLots that we got:

<img src = "Graph 2.png">
<img src = "Graph 1.png">
