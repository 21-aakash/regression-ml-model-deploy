
## 🏡 Boston House Price Prediction Web App

An intuitive and responsive web application that predicts house prices based on various input features using a machine learning model trained on the Boston housing dataset.

---
#### Input Fields
- 🔢 **OverallQual** – Overall material and finish quality (1-10)
- 🏠 **GrLivArea** – Above-ground living area in square feet
- 🚗 **GarageCars** – Garage car capacity
- 🧱 **TotalBsmtSF** – Basement square footage
- 🛁 **FullBath** – Number of full bathrooms
- 🏗️ **YearBuilt** – Year the house was originally built
- 🛠️ **YearRemodAdd** – Year of last remodeling
- 🪟 **1stFlrSF** – First floor area in sq ft
- 🛏️ **TotRmsAbvGrd** – Total rooms (excluding bathrooms)
- 🔥 **Fireplaces** – Number of fireplaces

---

### 🚀 Getting Started

#### 1. Clone the Repo

```bash
git clone https://github.com/your-username/boston-price-predictor.git
cd boston-price-predictor
```

#### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

#### 3. Run Flask App

```bash
python app.py
```

#### 4. Visit Locally

Open browser and navigate to:  
`http://localhost:5000`

---

### 🧠 ML Model Info

- Trained using `Linear Regression` (or your chosen regressor)
- Scikit-learn used for training and serialization
- Model stored as `model.pkl` and loaded in Flask app

---

### 🗂 Project Structure

```
├── static/
│   └── styles.css         # Optional external CSS
├── templates/
│   └── index.html         # Main UI
├── model.pkl              # Trained ML model
├── app.py                 # Flask backend
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

### 📸 Screenshots

_Optional: Add screenshots here if needed_

---

### 🧪 Example Test Input

```json
{
  "OverallQual": 8,
  "GrLivArea": 1500,
  "GarageCars": 2,
  "TotalBsmtSF": 800,
  "FullBath": 2,
  "YearBuilt": 2005,
  "YearRemodAdd": 2010,
  "1stFlrSF": 1100,
  "TotRmsAbvGrd": 6,
  "Fireplaces": 1
}
```

---

### 📃 License

MIT © 2025 – YourName  
Open to contributions and improvements! 🚀

---

Want a version with badges (like Python version, Flask, License)? Let me know and I’ll add them too.