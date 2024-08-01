# DDD_VGG16
# Distracted Driver Detection using Modified VGG-16 Architecture

This project focuses on detecting distracted driving behaviors, a significant cause of road accidents globally. We propose a modified VGG-16 Convolutional Neural Network (CNN) architecture to classify driver behaviors into various categories, such as safe driving, phone usage, adjusting the radio, and more. The modified model aims to reduce computational complexity while maintaining high accuracy, making it suitable for real-time applications in vehicles with limited computing power.

## Key Features:
- **Dataset**: Utilizes a dataset comprising 17,308 images categorized into 10 classes of driver behavior.
- **Architecture**: A simplified VGG-16 model with only 15M parameters, incorporating regularization techniques and LeakyReLU activation function for improved generalization.
- **Performance**: Achieves a detection accuracy of 96.31% with a significant reduction in parameters, making it efficient for deployment in resource-constrained environments.
- **Experimentation**: Includes a comparison with the original VGG-16 model and regularized versions, highlighting the advantages of the modified architecture.

## Research Objective:
To develop an efficient and accurate model for distracted driver detection that can be practically implemented in real-time systems.

## Limitations:
The model processes the entire image frame, which may include irrelevant features, leading to potential inefficiencies. Future work could focus on optimizing the model to emphasize local features of interest, further reducing computational costs.
