# Image_Segmentation
U-Net++ Semantic Segmentation Project
This repository contains a Jupyter notebook that demonstrates a U-Net++ based approach to semantic segmentation. The project was developed for the IITG AI Overnight Hackathon 2024 Kaggle competition, focused on accurately segmenting images at the pixel level.

Dataset
The dataset for this project was sourced from the IITG AI Overnight Hackathon 2024 Kaggle competition. In this challenge, participants were tasked with building models that could identify and classify pixel regions in images, promoting innovative approaches in computer vision.

The dataset structure includes:

Train: Original training images.
Labels: Corresponding segmented images with pixel labels and color-coded classes.
Test: Images for evaluating model predictions.
Each training image has an associated labeled mask image, where each pixel color represents a specific class. Additionally, each label has an accompanying JSON file that provides detailed polygonal metadata for accurate segmentation.

Project Structure
Data Preprocessing: Images and masks are resized to 512x512 and normalized. Masks are encoded with specific color mappings to distinguish between classes.
Model: Utilizes the U-Net++ architecture to improve segmentation accuracy by capturing fine details in the image boundaries.
Training: Includes code for model training with checkpoints saved during the process.
Evaluation: Evaluates the model’s performance, achieving approximately 75-80% accuracy.
Prerequisites
Python 3.x
Libraries: numpy, tensorflow or torch, opencv-python, matplotlib , sklearn
GPU recommended for faster training.
