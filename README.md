ao's Garbled Circuit Protocol: an Implementation
GitHub repository for an implementation of Yao's Garbled Circuit protocol for Secure Multi-Party Computation (SMPC) with an 8-bit adder as logical circuit. This repository includes all necessary files for running a local simulation of the protocol, including the source code, a detailed documentation, and a report that analyzes some possible real-world applications of this protocol.

Table of Contents
Introduction
Repository Structure
Getting Started
Documentation
Report
Source Code
Introduction
Yao's Garbled Circuit protocol is a fundamental technique in Secure Multi-Party Computation (SMPC), allowing multiple parties to jointly compute a function over their inputs while keeping those inputs private. This repository provides a Python implementation of the protocol along with detailed documentation and a comprehensive report.

Note that this implementation is heavily inspired by Oliver Roques' garbled-circuit repository.

Repository Structure
The repository is organized as follows:

.
├── documentation
│   ├── documentation.pdf
│   └── src
├── report
│   ├── report.pdf
│   └── src
├── src
│   ├── alice_input.txt
│   ├── bob_input.txt
│   ├── circuit.json
│   ├── main.py
│   ├── ot.py
│   ├── parties.py
│   ├── util.py
│   └── yao.py
├── README.md
├── requirements.txt

documentation/: Contains the detailed documentation in PDF format.
report/: Contains the project report in PDF format.
src/: Contains the source code and input files for the implementation.
README.md: This README file.
requirements.txt: List of dependencies required for the project.


Install Dependencies:

pip install -r requirements.txt
Run the Implementation:

Detailed usage instructions can be found in the documentation/documentation.pdf file, along with an intuitive explanation of Yao's Garbled Circuit protocol. All possible command line arguments, along with step-by-step instructions for running the implementation are unambiguously described there.

Documentation
The detailed documentation explaining the implementation and usage of Yao's Garbled Circuit protocol can be found in the documentation/ directory:

Documentation PDF
Article
A short article illustrating some potential practical use cases for Yao's Garbled Circuit can be found in the article/ directory:

Article PDF
Source Code
The src/ directory contains the source code and input files for the implementation, including:

alice_input.txt: Input file for Alice. Can be freely modified.
bob_input.txt: Input file for Bob. Can be freely modified.
circuit.json: JSON file representing the circuit for the computation (an 8-bit adder). Note that circuits of different size can be generated through the generate_and_save_circuit in util.py.
main.py: Main script to run the protocol.
ot.py: Implementation of Oblivious Transfer protocol.
parties.py: Implementation of the local actions for the parties involved (Alice and Bob).
util.py: Utility functions.
yao.py: Implementation of Yao's Garbled Circuit protocol.
