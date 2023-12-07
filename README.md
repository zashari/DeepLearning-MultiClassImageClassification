# Multi-class Image Classification on Urban Visual Pollution

### Introduction

The project aims to evaluate the effectiveness of two prominent neural network architectures, Convolutional Neural Networks (CNN) and Residual Networks (ResNet), in the realm of multi-class image classification. The primary objective is to identify which architecture yields higher accuracy in correctly predicting image classes. 

### Background

The field of image classification has witnessed significant advancements with the introduction of deep learning techniques, particularly CNNs and ResNets. CNNs are renowned for their proficiency in feature extraction and pattern recognition within images, making them a staple in image classification tasks. ResNets, on the other hand, are a type of CNNs that incorporate residual connections to combat the problem of vanishing gradients, allowing for the training of much deeper networks. This project aims to compare these architectures in a practical setting to discern their performance in multi-class image classification.

### Methodology and Experimentation

The project involved several key steps:

1. **Data Preparation and Exploration**: The train and test datasets were loaded, and the distribution of classes was visualized. Each class in the training dataset was explored with sample images.

2. **Model Development**: Multiple models were developed and tuned:
   - Initial models were built using CNN architecture with variations in kernel size and learning rate.
   - Tuning involved adjusting kernel sizes, activation functions, and learning rates.
   - ResNet architecture was also employed by adding residual connections to the CNN layers.

3. **Model Training and Evaluation**: Each model was trained on the training dataset, and its performance was evaluated based on accuracy on the validation set.

### Results

- The CNN models demonstrated varying degrees of accuracy, with some tunings performing better than others. However, none of the CNN-based models could surpass an accuracy threshold significantly.
- The implementation of the ResNet architecture yielded a notable improvement in accuracy. The final model achieved an accuracy of **74.3%**, outperforming all the CNN-based models.
- This superior performance of ResNet can be attributed to its ability to train deeper networks more effectively, thanks to its residual connections that mitigate the vanishing gradient problem.

### Conclusion

The experimental results underscore the effectiveness of ResNet over traditional CNN architectures in multi-class image classification tasks. The ability of ResNet to train deeper networks without losing the gradient information gives it a substantial edge in extracting nuanced features from images, leading to more accurate classifications. This finding has significant implications for future image classification projects, suggesting a preference for ResNet in scenarios where model complexity and depth are key factors for success.
