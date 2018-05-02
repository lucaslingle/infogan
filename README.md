# infogan

Minimalist, low-abstraction implementation of a specific InfoGAN model from [the InfoGAN paper](https://arxiv.org/abs/1606.03657).

This implementation focuses solely on the MNIST experiment from the paper, and uses the model architecture from that experiment.<br>

Our results corroborate those of the paper, and demonstrate that InfoGAN can learn semantically meaningful disentangled representatons of the MNIST dataset. 
In particular, when provided one categorical variable ```c1 ~ Cat(K=10, p=0.10)``` and two continuous variables ```c2, c3 ~ Unif(-1, 1)``` as latent variables, InfoGAN learned to use the categorical variable to represent digit class, and learned to use the continuous variables to represent digit angle and digit width.



