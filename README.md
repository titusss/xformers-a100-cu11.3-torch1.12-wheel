# xformers-a100-cu11.3-torch1.12-wheel
Xformers pip wheel for Paperspace A100 machines. CUDA 11.3 Torch 1.12

Works on Paperspace A100 machines.
Installation (without dependencies):
`pip install --no-deps https://github.com/titusss/xformers-a100-cu11.3-torch1.12-wheel/releases/download/0.0.16%2B814314d/xformers-0.0.16+814314d.d20230126-cp38-cp38-linux_x86_64.whl`

If you have the wrong PyTorch version, up/downgrade to 1.12.1 for CUDA 11.3:
`pip install -U torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113`


Xformers wheel, built on a Paperspace Core machine: 

Pytorch: 1.12.1+cu113
NVIDIA A100 80G GPU
Intel Xeon Gold 6342 CPU
Ubuntu 20.04 LTS
CUDA 11.3
Python 3.8.13
TORCH_CUDA_ARCH_LIST (Compute capabilities): 7.0+PTX 8.0 8.6


Xfomers SHA: 814314d
Version: 0.0.16
Built on: Jan 26th 2023

Main xformers repo: https://github.com/facebookresearch/xformers
