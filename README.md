# keras_jax: Keras API for JAX

## What is JAX?

[JAX](https://github.com/google/jax) is **AutoGrad** + **XLA**. JAX can automatically differentiate
native Python and NumPy functions. 

* With `jax.grad`, you can efficiently compute  any-order gradients w.r.t any variables
* JAX supports JIT compilation (`jax.jit`). It uses XLA to compile Python functions.
* JAX supports **vectorization** (`jax.vmap`) which can be used to batch code. You can also **parallelize** code across
multiple accelerators using `jax.pmap`).

## What is Keras?

[Keras](https://keras.io/) is the official high-level API for [TensorFlow](https://www.tensorflow.org/guide/keras).
Keras is very **user-friendly**, **intuitive**, and **easy**. Keras is quite extensible and you can go from research to 
production in no time. 

## What is keras_jax?

`keras_jax` aims to replicate the Keras API for JAX.  






**Note:** This is not a Google product. I am working on it in my free time apart from my day job. Expect **slow** to **very slow** progress. 

