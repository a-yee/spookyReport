# Spooky Author Classification

by Alex Yee

---

### Objective

`id# | 'some string here' | 'HPL'`

1. HP Lovecraft
2. Mary Wollstonecraft
3. Edger Allan Poe

+++

### Vectorization

$$alphabet = abcdefghijklmnopqrstuvwxyz!&-,.'\"?$$

$$\vec{char(c)} = \left[0, 0, 1,\ldots,0\right]^{T}$$ 

+++

### Vectorization Cnt.

$$str("hello") = \begin{bmatrix}
\vert&\vert&\vert&\vert&\vert\\\
\ldots\vec{o}&\vec{l}&\vec{l}&\vec{e}&\vec{h}\\\
\vert&\vert&\vert&\vert&\vert\\\
\end{bmatrix}
$$
