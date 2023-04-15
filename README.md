# Skin lesion type Detection 
> To build a CNN based model which can accurately detect skin lesion type. Among other lesions, Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> This project aims to develop a machine learning model that can classify skin lesions as either one of the 9 skin lesion types ie 
 'actinic keratosis',
 'basal cell carcinoma',
 'dermatofibroma',
 'melanoma',
 'nevus',
 'pigmented benign keratosis',
 'seborrheic keratosis',
 'squamous cell carcinoma',
 'vascular lesion'.
 The dataset used for this study is the ISIC 2019 Challenge dataset, which includes 2357  dermoscopic images of skin lesions, including 374 melanoma images. Melanoma is a type of skin cancer that can be deadly if not detected and treated early. Therefore, developing a reliable and accurate method for detecting lesion type can potentially save lives.


## Technologies Used
The following technologies were used for this project:

- Python - programming language used for building the machine learning model
- Scikit-learn - machine learning library used for model training and evaluation
- TensorFlow - machine learning library used for building deep learning models
- Keras - high-level API for building deep learning models
- Pandas - data manipulation and analysis library used for data preprocessing
- NumPy - numerical computation library used for data preprocessing
- Matplotlib - data visualization library used for displaying images and graphs
- Jupyter Notebook - an open-source web application for creating and sharing documents that contain live code, equations, visualizations, and narrative text.
- Google Colab - google colab used to run this model online over GPU.

## Conclusions
- Conclusion 1 from the analysis:
Model contains 3 convolutional units with 32,64 and 64 feature extractions and one FC-128 layer and 1 softmax layer
- Conclusion 2 from the analysis:
Without regularization, with class imbalance, without image augmentation but with normalized batches, model performs poorly with under 25% of training and validation accuracy in 20 epochs.
- Conclusion 3 from the analysis
With regularization, and little image augmentation but with class imbalance model performs gets better with around 50% of training and validation accuracy in 20 epochs.
- Conclusion 4 from the analysis
After regulrization, image augmentation with resolving class imbalance (adding 500 image to each class after augmentation) model accuracy reaches 80-90%.


## Acknowledgements
We would like to acknowledge the contributions of our team members and the work of many researchers in the field of solving classification problems using machine learning, which inspired this project. Our team also thanks the International Skin Imaging Collaboration for providing the ISIC Challenge dataset, which served as the foundation of our study. Furthermore, we would like to express our gratitude to the developers of Scikit-learn, TensorFlow, and Keras for creating the machine learning libraries used in this project. Lastly we would also thank creators of jupyter notebook and google colab for providing resources to run this model.


## Contact
Created by [@Zebafroz], [@anupamvaibhav], [@mazahir3393] - feel free to contact me!

