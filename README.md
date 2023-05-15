# Virtual-CT
Final Project

Due: Sat 12/10/22 11:59 PM

We implemented a virtual CT (specifically part of the colon) to detect abnormalities, such as benign tumor (polyps) and/or cancerous tumor; the algorithms were developed using python. Furthermore, the algorithm would essentially imitate the performance of a CT scanner in various orientations. We created a system that collects numerous projections along different orientations upon image slicing. It would consist of our code slicing the phantom image diagonally, horizontally, and vertically.

Instructions on how to run the code:
Press the run button.
Enter a x value for the tumor to be placed (100 < x < 150) any number not between the tumor will not be inside the colon.
Enter a y value for the tumor to be placed (100 < y < 150) any number not between the tumor will not be inside the colon.
Enter a slice type, "vertical", "horizontal", or "diagonal" anything else will be an invalid slice type.
Enter the number of slices, a integer value 1-255 anything else will be too few cuts or too many cuts.
Process while running the code:
Firstly, will display an image of the orginal phantom with the colon.
Secondly, then will ask for standard input and standard output (STDIN).
Thirdly, it will then create amount of the images wanted to be sliced.
Fourthly, it will display the image that have been cut and put it back together.
Lastly, close the first pop window then close the result image window after the ouput images will display.
Notes:
All of the code is in "main.py" file.
Images can be found inside the "output" folder, original.png is before tumor just colon, phantom.png is the one with a tumor inside the colon.
For the slice type ONLY ONE can be run at once.
Close pop-up windows after viewing.
When ran multiply times it will override the previous output images making it into the recent ran output images.
For instance, if the method is run again with a sliced image quantity of 3, as opposed to the previous iteration's 6 output files, the first 3 output files will be overwritten and the remaining 3 will be left alone.
