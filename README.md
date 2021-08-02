# Sampling-of-Image
Used different technique of image processing, to convert a 1080p image into (960 × 540) i.e., qHD image and again upsampled this image such, that we lose minimal data
Here I used grey scale image of a zebra.

![download](https://user-images.githubusercontent.com/58924096/127784274-b28461b8-2d74-418a-a12a-47acc187ef68.png)

Steps: - 

1.) Downsampled the original image (f) by dropping alternate pixel along length and breadth and name this as g. 

2.) Upsampled image (g) by using linear interpolation technique from OpenCv library and name this as g_u.

3.) Visualize the differene between f and g_u. 

![download (1)](https://user-images.githubusercontent.com/58924096/127784760-070226ef-0211-4b24-aba5-f31b9f061511.png)

4.) Now, use low pass filter of size (3 x 3). It just smooth the original image (f).

![download (3)](https://user-images.githubusercontent.com/58924096/127785090-594ac9f5-d9bf-401f-b517-df87ad63672c.png)

5.) Observe the difference between actual and the average image. 

![download (4)](https://user-images.githubusercontent.com/58924096/127785826-3f25a507-6962-41a8-a3d0-42cda56f6a9c.png)

Repeated all the above steps for average image and observe that image without using low pass filter gives better result.  
