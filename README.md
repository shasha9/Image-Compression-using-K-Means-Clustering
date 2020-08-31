# Image-Compression-using-K-Means-Clustering
This project focuses on applying the K-means clustering unsupervised learning algorithm using scikit-learn and Python to build an image compression application with interactive controls.This project consists of pre-processing high-resolution image data for k-means clustering,conducting basic exploratory data analysis (EDA) and data visualization,applying a computationally time-efficient implementation of the k-means algorithm, Mini-Batch K-Means,to compress images,and leveraging the Jupyter widgets library to build interactive GUI components to select images from a drop-down list and pick values of k using a slider.

* ##### Task 1:
Import essential modules and helper functions from NumPy,Matplotlib,scikit-learn,and Jupyter Widgets.
* ##### Task 2:
Data Pre-processing- Imporing images from a local directory and storing them as numpy arrays.Exploring the image attributes.Normalizing the pixel values and unrolling the arrays into vectors. 
* ##### Task 3:
Visualizing the Color Space using Point Clouds - Visualizing the set of pixels from the original image as two 2-D point clouds in color space.
* ##### Task 4: 
Visualizing the K-Means Reduced Color Space - Perform k-means clustering with scikit-learn's MiniBatchKMeans to reduce the number of possible colors in the image from over 16 million to 16.Compare and contrast the color space of the original image with that of the k-means compressed image.
* ##### Task 5: 
Creating Interactive Controls with Jupyter Widgets - Using the interact function to automatically create UI controls for function arguments.Defining an argument to control the value of k using a slider.Defining an argument to pick any image from a specified directory.
