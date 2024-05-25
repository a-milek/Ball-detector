.. Ball detector documentation master file, created by
   sphinx-quickstart on Sat May 25 12:52:21 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Ball detector's documentation!
=========================================
The program is designed to detect a metal ball appearing in the camera view. 
It is a modified version of the same program used to detect LED color changes, which you can find `here:  <https://a-milek.github.io/portfolio/led_detector.html>`_
A camera connected to an external computer captures live images of the surrounding. These images are then streamed to the computer using Motion, a video monitoring program, which shares the video to a designated HTTP address. 
The program can access the images from the address and analyze them to detect any changes between the current and previous images. 
This allows the program to determine if a ball appeared in the camera view, if  so the user will be notified by it's console output.

.. toctree::
   :maxdepth: 2
   :caption: Contents:



**Indices and tables**
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
