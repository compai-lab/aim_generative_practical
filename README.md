# aim_generative_practical
Practical on deep generative models

# AIM II - Practical Deep Generative Models

This repository contains the practical for generative models. It is based on PyTorch and will mostly be focused on applying AEs and diffusion models to the task of unsupervised anomaly segmentation. 
We provide healthy and anomalous data, a data-loader, a AE model, training routines, evaluaton scripts, and others as a starting point. 

[![Open Demo In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/compai-lab/aim_generative_practical/blob/main/main.ipynb)

## Installation

### When on your local machine

Clone this repository
```shell
git clone https://github.com/compai-lab/aim_generative_practical.git
```

Create (and activate) a new virtual environment (requires conda)
```shell
conda create --name mad python=3.9
conda activate mad
```

Install the required packages
```shell
cd mad_seminar_s23
python -m pip install -r requirements.txt
```

Download and extract the data
```shell
wget <http://get_link_from_moodle>
unzip data.zip
```

### When in Google Colab

Simply follow the instructions in `main.ipynb`
