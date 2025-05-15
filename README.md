# COVID-19 Data Analysis Project

## 📌 Project Description
A data analysis project examining COVID-19 trends across different countries, focusing on case progression, vaccination rates, and mortality patterns. The project uses Python for data processing and visualization.

## 🎯 Objectives
1. Analyze COVID-19 spread patterns in selected countries (USA, India, Kenya)
2. Compare vaccination rollout effectiveness
3. Examine case fatality rate differences
4. Visualize temporal trends in cases and deaths

## 🛠️ Tools & Libraries Used
- **Python 3**
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly Express
- **Geospatial**: GeoPandas (optional)
- **Notebook Environment**: Jupyter Lab/Notebook

## 🚀 How to Run/View the Project
### Option 1: View Online
1. The notebook is rendered directly on GitHub
2. For better rendering, use [nbviewer](https://nbviewer.org/)

### Option 2: Run Locally
```bash
# Clone repository
git clone https://github.com/carrendede/covid-analysis.git

# Navigate to project directory
cd covid-analysis

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter lab

📂 Project Structure
covid-analysis/
├── data/                    # Raw data files
│   └── owid-covid-data.csv
├── notebooks/               # Jupyter notebooks
│   └── covid_analysis.ipynb
├── visuals/                 # Generated visualizations
├── requirements.txt         # Python dependencies
└── README.md                # This file
