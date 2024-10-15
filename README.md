# CS5670 Computer Vision

## Project 5: Neural Radiance Fields (NeRF)

### Introduction

Implementing a Neural Radiance Fields (NeRF) system to synthesize novel views of complex 3D scenes based on a sparse set of input images.

* Train a fully-connected neural network to represent a scene
* Implement volume rendering techniques
* Use positional encoding to capture high-frequency functions
* Synthesize novel views from arbitrary camera poses

Detailed project description can be found [here](http://www.cs.cornell.edu/courses/cs5670/2024sp/projects/pa5/index.html).

### Steps

1. Implement the NeRF architecture (MLP)
2. Implement volume rendering
3. Apply positional encoding to input coordinates
4. Train the network on a dataset of images
5. Implement ray sampling and hierarchical volume sampling
6. Render novel views and evaluate results

### Structure

| Name         | Function                                        |
| ------------ | ----------------------------------------------- |
| /data        | Input image datasets                            |
| nerf.py      | Main implementation of NeRF model               |
| render.py    | Volume rendering functions                      |
| train.py     | Training loop and optimization                  |
| utils.py     | Utility functions for data processing           |
| evaluate.py  | Evaluation metrics for rendered images          |
| visualize.py | Functions for visualizing results               |

### Results

<video width="640" height="480" controls>
  <source src="lego_spiral_001000_rgb.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

For detailed information about the process and results of this project, please refer to the following Jupyter notebooks:

The code implementation for `NeRF` is located in the [CS5670_Project5_NeRF.ipynb](CS5670_Project5_NeRF.ipynb) file and
`MNIST` in the [CS5670_Project5_MNISTChallenge.ipynb](./CS5670_Project5_MNISTChallenge.ipynb) file