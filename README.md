# Background theory and literature

### @Stoudenmire:2016aa

The idea here is to represent training instances as product states in a tensor product space of $N_\text{pixels}$ spins, with single particle states

$$
\begin{pmatrix}
\psi^{(k)}_\downarrow \\ \psi^{(k)}_\uparrow
\end{pmatrix}=
\begin{pmatrix}
\cos(\pi x_k/2) \\ \sin(\pi x_k/2)
\end{pmatrix}.
$$

where $x_j\in[0,1]$ encodes the grayscale of the $k^\text{th}$ pixel.

A digit is then represented as an many body state with a MPS representation, which we can think of as a superposition of all different versions of a digit. On account of the MPS representation, one is never concerned with the full Hilbert space.

As far as I understand, no use is made in this paper of the 2D structure (as in convolutional nets).

See also the conference paper @Stoudenmire:2016ab.
