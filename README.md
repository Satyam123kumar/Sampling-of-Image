# Sampling-of-Image
Used different technique of image processing, to convert a 1080p image into (960×540) i.e., qHD image and again upsampled this image such, that we lose minimal data
Here I used grey scale image of a zebra. 
![download](https://user-images.githubusercontent.com/58924096/127784274-b28461b8-2d74-418a-a12a-47acc187ef68.png)

Steps: - 
1.) Downsampled the original image (f) by dropping alternate pixel along length and breadth and name this as g. 
2.) Upsampled image (g) by using linear interpolation technique from OpenCv library and name this as g_u.
3.) Visualize the differene between f and g_u. 
![download (1)](https://user-images.githubusercontent.com/58924096/127784760-070226ef-0211-4b24-aba5-f31b9f061511.png)

4.) 
Applied a Lowpassfilter on original image. And repeated the above process.
Compared and Analyse which technique gives better result by using scikit-imagel ibrary.
