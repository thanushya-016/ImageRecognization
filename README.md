# Sports Celebrity Classification

![image](https://github.com/user-attachments/assets/e2a3617b-b64c-4f74-ac2c-13720c5f54a7)

This project is centered around the classification of sports personalities using machine learning and image recognition techniques. We aim to build a system capable of recognizing and classifying images into one of the following five sports personalities:

- **Maria Sharapova** (Tennis)
- **Serena Williams** (Tennis)
- **Virat Kohli** (Cricket)
- **Roger Federer** (Tennis)
- **Lionel Messi** (Football)

The project showcases the end-to-end process of building a machine learning model, from data collection and cleaning to model deployment through a user-friendly web interface.

## Technologies Used

- **Python** for core programming and logic
- **Numpy & OpenCV** for data cleaning and image preprocessing
- **Matplotlib & Seaborn** for data visualization
- **Sklearn** for model building and evaluation
- **Flask** for creating the server backend
- **HTML/CSS/JavaScript** for building the web interface

## Workflow

1. **Data Collection**: Scraped and collected images using Google for the five sports personalities.
2. **Image Preprocessing**: Used OpenCV to clean, resize, and process the images for better model training.
3. **Model Building**: Created a machine learning model using Scikit-learn, focusing on image classification.
4. **Web Interface**: Built a simple and intuitive web interface where users can upload images for classification.
5. **Server**: Set up a Flask server to handle image upload, model inference, and return results to the front-end.

## Results

- The model is able to classify images with high accuracy.
- The interface allows for real-time predictions, displaying a probability score for each sports celebrity.
