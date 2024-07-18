# VIBE: Video Inference for Human Body Pose and Shape Estimation
[Official Project Link](https://github.com/mkocabas/VIBE)

## Running

## Windows Installation

### 0. Tools set-up
We need to install the following tools:
- Python: https://www.python.org/downloads/
- GIT: https://git-scm.com/download/win
- MSVC++ Redis (14.40.33810.0) : https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170
- FFMPEG (7.0.1) : https://www.gyan.dev/ffmpeg/builds/#release-builds
> Note: after extracted FFMPEG, add folder `bin` to the `Path` in System Environment Variables

- Miniconda: https://docs.anaconda.com/miniconda/

### 0Bis. CUDA-powered GPU 
First, update the latest GPU driver: https://www.nvidia.com/Download/index.aspx?lang=en-us and restart the system for the changes to take effect.

In order to check our GPU driver, use the following command:
```sh
nvidia-smi
```
Second, get the CUDA Compute Capability of your GPU, and find out which CUDA versions that the GPU supports on [CUDA Wikipedia page](https://en.wikipedia.org/wiki/CUDA#GPUs_supported).

For example, GPU on my system is NVIDIA GeForce RTX 3070 -> Compute Capability is 8.6 (or sm_86) -> CUDA verions the GPU supports are 11.1 - 11.4

> Note: execute command `nvidia-smi`

### 1. Virtual Environment for Python

### 2. CUDA and cuDNN

### 3. PyTorch

### 4. VIBE

### 5. Input data

## References
- https://github.com/carlosedubarreto/vibe_win_install
- CUDA Compute Capability, https://github.com/prabindh/mygpu?tab=readme-ov-file

