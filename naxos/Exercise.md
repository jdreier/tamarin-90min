## Exercise Naxos

This directory contains different versions of NAXOS. Solutions can be found in the directory `solutions`.


## Exercise 1
Consider NAXOS_01_simple.spthy.
- Remove specific elements:
    - Remove the first argument to the `h2` function used to compute the session key, and check with Tamarin what happens if you analyse the properties
    
      *Note that* you need to make the change both at the initiator and the responder
    - Remove the second argument instead, etc. etc.

## Exercise 2
Repeat the same questions for NAXOS_08_eCK.spthy
− Compare the results to before. Why do they differ?

## Exercise 3
Compare NAXOS_08_eCK.spthy and NAXOS_15_eCK_FPS.spthy
− Explain the difference (attacks?)
