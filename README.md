MIT iQuHack Quantum Rings Challenge Submission for Dorahacks Grant

Factoring 20-bit Semiprime Using Shor's Algorithm

This project implements an optimized version of Shor's Algorithm to factor a 20-bit semiprime using the Quantum Rings Simulator. The implementation focuses on reducing execution time, gate operations, and qubit usage, following insights from recent research on modular exponentiation.

### ✅ Factoring Results:
- **Semiprime (N)**: 744647
- **Factors (p, q)**: 809, 921
- **Execution Time**: 142.37 seconds
- **Gate Operations**: Optimized and Reduced
- **Qubits Used**: 44

* Optimizations Applied

1. Custom Modular Exponentiation Circuit:

Precomputed control rotations to reduce gate depth.

Minimal Toffoli gates for controlled operations.

2. Approximate Inverse QFT (AIQFT):

Reduced the number of controlled-phase gates while maintaining accuracy.

3. Dynamic Qubit Allocation:

Efficiently allocated qubits to maintain performance and resource management.


* How to Run the Code

1. Set up Quantum Rings Access:

Use your API key and email to connect to the simulator.

2. Execute the Main Script:

display_results_in_colab(20)

3. View Results in Colab:

Factors, execution time, gate operations, and qubit usage will be displayed in the output.




Future Work and Expansion

- Scale to 24-bit and 32-bit semiprimes: Extend the algorithm to factor larger semiprimes while maintaining efficiency.

- Reduce Gate Complexity Further: Explore advanced quantum arithmetic techniques to minimize the number of controlled operations.

- Parallel Execution for Multiple Values of : Increase the probability of success by running multiple instances with different bases.

- Integrate Classical-Quantum Hybrid Strategies: Combine quantum period-finding with classical number theory algorithms to improve performance.

- Leverage GPU Acceleration for Simulation: Use GPU resources to reduce the simulation time for quantum circuits involving higher bit sizes.



Prepared by:

Ankit Sharma - HackQubits

MIT iQuHack 2024 Submission
















