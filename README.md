[![Python](https://img.shields.io/badge/python-3.10+-informational.svg)](https://www.python.org/downloads/release/python-3918/)
# Generative Tutorials

Notebook Tutorials for Diffusion Models and Score-based Models using PyTorch.

## Prerequisites

You will need:

- `conda`
- `Git`

Optional:

- `NVIDIA Drivers` and `CUDA >= 12.1`

## Installation

Clone this repository (requires git ssh keys)

    git clone https://github.com/caetas/GenTutorials.git 
    cd gentutorials

### Normal Installation

    conda env create -f environment.yml
    conda activate python3.10

#### On Linux

You can setup the virtualenv by running the following commands:

    python -m venv .venv-dev
    source .venv-dev/bin/activate
    python -m pip install --upgrade pip setuptools
    python -m pip install -r requirements.txt

#### On Windows

You can setup the virtualenv by running the following commands:

    python -m venv .venv-dev
    .venv-dev/Scripts/Activate.ps1
    python -m pip install --upgrade pip setuptools
    python -m pip install -r requirements.txt

## Notebooks

The [`Diffusion Notebook`](DiffusionNotebook.ipynb) covers Denoising Diffusion Probabilistic Models ([DDPMs](https://arxiv.org/abs/2006.11239)) and Denoising Diffusion Implicit Models ([DDIMs](https://arxiv.org/abs/2010.02502))

## Extra Resources

Please also consider checking the [`GenerativeZoo`](https://github.com/caetas/GenerativeZoo).


