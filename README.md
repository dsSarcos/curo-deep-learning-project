# CURO Deep Learning Project

## Summary

This is my project for UGA's Center for Undergraduate Research Opportunities. 

To get the training and validation scripts to run properly, the paths to the proper locations need to be updated within the scripts. These include the paths to the datasets in the config files, as well as the paths to the backbone models for DPT, SegNet, and FCN8s. As of now, the code is disorganized because the project is a raw dump of what I used on several of UGA's CUDA servers and my own personal computer. When time allows, I'll clean it up to eliminate the patchwork and increase ease of use. 

While the project is currently unstable, I've included logs of my training runs in pytorch-semseg/runs. These runs were completed on UGA's CUDA servers.

## Sources

### Paper and Dataset
[Dataset](https://sites.google.com/view/dense-semantic-mapping/home)
[A fully end-to-end deep learning approach for real-time simultaneous 3D reconstruction and material recognition](https://arxiv.org/pdf/1703.04699.pdf)

### Submodules
[pytorch-semseg](https://github.com/meetps/pytorch-semseg)
[DPT](https://github.com/isl-org/DPT/tree/main/dpt)

## Environment

1. Create and activate a python environment.

$python venv env; source env/activate

2. Install the required packages

$pip install -r requirements.txt