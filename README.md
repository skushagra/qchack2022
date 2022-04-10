# Quantum Coalition Hackathon 2022

### Quantum Coins
Quantum coins is a game intended to show some of the fundamental properties of a quantum computer, which are superposition and uncertinity. The most basic unit of information in a classical computer is a bit (0 or 1).A quantum computer on the other hand uses qubit which has a more fluid nature than a bit. A qubit can simultaneously be 0 and 1 with some probability of being zero and some probability of being 1. A superposition is a property of a qubit to be in a fluid nature, which states that the state of the coin can be something other that 0 or 1, which in our case lies somewhere in between 0 and 1. The measurement of the quantum state in superposition leads to the collapse of the quantum state to either 0 or 1. This phenomenon is called Wave Function Collapse. The result of the collapse is stored in a classical bit C0, C1 etc. A superposition is created in a qubit by using a Hadamard Gate. A classical computer cannot create a bit that has a fluid nature. A bit is limited to its 0 and 1 state. To carry out operations in a classical computer various gates are used like the AND gate, OR gate, NOT gate, XOR gate etc. The NOT gate, also called a bit flip gate, converts the 0 stae to 1 state and 1 state to 0 state. A bit flip however has no effect on a superposition of a quantum state. This is the working principal of our game. Moreover when two H gates act on a single qubit we get a matrix which when applied to a state 0 or 1 does not change the input, as it forms an identity matrix. When a superposition is created and a bit flip is applied to it, superposition is not affected, when another H gate is applied the initial state of the qubit is recovered.
