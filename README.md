<h1>Early Detection of Parkinson's Disease using Hand Drawing and Speech Recognition</h1>
Project Overview
This project is part of my graduation thesis from the Faculty of Computer and Information Science, Scientific Computing Department, Ain Shams University. The primary objective is the early detection of Parkinson's disease by leveraging two key features: Hand Drawing Analysis and Speech Recognition. The project has been implemented in a mobile application using Flutter for the front-end and Flask for the back-end.

Key Features
Hand Drawing Analysis:

Users are prompted to draw three shapes: a spiral, a meander, and a circle. These shapes are then fused into one image with three channels.
This combined image is fed into a Convolutional Neural Network (CNN) model to detect any indications of Parkinson's disease based on the irregularities in the drawing.
Speech Recognition:

Users are required to read a text displayed on the screen, and their speech is recorded.
The recorded audio is analyzed using a Random Forest model to identify potential signs of Parkinson's disease through speech pattern analysis.
Results
Achieved Grade: A+
Recognition: Awarded for innovation in early detection methodologies.
Tech Stack
Mobile App: Flutter
Back-End: Flask
Machine Learning Models:
Convolutional Neural Network (CNN) for Hand Drawing Analysis
Random Forest for Speech Recognition Analysis
Project Structure
mobile_app/: Contains the Flutter code for the mobile application.
backend/: Contains the Flask back-end code responsible for handling the ML models and API.
models/: Contains the trained models (CNN and Random Forest) used for predictions.
data/: Contains the datasets used for training and validation of the models.
notebooks/: Contains Jupyter notebooks with the code for model training and evaluation.
README.md: This file.
Installation and Setup
Prerequisites
Python 3.7+
Flutter 2.0+
pip for Python package management
