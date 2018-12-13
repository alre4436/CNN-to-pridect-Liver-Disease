# CNN-to-pridect-Liver-Disease


By Aziz Alreshidi
Email : swe2010-m-s@hotmail.com


Abstract
Explore and compare machine learning techniques and tools used to predict liver disease for patients in India utilizing a set of health data measurements.
Description of data source and web links
The Indian Liver Patient Dataset (ILPD) contains 10 health variables for Indian patients along with a binary outcome variable indicating whether or not the patient has a liver disease.  The data set was published on 2012-05-21 by two professors and an associate computer science research professor.  

University of California, Irvine:  Center for Machine Learning and Intelligent Systems
ILPD (Indian Liver Patient Dataset) Data Set
https://archive.ics.uci.edu/ml/datasets/ILPD+(Indian+Liver+Patient+Dataset)#

Kaggle: UCI Machine Learning
Indian Liver Patient Records
https://www.kaggle.com/uciml/indian-liver-patient-records/version/1


Number of records and size of the dataset
This dataset contains a total of 583 records.  416 records are for patients that have a liver disease apart from 167 patients who do not have a liver disease.  The dataset is presented in CSV format with a file size of 24kb.	

Number and description of attributes in the dataset
10 features are recorded for these patients as well as classification labels of disease/no disease.


![1](https://user-images.githubusercontent.com/29342294/49695858-c844fb00-fb66-11e8-91c2-f06fb06f8d7f.png)


![1](https://user-images.githubusercontent.com/29342294/49695864-dd218e80-fb66-11e8-826d-2bceb8e07f63.png)

Using Convolutional Neural Networks (CNN)

Here is the CNN i put the input_diminetion as 11 becouse we have 11 features.

![1](https://user-images.githubusercontent.com/29342294/49968099-71368180-feea-11e8-9a44-00bbac7846f1.png)



See Corrolation between Features
![1](https://user-images.githubusercontent.com/29342294/49695975-5ff71900-fb68-11e8-97bd-7f1e9741df17.png)



![1](https://user-images.githubusercontent.com/29342294/49695882-11954a80-fb67-11e8-8d71-e5337bf3b16d.png)


![1](https://user-images.githubusercontent.com/29342294/49695889-2c67bf00-fb67-11e8-96a8-9945d5a9d3de.png)

ploting Model Performance
![1](https://user-images.githubusercontent.com/29342294/49695900-46090680-fb67-11e8-8002-fe62f281e0f6.png)


Classification Report

![1](https://user-images.githubusercontent.com/29342294/49695910-6f299700-fb67-11e8-9297-80daff7e02d2.png)

![1](https://user-images.githubusercontent.com/29342294/49695926-9b451800-fb67-11e8-9c42-f21af382c717.png)


