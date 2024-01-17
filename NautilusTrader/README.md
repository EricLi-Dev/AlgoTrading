# Install
## Manage jupyter notebook kernels from (base)
```
brew install python
brew install rust
conda activate base
conda install nb_conda_kernels # manage Jupyter kernels at base
```
## Create new env with Python3.12
```
conda create -n nt python=3.12
conda activate nt
conda install ipykernel # Jupyter kernel for this env
pip install -U nautilus_trader # Install Nautilus Trader
```

## Open jupyter-lab w/ all kernels at (base)
```
conda activate base
jupyter-lab # Start Jupyter Lab
```
