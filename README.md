# Plant Disease Classification using Convolutional Neural Networks: comparison of VGG16 and ResNet50.
The aim is to address critical challenges in agricultural productivity and food security by leveraging advanced deep learning models to identify plant health status accurately.The research explores how Convolutional Neural Networks (CNNs), specifically ResNet50 and VGG16, can accurately identify plant health status from diverse image datasets.

The study focuses on comparing the performance of two pre-trained CNN architectures, VGG16 and ResNet50, on two different datasets with varying complexities and distributions.

## SELECTION OF DATASET
Dataset 1: A combined dataset with 12 types of plant diseases and diverse image features. LINK:https://data.mendeley.com/datasets/hb74ynkjcn/5

Dataset 2: A balanced dataset with 39 types of plant diseases, divided into training (80%), validation (10%), and test (10%) subsets. LINK:https://data.mendeley.com/datasets/tywbtsjrjv/1

## Dataset 1 - 12 types plant leaves,
![0003_0001](https://github.com/user-attachments/assets/7dd1cc9e-af23-41d8-bf8d-459115ef8180)

## Dataset 2 - 39 types plant leaves,
![image (1)](https://github.com/user-attachments/assets/b289c56f-346c-4618-bc42-12992e6a2f8e)

## Experiments Conducted:
Experiment 1:
Both datasets were combined to evaluate the models' performance on a significantly variable dataset. The results highlighted the challenges posed by inconsistencies in image features, with both models underperforming due to the lack of preprocessing and standardization.

Experiment 2:
The datasets were used individually to evaluate model performance under controlled conditions. ResNet50 achieved over 90% accuracy in detecting healthy and diseased samples across 12 plant classes, outperforming VGG16 in precision and robustness.

## Key Findings
ResNet50 demonstrated superior performance compared to VGG16, particularly in identifying plant health across diverse conditions.
The importance of dataset preprocessing and standardization was emphasized for achieving high model accuracy.
Advanced CNN models show significant promise in revolutionizing agricultural practices by enabling precise and automated disease detection.

## Images prediction BY VGG16 from Dataset 1- 12 types
![image](https://github.com/user-attachments/assets/1a148893-eb1e-4790-a2a5-39420a1542a7)

## Images prediction by ResNet50 from Dataset 1 - 12 types
![image](https://github.com/user-attachments/assets/f3de64ef-faf7-4d66-8c4d-1c455c82e3ea)

## Images prediction by VGG16 from Dataset 2 - 39 types
![image](https://github.com/user-attachments/assets/e5512f7a-5207-4b1d-9c76-0dfa690f5628)

## Images prediction by ResNet50 from Dataset 2 - types
![image](https://github.com/user-attachments/assets/d38bc7e1-f16a-486b-ac9b-56f0bcb28d29)

## Technologies Used
- Deep Learning Frameworks: TensorFlow,Keras, ImageNet
- CNN Architectures: ResNet50, VGG16
- Programming Language: Python
- Dataset Source: Mendeley


## Conclusion
This research highlights the significant impact of dataset characteristics and model architecture on the performance of plant disease classification.
Experiment 1: Combining datasets with diverse image features—such as variations in brightness, pixel values, color range, and clarity—resulted in reduced model accuracy. This underscores the challenges posed by inconsistencies in input data.
Experiment 2: ResNet50 demonstrated superior effectiveness, achieving over 90% accuracy across 12 plant leaf classes and excelling in the classification of 39 types of healthy and diseased samples.

The deeper architecture and parameter optimization of ResNet50 enable it to handle complex image datasets more reliably than VGG16. These findings establish ResNet50 as a more robust choice for precise and automated plant disease detection in real-world applications.

## Future Enhancements
- Multilingual treatment recommendations for farmers.
- Integration with affordable camera technologies for widespread accessibility
- Direct connections to agricultural experts for real-time advice and scalability
- Community-Centric Insights, where farmers can share their experiences and learn from each other


