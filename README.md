Creating a Markov-Process Python code
A Markov process is a random process indexed by time, and with the property that the future is independent of the past, given the present. Markov processes, named for Andrei Markov, are among the most important of all random processes.

I try here to develop a simple trading strategy following the Markov Process. The goal is to compute the probability of the day (n+1) being "up" or "down" considering the performance of the day (n). The highest probability we obtain is 54%.

We try to get a better result by computing the probability of the day (n+1) being "up" considering that the 5 consecutive days before were "down". 
With this only one condition we get a 66% probability.
