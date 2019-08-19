# Panaroma-Stitcher
Stitches Multiple Images together to form a panaroma image.
Program created for CS 534 at UW Madison
## Working:
### Compute Feature Points
The program computes keypoints using SIFT feature detection.
### Match feature points and Compute Homographies
Correspondences between keypoints are detected.\
The incorrect matches are removed using the RANSAC algorithm.\
Calculate homographies using the remaining keypoint matches.
### Combine the images
Wrap the images using the calculated homographies.\
Blend the images together.
