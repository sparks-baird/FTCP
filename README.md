## Description

CrystalVAE is a python package for creating an general crystal representation and setting up generative VAE to inverse design new crystals based on material properties.

## Installation

To install, just clone the following repository:


pip install -r requirement.txt


## Usage

run `CVAE.py` with given number of elements and nsites.  This generates the crystal representation in both real and momentum space and encodes such representation into VAE latent space.

The package contains the following module and scripts:

| Module | Description |
| ------------- | ------------------------------ |
| `CVAE.py`      | Script for training the VAE with structured latent space according to material properties      |
| `featurizer.py`  | Script for data mining 3D crystal structure from MP.org and featurize it into both real and momentum space representation|
| `ultils.py` | Script for auxiliary functions|
| `requirements.txt`      | required packages    |

   

## Authors

