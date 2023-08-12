# Buy Predictor Flask App

The **Buy Predictor Flask App** is a web application that predicts whether a user will buy from a social network ad based on input features like salary, age, and gender. The prediction model uses a trained Naive Bayes classifier.

## 🚀 Getting Started

### Prerequisites

- Python 3.x (Python 3.6 or later recommended)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/buy-predictor-flask-app.git
   cd buy-predictor-flask-app
🛠️ Data Modeling and Training
Prepare your dataset with features like salary, age, and gender, along with corresponding labels indicating whether a user bought from the social network ad.

Perform data preprocessing, including feature scaling and encoding categorical variables.

Train a Naive Bayes classifier using libraries like scikit-learn. Hyperparameter tuning can significantly improve model performance.

Serialize the trained model and preprocessing components using the pickle module.

⚙️ Hyperparameter Tuning
Experiment with various hyperparameters of the Naive Bayes classifier to optimize performance.

Techniques like grid search or randomized search can help you find the best combination of hyperparameters.

Aim to achieve a high accuracy, such as the 92% accuracy you mentioned.
