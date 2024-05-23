# Liver Tumor Segmentation Implementations
This repository contains codes for Liver Tumor Segmentation from CT Scans using different state-of-the-art techniques and implementation of various research papers.

The Liver Tumor Segmentation Dataset - [LiTS](https://doi.org/10.1016/j.media.2022.102680) has been used for the implementations, but it can be generalized to any dataset by changing the tensorflow dataloaders.
The input images in the implementation are of 512x512 jpeg format, later resized to 256x256.

In each Jupyter Notebook, a cell indicating the version of tensorflow and keras used in the implementation has been added for easy reference and code reproducibility. In addition, numpy and tensorflow random seeds have also been included for the same.

Currently, the following models have been implemented -
1. [U-Net, Ronneberger et al.](https://doi.org/10.1007/978-3-319-24574-4_28)
2. [Attention U-Net, Oktay et al.](https://arxiv.org/abs/1804.03999)
3. [TransUNet, Chen et al.](https://arxiv.org/abs/2102.04306)
4. [DeepLabv3+, Chen et al.](https://arxiv.org/abs/1802.02611)

Feel free to leave your thoughts and get in touch for related discussion
