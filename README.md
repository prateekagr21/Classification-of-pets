# Classification of pets using Convolution Neural Networks!


## For Solving this Usecase, What I have done is :
- Collected the data and organized to form a meaningful dataset.
- Used binary classification for Dog and Cat images.
- Did Exploratory Data Analysis on the dataset.
- Visualizations were made by using Matplotlib and Seaborn Libraries.

### Did data Preprocessing.
### Did Data Augmentation.


# And then I made a Model for the Prediction :
## Used Convolution Neural Networks - CNN

# Created this model:
- Added CNN layer
- Max pooling
- Added second layer
- Flattening
- Added Dense Layer

## And then for the last layer,
- Used Support Vector Machine - SVM
- Since, it is a binary classification, so i used Linear SVM.

### Initialized the Model <br> and Trained it.
- by training for 20 epoches.


## Plotted the Prediction.
### Accuracy -
![image](https://user-images.githubusercontent.com/73397927/127969214-e75fef70-9075-4316-a852-126f0951840c.png)

### And Loss -
![image](https://user-images.githubusercontent.com/73397927/127969261-468a9b33-efea-41bb-9f46-e3bb781b95d0.png)

Finded the best parameters.
Saved the model using Tensorflow's Load_model.

# Now, for the Prediction part :
- Read an image from the test dataset
- And predicted it using the value of Array,
- In which the classification was distinguished using the positive and negative value of the resulted array.

## And did the prediction again, 
## _Model did right for the both time and hence, it works <br> And can be used for further classification regarding dog-cat images._
