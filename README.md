Crop Yield Prediction App

A full-stack Machine Learning mini project that predicts crop yield based on environmental conditions, soil type, crop details, and farming practices.

This project uses:

Frontend: React + Vite + Tailwind CSS
Backend: FastAPI
Machine Learning: Random Forest Model
Dataset Handling: Pandas
📌 Project Title and Brief Description
Project Title

🌾 Crop Yield Prediction App

Brief Description

Crop Yield Prediction App is a Machine Learning based mini project developed to predict agricultural crop yield using environmental and farming parameters. The project helps users estimate crop production based on factors like rainfall, temperature, soil type, irrigation, and fertilizer usage.

The application uses a trained Random Forest Machine Learning model integrated with a FastAPI backend and a React frontend to provide accurate and user-friendly crop yield predictions.

🛠️ Technology Stack and Tools Used
Frontend Technologies
React.js
Vite
Tailwind CSS
Axios
Material UI
Backend Technologies
FastAPI
Python
Uvicorn
Machine Learning Tools
Scikit-learn
Pandas
NumPy
Joblib
Development Tools
VS Code
Git & GitHub
Postman
📌 Features and Functionalities Implemented

✅ Predict crop yield using Machine Learning
✅ User-friendly frontend interface
✅ FastAPI REST API integration
✅ Real-time prediction response
✅ Input validation for agricultural data
✅ Random Forest Regression model implementation
✅ Backend and frontend integration
✅ Agricultural dataset processing and training

📌 Features

✅ Predict crop yield in kg/hectare
✅ FastAPI backend with REST API
✅ Modern React frontend
✅ Machine Learning model integration
✅ User-friendly interface
✅ Uses real agricultural parameters

🛠️ Tech Stack
Frontend
React
Vite
Tailwind CSS
Axios
Material UI
Backend
FastAPI
Uvicorn
Pandas
Joblib
Scikit-learn
Machine Learning
Random Forest Regression
📂 Project Structure
CropYieldApp/
│
├── backend/
│   ├── app.py
│   ├── train_model.py
│   ├── rf_model.joblib
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── crop_yield.csv
🚀 Installation and Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/crop-yield-prediction-app.git
cd crop-yield-prediction-app
⚙️ Backend Setup
Move to Backend Folder
cd backend
Create Virtual Environment
Windows
python -m venv venv
venv\Scripts\activate
Linux/Mac
python3 -m venv venv
source venv/bin/activate
Install Dependencies
pip install -r requirements.txt
Run Backend Server
python app.py

Backend will start at:

http://127.0.0.1:8000
💻 Frontend Setup
Open New Terminal
cd frontend
Install Dependencies
npm install
Run Frontend
npm run dev

Frontend will run at:

http://localhost:5173
🤖 Machine Learning Model

The project uses a Random Forest Regressor model trained on agricultural data.

Input Features
Region
Soil Type
Crop
Rainfall
Temperature
Weather Condition
Fertilizer Usage
Irrigation Usage
Days to Harvest
Output
Predicted Crop Yield (kg/hectare)
🔌 API Endpoint
POST /predict
Request Example
{
  "Region": "Madhya Pradesh",
  "Soil_Type": "Black Soil",
  "Crop": "Wheat",
  "Rainfall_mm": 120.5,
  "Temperature_Celsius": 28.5,
  "Weather_Condition": "Sunny",
  "Fertilizer_Used": true,
  "Irrigation_Used": true,
  "Days_to_Harvest": 110
}
Response Example
{
  "predicted_yield_kg_per_hectare": 5234.67
}
📊 Dataset

The dataset file used in this project:

crop_yield.csv

It contains agricultural and environmental information used for training the machine learning model.

🧠 Future Improvements
Add user authentication
Deploy project on cloud
Add live weather API integration
Improve prediction accuracy
Add data visualization dashboard
Mobile responsive UI improvements
📷 Screenshots

C:\Users\DELL\OneDrive\Pictures\Screenshots\Screenshot 2026-04-23 140904.png
C:\Users\DELL\OneDrive\Pictures\Screenshots\Screenshot 2026-04-23 140943.png
C:\Users\DELL\OneDrive\Pictures\Screenshots\Screenshot 2026-04-23 141141.png

🧪 How the Project Works
User enters crop and environmental details.
Frontend sends data to FastAPI backend.
Backend loads trained ML model.
Model predicts crop yield.
Result is displayed on the frontend.
👨‍💻 Author

Aashutosh Yadav
B.Tech CSE Mini Project

📜 License

This project is for educational and learning purposes.
