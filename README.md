# Quantum Gate Library
This repository is to collect and define quantum gates that are meaningful to quantum algorithms, domain applications, devices, and operations. This will serve as a standard for the support of our software tools.

## 1-qubit Gates

#### X Gate
X is a Pauli gate which flips the qubit, also known as NOT gate.
```math
X = \begin{bmatrix} 0 & 1 \\ 1 & 0 \end{bmatrix}
```
#### Y Gate
Y is a Pauli gate that applies both a bit-flip and a phase flip.
```math
Y = \begin{bmatrix} 0 & -i \\ i & 0 \end{bmatrix}
```
#### Z Gate
Z is a Pauli gate known as the phase flip gate.
```math
Z = \begin{bmatrix} 1 & 0 \\ 0 & -1 \end{bmatrix}
```
#### H Gate
H, also known as the Hadamard gate, is a Clifford gate that creates superposition.
```math
H = \frac{1}{\sqrt{2}} \begin{bmatrix} 1 & 1 \\ 1 & -1 \end{bmatrix}
```
#### S Gate
S is a Clifford gate, specifically the square root of Z phase gate.
```math
S = \begin{bmatrix} 1 & 0 \\ 0 & i \end{bmatrix}
```
#### SDG Gate 
SDG is the inverse of the S gate.
```math
SDG = \begin{bmatrix} 1 & 0 \\ 0 & -i \end{bmatrix}
```
#### T Gate
T, also known as the sqrt(S) phase gate or T gate. T is not a Clifford gate and is important for QEC.
```math
T = \begin{bmatrix} 1 & 0 \\ 0 & \frac{\sqrt{2}}{2} + i\frac{\sqrt{2}}{2} \end{bmatrix}
```
#### TDG Gate
TDG, also known as the inverse of the T gate, involves a complex phase adjustment.
```math
TDG = \begin{bmatrix} 1 & 0 \\ 0 & \frac{\sqrt{2}}{2} - i\frac{\sqrt{2}}{2} \end{bmatrix}
```



## 2-qubit Gates


## 3-qubit Gates



## Multi-qubit Gates
