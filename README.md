# MNIST PyTorch

A reference implementation of a simple deep neural network for classification on the MNIST data set.

## Environment set up
### Mac with M1 chip (Apple Silicon)
Using Miniforge:
```
conda create --name mnist-pytorch python=3.8
conda activate mnist-pytorch
conda install jupyter matplotlib tqdm
python -m pip install seaborn
python -m pip install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
```
