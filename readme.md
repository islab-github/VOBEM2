# VOBEM2: Vision Objects for Beam Management (Version 2)

![](fig4.jpg)

VOBEM2 is a vision dataset specially designed for the evaluation of the multi-view computer vision-aided wireless communicatons (multi-view SVWC) performance in millimeter and THz communication scenarios.
It consists of 210 pairs of RGB and depth images taken from two different views.

For more details of this work, see the paper "Role of Sensing and Computer Vision in 6G Wireless Communications", to appear in IEEE Wireless Communications http://isl.snu.ac.kr/publication.

## Preparation
Please download the VOBEM2 dataset from https://drive.google.com/drive/folders/1XZ0hEmMyXS-gBHSsaUwQ0C9wIue8uruh?usp=sharing.

In VOBEM2, we store the images and corresponding labels in two different folders named ‘image’ and ‘label’, respectively. To be specific, in the ‘image’ folder, there are two subfolders named ‘image_view0’ and ‘image_view1’, where each of which has three subsubfolders named ‘rgb’, ‘depth’, and ‘distance’. The ‘rgb’ subsubfolder contains RGB images, while the ‘depth’ subsubfolder contains corresponding depth images. In the ‘distance’ subsubfolder, the distance to the point in each pixel is included. This information is available in JSON format. On the other hand, the ‘label’ folder provides labels for images in ‘image_view0’ and ‘image_view1’ in TXT format. Each label includes the class information that objects are labeled with and their bounding box coordinates.
