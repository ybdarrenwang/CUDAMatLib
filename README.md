CUDAMatLib
==========
A library offering GPU parallel computation for array and matrix data types with CUDA.

Requirements
------------
* Linux/Unix
* g++ 4.2 or higher
* NVIDIA VGA card
* [NVIDIA CUDA toolkit](https://developer.nvidia.com/cuda-downloads) (>= CUDA 5.0)

Installation & Test
-------------------
* Use the header files in include/ folder directly.
* Refer to src/\*.cu for use cases.
* `make` to create binaries in bin/ for testing.

To-do
-----
* Complete declaired functions
* Figure out how to better incorporate different implementation of matrix multiplication
* Figure out how to better incorporate streamed version of CUDA algorithm
* Decide whether to incorporate archived functions
