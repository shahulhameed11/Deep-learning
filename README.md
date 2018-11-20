Name: Sohail Shahul Hameed
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
