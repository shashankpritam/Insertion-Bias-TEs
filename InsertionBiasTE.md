
The instructions for testing the insertion bias implementation:

1.  Distribute 1000 insertions randomly in the base population.
2.  Simulate the invasion for only 1 (or, if possible 0) generations.
3.  Check how many insertions are in piRNA clusters in the base population (let's use clusters with a size of 3% of the genome).
4.  Do this 100 times for each insertion bias (-100, -90....-10,0,10...90,100).
5.  Test if the number of insertions in piRNA clusters matches the theoretical expectations found here: [https://github.com/RobertKofler/invadego/blob/insertionbias/insertionbias-info.md](https://github.com/RobertKofler/invadego/blob/insertionbias/insertionbias-info.md).
6.  Make 21 boxplots (one for each insertion bias) and check if the observed values fit the expectations.
