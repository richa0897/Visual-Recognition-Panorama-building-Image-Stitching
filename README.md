# Visual-Recognition-Panorama-building-Image-Stitching

This task requires us to stitch images together to create a panoramic image. Panoramic photography is a technique that combines multiple images from the same rotating camera to form a single, wide photo. This process of combining multiple photos to produce a panorama is called image stitching.

##Overview of approach

• Detect key points and descriptors 
• Detect a set of matching points that is present in both images i.e. in the overlapping area 
• Apply the RANSAC method to improve the matching process detection 
• Apply perspective transformation on one image using the other image as a reference frame 
• Stitch images together
