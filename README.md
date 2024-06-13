This repository contains the implementation and research findings of a project aimed at recognizing the Irish Sign Language (ISL) alphabet using Motion History Images (MHIs) and Convolutional Neural Networks (CNNs). The project addresses the need for improved communication tools for the deaf and hard-of-hearing community by leveraging state-of-the-art deep learning techniques.

Overview
The objective of this research is to enhance the recognition of Irish Sign Language fingerspelling through computational processing. This repository includes the following key components:

Dataset: Utilization of the Irish Sign Language Hand Shape (ISL-HS) dataset, which includes both static and dynamic gestures representing the ISL alphabet.
Feature Extraction: Conversion of video frames into Motion History Images (MHIs) to capture the dynamic aspects of sign language gestures.
Data Augmentation: Application of various augmentation techniques to expand the dataset and improve model robustness.
CNN Architectures: Evaluation of multiple CNN models, including ResNet, Xception, Densenet, and Inception, to identify the most effective architectures for ISL recognition.
Experimental Results: Detailed results demonstrating the accuracy and performance of each CNN model on the augmented MHI dataset.
Methodology
Data Preprocessing: Conversion of the ISL-HS dataset into MHIs using custom Python scripts and OpenCV for capturing temporal motion information.
Data Augmentation: Implementation of augmentation techniques such as Gaussian noise, affine transformations, and scaling to enhance the dataset's diversity.
Model Training: Training various CNN architectures on the augmented dataset using TensorFlow and Keras, with fine-tuning to optimize model performance.
Evaluation Metrics: Assessment of models based on accuracy, precision, recall, and F1-Score to determine their effectiveness in recognizing ISL fingerspelling.
Results
The research highlights that Densenet architectures achieved the highest accuracy rates, with Densenet 121 reaching up to 90.38%. Other CNN models also showed promising results, demonstrating the potential of using MHIs combined with CNNs for sign language recognition.

Significance
This project contributes to the development of accessible communication technologies for the ISL community by providing a robust computational framework for sign language recognition. The methodologies and findings outlined in this repository aim to address the lack of communicative accessibility and foster inclusion for the deaf and hard-of-hearing community in Ireland.

Future Work
Future research will explore more complex challenges such as automated sign language annotation and the development of real-time recognition systems to further enhance the accessibility and usability of these technologies.
