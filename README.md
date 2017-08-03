# Python-optical-flow-tracking
Using Optical Flow for Detection Motion object. 


#Run
This code tested on OS X with Conda Python 3.6, and OpenCV 3 from conda-forge, but should work on other Operating systems, provided OpenCV 3 is available. 

This code is a fork of https://github.com/sahakorn/Python-optical-flow-tracking, which in turn was based on original code from the OpenCV docs: https://github.com/opencv/opencv/blob/2.4.12/samples/python2/opt_flow.py

Only basic support for OpenCV 3 has been added -- I'm not confident that hsv vis and glitch vis is working as it should be.

Usage:

1. using video path: python optical_flow.py [video source] 
2. using camera: python optical_flow.py 
