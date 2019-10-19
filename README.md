# takoyaki_cnn
In this repo, we are given two sets of image data for designing and training a classifier program. An extra evaluation data is given for evaluation of performance. 

The jupyter notebooks in this repo describe the pipeline of designing a **Convolution Neural Network (CNN)** for an image classification problem. The workflow includes
+ analysis the dataset and problem
+ choosing the right architecture 
+ establishing a baseline of performance
+ evaluate the baseline & identify ways for improvement
+ redesigning / fine-tuning the model architecture / hyper-parameters
+ evaluate the new design again for acceptance

The notebooks are written with markdown cells and comments in the code for self-explanatory purpose.

## Pre-requisite
The code was implemented in Ubuntu 18.04 environment. Please have the following installed in order to run the code:
- jupyter notebook
- python3 or above
- Keras
- Tensorflow >= 1.7
- Cuda 9
- opencv 3.3 or above with contrib

## Installation
1. Clone this repo or download & unzip the file in your environment. Then put class_a.npy, class_b.npy and field.npy (files **not** provided in the repo) into the repo folder.

2. Execute jupyter notebook in the repo folder and run the notebook in the following sequence:
+ 1_Basic_CNN.ipynb
+ 2_CNN_Data_Augmentation.ipynb
+ 3_VGG16.ipynb (the trained weights cannot be uploaded to github due to its large size. Please download the .h5 files from this Google Drive link: https://drive.google.com/file/d/1yxFynLD3NfcB18mkN0uJ0jHYpFefWThr/view?usp=sharing or follow the notebook to train.)
