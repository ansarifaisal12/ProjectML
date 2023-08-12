# Buy Predictor Flask App

The **Buy Predictor Flask App** is a web application that predicts whether a user will buy from a social network ad based on input features like salary, age, and gender. The prediction model uses a trained Naive Bayes classifier.

## 🚀 Getting Started

### Prerequisites

- Python 3.x (Python 3.6 or later recommended)

### Installation

1. **Clone the repository:**

   ```bash
   git https://github.com/ansarifaisal12/ProjectML.git
   cd buy-predictor-flask-app
## 🛠️ Data Modeling and Training
Prepare a dataset with features like salary, age, and gender, along with corresponding labels indicating whether a user bought from the social network ad.
Perform data preprocessing, including feature scaling and encoding categorical variables. 
Train a Naive Bayes classifier using libraries like scikit-learn. Hyperparameter tuning can significantly improve model performance. 
Serialize the trained model and preprocessing components using the pickle module.

## ⚙️ Hyperparameter Tuning
Experiment with various hyperparameters of the Naive Bayes classifier to optimize performance.
Techniques like grid search or randomized search can help you find the best combination of hyperparameters.
Aim to achieve a high accuracy, such as the 92% accuracy.

## 🌐 Flask Web Application Deployment
Place the trained model files (NBclassifier.pkl and scaler.pickle) in the same directory as app.py.
Update the Flask app code to load the trained model and preprocessing components.

## 🚀 Predictions
Enter the required information (salary, age, gender) in the input fields on the homepage.
Click the "Predict" button to submit the form.
The prediction result will be displayed on the same page.

## 📝 Notes
This application uses Flask to create a simple web interface for interacting with the prediction model.
Warnings related to InconsistentVersionWarning are due to version differences between the models used during pickling and the current version of scikit-learn.
This application is for educational and demonstration purposes.

## 📚 References
Flask Documentation
scikit-learn Documentation
## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.





