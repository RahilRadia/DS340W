# ADD-Net
Alzheimer’s Disease (AD) is a neurological brain disorder marked by dementia and neurological dysfunction that affects memory, behavioral patterns, and reasoning. Alzheimer’s disease is an incurable disease that primarily affects people over the age of 40. Presently, Alzheimer’s disease is diagnosed through a manual evaluation of a patient’s MRI scan and neuro-psychological examinations. Deep Learning (DL), a type of Artificial Intelligence (AI), has pioneered new approaches to automate medical image diagnosis. The goal of this study is to create a reliable and efficient approach for classifying AD using MRI by applying the deep Convolutional Neural Network (CNN). In this paper, we propose a new CNN architecture for detecting AD with relatively few parameters and the proposed solution is ideal for training a smaller dataset. This proposed model successfully distinguishes the early stages of Alzheimer’s disease and shows class activation maps as a heat map on the brain. The proposed Alzheimer’s Disease Detection Network (ADD-Net) is built from scratch to precisely classify the stages of AD by decreasing parameters and calculation costs. The Kaggle MRI image dataset has a significant class imbalance problem and we exploited a synthetic oversampling technique to evenly distribute the image among the classes to prevent the problem of class imbalance. The proposed ADD-Net is extensively evaluated against DenseNet169, VGG19, and InceptionResNet V2 using precision, recall, F1-score, Area Under the Curve (AUC), and loss. The ADD-Net achieved the following values for evaluation metrics: 98.63%, 99.76%, 98.61%, 98.63%, 98.58%, and 0.0549 for accuracy, AUC , F1-score, precision, recall, and loss, respectively. From the simulation results, it is noted that the proposed ADD-Net outperforms other state-of-the-art models in all the evaluation metrics.