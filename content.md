A complex number written in rectangular form as $z = x + iy$ has a natural partner obtained by flipping the sign of its imaginary part. This partner, the *complex conjugate*, appears throughout complex arithmetic — for example when dividing complex numbers or when computing a modulus.

# Definition

For a complex number $z = x + iy$, the **complex conjugate** is written $z^*$ (and sometimes $\overline{z}$). It is defined by negating the imaginary part while leaving the real part unchanged:

$$
z^* \equiv x - iy
$$

Taking the conjugate twice returns the original number, so conjugation is an *involutory* operation:

$$
(z^*)^* = z
$$

# Properties

Conjugation distributes over addition, subtraction, and multiplication, and it commutes with taking the multiplicative inverse:

$$
(z_1 \pm z_2)^* = z_1^* \pm z_2^* \\
(z_1 \cdot z_2)^* = z_1^* \cdot z_2^* \\
(z^{-1})^* = (z^*)^{-1}
$$

# Recovering the Real and Imaginary Parts

The conjugate provides a compact way to express the real and imaginary parts of $z$:

$$
\text{Re}(z) &= \frac{1}{2}\left(z + z^*\right)\\
\text{Im}(z) &= \frac{1}{2i}\left(z - z^*\right)
$$

Adding $z$ and $z^*$ cancels the imaginary parts and leaves twice the real part, while subtracting them cancels the real parts and leaves twice the imaginary part.
