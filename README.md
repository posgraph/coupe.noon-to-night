# Noon to Night Color Transfer
Torch implementation for transferring noon image to night image.

![result](/assets/result.jpg)

Network structure for transformation network looks:
![network](/assets/model.png)

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

## License ##
This software is being made available under the terms in the [LICENSE](LICENSE) file.

Any exemptions to these terms requires a license from the Pohang University of Science and Technology.

## About Coupe Project ##
Project ‘COUPE’ aims to develop software that evaluates and improves the quality of images and videos based on big visual data. To achieve the goal, we extract sharpness, color, composition features from images and develop technologies for restoring and improving by using it. In addition, personalization technology through user preference analysis is under study.  
  
Please checkout out other Coupe repositories in our [Posgraph](https://github.com/posgraph) github organization.

## Useful Links ##

  * [Coupe Library](http://coupe.postech.ac.kr/)
  * [POSTECH CG Lab.](http://cg.postech.ac.kr/)
