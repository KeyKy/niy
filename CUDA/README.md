[Niy](https://github.com/microic/niy)
====

While other deep learning frameworks can support GPU by simply using CuDNN, CuDNN is not suitable for Niy:
* Niy removes activation functions(sigmoid, tanh, relu, prelu...)
* Niy supports deconvolution(the reverse operation of convolution, not transposed convolution)
* Niy tries to remove all the matrix operations so as to be similar to biological neural network


To support parallel computing, we will use CUDA
