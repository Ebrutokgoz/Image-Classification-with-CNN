In e-commerce platforms, which have become quite common today, showing customers the products they are interested in has an importance in marketing as it increases sales. 
For this purpose, the products that customers have already purchased should be analyzed and their features and categories should be determined. An image classification application that can be used for the mentioned purpose created with this project.

In the project, a dataset consisting of images of clothes and the categories to which they belong is created, preprocessed, and used to train and then test a deep learning model. 
The model is trained to predict which category of clothing a given clothing image belongs to.

Convolutional Neural Network (CNN) is used for deep learning.
In order to get better performance with less data and to complete the process faster, instead of teaching this CNN model from scratch, we used transfer learning. 
Transfer learning is when machine learning methods store the knowledge gained from solving one problem and use that knowledge when faced with another problem. 
For this purpose, the MobileNet V2 model, which was pre-trained with the ImageNet dataset, was used. 

This project consists of following steps:
- dataset creation with web scraping (BeautifulSoup)
- data pre-processing (DifPy, Rembg, Keras)
- CNN deep learning model creation (used MobileNet V2 model) and training (Tensorflow)
- testing the model and analyzing the results.


