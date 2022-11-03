# Gradients

Previously, we learned that Neural Networks are optimizing for
a particular loss function, allowing us to get closer and closer
to the intended output. How do we decide how we should update our
weights or other parameters? **Gradients!**

Formally, the derivative of a function $f(x)$ is defined
as follows.

$$
\lim_{h \to 0} \frac{f(a + h) - f(a)}{h}
$$

The gradient of a function tells us how much it changes if we slightly
alter it's inputs. Let's look at a concrete example with a function $f(x) = 2x^2 + 10$.

$$
\begin{align*}
f(5) &= 60\\
f(5 + 0.0000001) &= 60.000002\\
f'(5) &= \frac{0.000002}{0.0000001} = 2
\end{align*}
$$