Name: Sohail Shahul Hameed
Signzy Assignment Submission Readme file                              13/10/2018
IDE: Spyder IDE
===============================================================
How the code works:

Read input path of the image.
Perform preprocessing like removal of background noise, skewness.
Perform closing morphology and edge detection using canny edge. 
Perform contours on the image.
Save the contours image in the specified output folder.

===============================================================
How to run the code:

First compile all the functions like checkSkew, cannyEdge, getContours, saveOutput, read.

Now, give the input path, where the images are stored, and the output path, to store all the output images.
Example: 
input_path="E:/New folder/input pics"
output_path="E:/New folder/output pics/"

Now, compile by calling the read(input_path, output_path) function.
Example:
read(input_path, output_path)

Go to the specified output folder and view the output images. 

===============================================================
Installation Process:
Below Link is to install opencv:
https://pypi.org/project/opencv-python/
--------------------
Below Link is to install numpy:
https://solarianprogrammer.com/2017/02/25/install-numpy-scipy-matplotlib-python-3-windows/