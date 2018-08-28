# tSNE-for-images

## Goal:
Given an image dataset, visualise some portion of it (say 1000 images) using tSNE.



## Data:
101_ObjectCategories dataset was used.

It consisted of around 10,000 images distributed among 101 categories.



## Model:
(1) VGG16 and (2) Resnet50 models pretrained on ImageNet were used to obtain representations of the images.



## Further steps:
The representations were transformed into 300-length-vector using PCA, and then tSNE was applied to further reduce it to 2 dimensions.

Thereafter, tSNE visualisation was performed, and then this visualisation was performed on grids for better visualisation.
