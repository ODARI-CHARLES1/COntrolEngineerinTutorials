
# CONTROLLABILITY AND OBSERVABILITY OF STATE-SPACE SYSTEMS

### A Practical Implementation Using Python and MATLAB

## 1. Introduction

In modern control engineering, two fundamental properties determine whether a
dynamic system can be effectively controlled and whether its internal states
can be reconstructed from its measured outputs.

These properties are:

1. **Controllability:** Determines whether an appropriate control input can
   transfer the system from any initial state to any desired final state
   within a finite time.
2. **Observability:** Determines whether the internal states of a system can
   be uniquely reconstructed using the available system outputs over a finite
   time interval.

Both properties are essential in control system design, particularly when
developing state-feedback controllers and state observers.

In this tutorial, we will:

- Understand the mathematical foundations of controllability and observability.
- Derive the controllability and observability matrices.
- Determine their ranks.
- Implement the analysis using Python.
- Repeat the analysis using MATLAB.
- Compare the results from both environments.
