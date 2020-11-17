# Facial image recognition with masks

* Author: Zhen Li

## Description

VGGface2 dataset is used for this project.
http://www.robots.ox.ac.uk/~vgg/data/vgg_face2/

MaskTheFace is used to generate synthesized masked images
https://github.com/aqeelanwar/MaskTheFace

Edgeconect is used to unmask and inpaint images
https://github.com/knazeri/edge-connect

Jupyter NoteBook scripts are included:
- CS230_FinalProject.ipynb : train and evaluate models
- models.ipynb : models for FR
- loss_function.ipynb : triplet and quintuplet loss implementation
- face_loader.ipynb : data loader
- crop_face.ipynb : crop facial images
