# CUDA Test

A bunch of test using RAPIDS and CUDA

## Prepare CUDA/Rapids environment

``` shell
# Download script to InstallConda
wget https://repo.anaconda.com/miniconda/Miniconda3-py310_23.3.1-0-Linux-x86_64.sh

# run script
sh Anaconda-latest-Linux-x86_64.sh

# RAPIDS Coda
conda create -n rapids-23.04 -c rapidsai -c conda-forge -c nvidia rapids=23.04 python=3.10 cudatoolkit=11.8

# Activate
conda activate rapids-23.04

```

---
## [TODO] Conda Dependencies 

See [environment.yaml](./environment.yaml)

## Create environment 

    conda env create -f environment.yaml 

## Activate environment
    conda activate cuda-test