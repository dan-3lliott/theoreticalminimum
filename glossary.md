# Glossary

## Classical Computer
Any non quantum computer whose basic unit of information is a bit. This includes the processors most people use everyday such as phones, laptops, supercomputers, etc.

![Laptop](/assets/img/laptop.png)

## Decoherence
The loss of quantum information of a qubit to its environment. This is characterized in a quantum computer by the decoherence time. The longer a qubit's decoherence time, the longer it is able to preserve its quantum information and therefore have quantum operations performed on it. 
## Qubit
The basic unit of information in a quantum computer, represented physically by a two state quantum system. A qubit differs from a classical bit in that it can exist in a superposition of its two quantum states. This is described mathematically by: \\( \ket{\psi} = \alpha \ket{0} + \beta \ket{1} \\) where \\( |\alpha|^2, |\beta|^2 \\) represent the probabilities of measuring the qubit's state to be in the $$\ket{0}$$ or $$\ket{1}$$ respectively. 

![Qubit](/assets/img/qubit-drawing.png)

## Entanglement
A non local interaction between multiple quantum systems such that their collective description cannot be broken down into the description of each individual quantum system. This is one of the fundamental tenants that make quantum computers powerful because when their qubits are entangled, the state space that they occupy scales by $$2^n$$ but one only needs to manipulate $$n$$ qubits, thus allowing for an exponential increase in information processing. 

![Quantum Computer](/assets/img/quantum-computer2.png)

## Hybrid Algorithm 
An algorithm that combines both classical and quantum algorithms. These algorithms have a part of them that runs on a quantum computer and another that runs on a classical computer. Hybrid algorithms have the most promise to offer computational advantage in the near term for certain tasks because they allow the quantum computer to perform fewer redundant computations. This is essential for current quantum computers becasue they suffer from errors and decoherence thus it is beneficial to minimize the number of computations that they need to do. 
## Moore's Law
An observation by Gordon Moore in the 1970's that the number of transistors in an integrated circuit doubles approximately every 18-24 months. This came to be known as Moore's Law and set a standard for the semiconductor industry to achieve. This law has held for the past 40 years however in recent years it is reaching it's limit as transistors reach atomic sizes. 
## Quantum Error Correction
A procedure in which errors in the quantum information of a qubit are corrected. This procedure takes multiple "physical qubits", qubits that represent the physical quantum systems in the quantum computer, and creates a "logical qubit", a qubit that behaves mathematically as an ideal qubit. Different quantum error correction schemes will require different numbers of physical qubits to form a logical qubit, with the minimum number of physical qubits required being 5. These error correction schemes differ from classical ones because the quantum state of a qubit can't be copied. 
## Quantum Turing Machine
An abstract model for quantum computation. Like a classical turing machine, any arbitrary quantum computation can be represented by a quantum turing machine. However, quantum circuits are used more often in practice for describing the implementation of a quantum algorithm on a quantum computer. 
## Quantum Circuit
A pictographic way of representing a quantum algorithm. Each rail represents a qubit and any operations performed on the qubit are placed along the line as labeled squares. Entangling operations such as multi qubit gates involve lines between qubits. 

