# QR Code Image Reader using Edge Detection
## Problem Description

I found that reading QR codes from images can be challenging due to the complex patterns and noise in the images. So, I decided to develop a QR code image reader using edge detection to accurately detect and decode QR codes from images.
## Previous Work

In addition to the techniques covered in class, including grayscale conversion, edge detection, and image resizing, I explored some other algorithms for image preprocessing and QR code detection. These include:

    Contrast enhancement
    Adaptive thresholding
    Hough transform
    Convolutional neural networks (CNNs)

I also used existing libraries such as OpenCV, ZXing, and ZBar to implement my approach.
## My Approach

My approach consists of the following steps:

    Load the image of the QR code
    Preprocess the image by applying operations such as resizing, contrast enhancement, adaptive thresholding, and grayscale conversion
    Detect the QR code in the preprocessed image using a QR code detection algorithm Hough transform
    Use the Zbar library to decode the QR code to extract the information it contains into a link. 

## Datasets

I did not use any additonal data sets outside of the ones built into the Zbar library. 

## Discussion

During the development of my QR code image reader, I encountered several challenges such as finding the optimal parameters for preprocessing and detection algorithms, handling various types of QR codes, and dealing with noise in the input images. If I kept working on the project, I would explore more advanced techniques such as deep learning-based approaches to improve the accuracy and robustness of my approach. I would also try to implement a qr code creation app in order to make it more robust for any person to do either with the one app. My approach differs from others in that I used a combination of various image preprocessing algorithms and QR code detection and decoding algorithms to accurately detect and decode QR codes from images. This approach was beneficial because it allowed me to achieve high accuracy and speed with relatively simple algorithms.
## Demo

I provide a live demo of my QR code image reader, where users can upload an image of a QR code and get the decoded information displayed on the screen.
