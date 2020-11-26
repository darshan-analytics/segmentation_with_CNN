# segmentation_with_CNN
1. This is to create binary mask for image where 0 is 'background' and 1 is 'person'
2. Through this one can create a filters to the images.
3. Trained U-Net with effcientnet-B0 as backbone and kept decoder type as an 'upsampling'
4. For Learning kept Adam as default.
5. Kept the activation function as softmax to get values from -1 to 1 range.
6. Got accuracy around 97% on validation dataset.
