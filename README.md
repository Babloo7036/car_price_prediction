# SMS Spam Detection

## Overview
This project is an SMS Spam Detection system that classifies messages as spam or ham (not spam). The system utilizes extensive text preprocessing techniques and machine learning models to achieve high accuracy. A Streamlit-based web application is developed for user-friendly interaction, and the model is deployed on Render for accessibility.

webapp Link - [https://car-price-prediction-2-hw0k.onrender.com]

## Features
- Extensive data cleaning and preprocessing.
- Machine learning model training and evaluation.
- Achieved 95% accuracy in classification.
- Web application built using Streamlit.
- Deployed on Render for public access.

## Dataset
Dateset Link - [https://github.com/Babloo7036/car_price_prediction/blob/main/Cardetails.csv]

I have download dataset from kaggle and it has columns feature name,	year, selling price, km driven,	fuel,	seller type, transmission,	owner,	mileage,	engine, max power,	torque, seats. It was preprocessed to remove noise, standardization, and categorical data into numerical data for machine learning.

## Text Preprocessing Steps
1. Removing unwanted columns.
2. Removing null & duplicate data.
3. convering categorical data into numerical formate.

## Machine Learning Model
Several models were trained and evaluated, with the best-performing model achieving 98% accuracy. The models tested include:
 - Linear regression 

## Web Application (Streamlit)
A Streamlit web application was developed to provide an interactive interface for users to classify SMS messages. The application allows users to:
- Input car details like menufactured year, no of km driven, fuel type, etc.
- Receive a real-time prediction of car price.

## Deployment
The application was deployed on Render, making it accessible to anyone with an internet connection. The deployment process included:
- Packaging the model and dependencies.
- Creating a Python script for Streamlit.
- Hosting the app on Render with an appropriate environment configuration.

## Installation & Usage
To run the application locally:
1. Clone the repository:
   ```sh
   git clone https://github.com/babloo7036/car_price_prediction.git
   ```
2. Navigate to the project directory:
   ```sh
   cd car_price_prediction
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
5. Open the provided local URL in a browser to interact with the application.

## Technologies Used
- Python
- Pandas, NumPy (Data Processing)
- Scikit-learn (Machine Learning)
- Streamlit (Web Application)
- Render (Deployment)

## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request with enhancements or bug fixes.

## Contact
For any queries or suggestions, feel free to reach out:
- GitHub: [Babloo](https://github.com/babloo7036)
- Email: babloo77018@gmail.com

---
This project showcases the power of machine learning in text classification and demonstrates deployment using modern web technologies. Hope you find it useful!
