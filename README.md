# Brain-MRI-Segmentation
# Problem Statement
 Segmentation of Brain MRI images using Deep Learning Techniques.
 



# Dataset
  http://braintumorsegmentation.org/
  
  4D array of MR images in the shape of (240, 240, 155, 4).
The first 3 dimensions are the X, Y, and Z values for each point in the 3D volume, which is commonly called a voxel.
The 4th dimension is the values for 4 different sequences
0: FLAIR: "Fluid Attenuated Inversion Recovery" (FLAIR)
1: T1
2: T1c
3: T2

A 3D array with the shape of (240, 240, 155).
The integer values in this array indicate the "label" for each voxel in the corresponding image files:
0: Background
1: Edema 
2: Non-enhancing tumor
3: Enhancing tumor
Edema ,Non-enhancing tumour , Enhancing tumour are constituents of Glioma(Brain Tumour).

# Methodology
[1] Exploring and Preprocessing of Data

[2] Making CNN(U-Net) Model

[3] Metrics

# Implementation and Results


# References
[1] https://github.com/wiqaaas/youtube/tree/master/Deep_Learning_Using_Tensorflow/Image_Segmentation_using_U-Net

[2] https://www.analyticsvidhya.com/blog/2021/06/introduction-to-skull-stripping-image-segmentation-on-3d-mri-images/#h2_6

[3] https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwi91fbsrJXxAhVeH7cAHSZjC5AQFjAGegQIChAE&url=https%3A%2F%2Fwww.mdpi.com%2F2076-3417%2F9%2F3%2F569%2Fpdf-vor&usg=AOvVaw27QvVMiUr0X3aU3ytxpzHX

[4]https://arxiv.org/pdf/1810.10853.pdf

[5] https://link.springer.com/chapter/10.1007/978-3-030-11726-9_4
