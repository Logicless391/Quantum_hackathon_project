# Hackathon Information
Developed during the Quantum Hackathon 2026 using the Qniverse QSDK.

---

## OpenQASM to QniverseCircuit Converter

## Problem Statement

Develop a converter that accepts OpenQASM 2.0 or OpenQASM 3.0 source code as input and returns an equivalent QniverseCircuit object using the Qniverse QSDK interfaces.

---

The converter must:

- Support a defined subset of OpenQASM constructs.
- Preserve the semantics of supported operations.
- Detect malformed source code.
- Report unsupported and invalid instructions.
- Handle invalid qubit indices.
- Reject unsupported dynamic constructs.

---

## Objective

The objective of this project is to bridge OpenQASM programs with the Qniverse SDK by providing a reliable source-to-circuit conversion mechanism.

The converter transforms OpenQASM instructions into executable QniverseCircuit objects while performing syntax and semantic validation.

---

## Solution Overview

The proposed solution consists of four major stages:

1. Input Processing
2. Validation
3. Parsing
4. Circuit Generation

The converter reads OpenQASM code, verifies correctness, constructs an equivalent quantum circuit, and reports any detected errors.



## Supported Features

### OpenQASM Versions

- OpenQASM 2.0
- OpenQASM 3.0

### Supported Gates

| Gate | Description |
|--------|------------|
| h | Hadamard Gate |
| x | Pauli-X Gate |
| y | Pauli-Y Gate |
| z | Pauli-Z Gate |
| cx | Controlled-NOT Gate |

### Supported Operations

- qreg declarations
- creg declarations
- Single-qubit gates

## Example input
<img width="310" height="321" alt="image" src="https://github.com/user-attachments/assets/3e960344-1e74-4bf8-8600-c9606d5b0acf" />

---

## Example output
<img width="420" height="488" alt="image" src="https://github.com/user-attachments/assets/1da172f3-da57-44b0-9e90-4eac7eb7582c" />

