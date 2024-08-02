# Disentangled Latent Spaces Facilitate Data-Driven Auxiliary Learning #

## Installation ##
**1. Repository setup:**
* `$ git clone https://github.com/intelligolabs/Detaux`
* Download 3dshapes.h5 from https://console.cloud.google.com/storage/browser/3d-shapes;tab=objects?prefix=&forceOnObjectsSortingFiltering=false
* Move the dataset to the 'data' folder in the root directory of the project.

**2. Conda enviroment setup:**
* `$ conda create -n detaux python=3.7`
* `$ conda activate detaux`
* `$ python -m pip install pytorch-lightning==1.9.4`
* `$ cd disentanglement_library/`
* `$ python -m pip install -v -e .`
* `$ python -m pip install tensorflow-gpu==1.14`
* `$ python -m pip install --upgrade tensorboard`
* `$ cd ../`
* `$ python -m pip install wandb`
* `$ pip install torchvision`

## Run Detaux ##
1. To run the disentanglement part, use the file `detaux.py`. In particular, `launch_dis.sh` it contains the list of arguments used to run the model.
2. To run the clustering part, use the file `clustering.py`.  In particular, `launch_clustering.sh` it contains the list of arguments used to run the model.

## Citation ##

```
@article{skenderi2023disentangled,
  title={Disentangled Latent Spaces Facilitate Data-Driven Auxiliary Learning},
  author={Skenderi, Geri and Capogrosso, Luigi and Toaiari, Andrea and Denitto, Matteo and Fummi, Franco and Melzi, Simone and Cristani, Marco},
  journal={arXiv preprint arXiv:2310.09278},
  year={2023}
}
```
"# ML_DL_project" 
