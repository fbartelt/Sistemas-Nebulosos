# Lista 2 - Sistemas Nebulosos (Parte 1)

## Felipe Bartelt de Assis Pessoa - 2016026841

## Wanderson Maciel Filho - 

---

[TOC]

# Q1

$$
Q(U,V)=\begin{bmatrix}0 &0.8 &0.6 & 0.25\\0.7&0.98&0.15&0.5\end{bmatrix}\\
L(U,V)=\begin{bmatrix}1 &0.2 &0.6 & 0.8\\0.85&0.3&0.8&0.88\end{bmatrix}\\
R(V,W)=\begin{bmatrix}1 &0.4 &0.2\\0.1&0.4&0.7\\0.4&0.15&0.05\\0.85&0.3&0.1\end{bmatrix}\\
$$

$$
\lnot L(U,V) = 1 -\begin{bmatrix}1 &0.2 &0.6 & 0.8\\0.85&0.3&0.8&0.88\end{bmatrix} = \begin{bmatrix}0 &0.8 &0.4 & 0.2\\0.15&0.7&0.2&0.12\end{bmatrix}\\
M(U,V) = Q(U,V)\ \wedge\ \lnot L(U,V)\\=
\begin{bmatrix}\min(0,0) &\min(0.8,0.8) &\min(0.6,0.4) & \min(0.25,0.2)\\\min(0.7,0.15)&\min(0.98, 0.7)&\min(0.15,0.2)&\min(0.5,0.12)\end{bmatrix}\\
\therefore M(U,V)=\begin{bmatrix}0 &0.8 &0.4 & 0.2\\0.15&0.7&0.15&0.12\end{bmatrix}
$$

$$
P = Q\circ R =\\
\scriptsize
\begin{bmatrix}\max(0\cdot1,0.8\cdot0.1,0.6\cdot0.4,0.25\cdot0.85) &
\max(0\cdot0.4,0.8\cdot0.4,0.6\cdot0.15,0.25\cdot0.3)&
\max(0\cdot0.2,0.8\cdot0.7,0.6\cdot0.05,0.25\cdot0.1)
\\\max(0.7\cdot1,0.98\cdot0.1,0.15\cdot0.4,0.5\cdot0.85)
&\max(0.7\cdot0.4,0.98\cdot0.4,0.15\cdot0.15,0.5\cdot0.3)
&\max(0.7\cdot0.2,0.98\cdot0.7,0.15\cdot0.05,0.5\cdot0.1)
\end{bmatrix}\normalsize\\
\therefore P(U,W) = \begin{bmatrix}0.24 &0.32 &0.56\\0.7&0.392&0.686\end{bmatrix}\\
$$

# Q2

$$
\mu_B =\mu_A\circ R= \begin{bmatrix}1&0.5&0.4&0.2\end{bmatrix}\circ
\begin{bmatrix}1&0.8&0&0\\0.8&1&0.8&0\\0&0.8&1&0.8\\0&0&0.8&1\end{bmatrix}=
\begin{bmatrix}1 & 0.8 &0.5 & 0.4 \end{bmatrix}
$$

# Q3

