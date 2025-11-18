# The Problem and the Quantum solution
## The problem 
We need random number but normal computers cannot create perfect randomness
## The Quantum solution
Quantum mechanics provides natural randomness throgh qubits.
# The code
## Quantum system
A quantum system is created by making a circuit with a selected number of qubits. These qubits are connected to classical bits so their final measured values can be read.
## Superposition
Next, the code applies the Hadamard (H) gate to every qubit. This gate puts each qubit into a superposition state where it is equally likely to be 0 or 1. At this stage, the qubits are fully random but not yet observed.
## Map and Measure
Finally, the code measures all qubits. When measured, the superposition collapses into a random binary string (for example, 0101). The code then converts that binary string into a normal integer, such as 5. That number becomes the final quantum random output.
# Conclusion
My project shows Simple quantum random number generator by using qiskit. It uses a few qubits, applies Hadamard gates to all of them, thereby putting each qubit into a state that is completely random. After that, the qubits are measured, and this measurement produces a random sequence of 0s and 1s. This binary sequence is then converted into a normal integer in code. It then prints this number, as well as the number of qubits and the range of possible values. In a nutshell, the program uses quantum mechanics to generate a truly random number.



