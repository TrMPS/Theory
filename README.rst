
# Background theory and literature

## [Stoudenmire and Schwab](http://papers.nips.cc/paper/6211-supervised-learning-with-tensor-networks)

The idea here is to represent training instances as product states in a tensor product space of $N_\text{pixels}$ spins, with single particle states

$$
\begin{pmatrix}
\psi^{(k)}_\downarrow \\ \psi^{(k)}_\uparrow
\end{pmatrix}=
\begin{pmatrix}
\cos(\pi x_k/2) \\ \sin(\pi x_k/2)
\end{pmatrix}.
$$

where $x_k\in[0,1]$ encodes the grayscale of the $k^\text{th}$ pixel.

A digit is then represented as an many body state with a matrix product state (MPS) representation, which we can think of as a superposition of all different versions of a digit. On account of the MPS representation, one is never concerned with the full Hilbert space.

As far as I understand, no use is made in this paper of the 2D structure (as in convolutional nets).
