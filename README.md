
## Yao's Garbled Circuit Protocol: An Implementation

Welcome to the GitHub repository for the implementation of Yao's Garbled Circuit protocol for Secure Multi-Party Computation (SMPC) with an 8-bit adder as the logical circuit. This repository includes all necessary files for running a local simulation of the protocol, along with detailed documentation and a report analyzing potential real-world applications.

### Repository Structure

The `src/` directory contains the source code and input files for the implementation, including:

- **alice_input.txt**: Input file for Alice. This file can be freely modified to test different inputs.
- **bob_input.txt**: Input file for Bob. This file can also be freely modified to test different inputs.
- **circuit.json**: A JSON file representing the circuit for the computation (an 8-bit adder). Note that circuits of different sizes can be generated using the `generate_and_save_circuit` function in `util.py`.
- **main.py**: The main script to run the protocol.
- **ot.py**: Implementation of the Oblivious Transfer protocol, which is essential for the secure computation.
- **parties.py**: Implementation of the local actions for the parties involved (Alice and Bob).
- **util.py**: Utility functions to support the main operations and assist in circuit generation.
- **yao.py**: Implementation of Yao's Garbled Circuit protocol, the core component of this project.

### How to Use

To run the simulation, follow these steps:

1. **Set Up the Environment**: Ensure you have Python installed on your system. You may also need to install additional dependencies as listed in `requirements.txt`.
2. **Modify Input Files**: Adjust the `alice_input.txt` and `bob_input.txt` files with your desired inputs.
3. **Run the Main Script**: Execute `main.py` to start the protocol simulation.

### Documentation and Reports

- **Documentation**: Detailed documentation is provided within the repository to help understand the implementation and its components.
- **Report**: A comprehensive report is included, analyzing possible real-world applications of Yao's Garbled Circuit protocol and its effectiveness in preserving privacy during multi-party computations.


