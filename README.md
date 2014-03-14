Thesis:
=============

This repository will hold the current working state of the reports for my thesis
work (Preproposal, Proposal, Thesis, and a possibly Technical Report).

### Project Description ###

Process Cooperativity as a Feedback Metric in Concurrent Message-Passing Languages

Runtime systems for concurrent languages have begun to utilize feedback mechanisms
to influence their scheduling behaviour as the application proceeds. These feedback
mechanisms rely on metrics by which to grade any alterations made to the scheduling
system. As the application's phase shifts, the feedback mechanism is tasked with
modifying the scheduler to reduce it's overhead and increase the application's
efficiency.

For example, feedback mechanism could utilize the ratio of I/O to CPU bound
processes within a set number of rounds to be the metric by which it grades it's
efficiency. If it is too high the runtime should give each process less time to 
compute, so it can get through more processes in a round, thus reducing the drag
the CPU bound processes have on the system. The inverse would have the opposite 
effect.

Cooperativity is another possible metric by which to grade a system. In biochemistry
the term cooperativity is defined as the increase or decrease in the rate of
interaction between a reactant and a protein as the reactant concentration increases.
This definition translates well as an information theoretic definition as: the
increase or decrease in the rate of interaction between a process and a communication
mode as the number of processes increase.

Communication mode in this sense would be a function of interprocess communication
such as asynchronous mail-boxes, synchronous channel or even shared memory. In any
example the sending process will need to interact with this method as a means of
interacting with another concurrent process. I will focus on Swap Channels (which
are synchronous rendezous points).

I will attempt to answer the following questions:
* Are the abstractions of a process and communication channel conducive to quantifying
  cooperativity of a system? What generalizations can be made without obscuring important
  factors?
* What factors effect the cooperativity of a runtime system? Also, what mechanisms can be used
  to update the runtime system to positively improve cooperativity in a given phase?
* Is cooperativity a comparable metric for feedback scheduling?

Links:
* [ErLam](https://github.com/dstar4138/erlam) (The tool I'm working on for this thesis.)
* [My Homepage](http://dstar4138.com) (Where I will blog about progress and interesting research.)
* [Professor Fluet's Homepage](http://cs.rit.edu/~mtf) (My Chair for my MSc work.)
