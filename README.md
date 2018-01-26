# Viola-Jones Face detection example

This is an example of face detection to show how to do real-time image processing using OpenCV.

## Prerequisite

Python 3.5 and OpenCV 3.

1. Download and install Anaconda3-4.2 (64bit version, python 3.5) from https://repo.continuum.io/archive/. (Note: Not the latest version)
1. Open Anaconda Prompt as administrator.
1. Install OpenCV.
   
   ```
   > conda install -c menpo opencv3
   ```

## How to use

1. Run the example code.

   ```
   > python testfacedetect.py haarcascade_frontalface_default.xml
   ```

1. Press 'q' to quit the program.

You can try different object detection using xml available under `Anaconda3/pkgs/opencv3-<version>/Library/etc/haarcascades`.

## Note

Reference: https://en.wikipedia.org/wiki/Viola%E2%80%93Jones_object_detection_framework

Please also see the example of [planar object detection using feature point matching](https://github.com/hkawash/feature-matching-example), which uses different method for object detection.


