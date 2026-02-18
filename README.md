

This repository contains two main folders:

1. **IFD_AI** – Contains Jupyter notebooks developed to build and train a CNN-based image and video forgery detection model using the FIDAC and CASIA datasets.

2. **IFD_WebApp** – Contains a Django-based web application built to provide a user-friendly interface for detecting image and video forgeries in real time.

## Dataset

This project utilizes the publicly available FIDAC (Forged Images Detection and Classification) dataset provided by an IEEE-published study. The dataset consists of original camera-clicked images along with their tampered versions and was used for training and evaluating the CNN model.

Using this dataset, I designed and implemented the complete forgery detection pipeline, including ELA preprocessing, CNN model training, performance evaluation, and deployment through a Django web application.

## Pre-trained Models

Pretrained weights used during experimentation are provided below:

- [Image Model weigths](https://drive.google.com/drive/folders/1B4ODeK_QQ6XMFo6i6EEup1nZC6PllVfu?usp=sharing)
- [Video Model weigths](https://drive.google.com/drive/folders/1irYZbRnr4Y7jKieSyhjxHxwk43oSMqh-?usp=sharing)

## Running the Web Application

To run the web application on Windows, Linux, or Mac, follow these steps:

1. Install Python3 and pip3
2. Clone this repository
3. Open a terminal and navigate to the IFAKE_WebApp folder
4. Run the following command to install the required Python packages:

    ```
    pip3 install -r requirements.txt
    ```

5. Run the following command to start the web application:

    ```
    python3 manage.py runserver
    ```

6. Open a web browser and go to http://127.0.0.1:8000/ to access the web application.

## Screenshots
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/index.JPG" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/imageDetection1.png" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/imageDetection2.png" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/metadata.JPG" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/videoDetection.png" alt="Image description" width="60%">
<img src="https://raw.githubusercontent.com/shraddhavijay/IFAKE/master/screenshots/pdfDetection.png" alt="Image description" width="60%">




The screenshots show different features of our web application, including the image and video forgery detection functionality, and the ability to upload and view results of detected forgeries.




