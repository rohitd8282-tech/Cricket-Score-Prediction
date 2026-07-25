# 🏏 Cricket Score Predictor

A Machine Learning web application that predicts the final score of a cricket match based on the current match situation.

---

## 🚀 Features

* Predicts final score in real-time
* Simple and interactive UI using Streamlit
* Uses Machine Learning (Random Forest Regressor)
* Fast and lightweight

---

## 📊 Input Parameters

The model takes the following inputs:

* Current Runs
* Wickets Fallen
* Overs Completed
* Runs in Last 5 Overs
* Wickets in Last 5 Overs

---

## 🧠 Machine Learning Model

* Algorithm: Random Forest Regressor
* Trained on historical cricket match data
* Outputs predicted final score

---

## 📁 Project Structure

```
cricket-score-predictor/
│
├── app.py              # Streamlit app
├── train_model.py      # Model training script
├── model.pkl           # Trained model file
├── dataset.csv         # Dataset
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/your-username/cricket-score-predictor.git
cd cricket-score-predictor
```

2. Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Usage

### Step 1: Train the model

```
python train_model.py
```

### Step 2: Run the app

```
streamlit run app.py
```

---

## 📷 Demo

Enter match details and click **Predict Score** to get the predicted total.

---

## 🌐 Deployment

You can deploy this app using:

* Streamlit Cloud
* Vercel (for frontend)
* Heroku

---

## 🔮 Future Improvements

* Add team & venue-based prediction
* Improve accuracy using advanced models (XGBoost)
* Add win probability prediction
* Use real IPL dataset

---

## 🤝 Contributing

Feel free to fork this repository and improve the project.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙌 Author

Developed by** ROHIT KUMAR**

---

⭐ If you like this project, give it a star!
