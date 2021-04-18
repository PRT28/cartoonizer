# cartoonizer
 
 It is a python script which converts normal images to cartoon styled images
 
 ![Image](https://github.com/PRT28/cartoonizer/blob/main/Stack.jpg)

 1. Left Image is normal 
 2. Right Image is the converted image using script
 
## Steps used in converting the image
 1. Apply a bilateral filter to reduce the colour palette.
 2. Convert the image to gray scale.
 3. apply a median blur to reduce image noise in the grayscaled image.
 4. Create an edge mask from grayscale image using adaptive threshold.
 5. Combine the color image and edge mask.
