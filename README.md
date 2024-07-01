#Grayscaling

Grayscaling is the process of converting an image from other color spaces e.g. RGB, CMYK, HSV, etc. to shades of gray. It varies between complete black and complete white.

#Importance of grayscaling 

Dimension reduction: For example, In RGB images there are three color channels and three dimensions while grayscale images are single-dimensional.
Reduces model complexity: Consider training neural articles on RGB images of 10x10x3 pixels. The input layer will have 300 input nodes. On the other hand, the same neural network will need only 100 input nodes for grayscale images.
For other algorithms to work: Many algorithms are customized to work only on grayscale images e.g. Canny edge detection function pre-implemented in the OpenCV library works on Grayscale images only.

#Sample Image

![download](https://github.com/RidhiSood22/Image-processing---GrayScale-/assets/142926361/c258d946-5abf-4122-b441-e29f2497f5f7)
