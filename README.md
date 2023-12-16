
# End-to-End Object Detection with DETR

### A basic object detection implementation of the DETR (DEtection TRansformers) model may be found in this repository. DETR is a transformer-based approach that does not require complicated anchor box techniques for end-to-end object detection.

# Model Overview
### The DETR model in this implementation is a demonstration version with the following characteristics:

### Backbone: ResNet-50
### Positional Encoding: Learned positional encoding instead of sine positional encoding
### Positional Encoding Placement: Passed at input instead of attention
### Bounding Box Predictor: Fully connected (fc) layer instead of a multi-layer perceptron (MLP)
### Performance: Achieves approximately 40 AP on COCO val5k and runs at around 28 FPS 

## Installation

### install jupyter notebook
### install torch torchvision 
### install tensorflow

# Usage

### install the neccessary things on the device and run the AIDI_Final_term_project.ipynb 

# Customization 

### Additional data augmentation techniques have been implemented in this project to improve object detection. The function of transformation

### By incorporating variations in scale, orientation, and colour, these augmentations seek to increase the robustness of the model. Please feel free to modify the transform function further to include more augmentations or change the parameters to suit your needs.

### Better generalisation and performance might result from experimenting with various data augmentation techniques, particularly when working with heterogeneous datasets or difficult environmental conditions. Make sure to thoroughly assess and evaluate the effects of these modifications before making any changes.


```python

```
