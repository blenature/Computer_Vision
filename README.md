This is an image-processing assignment

The task is to apply a suitable geometric transformation to Figure 1 (download it from https://www.cse.uoi.gr/~sfikas/teaching/assignment2_3/granma.jpg), 
to form an image of size 1000 × 1000 such that it contains only the newspaper, and the newspaper with its sides coinciding with the boundaries of the picture.
The user is asked for the points corresponding to the four corners of the object. 
The image is desplayed, and the user must click on the corners of the newspaper (use of OpenCV's setMouseCallBack and waitKey functions).
To apply the transformation, you can also use OpenCV's "ready-made" warpPerspective function. 
Do not use anything ready-made except for basic operations and linear algebra functions, is in the calculation of the 3 × 3 matrix corresponding to the projective transformation (or 'perspective transform' or 'homography') that must be applied in order to obtain the desired result. 
This table has 9 elements, from of which 8 correspond to variable parameters. 
