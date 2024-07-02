### Car Crashes

*Easy*

**Q:** On a given busy intersection, the probability of at least one car crash in a 1 hour time interval is $\frac{8}{9}$. Assuming that car crashes occur independently of one another and at a constant rate throughout time, find the probability of at least one car crash in a 30 minute interval.

**A:** Let the probability in question be $p$. We know that the probability there is no car crash in the hour interval is $\frac{1}{9}$ by complementation.  This is the same as saying that there is no car crash in each of the intervals consisting of the first and last 30 minutes of the hour. By the question, we can say that the number of car crashes in disjoint intervals are independent. This is because they occur at a constant rate throughout time and the arrivals are independent. The probability of no car crash in each of those two intervals individually is $1-p$, so the probability of no car crash in both intervals is $(1-p)^2$, Thus, $(1-p)^2=\frac{1}{9}$, so $p=\frac{2}{3}$.

