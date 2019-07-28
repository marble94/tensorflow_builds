# Tensorflow Builds
Some builds of tensorflow for certain cpu instruction sets. 
Feel free to use and share.

## Overview
Each build will be documented that you know which build might right for you.
|Name | March | Other CPU Instruction Sets | Configure Options used | GPU Support | Built with |
| --- | --- | --- | --- | --- | --- |
| tensorflow-1.13.2-cp37-cp37m-linux\_x86\_64\_k8\_ubuntu1904\_py37\_cuda10.whl | K8 | None | /usr/bin/python3 (Python3.7 <br> XLA JIT support? No <br>OpenCL SYCL support? No<br>
ROCm support? No<br>CUDA support? Yes<br>CUDA SDK version? 10.0<br>cuDNN version? 7.0<br>TensorRT support? No<br>NCCL version? Default<br>Compute Capabilities? 5.0,6.1<br>clang as CUDA compiler? No
<br>gcc version used? gcc-7<br>MPI support? No<br>bazel-options? -march=K8<br> ./WORKSPACE for Android builds? No<br> | Yes, NVIDIA Cuda 10.0 | Python 3.7, Ubuntu1904, GCC-7 |

