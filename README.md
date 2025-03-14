# Eye_disease_detection
This project aims to develop a web application using Flask for user dashboard functionality and cataract prediction. The application utilizes the Ocular Disease Detection dataset obtained from Kaggle, specifically filtering data for cataract-positive cases.

# Dataset
The dataset used in this project is the [Ocular Disease Detection dataset](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k) from Kaggle. Please refer to the dataset's documentation and terms of use for specific details.

# Prediction Model
The cataract prediction model utilized in this application can be accessed [here](https://drive.google.com/file/d/1Dtz5oYnWIpveowxbsRyG-N7ywAJTafo3/view?usp=sharing). It is crucial to place the model file in the same directory as the `app.py` file for proper functionality. If the model file is not working use VGG16.ipynb file to custom train your model and use that model for the application while doing so make sure to save the model with name vgg16_1.h5.

# Project Structure
## Directories
static: Contains static files (e.g., CSS, JavaScript) utilized within the web application.
templates: Consists of HTML templates defining the web interface's structure.
uploads: Directory designated for uploaded files within the application.
