# Depth-Estimation-from-Monocular-Images-using-Deep-Learning

This is an exercise in Depth Estimation using transfer learning implemented in Keras using TensorFlow backend. A DenseNet-169 model with pre-trained weights (trained on ImageNet) is used as the encoder section of a U-net with the decoder section using Conv2dtranspose and some intermediate convoltion layers. The model was trained using NYU Depth V1 database, however, the images were resized to 120x160 (HxW) due to hardware limitations.

## Sample Output

![Sample output](https://user-images.githubusercontent.com/49246680/92951972-daab4180-f47c-11ea-805f-e376e570a0e2.png)

### 3D Reconstruction using above depth map

![3D Point Cloud](https://user-images.githubusercontent.com/49246680/92952066-fadb0080-f47c-11ea-86b5-bf47290ed88f.png)
