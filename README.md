# CUDA-PyTorch-Jupyter-Notebook-NVIDIA-RTX-3080
I have seen some struggles online about getting CUDA and PyTorch to agree with one another within a Jupyter Notebook. Here is what I did to get it to work.  

App Verions:
- PyTorch: 2.5.1
- CUDA: 11.8
- Windows 10

### 1. Uninstall Current CPU-only PyTorch
```bash
pip uninstall torch torchvision torchaudio
```

### 2. Install the desired version of CUDA.
CUDA toolkit versions can be found here https://developer.nvidia.com/cuda-toolkit-archive.
```bash
pip uninstall torch torchvision torchaudio
```
