<img src="https://i.ibb.co/YyLtKRd/github-art-copy-3.png" align="center" width="100%">
The Bell states, a concept in quantum information science, are specific quantum states of two qubits that represent the simplest (and maximal) examples of quantum entanglement. The Bell states are a form of entangled and normalized basis vectors. Understanding of the Bell states is essential in analysis of quantum communication (such as superdense coding) and quantum teleportation. 

### Goals
To play with around the sample code given by the QDK kit to understand how different quantum operations are executed in Q#, and how a simple entanglement of two Qbits can be created using the Hadamard and CNOT gate

I'm writing this README to keep a log of concepts I learnt after going through some concepts of QComputing and Microsoft's QDK
### Concepts
The bell state is the simplest representation of entanglement. The pair of QBits are put in the Bell state with the following quantum operations: 

![Bell State|Small](https://www.researchgate.net/profile/Panagiotis_Botsinis/publication/236883187/figure/fig26/AS:667098036592645@1536059974257/Quantum-circuit-for-generating-the-entnagled-Bell-state-1-2-00-11.png)

### Q# Gist 
Essentially, we create two QBits and apply the gates to entangle them.
~~~~cs
  qubits = Qubit[2]
  H(qubits[0]);
  CNOT(qubits[0],qubits[1]);
~~~~

### Microsoft's Quantum Development Kit 
This project was built and run using Microsoft's QDK. 
[![QDK|Small](https://cdn-ak.f.st-hatena.com/images/fotolife/u/ut25252/20171215/20171215001916.png)](https://marketplace.visualstudio.com/items?itemName=quantum.DevKit)
