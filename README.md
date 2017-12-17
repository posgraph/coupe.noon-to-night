# Noon to Night Color Transfer
Torch implementation for scoring sharpness of a blur image.
![result](/assets/result.jpg)
Network structure for transformation network looks:
![network](/assets/network.png)

This repository contains train and test codes for reproduce.
Pretrained network model and dataset will be distributed soon.

--------------------------

## Prerequisites
- torch

## Getting Started
### Installation
- Install torch from http://torch.ch/
- Clone this repo:
```bash
git clone https://github.com/posgraph/coupe.noon-to-night.git
cd coupe.noon_to_night/Noon\ to\ Night
```

## Training and Test Details
- you need to specify directories for dataset, checkpoint and sample in main.py
- To train a model,  
```bash
th train.lua
```
- To test the model,
```bash
th inference.lua
```
