# DASHTOON_Generative_AI

The dashtoon_GAI.ipynb Jupyter File consist of demonstration of the Neural Network Style Transfer 
Description:

This Jupyter notebook demonstrates the implementation of a style transfer algorithm using the pre-trained VGG-19 model based on Convolutional Neural Networks (CNNs). The primary goal is to extract content and style features from input images and generate a new image that combines the content of one image with the artistic style of another.

Key Features:

VGG-19 Pre-trained Model:

The notebook utilizes the VGG-19 model, a powerful deep learning architecture pre-trained on ImageNet. The model is loaded, and intermediate layers are used for feature extraction.
Input Image Paths:

The user is prompted to provide the file paths for two images: a style image (e.g., a painting) and a content image. These images serve as the basis for style transfer.
Content and Style Feature Extraction:

Intermediate layers of the VGG-19 model are employed to extract both content and style features from the provided images. These features play a crucial role in the subsequent style transfer process.
ADAmax Optimizer:

Initially, the notebook uses the ADAmax optimizer for optimization during the style transfer process. ADAmax is known for its efficiency and effectiveness in optimizing deep neural networks.
Optimization Enhancement:

The notebook suggests the potential enhancement of the optimization process by incorporating the L-BFGS optimizer. While L-BFGS is known for producing high-quality results, it is acknowledged that it might require more time and memory resources. Users are provided with the option to experiment with L-BFGS for improved stylized image generation.
Conclusion:

The notebook offers a comprehensive exploration of style transfer using VGG-19, focusing on content and style feature extraction. Users can experiment with different image pairs, optimizer choices, and intermediate layers to achieve varied stylization effects. The flexibility provided allows for both artistic exploration and code optimization based on available computational resources.
Note:

It is recommended to install the required dependencies, such as TensorFlow and PIL, before running the notebook. Additionally, users should be mindful of potential memory constraints when considering the use of the L-BFGS optimizer.
