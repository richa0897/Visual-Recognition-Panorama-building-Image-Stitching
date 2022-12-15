# Visual-Recognition-Panorama-building-Image-Stitching

This task requires us to stitch images together to create a panoramic image. Panoramic photography is a technique that combines multiple images from the same rotating camera to form a single, wide photo. This process of combining multiple photos to produce a panorama is called image stitching.

## Overview of approach

• Detect key points and descriptors

• Detect a set of matching points that is present in both images i.e. in the overlapping area

• Apply the RANSAC method to improve the matching process detection

• Apply perspective transformation on one image using the other image as a reference frame

• Stitch images together


![image](https://user-images.githubusercontent.com/94607222/207853704-60a7915a-2bb3-4686-8dc1-44de949dd661.png)
![image](https://user-images.githubusercontent.com/94607222/207853761-a6bf8d11-8ad0-45a2-b1f9-d334b1570ef7.png)

## Result

![image](https://user-images.githubusercontent.com/94607222/207853888-f283ee8a-2508-45c0-b97b-c81aa9ec0d8f.png)
![image](https://user-images.githubusercontent.com/94607222/207853916-7fb530f9-5e0f-44cb-bf08-bcdaed7d4997.png)

![image](https://user-images.githubusercontent.com/94607222/207853968-6327c8a8-5b36-44d4-b3ac-8375f0b0e3f3.png)

