# Color Detection 
Colour detection is the process of detecting the name of any color. Simple isn’t it? Well, for humans this is an extremely easy task but for computers, it is not straightforward. Human eyes and brains work together to translate light into color. Light receptors that are present in our eyes transmit the signal to the brain. Our brain then recognizes the color. Since childhood, we have mapped certain lights with their color names.

# Color-Detection-OpenCV
An application through which you can automatically get the name of the color by clicking on them.

# Colors Dataset
Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255. So in how many ways we can define a color? The answer is 256*256*256 = 16,581,375. There are approximately 16.5 million different ways to represent a color. In our dataset, we need to map each color’s values with their corresponding names. But don’t worry, we don’t need to map all the values. We will be using a dataset that contains RGB values with their corresponding names. 
The colors.csv file includes 865 color names along with their RGB and hex values.

# Project Description 
Color_detection.py – main source code of the project.
timesquare2.jpg – sample image for experimenting.
Colors.csv – a file that contains our dataset.

some of functions used in this project:

 pd.read_csv():
 reads the CSV file and loads it into the pandas DataFrame. We have assigned each column with a name for easy accessing.
 draw_function():
 It will calculate the rgb values of the pixel which we double click. The function parameters have the event name, (x,y) coordinates of the mouse position, etc. In the function, we check if the event is double-clicked then we calculate and set the r,g,b values along with x,y positions of the mouse.
cv2.imshow() is used to draw the image on the window. 
cv2.rectangle and cv2.putText() functions: When the user double clicks the window, it will draw a rectangle and get the color name to draw text on the window.

# Prerequisites
-> OpenCV

-> Pandas

note : you can install these libraries by running the command mentioned below in cmd.

pip install opencv-python numpy pandas


I would Highly Appreciate if you Star this repository.

Code by rimmelasghar with ❤
