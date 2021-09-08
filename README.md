# Inception-V3-Keras


### Implementation of Inception V3 convolutional neural network

The model itself is made up of symmetric and asymmetric building blocks, including convolutions, average pooling, max pooling, concats, dropouts, and fully connected layers. Batchnorm is used extensively throughout the model and applied to activation inputs. Loss is computed via Softmax

![Screenshot 2021-09-08 194906](https://user-images.githubusercontent.com/62859032/132559230-c0950d92-1bcd-4012-97bf-f9c0782758d3.png)

### Model Structure 

It consists of 3 main building blocks
  - Module A
  - Module B 
  - Module C
  
 and 2 different Grid Size Reduction Blocks.
 
 **Architecture**
  - Stem
  - 3x Module A
  - Grid Size Reduction
  - 5x Module B
  - Grid Size Reduction
  - 2x Module C
  - Global Average Pool layer
