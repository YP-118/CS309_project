# CS309_project

## AI-Generated Anime Figure Detection

This project focuses on developing an efficient system for detecting anime figures within images using advanced object detection techniques. It employs a dual approach utilizing YOLO for object localization and a choice of Convolutional Neural Networks (CNN) or Transformers as the backbone for feature extraction.

**Key Methods:**

- **YOLO (You Only Look Once)**: A real-time object detection algorithm known for its speed and accuracy.
- **Backbone**: Selection between CNNs and Transformers to extract meaningful features from images.

### Project Components

#### Presentation
- [PPT](./CS309.pdf)  
   This PPT might make it easier to understand.

#### Comprehensive Report
- [Report](./CS309_final_project.pdf)  
   An in-depth written analysis of the project, including implementation details, experiment results, and conclusions.

### Dataset Creation
Refer to the _PPT_ for instructions on crafting a custom dataset tailored to anime figure detection.

### Code Implementation

- **YOLO Implementation**
  - [yolov5_anime](https://github.com/zymk9/yolov5_anime)
    
    Note: Minor adjustments are required to get ideal output as discribed in project.

- **Backbone Implementation Tips**
  - Choose a suitable backbone for binary classification (e.g., ResNet, EfficientNet, or a Transformer model).
  - Ensure the model returns a probability score for binary classification tasks.

- **Training Weights**
  - Train your backbone to output probabilities, converting the task into straightforward binary classification.

**For Code Access:**

Should you require further code snippets or have inquiries, please reach out via email to yp118@duke.edu with a reasonable request.
