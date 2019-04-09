# Visualizing-Dominant-Color
Seeing dominant colour in an image using OpenCV.

This project is showing the dominant colours in an image using the OpenCV library.

Datasets - I have done the visualisation of some image data which were take by me on my Camera.

I have run the code using the kaggle kernels in the website kaggle.com.

By default CV2 shows images in BGR format. So, I have converted it to RGB to see the original image.

I have created some functions :- 
RGB2HEX() - To format the color of the image to hex code.
get_image() - Read the image, converts BGR to RGB image, removing white, grey and black color and then returns the image.
get_colors() - It predicts the dominant colors of the image using K-means clustering algoritm.

I have wrote some extra codes for image resizing and for seeing image using color.
