# Image-processing-text-extraction
extract text from images with the help of matlab program.

The input image is first read and then converted into gray scale. Followed by region proposals which is decided by the pixel intensity difference. Bounding box is formed over the characters and then individual characters are extracted.

The first step is to read the input image and display the input image. Then the colored image is converted from the colour(RGB) image to a Gray scale. Then the gray image is converted from the Gray scale image to binary image. To remove all Boundary connected Objects which are less than 30 pixels.
Measure the properties of the Image regions and Plot the bounding Box. Finally Letter segmentation is done and indvidual characters are extracted.

