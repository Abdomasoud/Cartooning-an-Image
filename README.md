# Cartooning-an-Image

First we downscale the image and then apply bilateral filter to get a cartoon flavor. Then again we upscale the image.
Next step is getting a blurred version of the original image. Now, we don’t want the colors to interfere in this process. We only want the blurring of the boundaries. For this, we first convert the image to gray – scale and then we apply the media blur filter.
Next step is to identify the edges in the image and then add this to the previously modified images to get a sketch pen effect. For this first we are using adaptive threshold. You can experiment with other types of threshold techniques also. Because Computer Vision is all about experimenting. In step 5, we compile the final images obtained from the previous steps.
