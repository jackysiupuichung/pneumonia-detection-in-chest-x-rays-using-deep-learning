# pneumonia detection in chest x rays using deep learning

Simple CNN model to detect pneumonia from chest x-ray images
Project description: The aim of this project is to develop a deep learning method to detect and classify human disease from medical images, which detects pneumonia symptoms from x ray images derived from patient data.
Dataset source: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
Project workflow and highlights:
- Implement the Kaggle api to download the data
- Dataset distribution and structure reformation to adjust for skewed training validation and testing split
- Include weights for class to counteract skewed normal vs pneumonia samples in dataset
- Develop CNN model with Kera api
- Fine tuning with Kera callback

Reference
Kermany DS, Goldbaum M, Cai W, Valentim CC, Liang H, Baxter SL, McKeown A, Yang G, Wu X, Yan F, Dong J. Identifying medical diagnoses and treatable diseases by image-based deep learning. Cell. 2018 Feb 22;172(5):1122-31.
https://www.kaggle.com/amyjang/tensorflow-pneumonia-classification-on-x-rays


