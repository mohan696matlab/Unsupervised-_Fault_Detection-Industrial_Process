## Introduction
Welcome to our tutorial series on unsupervised machine learning techniques for fault detection using the Tennessee Eastman Process dataset. In this playlist, we will cover various unsupervised machine learning techniques for detecting anomalies and faults in the process. We will start with statistical methods and progress to more complex techniques such as PCA reconstruction, autoencoder-based reconstruction, ensemble learning, CNN, LSTM-based next-step prediction, Transformer-based anomaly detection, and XAI methods on autoencoders. By the end of this tutorial series, you will have a comprehensive understanding of how unsupervised machine learning can be used to detect faults in complex industrial processes. This repository is a part of [youtube playlist](https://youtube.com/playlist?list=PLoSULBSCtoffIldbr898SDp5gIqo8XL-t).

![alt text](/images/Youtube_thumbnail.png)

## Requirements

- Python 3
- pyreadr
- matplotlib
- seaborn
- numpy
- pandas
- scikit-learn
- tensorflow
- keras


## Usage/Examples

Video 1: [Statistical Method for Anomaly Detection](https://www.youtube.com/watch?v=iCTU-IZ6rPQ&list=PLoSULBSCtoffIldbr898SDp5gIqo8XL-t&index=2&t=73s) 

In this video, we will provide an introduction to statistical methods for anomaly detection. We will discuss the basic concepts of statistical process control, including control charts and process capability analysis. We will also demonstrate how to detect anomalies using statistical methods.

Video 2: [PCA Reconstruction-based Anomaly Detection](https://youtu.be/8d54sXKIIoE)

In this video, we will introduce the concept of Principal Component Analysis (PCA) and demonstrate how it can be used for anomaly detection. We will also discuss the limitations of PCA and how it can be improved by incorporating additional features. 

I realized that I made a mistake when demonstrating how to use the Pandas iloc function. Specifically, I used the following code: df.iloc[:3], when I should have used the code df.iloc[:, 3:] instead. This error may have caused unexpected results when working with your DataFrame. To correct this mistake, please replace df.iloc[:3] with df.iloc[:, 3:] in your code. This will select all rows and all columns starting from the 4th column of your DataFrame.

Video 3: [Autoencoder-based Reconstruction](https://youtu.be/C9r0APK4Mws)

In this video, we will introduce autoencoders and demonstrate how they can be used for anomaly detection. A brief introduction of autoencoder will be followed by implementation

Video 4: [Ensemble Learning](https://youtu.be/01LdiQIlyGo) 

In this video, we will introduce ensemble learning techniques and demonstrate how simple regression model can be used for anomaly detection. We will also discuss the advantages of ensemble learning over single models.

Video 5: CNN, LSTM-based Next Step Prediction

In this video, we will introduce convolutional neural networks (CNN) and long short-term memory (LSTM) models and demonstrate how they can be used for next-step prediction in the Tennessee Eastman Process dataset. We will also discuss how this technique can be used for anomaly detection.

Video 6: Transformer-based Anomaly Detection

In this video, we will introduce transformers and demonstrate how they can be used for anomaly detection in the Tennessee Eastman Process dataset. We will also discuss the advantages of transformer models over traditional machine learning models.

Video 7: XAI Method on Autoencoders

In this video, we will introduce Explainable AI (XAI) and demonstrate how it can be used on autoencoders to explain the anomalies detected by the model. We will also discuss the importance of XAI in complex industrial processes.

Average F1 score (average='macro') obtained from various methods on this dataset with Unsupervised Learning excluding Fault Number 3 and 9
| Method                                    | F1 Score |Accuracy|
|-----------------------------------------  |----------|----------|
| Statistical Method for Anomaly Detection  |  0.679   |  0.787   |
| PCA Reconstruction-based Anomaly Detection|  0.619   |  0.723   |
| Autoencoder-based Reconstruction          |  0.627   |  0.729   |
| Ensemble Learning                         |  0.690   |  0.818   |
| CNN, LSTM-based Next Step Prediction      |  0.591   |  0.826   |
| Transformer-based Anomaly Detection       |          |          |
| XAI Method on Autoencoders                |          |          |

## Acknowledgements

 - [The TEP Dataset](https://www.kaggle.com/datasets/averkij/tennessee-eastman-process-simulation-dataset)
 - [Blog Post on TEP process](https://keepfloyding.github.io/posts/data-explor-TEP-3/)
 - [Research Paper on PCA based reconstruction](https://www-sciencedirect-com.ressources-electroniques.univ-lille.fr/science/article/pii/S2405896320300860)


