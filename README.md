# Cats_VS_Dogs
<div align="center">
  <img src="https://storage.googleapis.com/kaggle-competitions/kaggle/3362/media/woof_meow.jpg">
</div>
A kaggle classification problem where the model classifies the image as a cat or a dog

## Dependencies:
    Python 3.5.x
    PIL
    Pandas
    Numpy
    zipfile
    matplotlib
    TensorFlow
    sklearn
    
## Pipeline
<div align="center">
  <img src="https://github.com/Heba-Atef99/Cats_VS_Dogs/blob/main/cats_vs_dogs__pipeline.jfif">
</div>

Input Layer: It represent input image data. It will reshape image into single diminsion array. Example your image is 64x64 = 4096, it will convert to (4096,1) array.

Conv Layer: This layer will extract features from image.

Pooling Layer: This layerreduce the spatial volume of input image after convolution.

Fully Connected Layer: It connect the network from a layer to another layer.

Output Layer: It is the predicted values layer.

## Transfer Learning
I have applied two different Transfer Learning approaches;

- Feature Extractor
- Fine Tunning



