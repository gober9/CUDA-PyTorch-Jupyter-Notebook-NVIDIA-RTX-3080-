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
CUDA toolkit versions can be found here https://developer.nvidia.com/cuda-toolkit-archive. I am using CUDA 11.8, and the version of PyTorch does work for this GitHub. 

### 3. Install PyTorch with the CUDA 11.8 Support.
```bash
pip install torch==2.5.1 torchvision==0.20.1 torchaudio==2.5.1 --index-url https://download.pytorch.org/whl/cu118
```
