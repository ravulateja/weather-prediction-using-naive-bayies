🌦️ Weather Prediction using Naive Bayes (Rain / No Rain)


This project uses the Naive Bayes classification algorithm to predict whether it will Rain or Not Rain based on historical weather data.

🧠 About the Project
Naive Bayes is a probabilistic classifier based on Bayes’ Theorem, assuming independence among predictors. In this project, we apply it to classify weather outcomes as Rain or No Rain.

📁 Dataset
The dataset contains weather-related features such as:

Outlook (Sunny, Overcast, Rain)

Temperature (Hot, Mild, Cool)

Humidity (High, Normal)

Wind (Strong, Weak)

Rain (Yes, No) ← Target variable

You can use a CSV file (weather.csv) or hardcoded data for training.

Example rows

Outlook	Temperature	Humidity	Wind	Rain
Sunny	Hot	High	Weak	No
Rain	Mild	Normal	Strong	Yes
Overcast	Cool	High	Weak	No

⚙️ Installation & Requirements
Python Version
Python 3.6 or higher

Libraries
Install required libraries using pip:


pip install pandas scikit-learn

🚀 How to Run
Clone the Repository


git clone https://github.com/your-username/weather-prediction-using-naive-bayes.git

cd weather-prediction-using-naive-bayes

Run the Python Script



python weather_prediction.py

Output

The script will train the model and predict whether it will rain based on test inputs:


Prediction: Rain

Accuracy: 91.67%
🧪 Model Logic
Calculates prior and likelihood probabilities for each class (Rain / No Rain)

Applies Bayes’ Theorem to make predictions

Can be implemented from scratch or using scikit-learn’s GaussianNB or CategoricalNB

📂 Project Structure

weather-prediction-using-naive-bayes/
│
├── weather_prediction.py     # Python script
├── weather.csv               # Weather dataset
└── README.md                 # This file
📘 References
Naive Bayes - Wikipedia

scikit-learn: Naive Bayes

📄 License
This project is licensed under the MIT License.
