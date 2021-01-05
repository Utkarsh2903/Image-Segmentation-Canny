# Image-Segmentation-Canny

The method of partitioning a digital image into several segments (sets of pixels, also known as image objects) is known as Image Segmentation. The aim of segmentation is to 
simplify and/or alter the representation of an image into something that is easier to analyse and more meaningful. Segmentation of images is usually done to locate objects 
and boundaries (lines, curves, etc.). It is the process of assigning a label to every pixel in an image such that pixels with the same label share certain characteristics. 
There are various deep learning based method available to perform this task.

In this project we use edge detection for segmenting the objects out of the images in the dataset without using any neural network. We first grayscale the image for ease in 
application of enhancement methods after which to increase the accuracy of the segmentation process we use thresholding for enhancing the image by increasing the contrast 
for better edge detection. After finding the edges of the object the output is used to create a segmentation mask for the image. The mask is then stacked onto the original 
image and the original pixel values are kept in the segmented region.

There are various applications of Image Segmentation, like in case of medical image processing, the area of interest is extracted from the X-rays which leads to better
visualization and better diagnosis of disease efficiently.
