---
title: "Ai powered Disease Prediction System"
date: 2025-02-05 10:12:43 +0000
categories: [Artificial Intelligence, Web Development, Machine Learning, Health Tech, DevOps]
tags: 
  - Flask, AI in Healthcare, Disease Prediction, Python Projects, Model Deployment
author: "<nabil>" 
description: "AI-powered disease prediction model on Render, providing real-time health insights from live input with precision and efficiency."
pin: true
image: 
  path: "/assets/images/ai-disease.jpeg"
  alt: "Ai powered Healthcare"
---



# Disease Prediction System


The **Disease Prediction System** is an AI-powered web application designed to predict diseases based on user-provided symptoms. Built with Flask, Python, and machine learning, this system provides an intuitive interface for users to select their symptoms and receive a predicted diagnosis. The project is deployed on **Render** and is accessible online.

## Live Demo

You can access the live application here:  
👉 [https://know-your-disease.onrender.com](https://know-your-disease.onrender.com)

---

## Features

- **Symptom Selection**: Users can select multiple symptoms from a searchable dropdown list.
- **AI-Powered Prediction**: The system uses a trained machine learning model to predict the most likely disease based on the selected symptoms.
- **User-Friendly Interface**: A clean and responsive design ensures a seamless user experience.
- **Real-Time Results**: Predictions are displayed instantly after submitting the form.
- **Deployed on Render**: The application is hosted on Render for easy access.

---

## Technologies Used

- **Frontend**:
  - HTML, CSS, JavaScript
  - Bootstrap for responsive design
  - Select2 for searchable dropdowns
- **Backend**:
  - Flask (Python web framework)
- **Machine Learning**:
  - Scikit-learn for model training and prediction
  - Joblib for model serialization
- **Deployment**:
  - Render for hosting the Flask application

---

## How It Works

1. **Symptom Selection**: Users select their symptoms from a dropdown list. The list is searchable, making it easy to find specific symptoms.
2. **Feature Vector Creation**: The selected symptoms are converted into a binary feature vector, where each symptom is represented as `1` (present) or `0` (absent).
3. **Model Prediction**: The feature vector is passed to the trained machine learning model, which predicts the most likely disease.
4. **Result Display**: The predicted disease is displayed to the user in real-time.

---

## Project Structure

```
disease-prediction-system/
├── app.py                  # Flask application and routing
├── templates/              # HTML templates
│   └── index.html          # Main page with symptom selection form
├── static/                 # Static files (CSS, JS, images)
├── disease_prediction_model.joblib  # Trained machine learning model
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## Setup and Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AnnNaserNabil/disease-prediction-system.git
   cd disease-prediction-system
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask Application**:
   ```bash
   python app.py
   ```

4. **Access the Application**:
   Open your browser and navigate to `http://127.0.0.1:5000`.

---

## Deployment

The application is deployed on **Render**, a cloud platform for hosting web applications. The deployment process involves:

1. Pushing the code to a GitHub repository.
2. Connecting the repository to Render.
3. Configuring the build and start commands.
4. Deploying the application.

The live application can be accessed at:  
👉 [https://know-your-disease.onrender.com](https://know-your-disease.onrender.com)

---

## Future Enhancements

- **Expand Symptom List**: Add more symptoms to improve prediction accuracy.
- **Multi-Disease Prediction**: Allow the model to predict multiple possible diseases.
- **User Accounts**: Enable users to save their symptom history and predictions.
- **Mobile App**: Develop a mobile version of the application for easier access.

---

## Credits

This project was created by **[Ann Naser Nabil](https://github.com/AnnNaserNabil)**.  
Feel free to contribute or provide feedback!

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
