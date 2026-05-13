# Energy Consumption Prediction

This project predicts household energy consumption using machine learning.
# ⚡ Energy Consumption Prediction

A machine learning–based web application that predicts energy consumption based on building and environmental parameters.  
The project includes a trained ML model, a Flask web interface, and is deployed online for real-time usage.

🌐 **Live Demo:**  
https://energy-consumption-prediction-2-3.onrender.com/

📂 **GitHub Repository:**  
https://github.com/P-lahari93/Energy-Consumption-Prediction-2

---

## 📌 Overview

Energy Consumption Prediction is designed to estimate energy usage efficiently using historical data and machine learning techniques.  
Users can input parameters through a web interface and instantly receive predicted energy consumption values.

This project demonstrates:
- Data preprocessing
- Machine learning model training
- Flask-based web application
- Cloud deployment using Render

---

## 🚀 Features

- User-friendly web interface
- Real-time energy consumption prediction
- Machine learning model integration
- Dataset upload support
- Fully deployed online application

---

## 🧠 How It Works

1. The dataset is preprocessed and used to train a machine learning model.
2. The trained model and scaler are saved as `.pkl` files.
3. The Flask backend loads the model and scaler.
4. User inputs are processed and passed to the model.
5. The predicted energy consumption is displayed on the web page.

---

## 📁 Project Structure
Energy-Consumption-Prediction-2/
│
├── data/ # Dataset files
├── static/ # CSS, images
├── templates/ # HTML templates
├── app.py # Flask application
├── train_model.py # Model training script
├── database.py # Database configuration
├── model.pkl # Trained ML model
├── scaler.pkl # Data scaler
├── requirements.txt # Python dependencies
├── Procfile # Render deployment config
└── README.md # Project documentation

## 🛠 Tech Stack

- **Python**
- **Flask**
- **Machine Learning**
- **HTML / CSS**
- **Render (Deployment)**

---

## 📦 Installation (Local Setup)

1. Clone the repository:
```bash
git clone https://github.com/P-lahari93/Energy-Consumption-Prediction-2.git
cd Energy-Consumption-Prediction-2
Create a virtual environment:

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Run the application:

python app.py
Open in browser:

http://localhost:5000
📊 Usage
Enter required parameters in the web form

Submit the form

View predicted energy consumption instantly

🤝 Contributions
Contributions are welcome!
Feel free to fork the repository, make improvements, and submit a pull request.

📄 License
This project is open-source and available under the MIT License.


---

