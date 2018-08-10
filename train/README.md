# Tutorials (Computer Vision)

## Introduction

Welcome to the labs.earth collaborative laboratory tutorials on machine learning. 

The computer vision (CV) tutorials will start with the basics and progress to advanced real world applications. The tutorials go beyond explaining the code and steps, to include the answers to the anticipated what and why questions.

## The First Steps in using Gap for Computer Vision (CV)

The first step in using Gap for machine learning (ML) of computer vision (CV) is learning to classify a single object in an image.
Is it a dog, a cat, what digit is it, what sign language digit is it, etc...

To do single object classification, depending on the images, one will use either a artificial neural network 
([ANN](https://github.com/andrewferlitsch/Training/blob/master/AITraining/Fundamentals/Machine%20Learning/ML%20Neural%20Networks.pptx)) 
or a convolutional neural network ([CNN](https://github.com/andrewferlitsch/Training/blob/master/AITraining/Fundamentals/Machine%20Learning/ML%20Convolutional%20Neural%20Networks.pptx)).

In either case, the raw pixel data is not directly inputted into a neural network. Instead, it has to be prepared into machine learning (ML) ready data. How it is prepared/transformed is dependent on the image source, the type and configuration of the
neural network, and the target application.

Images can come from a variety of sources, such as by your cell phone, images found on the Internet, a facsimile image (FAX), a frame from a video stream, a digitized dental x-ray, electron microscopy, etc. Images go from very basic like 1-bit BW single channel (color plane) images, to 8-bit gray scale single channel, to 8-bit color three channel (RGB), to 8-bit color four channel (+alpha channel), to 16-bit high tone (CMYK), to stereoscopic images (3D), and other 3D image representations.

Before the advent of machine learning with computer vision and today's modern ML/CV frameworks, working with and building real world applications was oncee the exclusive domain of imaging scientists.
