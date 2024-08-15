# Deepfake Detection with Meso4

Deepfakes are synthetic media, such as images and videos, generated using deep neural networks. These forgeries are designed to be almost indistinguishable from authentic media, posing significant challenges in media authentication.

This project focuses on detecting deepfakes using the Meso4 model, a compact yet effective neural network architecture specifically engineered for facial forgery detection. The Meso4 model was trained on deepfake datasets, enabling it to identify subtle inconsistencies that are often imperceptible to the human eye.

## Project Overview

The goal of this project is to leverage the Meso4 architecture to detect deepfake content. The Meso4 model was chosen for its balance between accuracy and computational efficiency, making it suitable for practical applications in real-world scenarios.

Key aspects of this project include:
- **Model Architecture**: Meso4 is a compact convolutional neural network (CNN) designed to detect facial forgeries in videos and images. Its architecture allows for effective detection while maintaining a lightweight structure suitable for various platforms.
- **Training and Testing**: The Meso4 model was fine-tuned and tested on deepfake datasets to achieve optimal performance. Through hyperparameter tuning and the use of pre-trained weights, the model achieved a validation accuracy of 88.9% and a test accuracy of 94.43%.
- **Application**: This project demonstrates how the Meso4 model can be integrated into systems for detecting deepfake content, providing a foundation for further exploration and improvement in media authentication technologies.

## Features

- **Deepfake Detection**: The core functionality of the project is detecting deepfakes using the Meso4 model.
- **Pre-Trained Weights**: The model utilizes pre-trained weights, which significantly improve detection accuracy and reduce training time.
- **Hyperparameter Tuning**: Extensive hyperparameter tuning was conducted to optimize the model's performance, resulting in a validation accuracy of 88.9% and a test accuracy of 94.43%.
- **Real-World Application**: The project showcases the practical application of deepfake detection technology, highlighting the model's effectiveness in identifying forgeries in various media types.

## Dataset

The Meso4 model was trained and tested on a deepfake dataset. You can use your dataset to further fine-tune the model or evaluate its performance on different types of media.

## Resources

    •    Paper:  MesoNet: a Compact Facial Video Forgery Detection Network
    •    Paper's Link: https://arxiv.org/abs/1809.00888
    •    Original MesoNet GitHub Repository: https://github.com/DariusAf/MesoNet
    
## Conclusion

This deepfake detection project using the Meso4 model provides a robust framework for identifying synthetic media. It serves as a valuable tool for anyone interested in exploring or implementing deepfake detection technologies. The project lays the groundwork for further enhancements, potentially improving the accuracy and applicability of deepfake detection in various fields.
