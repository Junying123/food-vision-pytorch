# Food Vision Project Overview
This project, leveraging PyTorch, applies deep learning models for image classification of food items, focusing on three classes: pizza, steak, and sushi. Starting with a baseline model using TinyVGG on 10% of the Food101 dataset, the project evolved to incorporate transfer learning with EfficientNet models, improving accuracy and confidence in predictions.

Experimentation and Model Evolution
Initial Setup:
Base model: TinyVGG.
Dataset: 10% of Food101, classes limited to pizza, steak, sushi.
Transfer Learning Enhancements:
Model: EfficientNet B0, with 20% dropout, trained on 10% dataset.
Improved results with EfficientNet B2 on 20% dataset, extending training to 10 epochs.
Modular Implementation:
Codebase modularized for reusability and maintenance (Refer to project directory structure).
Scripts include train.py, predict.py, model_builder.py, and utilities for data setup and handling.
Experimental Tracking:
Utilized TensorBoard for tracking and comparing model performance across different setups.
Best performance achieved with EfficientNet B2, training on 20% of the dataset over 10 epochs, achieving over 80% probability in class predictions.
Deployment and Demonstration:
Chose EfficientNet B2 for deployment due to superior prediction speed, despite Vision Transformer (ViT) showing high accuracy.
Developed a Gradio web interface for real-time predictions of the three classes, deployed as "Food Vision Mini" on Hugging Face Spaces.
Expanded to "Food Vision Big", deploying a model capable of predicting 100 classes from the complete Food101 dataset, also using EfficientNet B2 and available on Hugging Face Spaces.
Usage
Interactive demos available at:

Food Vision Mini: [Link to Gradio app]
Food Vision Big: [Link to Hugging Face Space]

#Food-Vision-Pytorch

##Food-Vision-Pytorch
Model Deployment

Gareth0320/foodvision_big : https://huggingface.co/spaces/Gareth0320/foodvision_big

Gareth0320/foodvision_mini : https://huggingface.co/spaces/Gareth0320/foodvision_mini 

![Screenshot 2024-04-10 041006](https://github.com/Junying123/food-vision-pytorch/assets/92530725/b2b854d1-e41f-4ee8-b568-c050bd2cb8a1)

![Screenshot 2024-04-10 041454](https://github.com/Junying123/food-vision-pytorch/assets/92530725/1972c4e6-267b-46e9-be15-6a68f595f32a)

![Screenshot 2024-04-10 041057](https://github.com/Junying123/food-vision-pytorch/assets/92530725/c4a7e8a3-3984-428a-bbc4-04842ace9352)
