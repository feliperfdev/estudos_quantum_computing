# Estudos em Quantum Computing

## Sumário

- [1. Introdução à Computação Quântica](estudos/1_introducao.md)
  - Superposição Quântica
  - Qubit vs Bit Clássico
  - Emaranhamento (ou entrelaçamento) quântico
  - O estado de Bell
- [2. Quantum Gates - Portas quânticas]()
- [3. Circuitos Quânticos]()

<div align='center'>

<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Quantum_teleportation_circuit.svg/300px-Quantum_teleportation_circuit.svg.png'>

</div>

3. **Hadamard Gate**

   A basic operation that transforms a qubit into an equal superposition of its 0 and 1 states, creating a state where the qubit has a 50% chance of being measured as 0 and a 50% chance of being measured as 1.

<img src='https://www.researchgate.net/publication/263046229/figure/fig3/AS:296567878766594@1447718700257/the-Hadamard-gate.png'>

4. **The CNOT (Controlled NOT) Gate**

   A two-qubit operation where the state of the second qubit (target) is flipped if the first qubit (control) is in the state 1, otherwise, the target qubit remains unchanged.

   <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Cnot-compared-to-xor.svg/220px-Cnot-compared-to-xor.svg.png'>

5. **Pauli Operators**

   A set of three basic matrices (Pauli-X, Pauli-Y, and Pauli-Z) used to describe quantum gates that can change the state of a qubit by flipping its state, rotating it, or inverting its phase.

In quantum computing, operators like ZZ, XX, and YY perform specific transformations on qubit states, altering their properties such as phase, amplitude, or entanglement.
