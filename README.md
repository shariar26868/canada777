# 📂 Project Structure — `canada777`

```text
canada777/
├── venv/                      # Python virtual environment (excluded from version control)
├── app/                       # Core application package
│   ├── config/                # Configuration files and constants
│   │   └── settings.py
│   ├── routes/                # API route handlers for different features
│   │   ├── churn.py
│   │   ├── engagement.py
│   │   ├── fraud.py
│   │   ├── ltv.py
│   │   └── segmentation.py
│   ├── services/              # Business logic and data-related services
│   │   └── data_service.py
│   ├── utils/                 # Utility functions, logging, API clients, etc.
│   │   ├── api_client.py
│   │   └── logger.py
│   └── main.py                # Entry point to run the application
├── scripts/                   # Standalone scripts for tasks like model training
│   └── train_models.py
├── requirements.txt           # Project dependencies
├── data/                      # Data assets and ML model files
│   ├── bonuses.json
│   ├── deposits.json
│   ├── logs.json
│   ├── players.json
│   └── models/                # Pre-trained machine learning models
│       ├── churn_model.pkl
│       ├── engagement_model.pkl
│       ├── fraud_model.pkl
│       ├── ltv_model.pkl
│       └── segmentation_model.pkl
