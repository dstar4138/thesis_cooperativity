# Thesis: #
### Process Cooperativity as a Feedback Metric in Concurrent Message-Passing Languages


This repository holds the documents for my MSc thesis work 
(Pre-proposal, Proposal, Thesis, and Defense Presentation). 
I leave this repository open for posterity purposes, as a template for 
future graduate students. Good Luck! 


## Thesis Abstract ##

*Defended:* - August 12th, 2014

Runtime systems for concurrent languages have begun to utilize feedback
mechanisms to influence their scheduling behavior as the application proceeds.
These feedback mechanisms rely on metrics by which to grade any alterations made
to the schedule of the multi-threaded application. As the application's phase
shifts, the feedback mechanism is tasked with modifying the scheduler to reduce
its overhead and increase the application's efficiency.

Cooperativity is a novel possible metric by which to grade a system. In
biochemistry the term cooperativity is defined as the increase or decrease in
the rate of interaction between a reactant and a protein as the reactant
concentration increases. This definition translates well as an information
theoretic definition as: the increase or decrease in the rate of interaction
between a process and a communication method as the number of processes
increase.

This work proposes several feedback mechanisms and scheduling
algorithms which take advantage of cooperative behavior. It further compares
these algorithms to other common mechanisms via a custom extensible runtime
system developed to support swappable scheduling mechanisms. A minimalistic
language with interesting characteristics, which lend themselves to easier
statistical metric accumulation and simulated application implementation, is
also introduced.

Links:
* [Professor Fluet's Homepage](http://cs.rit.edu/~mtf) (My Chair for my MSc work.)
* [Thesis Blog](http://cs.rit.edu/~ard4138/blog-posts) (Where I posted about thesis progress.)
* [ErLam](https://github.com/dstar4138/erlam) (The tool I built to aid in this thesis.)
* [My Homepage](http://dstar4138.com) (Where I will blog about other interesting research and my life.)
