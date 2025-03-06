# k-means-img-compression
An odd way to compress images by using K-means clustering to reduce the number of colors.

The image size of an image after being compressed using this method will depend on the image type (extension) because each image type such as jpg or png have different methods of compressing the images. I will only cover the image size evaluation of png type images only.

Based on the Portable Network Graphics (PNG) Specification [13], if the number of distinct pixel values is 256 or less and the alpha channel is absent then the alternative indexed-colour representation, achieved through an indexing transformation, may be more efficient for encoding.

![png specification](https://www.w3.org/TR/2003/REC-PNG-20031110/png-figures/fig44.png)
