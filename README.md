Noises-and-Filters-GUIDE
========================

This program can be use to understand how noises and filters interact with 2D and 3D images.
Also, it uses a GUIDE interface and it is a good exemple to know how to create it in MATLAB.
It works in MATLAB for all operating system.

Put all files in .zip in the same directory.

When you run the program, dont forget to remplace "enter value" line for the intensity of noises and 
the configuration of filters before using it.

You can discover or test how noises interact with images.
You can set three noises with different intensity:

_Salt and pepper noise

_Gaussian noise

_Speckle noise


Then you can add filters and set their configuration:

_Median filter for 2D images (gray images)

_Median filter for 3D images (color images) program found here: http://www.biomecardio.com/matlab/medfilt3.html#1

_Average filter

_Gaussian Filter

You can watch their histogram, or understand what's happen in Fourrier transform

And if you want to compare you image with the original image(without noise and filter), use compare 2D and compare 3D.

At the end you can watch the mean square error (MSE) to know which filter is better than others for a typical noise.



