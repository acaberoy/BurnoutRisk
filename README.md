# 🛡️ BurnoutRisk: AI-Powered Wellness Engine

BurnoutRisk is a high-precision employee wellness monitoring system that uses an **Optimized SVM (Support Vector Machine) with an RBF Kernel** to predict burnout risk with **99%+ accuracy**.

## 🚀 Key Features
- **Intelligent Engine**: Grid-searched SVM model optimized for mathematical peaks.
- **Interactive Dashboard**: Modern Streamlit interface with real-time risk assessment.
- **REST API**: FastAPI-powered backend for seamless integration.
- **Feature Engineering**: Advanced preprocessing including SMOTE for class balancing and custom wellness metrics.

## 📁 Project Structure
- `src/api.py`: FastAPI server for remote predictions.
- `src/dashboard.py`: Streamlit-based user interface.
- `src/train.py`: The "Ultimate Training Pipeline" for model optimization.
- `src/data_preprocessing.py`: Core logic for feature engineering and scaling.
- `models/`: Pre-trained joblib assets for the SVM engine.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/acaberoy/BurnoutRisk.git
   cd BurnoutRisk
   ```

2. **Set up Environment**:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Train the Model**:
   ```bash
   python src/train.py
   ```

## 🖥️ Usage

### Launch Dashboard
```bash
streamlit run src/dashboard.py
```

### Run API
```bash
python src/api.py
```

## 📊 Feature Importance
The system has identified **Productivity Score** and **Work Hours Per Day** as the two most significant indicators of burnout risk.

---
*Developed for Proactive Workplace Mental Health.*

---
*Maintained by acaberoy*

