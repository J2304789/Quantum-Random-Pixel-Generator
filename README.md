# Quantum Random Pixel Generator

### Developed by:

 - Muhammad Jawwad Javeed Iqbal [[Linkedin](https://linkedin.com/in/jawwad-javeed/)]


## 📚 Table of Contents

* [Project Purpose](#-project-purpose)
* [About](#-about)
* [Required Environment Installations](#-required-environment-installations)


## 📒 Project Purpose

Presently, many modern-day Random Number Generation (RNG) programs do not generate truly randomized numbers, rather they generate pseudorandom numbers determined through specified algorithms.
  
At the same time, current True Random Number Generation (TRNG) programs utilize techniques such as measuring the fluctuations of voltage in order to generate truly random numbers, but are not easily accessible for coding projects.
  
This project aims to resolve both of those issues by using the properties of [Quantum Superposition](https://www.ibm.com/topics/quantum-computing)  alongside IBM's quantum computers in order to generate truly random numbers and plot the visualization of the corresponding probabilities for multiple Qubits set to the |+> or |-> basis.

## 📖 About
Random Number Generation (RNG) program that uses Quantum Superposition in order to achieve True Random Number Generation and plot the visualization of the corresponding probabilities for a Qubit set to the |+> or |-> basis.

For this project it is recommended to use one of IBM's Quantum computers instead of a simulator in order to generate truly random numbers, however for testing purposes the [QASM Simulator](https://qiskit.org/documentation/stubs/qiskit.providers.aer.QasmSimulator.html#qasmsimulator) is the most accurate and similar to a real-life Quantum Simulator and is used as a proof of concept.

## 💻 Required Environment Installations

```
$ pip install Qiskit

``` 
