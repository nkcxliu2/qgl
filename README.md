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
#### RX Gate 
The RX gate performs a rotation around the X axis by an angle ($\theta$). 
```math
RX(\theta) = \begin{bmatrix} \cos(\theta/2) & -i\sin(\theta/2) \\ -i\sin(\theta/2) & \cos(\theta/2) \end{bmatrix}
```
#### RY Gate
The RY gate performs a rotation around the Y axis by an angle $\theta$. 
```math
RY(\theta)= \begin{bmatrix} \cos(\theta/2) & -\sin(\theta/2) \\ \sin(\theta/2) & \cos(\theta/2) \end{bmatrix}
```
#### RZ Gate 
The RZ gate performs a rotation around the Z axis by an angle $\theta$.
```math
RZ(\theta) = \begin{bmatrix} \cos(\theta/2) - i\sin(\theta/2) & 0 \\ 0 & \cos(\theta/2) + i\sin(\theta/2) \end{bmatrix}
```

#### SX Gate
The SX gate, also known as the sqrt(X) gate, performs a $\sqrt{X}$ operation, which is a half-way rotation around the X-axis on the Bloch sphere.
```math
SX = \begin{bmatrix} \frac{1+i}{2} & \frac{1-i}{2} \\ \frac{1-i}{2} & \frac{1+i}{2} \end{bmatrix}
```
#### P Gate
The P gate, also known as the phase gate, applies a phase shift $\theta$ to the state of a qubit. It is not a global phase gate but specifically shifts the phase of the |1⟩ state.
```math
P(\theta) = \begin{bmatrix} 1 & 0 \\ 0 & \cos(\theta) + i\sin(\theta) \end{bmatrix}
```
#### U Gate 
The U gate is a general unitary operation defined by three parameters: $\alpha$, $\beta$, and $\gamma$. It represents a comprehensive rotation in the Bloch sphere that can achieve any single qubit quantum gate.
```math
U(\alpha, \beta, \gamma) = \begin{bmatrix}
\cos(\alpha/2) & -e^{i\gamma}\sin(\alpha/2) \\
e^{i\beta}\sin(\alpha/2) & e^{i(\beta+\gamma)}\cos(\alpha/2)
\end{bmatrix}
U(\alpha, \beta, \gamma) = \begin{bmatrix}
\cos(\alpha/2) & -(\cos(\gamma) + i\sin(\gamma))\sin(\alpha/2) \\
(\cos(\beta) + i\sin(\beta))\sin(\alpha/2) & (\cos(\beta+\gamma) + i\sin(\beta+\gamma))\cos(\alpha/2)
\end{bmatrix}
```


## 2-qubit Gates


## 3-qubit Gates



## Multi-qubit Gates
