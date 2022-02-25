# opencv

## Convert Image to a Pencil Sketch using Python

This is going to be interesting. We will be writing the code step by step with the explanation.

We will use the OpenCV library for this project. Install it using pip install opencv-python command.

Step 1: Find an image that you want to convert to a pencil sketch.

We are going to use a dog image. You can choose whatever you want.

Step 2: Read the image in RBG format and then convert it to a grayscale image. Now, the image is turned into a classic black and white photo.

Step 3: Invert the grayscale image also called the negative image, this will be our inverted grayscale image. Inversion is basically used to enhance details.

Step 4: Finally create the pencil sketch by mixing the grayscale image with the inverted blurry image. This is done by dividing the grayscale image by the inverted blurry image.

