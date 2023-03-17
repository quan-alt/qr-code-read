QR Code Image Reader using Edge Detection
Problem Description

QR codes are commonly used in various applications, such as advertising, payment, and information sharing. However, reading QR codes from images can be challenging due to the complex patterns and noise in the images. In this project, we aim to develop a QR code image reader using edge detection to accurately detect and decode QR codes from images.
Previous Work

We build upon the techniques covered in class, including grayscale conversion, edge detection, and image resizing. We also use existing libraries such as OpenCV, ZXing, and ZBar to implement our approach.
Our Approach

Our approach consists of the following steps:

    Load the image of the QR code
    Preprocess the image by applying operations such as resizing, thresholding, blurring, or grayscale conversion
    Detect the QR code in the preprocessed image using a QR code detection algorithm
    Decode the QR code to extract the information it contains

Datasets

We use several datasets to test and evaluate our approach, including synthetic and real-world images of QR codes with varying levels of complexity and noise.
Results

We evaluate the performance of our QR code image reader using various metrics, including accuracy, speed, and robustness to noise. Our results show that our approach can accurately detect and decode QR codes from images with high accuracy and speed.
Discussion

During the development of our QR code image reader, we encountered several challenges, such as finding the optimal parameters for preprocessing and detection algorithms, handling various types of QR codes, and dealing with noise in the input images. If we kept working on the project, we would explore more advanced techniques such as deep learning-based approaches to improve the accuracy and robustness of our approach. Our approach differs from others in that we use a combination of grayscale conversion, edge detection, and QR code detection and decoding algorithms to accurately detect and decode QR codes from images. This approach was beneficial because it allowed us to achieve high accuracy and speed with relatively simple algorithms.
Demo

We provide a live demo of our QR code image reader, where users can upload an image of a QR code and get the decoded information displayed on the screen.
References

We provide a list of references used in the development of our QR code image reader, including academic papers, code repositories, and online tutorials.
