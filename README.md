# COVID CT Diagnosis

Coronavirus 2019 (COVID-19) has spread all over
the world and caused deaths in thousands of number. One of the
important reason this spread is less accurate and late diagnosis
of the disease. Also most of the diagnosis methods can have
good chance of giving false negative test results. There has been
great efforts in developing computational methods which can
analyse the lung’s image and diagnose the disease. Due to privacy
reasons often these works are difficult to reproduce because the
CT scan data is not available publicly. Besides this large amount
of data is required for training models to predict COVID-19
accurately. We built the dataset by combining multiple publicly
available datasets which resulted into hundreds of lungs CT Scan
images. We applied various data pre-processing and data mining
techniques on these datasets and trained various classification
models. Specifically we used RESNET-50 pre-trained model for
feature extraction from images. Then we trained SVM, KNN and
DNN on the extracted features by applying PCA and without
PCA. Our approach achieves highest accuracy of 89% and
highest F1 score of 87.7% in diagnosing COVID-19 from CT
scans even though the dataset is limited.

## Approach
![Approach](https://user-images.githubusercontent.com/27214644/128904733-6e28e19a-1463-4bf4-8c93-edd438e7785d.png)

## Dataset Links
- https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset?select=non-COVID
- https://github.com/UCSD-AI4H/COVID-CT
