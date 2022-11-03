# Neural Networks

(Artificial) Neural Networks are a mathematical model of
the human brain. In the human brain, the neuron is the most basic
unit. In neural networks, we model neurons using a *perceptron*.

:::{figure-md} markdown-fig
<img src="images/perceptron.jpeg" alt="Perceptron" width="450px">

Perceptron ([Source](https://cs231n.github.io/neural-networks-1/))
:::

When a neuron fires (activates) in the human brain, this may cause other neurons
to also fire. Similarly, the *perceptron* will receive a signal $x$ from other
artificial neurons, and this will have some influence, controlled by a weight $w$, in the output of the perceptron. If $w$ is a negative number, then this synapse will have an inhibitory influence in the neuron. Otherwise, if $w$ is positive, it will have
an excitatory influence.

Then, the perceptron "aggregates" the signals using a weighted sum and a bias $b$, an extra term used to represent the threshold for the artificial neuron to fire.

```{margin} Note
$y$ represents the output signal of the perceptron
```

$$
    y = w_0x_0 + w_1x_1 + \ldots + w_nx_n + b = \Sigma_i w_ix_i + b
$$

So far, we've actually calculated the equivalent to the level of activity of our artificial neuron. In a biological neuron,
once it reaches a certain threshold, a signal is fired.
Inspired by human biology, McCulloch and Pitts introduced the following activation
function $f$.

$$
f(a) = 
\begin{cases}
    1 & \text{if $a \geq 0$}\\
    0 & \text{if $a \lt 0$}
\end{cases}
$$

We can then apply it to the activity level of our neuron, which we've calculated before (weighted sum and bias), to obtain a simple mathematical model of a human neuron.

$$
    y = f(\Sigma_i w_ix_i + b)
$$

There are many other activation functions e.g. RELu, tanh, ... each with different strengths and weaknesses.

```{note}
This section is heavily inspired by the introduction to artificial
neurons from the CS231n course at Stanford. If you're looking to supplement
your understanding we recommend taking a look [here](https://cs231n.github.io/neural-networks-1/)
```