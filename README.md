# Retinanet Utilities

This repository contains Python utility scripts used for data/image preprocessing for the project I contributed. Some of the utilities posted here were not available directly, so notebooks here can be helpful (mostly for pre-processing & annotation arranging) for DL practicioners with [RetinaNet](https://github.com/fizyr/keras-retinanet).

Although the RetinaNet is deprecated now, this repository still offers some of the commonly used image and annotation processing methods for other object detection model implementations. Also, it seems like the RetinaNet still will be usable, however the up-to-date implementation of RetinaNet will probably be hosted with torchvision. I recommend checking [RetinaNet](https://github.com/fizyr/keras-retinanet) for further details. 

## Notebook Contents

### *cropscale.ipynb*
* *Croping & scaling for the image dataset.*
* *Divides the images in the dataset into grids with selected parameters and creates a new annotations file.*
* *Will convert this to a Python executable in near future.*
### *csv-path-fixing.ipynb.ipynb*
* *If the environment that we are being worked on changes, probably image paths will require new paths as well. This notebook offers a fast adaptation.*
* *Can also be used for discarding annotations for objects which extend out of the images.*
### *discard_out_of_boundary.ipynb*
* *Same as the bullet above. Please check the notebook for further details.*
### *new-annotations-fulldataset.ipynb*
* *A handful of annotation pre-processing.*


## TO-DO
> 1. Currently commited with initial formats of ipynb files. I will add more guidelines to them.
> 2. Will add a documentation.
> 3. Preparing Python executables for these notebooks.
