---
title: "Computer Vision Expression Detection and Classification"
excerpt: "A custom CNN to detect and classify expressions"
project_type: college 
header:
  teaser: /assets/images/seniorproj-cpp/teaser.png
  overlay_image: /assets/images/seniorproj-cpp/overlay.png
  overlay_filter: 0.3
gallery:
  - url: /assets/images/seniorproj-cpp/photo1.png
    image_path: /assets/images/seniorproj-cpp/photo1.png
    alt: "photo 1"
  - url: /assets/images/seniorproj-cpp/photo2.png
    image_path: /assets/images/seniorproj-cpp/photo2.png
    alt: "photo 2"
  - url: /assets/images/seniorproj-cpp/photo3.png
    image_path: /assets/images/seniorproj-cpp/photo3.png
    alt: "photo 3"
---

## Overview
This was my senior project from college, developed between 2019-2020. The Github repo is available [here](https://github.com/Reconfigurable-Computing-CalPoly-Pomona/Emotional-Response-Animatronic). The presentation, showcasing technical details, is linked below.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    src="https://www.youtube.com/embed/V8JK8axZZhU"
    title="YouTube video player" frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
  </iframe>
</div>

The Expression Detector is a computer vision system designed to detect the presence of facial detection systems, generate a system of facial landmarks, and pass it to a custom Convolutional Neural Network (CNN), in order to classify the emotion of expression. The expression data would then be passed to a small animatronic system, which would respond differently based on the detected emotion.

The system acquired facial data using the *dlib* library to detect expression presence, and the resulting plot of facial landmarks was passed to the CNN. The CNN's evaluation was then passed over a data bus to the microcontroller which drove the animatronic circuitry. Each step of the process was driven by Python.

I was responsible for all aspects of the neural network's training and execution, including the hardware that powered the model. I trained the model on the fer2013 facial dataset, using a model structure similar to VGG16. The training was accomplished via Tensorflow and Keras, in a Python environment. The model was converted into the TFLite execution format, and run on a Raspberry Pi Zero W, for smaller power consumption and physical footprint.

## Photos
{% include gallery caption="Photos of the project." %}

## Contributions
- Research and development of CNN
- Implementation of full computer vision pipeline
    - Image detection, feature extraction, classification via CNN