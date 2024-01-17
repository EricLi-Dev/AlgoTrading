# Install
## Manage jupyter notebook kernels from (base)
```
conda activate base
conda install nb_conda_kernels
```
## Create new env with Python3.12
```
conda create -n nt python=3.12
conda activate nt
conda install ipykernel
pip install -U nautilus_trader
```

## Open jupyter-lab w/ all kernels at (base)
```
conda activate base
jupyter-lab
```