````markdown
# U-Net From Scratch (PyTorch)

A clean implementation of the original U-Net architecture in PyTorch built entirely from basic `torch.nn` modules for educational purposes.

The objective of this project is to understand how U-Net works internally by implementing every building block manually instead of relying on high-level segmentation libraries.

---

## Features

- Implementation of U-Net from scratch
- Modular implementation using reusable building blocks
- Step-by-step shape walkthrough
- Skip connection implementation using feature concatenation
- Designed for learning and experimentation

---

## Architecture

The model follows the original U-Net architecture proposed by Ronneberger et al.

- Encoder
    - Double Convolution
    - Max Pooling

- Bottleneck

- Decoder
    - Transposed Convolution
    - Skip Connections
    - Double Convolution


---# u-net-from-scratch
