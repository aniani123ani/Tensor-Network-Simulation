# Tensor-Network-Simulation
Simulating quantum circuits becomes computationally expensive as the number of qubits and circuit depth increases. Tensor networks provide a structured approach to approximate large quantum states by exploiting their entanglement properties. This project focuses on integrating tensor network simulations within PennyLane to efficiently handle circuits that are challenging for conventional simulators.
# Why working on this unique code?
1- To demonstrate the integration of tensor network simulations into PennyLane.

2- Alos, to simulate large quantum circuits with reduced computational overhead using tensor networks.

3- Moreover, to compare the accuracy and efficiency of tensor network-based simulations against traditional statevector simulators.

4- Finally, to Apply the technique to a meaningful quantum algorithm, such as the Quantum Fourier Transform (QFT) or a small-scale quantum chemistry problem.

# Methods used in my project:

I utilized tensor networks, specifically matrix product states (MPS) and tree tensor networks, to efficiently represent quantum states by leveraging their entanglement structure.
I decomposed quantum gates into tensor operations to directly operate on the network. To integrate this approach, I developed a custom PennyLane device as the simulation backend, implementing tensor contraction for gate measurements. 
I benchmarked the performance by simulating circuits of varying sizes and entanglement, comparing execution time and memory usage against PennyLane’s default.qubit simulator. Additionally, I visualized entanglement entropy and tensor bond dimensions to demonstrate the adaptability and efficiency of the tensor network during simulations

