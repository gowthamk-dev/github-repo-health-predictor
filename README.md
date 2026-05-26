# 📊 GitHub Repo Health Predictor

A Machine Learning-powered web dashboard that analyzes real-time GitHub metrics to predict whether a repository is actively maintained or inactive.

## 🎯 Project Goal
To help developers and decision-makers instantly gauge the vitality and maintenance status of any open-source GitHub project using data-driven insights.

## 🚀 Features
- **🔍 Real-Time Metrics Extraction**: Uses the GitHub API to fetch commits, issues, PRs, and star history.
- **🤖 Machine Learning Prediction**: Deploys a trained Random Forest model to classify the repo as Active or Inactive.
- **📊 Comprehensive Visualizations**: View activity bars, engagement pie charts, and model feature importance.
- **🌍 Bulk Analysis Mode**: Evaluate multiple repositories at once to compare health scores.
- **📄 Instant Exports**: Download your prediction analytics instantly as **CSV, HTML, or PDF** reports.
- **👆 Simple & Clean UI**: Built with Streamlit for a smooth and responsive user experience.

## 🧠 AI Usage
- **Random Forest Classifier**: Trained on historical repository data (commits, PRs, contribution days, forks) to accurately predict future maintenance activity.
- **Automated Feature Engineering**: Converts raw GitHub API data into normalized feature vectors for immediate prediction.

## 🛠️ Tech Stack
- **Python 3**
- **Streamlit** (Web Dashboard)
- **Scikit-Learn** (Machine Learning Model)
- **Pandas / Matplotlib / Seaborn** (Data Processing & Visualization)
- **PyGitHub** (API Integration)

## 📱 Application Flow
1. **Configuration**: Enter a GitHub Personal Access Token (for higher API rate limits).
2. **Selection**: Choose to analyze a Single Repository or Multiple Repositories.
3. **Input**: Enter the target `https://github.com/user/repo` link(s).
4. **Analysis**: The app fetches real-time data and runs it through the ML model.
5. **Results**: View the health status (Active/Inactive), probabilities, and metric charts.
6. **Export**: Click to download the generated report in PDF, HTML, or CSV formats.

## 🔧 Setup Instructions
1. **Clone the repo**
   ```bash
   git clone https://github.com/gowthamk-dev/github-repo-health-predictor.git
   cd github-repo-health-predictor
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the application**
   ```bash
   streamlit run app.py
   ```
4. **Open in browser**
   Navigate to `http://localhost:8501` and enter your GitHub URLs!

## 👨‍💻 Author
**Gowtham K**

## 📝 Note
This is an educational prototype demonstrating the integration of machine learning pipelines with live API data using interactive web components.
