yao's Garbled Circuit Protocol: an Implementation
GitHub repository for an implementation of Yao's Garbled Circuit protocol for Secure Multi-Party Computation (SMPC) with an 8-bit adder as logical circuit. This repository includes all necessary files for running a local simulation of the protocol, including the source code, a detailed documentation, and a report that analyzes some possible real-world applications of this protocol.

The src/ directory contains the source code and input files for the implementation, including:

*alice_input.txt: Input file for Alice. Can be freely modified.
*bob_input.txt: Input file for Bob. Can be freely modified.
*circuit.json: JSON file representing the circuit for the computation (an 8-bit adder). Note that circuits of different size can be generated through the generate_and_save_circuit in util.py.
* main.py: Main script to run the protocol.
*ot.py: Implementation of Oblivious Transfer protocol.
*parties.py: Implementation of the local actions for the parties involved (Alice and Bob).
*util.py: Utility functions.
*yao.py: Implementation of Yao's Garbled Circuit protocol.
