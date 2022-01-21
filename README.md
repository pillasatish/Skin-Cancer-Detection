# Skin_cancer_detection_using_CNN

In the project, we are using Convolutional Neural Networks (CNN) to accurately classify pigmented skin lesion in dermoscopic images to detect the malignant skin lesions as early as possible. Two convolutional neural networks with varied architecture and/or depth, as well as data pre-processing methods, are examined in the project to see how they affect classification performance of skin lesions. The models used are CNN architecture VGG16Net and InceptionNet-V3. 

***
The project has been written in Python and consists in a Jupyter notebook(google colab) containing both the source code and the project documentation. 

Dataset: HAM10000 dataset is directly downloaded from kaggle by loading the kaggle API.

**Code-Flow**

The main Python libraries used to design the source code are scikit-learn, scikit-image, Keras, numpy, pandas and matplotlib.

Pandas and numpy for data cleansing and data exploration.

matplotlib for data visulization.

scikit-image is an open source image processing library based on NumPy and SciPy, which includes several modules that implement all the main image processing algorithms for segmentation, geometric transformations, color space manipulation, filtering, morphology operations, feature extraction and so on. 

Keras, is one of the most popular Python libraries for deep learning, designed to be interoperable with the most well-known frameworks for machine learning and neural network applications like Tensorflow

**Dataset load form Kaggle**

We are loading dataset from kaggle directly, you can find step by step process of loading the data from kaggle form the foolowing youtube link(https://www.youtube.com/watch?v=57N1g8k2Hwc), First we need to generate a API token with our kaggle account, While running the files.upload in google colab we need upload the file to authenticate our kaggle account.  

Once the dataset is downloaded and loaded into google colab you can run all the pre-process step in the code snippets, Every line of code block as pre-text for easy understanding of the code. 


**Code**

The SkinCancerDetection_B21047209_SATISH_PILLA.IPNYB file contains the source code for the entire project. For line of the code there is clear instruction of why were are running the particular code block.

The kaggle.json file is the API token file to authenticate the kaggle account and downlaod the dataset form kaggle. 

**Abstract**

B210472095_SATISH_PILLA_MACHINE_LEARNING_ABSTRACT.pdf contains the abstract of the project.

**Report**

B210472095_SATISH_PILLA_MACHINE_LEARNING_REPORT.pdf is the overall report of the project. The report is organized as follows:

1 Introduction	

2 Dataset	

3 Transfer Learning	

4 Convolution Neural Network	

4.1 VGG16Net Architecture	

4.2 InceptionV3 architecture	

5 Data Pre-processing	

5.1 Data Editing and Cleansing	

5.2 Data Splitting	

5.3 Feature Normalization	

5.4 Data Augmentation	

6 Modelling and Results

6.1 Results

7 Conclusion and Future work

Future work

8 Reference

