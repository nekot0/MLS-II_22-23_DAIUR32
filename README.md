# MLS-II_22-23_DAIUR32


## About this repository

This repository is part of the assignment of Applied Machine Learning Systems II (ELEC0135_22-23). There are two files in the jupyter notebook format. Each file can be run on Kaggle platform. 



## Descriptions

### file 1 ([run on Kaggle](https://www.kaggle.com/code/nekot0/effdet-simpletest))

This code is a test implementation of training the EfficientDet model using effdet, a pytorch-based implementation of EfficientDet. It deals with a task in a simple setting where the imput images have one red circle on a black square background. The model is trained to output the potential bounding boxes for a red circle. 

This code is based on [the blog article](https://endaaman.me/tips/training-effcientdet-pytorch) written in Japanese, and my contribution is explained in [this article](https://dev.to/nekot0/efficientdet-implementation-in-a-simple-setting-4em3) written by myself. 

** Requirements **
- [effdet-0.3.0 modified by myself](https://www.kaggle.com/datasets/nekot0/effdet-030-package-dataset)
- omegaconf-2.3.0
- timm-0.6.13
- antlr-4.9.3
- pycocotools-2.0.2
- huggingface_hub-0.13.3
- torch-1.13.0
- albumentations-1.3.0



### file 2 ([run on Kaggle](https://www.kaggle.com/code/nekot0/siim-covid19-detection-effdet-basecase))

This code is part of the model developed in my report. It makes a database of the training data and fine-tunes an EfficientDet model implemented with effdet so that the model outupts for each image potential bounding boxes and classes predicted. 

The errors we potentially meet when running the code are explained in the blogs below. 
[Errors in the implementation of model training with effdet (5 April)](https://dev.to/nekot0/errors-in-the-implementation-of-model-training-with-effdet-4pcd)
... to be continued

** Requirements **
- [effdet-0.3.0 modified by myself](https://www.kaggle.com/datasets/nekot0/effdet-030-package-dataset)
- omegaconf-2.3.0
- timm-0.6.13
- antlr-4.9.3
- pycocotools-2.0.2
- huggingface_hub-0.13.3
- torch-1.13.0
- albumentations-1.3.0
- [Packages provided by AWSAF](https://www.kaggle.com/code/awsaf49/pydicom-conda-helper)
- [Dataset provided by SIIM](https://www.kaggle.com/competitions/siim-covid19-detection/data)
