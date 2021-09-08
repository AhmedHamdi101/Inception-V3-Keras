# Inception-V3-Keras

![Screenshot 2021-09-08 194906](https://user-images.githubusercontent.com/62859032/132559230-c0950d92-1bcd-4012-97bf-f9c0782758d3.png)


### Implementation of Inception V3 convolutional neural network

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
