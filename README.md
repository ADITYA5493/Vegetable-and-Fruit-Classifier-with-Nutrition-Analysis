# Vegetable and Fruit Classifier with Nutrition Analysis

## Overview

This project is a web application built using Flask and TensorFlow for classifying images of vegetables and fruits. It utilizes a fine-tuned InceptionV3 model to predict the type of vegetable or fruit from an uploaded image. Additionally, the application provides nutrition information for the predicted item based on a pre-loaded dataset.

The project also Generative AI to generate interesting facts about the identified vegetable or fruit, making it an informative tool for nutrition specialists or anyone interested in learning more about different produce.

## Features

- **Image Classification:** Utilizes a pre-trained InceptionV3 model to classify vegetables and fruits.
- **Nutrition Analysis:** Retrieves nutrition information from a CSV dataset for the predicted item.
- **Fun Facts Generation:** Uses the Google Generative AI API to generate interesting facts about the identified item.
- **Web Interface:** Provides a simple web interface for users to upload images and receive predictions and nutrition information.

## Prerequisites

- Python 3.10
- Flask
- TensorFlow
- pandas
- google.generativeai

  ## Future Enhancements

- [ ] Improve model accuracy through further training.
- [ ] Expand the dataset for more diverse predictions.
- [ ] Enhance the user interface for better user experience.
- [ ] Implement user authentication for personalized experiences.
