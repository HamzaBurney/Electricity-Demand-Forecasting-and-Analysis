# Electricity Demand Forecasting and Analysis

This project implements various machine learning models to forecast electricity demand across multiple cities in the United States. It combines weather data, temporal features, and demand patterns to create robust forecasting models and identify patterns through clustering.

## Features

- Multiple forecasting models:
  - LSTM Neural Network
  - XGBoost
  - Linear Regression
  - Random Forest
- Clustering analysis using PCA and K-means
- Anomaly detection using multiple methods
- Interactive Streamlit dashboard
- Comprehensive model performance analysis

## Project Structure

```
├── app.py                 # Streamlit dashboard
├── improved_models.py     # Enhanced model implementations
├── models/               # Saved model files
├── data/                 # Data files
├── project_report.md     # Detailed project report
└── requirements.txt      # Project dependencies
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/electricity-demand-forecasting.git
cd electricity-demand-forecasting
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit dashboard:
```bash
streamlit run app.py
```

2. Access the dashboard at `http://localhost:8501`

## Model Performance

| Model | MAE | RMSE | R² Score |
|-------|-----|------|----------|
| LSTM Neural Network | 15.23 | 22.45 | 0.9999 |
| Improved XGBoost | 24.77 | 35.82 | 0.9999 |
| Improved Linear Regression | 40.81 | 70.30 | 0.9997 |
| Improved Random Forest | 516.77 | 748.47 | 0.9672 |

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Weather data sources
- Electricity demand data providers
- Open-source libraries and tools used in this project 