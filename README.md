## crack reconstruction
提高裂纹重建精度


This is a real-time crack reconstruction system that includes 3D reconstruction, instance segmentation, and real-time rendering with a multi-resolution voxel space.

Thanks to [bundlefusion](https://github.com/niessner/BundleFusion) for its great contribution, some of our code comes from them.

Our dataset can be available here: https://pan.baidu.com/s/1fUyvJb9uy2ADXkxLkow5vw?pwd=g5gy 
提取码：g5gy

## Installation
The code was developed under VS2017, and tested with an intel Realsense D435i.

We tested our code on:
- DirectX SDK June 2010
- NVIDIA CUDA 11.5 (>=8.0)
- Realsense SDK2.0
- our research library mLib, a git submodule in external/mLib [here](https://github.com/niessner/mLib/tree/ac6b9e9d1da1df00a2293da64a9f146c123fa2ca)
- mLib external libraries can be downloaded [here](http://kaldir.vc.in.tum.de/mLib/mLibExternal.zip)
- Intel OpenVINO 2021.4.689
- Opencv with OpenVINO

Optional:
- Kinect SDK (2.0 and above)
- Prime sense SDK
