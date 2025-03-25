# Image-sentiment-analysis
## Overview
Understanding emotions in images is crucial for applications in social media analysis, marketing, and human-computer interaction. This project focuses on image sentiment classification, where a deep learning model is trained to predict whether an image expresses a positive or negative sentiment.

The model uses a Convolutional Neural Network (CNN) architecture to achieve a balance between computational efficiency and high accuracy. Unlike traditional text-based sentiment analysis, this approach enables understanding visual emotions, making it valuable for analyzing user-generated content, advertisements, and even human facial expressions in various contexts.

This repository provides everything needed to train, test, and deploy the sentiment classifier. The project can be extended by integrating additional sentiment categories, fine-tuning the architecture, or deploying it as a real-time application using Flask or Gradio.

## Dataset
The dataset was scraped from Google Images and underwent extensive preprocessing:
  - Removal of corrupted or incorrect images
  - Resizing to 256x256 resolution
  - Real-time loading and augmentation (rotation, flipping)

## Results
- The model achieved high accuracy with minimal overfitting.
- The confusion matrix confirmed strong classification performance.

## How to Run the Project

Clone the repository:
git clone https://github.com/Gunjan-Goyal/Image-Sentiment-Classifier.git
cd Image-Sentiment-Classifier

Install dependencies:
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook

Open Image Sentiment Classifier.ipynb and run all cells.

## Dependencies
- Python 3.8+
- TensorFlow & Keras
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-Learn

## Future Improvements
- Expand dataset for better generalization
- Optimize model for real-time predictions
- Deploy as a web application using Flask/Gradio
