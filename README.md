# Convolutional Neural Networks Ophthalmology
Ocular Disease Recognition from Fundus Photographs with CNN transfer learning.

This project uses Ocular Disease Recognition Dataset [1]: <br>
Ocular Disease Intelligent Recognition (ODIR) is a structured ophthalmic database of 5,000 patients with age, color fundus photographs from left and right eyes and doctors' diagnostic keywords from doctors. This dataset is meant to represent ‘‘real-life’’ set of patient information collected by Shanggong Medical Technology Co., Ltd. from different hospitals/medical centers in China. In these institutions, fundus images are captured by various cameras in the market, such as Canon, Zeiss and Kowa, resulting into varied image resolutions.

Annotations were labeled by trained human readers with quality control management. They classify patient into eight labels including:

* Normal (N)
* Diabetes (D)
* Glaucoma (G)
* Cataract (C)
* Age related Macular Degeneration (A)
* Hypertension (H)
* Pathological Myopia (M)
* Other diseases/abnormalities (O)


This project is focused on differentation of fundus photographs with Pathological Myopia from photographs of healthy eyes. <br>
It constists of following Colab notebooks: 
1. EDA_Dataset_Split 
    - Exploratory Data Analysis 
    - Patient-stratified train-valid-test split 
2. Transfer_learning_DenseNet 
    - Training, predicting and evaluation of DenseNet121-based model.

<br>
Performance of the best model: <br>
<br>

![Alt text](https://github.com/SylwiaNowakowska/Convolutional_Neural_Networks_Ophthalmology/blob/master/Model_1_AUROC.png)
<br>

![Alt text](https://github.com/SylwiaNowakowska/Convolutional_Neural_Networks_Ophthalmology/blob/master/Model_1_precision_recall.png)
<br>

![Alt text](https://github.com/SylwiaNowakowska/Convolutional_Neural_Networks_Ophthalmology/blob/master/Model_1_f1_tresh.png)
<br>

![Alt text](https://github.com/SylwiaNowakowska/Convolutional_Neural_Networks_Ophthalmology/blob/master/Model_1_cf_matrix.png)


References: <br>
[1] https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k
