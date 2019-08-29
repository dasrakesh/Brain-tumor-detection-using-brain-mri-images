Link - https://figshare.com/articles/brain_tumor_dataset/1512427/5
If anyone wants to downlaod dataset used in this project then you can refer to above given link
# Brain-tumor-detection-using-brain-mri-images
In this project I identified the types of brain tumor from MRI images using Machine learning techniques
# Introduction
1. MRI is a technique  that uses powerful magnets, radio waves, and a computer to make detailed pictures inside our body.
2. MRIs can be done on different parts of our body
3. It is useful for looking at soft tissues and the nervous system
4. Information  technology  and  e-health  care  system  in  the medical field helps clinical experts to provide effective diagnosis,
treatment and monitoring of the  disease  for  better  health  care  to  the  patient 
# Methodology
The image processing techniques are applied to the dataset that we have acquired then we have extracted the useful features that 
are necessary for further analysis
1. Image Aquisition
2. Image Preprocessing
3. Segmentation 
4. Feature extraction
5. Classifiaction

# IMAGE AQUISITION
This brain tumor dataset containing 3064 T1-weighted contrast-inhanced images
from 233 patients with three kinds of brain tumor: 
meningioma (708 slices), 
glioma (1426 slices), and 
pituitary tumor (930 slices).
This data is organized in matlab data format (.mat file). Each file stores a struct
containing the following fields for an image:

cjdata.label: 1 for meningioma, 2 for glioma, 3 for pituitary tumor
cjdata.PID: patient ID
cjdata.image: image data
cjdata.tumorBorder: a vector storing the coordinates of discrete points on tumor border.
cjdata.tumorMask: a binary image with 1s indicating tumor region

# Image Preprocessing
1. Image de-noising is an important task in any type of image processing
2. The aim of pre-processing is an improvement of the image data that suppresses unwanted distortions or enhances
some image features important for further processing
3. Most enhancement and noise reduction techniques are used to get better results
4. Enhancement will bring about more prominent edges and noise will be reduced and so the blurring of image is decreased. 

# Segmentation
1. In image segmentation the image is divided into regions. 
2. Image segmentation is used for measuring and visualizing the brain’s anatomical structures, for analyzing brain changes,
and for better diagnosis
3. Brain MRI segmentation is an essential task in many clinical applications because it influences the outcome of the entire analysis.
This is because different processing steps rely on accurate segmentation of anatomical regions

# Feature Extraction
1. It is the process of collecting higher-level information of an image such as shape, texture, color, and contrast
2. It is used effectively to improve the accuracy of diagnosis system by selecting prominent features
3. We have extracted following features sucha s:
        -Entropy
        -Standard Deviation
        -Mean
        -Energy
        -Skewness
        -kurtosis

# Classification
The computer program learns from the data input given to it and then uses this learning to classify new observation
Here we have used different supervised as well as unsupervised algorithms such as:
  -KNN
  -SVM
  -Random Forest
  -Decision tree
  -Naive bayes
  -MLP





