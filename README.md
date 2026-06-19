


# Project Overview

***A full-stack web application for detecting web attacks using AI/ML, featuring a modern cyber-themed UI and real-time prediction.***


   





## Features

- **AI-Powered Detection:** Uses a trained Random Forest model for web attack prediction.
- **User-Friendly Web Interface:** Enter network flow features and get instant predictions.
- **Loader & Animated UI:** Modern cyberpunk design with animated loader and modal results.
- **Input Validation:** Ensures all required features are provided and valid.
- **Prediction Modal:** Displays prediction and input summary in a stylish popup.





---

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript (Vanilla), Jinja2 (Flask templating)
- **Backend:** Python, Flask
- **Machine Learning:** scikit-learn, imbalanced-learn, joblib
- **Model:** Random Forest Classifier (trained on 4 selected features)
- **Other:** Bootstrap (optional), Pandas, NumPy



## Project Structure

```
CYBER_PROJECT/
│
├── app.py                        # Flask backend
├── random_forest_model_4_features.joblib  # Trained ML model
├── web_attacks_balanced.csv      # Dataset (for reference/training)
├── Untitled.ipynb                # Model training notebook
├── static/
│   └── assets/
│       └── i-am-free-anonymous.960x540.mp4  # Background video
└── templates/
    └── index.html                # Main web UI
```

---







