## Practical Session - Recognizing Numbers with DL -

### Setting up Environment and Packages 

1. Intall Anaconda (https://www.anaconda.com/products/distribution).
2. Create a new environment with python 3.9:
```
conda create --name dl_tutorial python=3.9
```
3. Enter the new environment:
```
conda activate dl_tutorial
```
3. Install the required packages:
```
# PyTorch (ask me for this precise line. It depends on your computer.
conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch 
# Matplotlib -- used for plotting --
conda install -c conda-forge matplotlib
# Jupyter
conda install -c conda-forge jupyterlab
```

### Clone from github