# 📊 HCI Anomaly Detection System

An interactive Streamlit web application to **detect anomalies in log datasets** using machine learning (Isolation Forest). It supports both uploading custom CSVs and selecting from sample datasets.


---

## 🔍 Features

- 📁 Upload your own CSV file or choose from built-in datasets
- 🤖 AI-powered anomaly detection using Isolation Forest
- 📈 Interactive exploration of logs and outlier results
- 💡 Simple and intuitive interface built with Streamlit

---

## 🚀 Live Demo


---

## 📂 Sample Datasets

- `web_logs.csv`: Web application log data
- `db_logs.csv`: Database access log data
- `file_logs.csv`: File system access log data

Located inside the `sample_datasets/` folder. Selectable from the dropdown menu in the app.

---

## 🛠️ How to Run Locally

```bash
git clone https://github.com/your-username/hci-anomaly.git
cd hci-anomaly
pip install -r requirements.txt
streamlit run app.py
