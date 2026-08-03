# 🍎 GET324 – Laboratory Exercise 10 (Mini-Project)

# Fresh Apple vs. Rotten Apple Classification Using MobileNetV2 and Streamlit

## Project Overview

This project presents a binary image classification web application that determines whether an uploaded apple image is **Fresh** or **Rotten**. The system leverages **MobileNetV2**, a lightweight deep learning model pre-trained on ImageNet, through transfer learning to achieve high classification accuracy. 

The trained model is integrated into a **Streamlit** web application, allowing users to upload an apple image and receive an instant prediction along with the model's confidence score. The application demonstrates the practical use of Artificial Intelligence and Computer Vision in food quality inspection and agricultural automation. 


## Features

* Binary image classification (Fresh or Rotten Apple)
* MobileNetV2 transfer learning model
* User-friendly Streamlit web interface
* Image upload functionality
* Real-time prediction
* Confidence score display
* Lightweight and suitable for deployment


## Project Structure

```text
GET324-CO1-Apple-Classification/
│
├── app.py                     # Streamlit web application
├── requirements.txt           # Python dependencies
├── notebooks/
│   └── train_model.ipynb      # Data preparation, model training, and evaluation
├── model/
│   └── apple_model.h5         # Trained MobileNetV2 model
├── dataset/                   # Fresh and Rotten Apple dataset
└── README.md                  # Project documentation
```


# Dataset

The project uses a dataset containing images of **Fresh Apples** and **Rotten Apples** collected for binary image classification.

The dataset consists of two classes:

* Fresh Apple
* Rotten Apple

Before training, all images were preprocessed by:

* Resizing to **224 × 224 pixels**
* Normalizing pixel values
* Applying data augmentation techniques including:

  * Random rotation 
  * Horizontal flipping
  * Zooming
  * Shifting

The dataset was divided into:

* **80% Training**
* **10% Validation**
* **10% Testing**


# Model Development

The classification model was developed using **TensorFlow** and **Keras** with the **MobileNetV2** architecture.

The development pipeline included:

* Dataset preprocessing
* Data augmentation
* Transfer learning using MobileNetV2
* Fine-tuning the model
* Model evaluation
* Saving the trained model

The final trained model was saved as:

```text
model/apple_model.h5
```


# Technologies Used

* Python
* TensorFlow
* Keras
* MobileNetV2
* NumPy
* Matplotlib
* Pillow (PIL)
* Streamlit
* Google Colab


# Running the Application

Clone the repository:

```bash
git clone https://github.com/yourusername/GET324-CO1-Apple-Classification.git
```

Move into the project folder:

```bash
cd GET324-CO1-Apple-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

The application will open automatically in your browser.


# Training the Model

To retrain the model:

1. Download or prepare the Fresh and Rotten Apple dataset.
2. Place the dataset in the appropriate project directory.
3. Open:

```text
notebooks/train_model.ipynb
```

4. Run all notebook cells sequentially.
5. The trained model will be saved automatically as:

```text
model/apple_model.h5
```


# Web Application

The Streamlit application allows users to:

* Upload an apple image.
* Display the uploaded image.
* Predict whether the apple is **Fresh** or **Rotten**.
* Display the confidence level of the prediction.
* Produce fast and reliable classification results.


# Performance

The MobileNetV2 transfer learning model achieved excellent classification performance on the test dataset, demonstrating its effectiveness for automated apple quality assessment.

Performance metrics evaluated include:

* Classification Accuracy
* Loss
* Precision
* Recall
* Prediction Confidence


# Challenges Encountered

Several challenges were encountered during the development of this project:

* Preparing and organizing the dataset into the required directory structure.
* Ensuring all images were resized consistently for model training.
* Preventing overfitting through appropriate data augmentation and validation.
* Integrating the trained model with the Streamlit interface.
* Correctly interpreting prediction probabilities to ensure accurate classification results.

These challenges were successfully resolved through preprocessing improvements, model fine-tuning, and application testing.


#  Future Improvements

Possible enhancements include:

* Support for multiple apple diseases.
* Multi-class fruit classification.
* Mobile application deployment.
* Real-time camera-based detection.
* Batch image prediction.
* Disease severity estimation.
* Fruit quality grading.
* Cloud deployment for wider accessibility.


# Deployment

The application can be deployed using:

* Streamlit Community Cloud
* Render
* Railway
* Hugging Face Spaces


# Team Members

**GitHub ID           Registration Number      Name**

danieludobia500-lang  22/EG/CO/1740      Daniel Ebio Udobia

Emark068b             22/EG/CO/1720      Mark Enimini Sunday 

ukemeinimfon42        22/EG/CO/1670      Udofa Inimfonabasi Ukeme

pauldavid7172-gif     22/EG/CO/1650      Okonnah Paul David

lilzeese2-wq          22/EG/CO/1681      Ikoh Iniobong Moses 

Teejay-101            22/EG/CO/1730      Ottuk, Utibeabasi Josiah

bjnnsewo-cyber        22/EG/CO/1820      Benjamin Joseph nnsewo 

limmrax               22/EG/CO/1710      Urua, Edikan Usen

aharanwavicky-creator 22/EG/CO/1750      Aharanwa victor kemakolam 

lassbhorn51-oss       22/EG/CO/1700      UDOFIA BEST

eliscosucess20-sudo   22/EG/CO/1760      Etim, Elijah Edet

Donblast203           22/EG/CO/1770      Udo, Emediong Isaiah

Prince-app-stack      22/EG/CO/1781
John, Prince Kingsley 


# Conclusion

This project demonstrates how transfer learning with MobileNetV2 can be effectively applied to automate apple quality inspection through image classification. By integrating deep learning with a Streamlit web application, the system provides an efficient, accurate, and user-friendly solution for distinguishing between fresh and rotten apples. Such intelligent systems have promising applications in agriculture, food processing, retail, and supply chain quality control.


**Course:** GET324 – Laboratory Exercise 10 (Mini-Project)

**Project Title:** Fresh Apple vs. Rotten Apple Classification Using MobileNetV2 and Streamlit
