# Waste_Image_Classification
This supervised Machine Learning model is the start to solve the problem by classifying what waste we have by using images we capture. In this model, we have 45 different types of waste.
We get the dataset from Kaggel https://www.kaggle.com/raijincheng/rethink-recycle-dataset. it consist 45 folders of different types of waste, with almost 8.000 different images. The 101 categoreis is based on this catalogue https://recycle.rethinktw.org/catalogue/.

We do some EDA, image data preparation, PCA to reduce the dimension, modelling using scikit-learn, and evaluating the model. We save the model so we can use it for model deployment at streamlit.

We use pyton libraries os, pathlib, cv2, matplotlib.pyplot, scikit-learn, joblib.
