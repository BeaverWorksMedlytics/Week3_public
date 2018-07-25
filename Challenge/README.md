# Week3

## Mammogram_Analysis Challenge Notebook
Contains a Jupyter notebook (to be opened in Colab) with the challenge details explained fully.

## Mamm_Images
Mamm_Images file altogether contain contains 2000 jpegs of segments of Mammogram images from the Digital Database for Screening Mammography (DDSM) and the Curated Breast Imaging Subset of DDSM (CBIS-DDSM). Train_Mamm_Images = 1000 jpegs, Eval_Mamm_Images = 500 jpegs, Test_Mamm_Images = 500 jpegs

Both datasets are publicly available:
* DDSM - http://marathon.csee.usf.edu/Mammography/Database.html
* CBIS-DDSM - https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM

Jpegs and labels were extracted from a tfrecords dataset curated by Eric Scuccimarra (https://www.kaggle.com/skooch)

## Eval and Train Simple_Labels and Complex_Labels
These are .csv files containing ordered labels for the images

## Classifier_Evaluation
This is a Jupyter notebook containing a function that will evaluate each group's classifier results and report accuracy and f1 score
