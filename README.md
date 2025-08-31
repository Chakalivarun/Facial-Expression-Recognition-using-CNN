## 🧠 Facial-Expression-Recognition-using-CNN

![image](https://github.com/user-attachments/assets/bdf4cc87-3e28-4a03-a9b5-21542d49765b)   ![image](https://github.com/user-attachments/assets/952e9e04-aeb7-4afb-bfda-9655260b9c73)


------------------------------------------------------------------------------------------------------------------------------------------------------------

## 👀 Overview
This project focuses on recognizing micro facial expressions using Convolutional Neural Networks (CNN). Micro-expressions are subtle, involuntary facial expressions that occur briefly and reveal genuine emotions. Detecting them can be crucial in areas like security, psychology, and suspect interrogation. The model is trained and evaluated using two benchmark datasets: CASME II (for micro-expressions) and FER-2013 (for facial expressions).Let's embark on this exciting journey!

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Features
CNN-based architecture for emotion classification

Trained on both macro and micro-expression datasets

Handles subtle facial movements in short image sequences

Comparative analysis using different datasets

Results visualization included

------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧠 CNN Architecture
The CNN model consists of:

Input Layer – Preprocessed grayscale facial images

Convolutional Layers – Feature extraction with ReLU activation

Max Pooling Layers – Dimensionality reduction

Flatten Layer – Transforms data for dense layers

Dense Layers – For final classification

Output Layer – Softmax activation to classify emotion categories

CNN Architecture Diagram:
![image](https://github.com/user-attachments/assets/3019d87d-7e12-4acb-8c2d-0d6bb1aa7ffb)

---------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Dataset
1. CASME II
Focuses on spontaneous micro-expressions

Contains high frame rate facial sequences

Used for training a model to recognize subtle expressions

Training Accuracy: 92%

2. FER-2013
Publicly available dataset with 35,000+ labeled facial expression images

Contains 7 emotion categories

Training Accuracy: 73%

Dataset Link: https://www.kaggle.com/datasets/msambare/fer2013

---------------------------------------------------------------------------------------------------------------------------------------

## Workflow Diagram 

![image](https://github.com/user-attachments/assets/5046080e-0166-4725-8409-2ce25dca76a9)

-----------------------------------------------------------------------------------------------------------------------------------------

## ✅ Results
Dataset	Training Accuracy
CASME II	92%
FER-2013	73%

CASME II showed superior performance due to focused and high-quality micro-expression data

FER-2013 provided good generalization for common facial expressions

![image](https://github.com/user-attachments/assets/fba04b81-d310-4c41-8626-63711ed52ec9)

![image](https://github.com/user-attachments/assets/eb3da525-28c4-42eb-ba75-6a28111332f8)


![image](https://github.com/user-attachments/assets/a2f7630a-df93-4db0-928b-82a87f6468c4)

![image](https://github.com/user-attachments/assets/7b1b8d65-de94-47f8-9fb0-a97808313106)

---------------------------------------------------------------------------------------------------------------------------------------------------

## 📚 References

https://www.kaggle.com/datasets/msambare/fer2013

https://paperswithcode.com/sota/micro-expression-recognition-on-casme-ii-1

https://github.com/yuxinhe/CASME2-Micro-Expression-Database-SVM

https://ieeexplore.ieee.org/abstract/document/10820184

--------------------------------------------------------------------------------------------------------------------------------------------------------
