# Detection of vegetation in croplands

This repository is dedicated to detecting vegetated areas in JPG images acquired over croplands. Images are from different distances and points of view. 


# Files

For a better understanding of this repository, it is explained in detail in the following:

## data

There are five different images of croplands that are used to implement the proposed vegetation detection method.

## docs

You can find my final report about different results in this folder as a .ppt file.

## results

There are two distinct folders in 'results'. In 'RGBtoOther', you can find different results of converting default RGB image space to other spaces like HSV, HLS, and YIQ.
In 'OutputKmeans', different results of clustering each feature space using Kmeans or Fuzzy C0means algorithms.

## src

My code was developed in Google Colab. So, you can find a .ipynb file in 'src'. You can either easily download and upload it to your drive to use it in Google Colab or use it on your local computer.' By the way, you must change the directory address of each input & output image based on your system.
