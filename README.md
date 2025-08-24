# Coin Recognition Project
This project is a Google Colab notebook that can identify different Indian coins from images. It uses computer vision to "see" and "learn" the features of coins, and then it predicts what a new coin is.

# How It Works
__The notebook follows a few simple steps:__

__Preparation:__ It sets up all the tools needed and connects to your Google Drive, where your coin pictures are stored.

__Training:__ It looks at a lot of coin pictures to learn what each type of coin looks like. It focuses on things like their shape and texture.

__Prediction:__ After learning, it can take a new picture of a coin you upload and tell you which coin it is, along with how sure it is about the guess.

# How to Use It
__Open the Notebook:__ Open Coin_recognition.ipynb in Google Colab.

__Organize Your Photos:__ Put your coin images into folders in your Google Drive. Each folder should have a different type of coin. For example:

MyDrive/Indian-Coin-Currency-Dataset/

├── 1_Rupee/

├── 2_Rupees/

├── 5_Rupees/

└── 10_Rupees/

__Run the Cells:__ Go through the notebook and run each cell in order. The notebook will guide you through the process of setting up, training the model, and making a prediction.

# What's Inside the Code?
The code uses popular Python libraries for machine learning and computer vision to handle the following tasks:

__opencv-python-headless:__ For processing images (like resizing and changing colors).

__scikit-learn:__ For the machine learning part, including training the model that makes the predictions.

__joblib:__ For saving the trained model so you don't have to train it every time.

# Where Can This Be Used?
Coin recognition technology can be applied in many different fields, including:

__Automated Vending Machines:__ Vending machines can use this technology to automatically verify and accept coins.

__Self-Checkout Kiosks:__ Retail stores can use this for quick and accurate coin counting at self-service checkout points.

__Banking and Currency Exchange:__ Banks can use this to quickly sort and count coins, improving efficiency and accuracy.


# Dataset link:https://data.mendeley.com/datasets/k49x47v732/1?utm_source=chatgpt.com


