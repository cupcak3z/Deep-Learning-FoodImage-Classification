# Deep-Learning-FoodImage-Classification

##Problem
The classification of food images is a significant challenge within the domain of computer vision and deep learning. This is driven by the growing demand for automation and precision in food-related industries such as health, nutrition, retail, and hospitality.  The ability to accurately classify food or food images can enable applications like calorie estimations, dietary tracking, automated menu recommendations, and even food waste management.
Food image classification is a complex task due to high intra-class variance, inter-class similarity, and dataset size and diversity. Images within a single food category can vary greatly depending on lighting and presentation. There might also be similarities between different food types such as pasta and noodles or soups and stews. Large datasets such as this one, Food-101, contain diverse images that require preprocessing and effective modelling to achieve successful classification.

## Objective
The goal of thisproject is to develop a deep learning-based classification model that is capable of recognising and classifying images of 10 distinct food types. In this case, the assigned food types are beignets, breakfast burrito, clam chowder, crème brulee, croque madame, cupcakes, French onion soup, hummus, pad thai, shrimp and grits. The purpose of the task is to leverage the dataset provided and utilise deep learning algorithms and techniques to build and evaluate the models for optimal performance.
Some challenges to address are data complexity, performance evaluation, and practical application. The dataset contains high-resolution images which can result in computational overhead or longer training times. Therefore, efficient data preprocessing, resizing, and augmentation are critical to manage computational load without sacrificing performance. Models built must be rigorously evaluated on a test set to measure the real-world applicability of the model. Thus, a detailed comparison of the model’s accuracy and loss during the testing phase is necessary to identify the best-performing model. After identifying the best model, real-world food images are to be downloaded from the internet to continue with further testing of its reliability outside the curated dataset.

## Approach
The approach towards this problem is crucial in ensuring seamless processing and efficient model building and evaluation. 
Data is loaded and processed to ensure that there is data for the model to train, validate and test on. 
Different models are created to explore the different combinations of parameters or possible pre-trained models that can be utilised. A baseline model is created first then further improved on. For models created from scratch, a convolutional neural network architecture is created using Conv2D and Dense Layers. The model is then incrementally increased in complexity such as adding more layers, changing number of nodes, and using different optimisers. This is to optimise the performance of the model while avoiding overfitting. As for the models that leverages pre-trained models, different types of pre-trained models are used with methods such as freezing layers, and unfreezing last layer be attempted to fine tune the model. 
The model is then evaluated using the test data subset, using metrics such as accuracy and loss. The performance of the models are then compared to determine to best possible model. The results of each model are visualized using training and validation curves after each model training to show how the models improved over epochs. This is also to identify the smallest number of epochs to achieve the best possible performance. 
The best model is then deployed and tested on real-world food images from the internet. Its performance is also analysed on unseen data to discuss its reliability and accuracy in predicting the 10 food classes provided.

## Sources and References
Source: Food Images (Food-101) Kaggle

Link: <a href="url">[Dataset Link](https://www.kaggle.com/datasets/kmader/food41)</a>
