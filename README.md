# Face Recognition of Children with Martin-Bell syndrome using enhancing dataset techniques
This repository contains the final project for the module "AI for Visual Perception in HCI & HRI" of Electives in AI (Master in Artifical Intelligence and Robotics, Sapienza University, Rome) held by prof. Christian Napoli during the accademic year 2020/2021. 

## Table of Contents
- [Face Recognition of Children with Martin-Bell syndrome using enhancing dataset techniques](#Face-Recognition-of-Children-with-Martin-Bell-syndrome-using-enhancing-dataset-techniques)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)

## Description
One of the numerous applications of modern face recognition techniques is the diagnosis of rare dysmorphic syndromes, characterized by abnormal facial features, among other factors. While this problem shares some characteristics with other image classification tasks, it presents peculiar challenges, such as samples scarcity and the need to recognize specific patterns  in facial features. This report describes how a combination of various techniques, specifically Graph Convolutional Neural Networks (GCNNs) and image augmentation, can be applied to address these challenges. Furthermore, the high performance of the proposed method is demonstrated through a series of tests conducted on a custom dataset designed specifically for recognizing children with X-Fragile Syndrome (FXS). The experiments highlight that the combination of graph CNNs, feature attention, and data augmentation with the classic VGG model surpasses the baseline in terms of accuracy, specificity and sensitivity.

### Dataset
A fundamental step of the project was to construct the dataset because: (i) being FXS a rare disease, there are not many publicly available frontal images of children online; (ii) dealing with children adds difficulty in acquiring public images due to specific privacy laws for minors; (iii) often, the available photos are low-resolution, nonfrontal, or contain elements obstructing the face. 

The methods employed to increase the dataset’s size can be divided into three categories: (i) data augmentation via image transformation, (ii) image generation, and (iii) face segmentation and landmarks attention. 
The datasets created with the different methods are store the folder [dataset](datasets). 
### Generative Adversarial Network
### Facial feature extraction
### Gestalt algorithm
### CNN model
### Results
### References

## Installation
## Usage
## Contributing
## License
## Acknowledgements

