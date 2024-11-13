# M526/P623 Quantum Computation
A repository for M526/P623 Quantum Computation, IF, NU. 

## Announcements

## Course information

What does it mean to compute something, and how can we characterize computational efficiency? These questions lie at the heart of our algorithm-driven lives, influencing everything from automation to information security. Beyond these practical concerns, they also touch on profound philosophical questions about intelligence, creativity, and what makes us humans. (Is it CAPTCHA?) Implications of the theory of computation to such questions was [obvious to Turing himself](https://en.wikipedia.org/wiki/Computing_Machinery_and_Intelligence), but what he didn't anticipate was that quantum theory, if used as a foundation of information processing, would fundamentally transform our understanding of what is computationally feasible, shifting the boundary between what we consider easy and hard problems.

This course is the second half of a year-long sequence on quantum information and computation given at the Institute for Fundamental Study (IF), Naresuan University, academic year 2024. The course will consist of 32 lectures, 1.5 hours each. 

<!--For roughly the first half of the course, we'll put on our computer-scientist hats and examine computational thinking and kinds of algorithms we could run on a large-scale, error-free quantum computer. Then we’ll explore the fundamental idea required to build such a machine–quantum error correction–and, if time permits, discuss other computationally equivalent models of quantum computation and the ongoing quest to find concrete advantages of quantum computers over their classical counterparts. -->

There is no single textbook that covers every topic in the way that I want. *Classical and Quantum Computation* by Kitaev, Shen, and Vyalyi comes close, but 

- [MM] Cristopher Moore and Stephan Mertens, *The Nature of Computation*, Oxford University Press, 2011
- [NC] Michael Nielsen and Isaac Chuang, *Quantum Computation and Quantum Information*, Cambridge University Press, 2000
- [Pre] John Preskill, Caltech's Ph219 [Quantum Information and Computation](http://theory.caltech.edu/~preskill/ph229/) lecture notes
- [Got] Daniel Gottesman, *Surviving as a Quantum Computer in a Classical World*, [book draft](https://www.cs.umd.edu/class/spring2024/cmsc858G/QECCbook-2024-ch1-15.pdf)
- [KSV] A. Yu. Kitaev, A. H. Shen, and M. N. Vyalyi, *Classical and Quantum Computation*, American Mathematical Society, 2002

|Topics|Resources|Perspectives|
|:-----|:--------|:-----------|
|*Computational models*: Turing machine; undecidability; classical circuit model; expotential-size circuit exists; reversible computing; quantum circuit model; subadditivity of errors; Solovay-Kitaev theorem; [convenient illusion of Hilbert space](https://arxiv.org/abs/1102.1360)|NC 3, MM 2|Pre 5|
|*Quantum algorithms*: quantum algorithms based on Fourier transform: Deutsch-Jozsa algorithm, Simon’s algorithm, quantum phase estimation (QPE), RSA cryptosystem, Shor's algorithm for factoring and discrete logarithms, hidden subgroup problem (HSP); Grover’s search algorithm|MM 15|Pre 6|
|*Quantum error correction*: classical linear codes; repetition codes and the Shor code; general properties of quantum error-correcting codes; stabilizer formalism; Gottesman-Knill theorem; basics of fault tolerance|Pre 7, Got I|NC 10, KSV 15|
|*Alternative models of quantum computation and limits to classical simulation of quantum computers*|MM 4-5, KSV 1-4,8-9|

## Schedule

## Grading Scheme

### MS level

### PhD level

- Alternative schemes for universal quantum computation, for instances, adiabatic quantum computation, topological quantum computation, restricted models of quantum computation supplied with magic
- Delegated quantum computation
- Advanced quantum algorithms: Hamiltonian simulations, HHL algorithm for linear systems of equations, block encoding and Quantum Singular Value Transform (QSVT)
- QMA: A quantum analog of the class NP
- MIP*: Interactive proofs with entangled provers
