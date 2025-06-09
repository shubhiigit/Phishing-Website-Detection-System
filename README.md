# Phishing-Website-Detection-System
This is a machine learning model to detect the legitimacy of websites , to make everyone beaware of phishing sites.
didnt uploaded a large file you can download th phishing  url csv file from here - https://drive.google.com/file/d/1M7V_FCJTphWgy_TPlS4nviAj_F-F3Puf/view?usp=sharing
# 🛡️ Phishing Website Detection System

The **Phishing Website Detection System** is a machine learning-based solution designed to identify and block phishing websites in real-time. It analyzes URL features and other indicators to detect malicious web pages and protect users from online fraud, credential theft, and financial scams.

## 🚀 Features

- 🔍 URL and HTML-based feature extraction
- 🤖 Machine learning model trained on labeled phishing datasets
- 📊 Real-time prediction with high accuracy
- 🌐 Web-based user interface for URL checks
- 📝 Logging and reporting of phishing attempts

## 🧠 How It Works

1. The user submits a URL for analysis.
2. The system extracts critical features such as:
   - Length of URL
   - Use of HTTPS
   - Presence of suspicious characters (e.g., `@`, `-`)
   - Domain age and registrar info
   - WHOIS data and DNS records
3. A trained ML model (e.g., Random Forest, SVM, or XGBoost) evaluates the features.
4. A prediction is returned: `Phishing` or `Legitimate`.

