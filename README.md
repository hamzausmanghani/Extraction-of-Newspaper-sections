# Extraction-of-Newspaper-sections

## ABOUT

-It is a digital image processing project which extract all sections present in newspaper. <br>
-Data preprocessing and annotation for the training of model. <br>
-Used yolov4 to achieve the output.


## ALTERNATIVE

-The output can also be achieved by performing following steps: <br>
1- Convert image to grayscale. <br>
2- Apply thresholding/canny filter. <br>
3- Apply 2D filter with kernal which highlight only horizontal and vertical lines. <br>
4- Use houghline for line detection. Contours with specified area/height/width will also work. <br>
5- Get region of each section by calculating intersections. <br>

But this method is only applicable for images which are static.
