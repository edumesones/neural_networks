# Neural Network Models & Use Cases

A collection of Jupyter notebooks implementing the main families of neural networks,
each applied to a concrete task and walked through end-to-end (preprocessing → model →
training → evaluation). Built as a hands-on reference for the core deep-learning
architectures.

## Architectures covered

| Type | Notebook focus | Notes |
|------|----------------|-------|
| **FNN** — Feedforward NN | tabular / baseline classification | |
| **CNN** — Convolutional NN | image classification | |
| **RNN** — Recurrent NN | sequence modelling | |
| **GAN** — Generative Adversarial Net | image generation | GPU vs CPU compared; sample outputs per epoch in `images_generated/` |
| **BERT** — Transformer | NLP fine-tuning | GPU required |

The `images_generated/` folder shows the GAN's output sampled at each training epoch,
so you can see learning progress visually.

## Tech stack
Python · TensorFlow / Keras · NumPy · Jupyter · (GPU recommended for GAN/BERT)

## Use
Open any notebook and run top-to-bottom; each is self-contained with its own data
loading and training loop.
