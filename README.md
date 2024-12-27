# handwritten-text-generator
Project Overview
This project involves the development of a conditional diffusion model capable of generating handwritten text images from input text. The model was implemented as part of a course project for EE698R under the guidance of Prof. Vipul Arora, IIT Kanpur.

Features

Conditional Diffusion Model: Generates high-quality handwritten text images based on user input.
U-Net Architecture: Core model architecture, enhanced with performance optimization techniques.

Classifier-Free Guidance: Conditions the model on input English letters for improved responsiveness.
Image Pre-processing with OpenCV: Ensures clean and accurate output by merging generated images in sequence.
Deployed on Hugging Face: Interactive, web-based usage of the model.

Flask API: Provides seamless interaction and integration with external applications.

Implementation Highlights

Model Architecture: Built the conditional diffusion model using U-Net architecture for high performance and flexibility.

Performance Optimization: Applied techniques like exponential moving average (EMA) for model stability and accuracy.

Text-to-Image Conditioning: Integrated classifier-free guidance to adapt the model to varying text inputs.

Image Processing: Used OpenCV to preprocess and merge output images into a coherent final image.
