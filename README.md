# Tensorflow Builds
Some builds of tensorflow for certain cpu instruction sets. 
Feel free to use and share.

## Overview
Each build will be documented that you know which build might right for you.

|Name | March | Other CPU Instruction Sets | GPU Support | Built with |
| --- | --- | --- | --- | --- |
| tensorflow-1.13.2-cp37-cp37m-linux\_x86\_64\_k8\_ubuntu1904\_py37\_cuda10.whl | K8 | None | Yes, NVIDIA Cuda 10.0 | Python 3.7, Ubuntu1904, GCC-7 |

## Detailed Configuration Options
### tensorflow-1.13.2-cp37-cp37m-linux\_x86\_64\_k8\_ubuntu1904\_py37\_cuda10.whl
* /usr/bin/python3 (Python3.7)
* XLA JIT support? No
* OpenCL SYCL support? No 
* ROCm support? No
* CUDA support?Yes
* CUDA SDK version? 10.0
* cuDNN version? 7.0
* TensorRT support? No
* NCCL version? Default
* Compute Capabilities? 5.0,6.1
* clang as CUDA compiler? No
* gcc version used? gcc-7
* MPI support? No
* bazel-options? -march=K8
* ./WORKSPACE for Android builds? No
