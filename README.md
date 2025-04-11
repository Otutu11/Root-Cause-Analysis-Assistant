

# 🧠 Root Cause Analysis Assistant

A lightweight Python-based assistant that uses machine learning and synthetic data to predict the **root causes** of technical or operational issues based on observed problems and contributing factors.

## 📌 Project Overview

This project simulates and automates the **Root Cause Analysis (RCA)** process using a decision tree model trained on synthetic incident data. It can assist system administrators, QA engineers, and operations teams in identifying probable causes behind system anomalies such as crashes, slow responses, or network drops.

---

## 🛠 Features

✅ Synthetic dataset generation  
✅ Decision Tree classifier for root cause prediction  
✅ Easy-to-use CLI assistant  
✅ Exportable dataset (`.xlsx`) for further analysis  
✅ Lightweight and extendable

---

## 📂 Repository Structure

```bash
root-cause-analysis-assistant/
├── root_cause_assistant.py       # Main Python script
├── synthetic_root_cause_data.xlsx # Generated synthetic dataset
├── root_cause_model.pkl          # Trained Decision Tree model (auto-generated)
└── README.md                     # This file

⚙️ Installation

    Clone the repository:

git clone https://github.com/yourusername/root-cause-analysis-assistant.git
cd root-cause-analysis-assistant

    Install required dependencies:

pip install pandas numpy scikit-learn joblib

▶️ Usage

Run the assistant script in your terminal:

python root_cause_assistant.py

Enter the problem and observed factor when prompted to receive the most likely root cause.
🧪 Example

Problem: System Crash
Observed Factor: High CPU Usage

Predicted Root Cause: Hardware Failure

📊 Dataset Preview

The synthetic dataset includes the following fields:
Problem	Observed_Factor	Root_Cause
System Crash	High CPU Usage	Hardware Failure
Data Loss	Low Disk Space	Configuration Error
Connection Drop	Network Latency	Network Issue
...	...	...
🔍 Model Logic

A simple DecisionTreeClassifier from scikit-learn is trained on encoded features (Problem, Observed_Factor) to classify the Root_Cause. You can inspect or retrain the model by modifying train_model() in root_cause_assistant.py.
🚀 Future Improvements

    Add web-based interface (e.g., Flask or Streamlit)

    Integrate real-world RCA logs

    Add explainability (e.g., SHAP values)

    Support multi-factor and temporal RCA

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
🤝 Contributing

Contributions are welcome! Please fork the repo, make your changes, and submit a pull request.
👨‍💻 Author


📫 Connect with me on LinkedIn
🌍 AI + ML + RCA Enthusiast | Geospatial + Climate Tech Developer


Let me know if you’d like me to also generate a `LICENSE` file or convert this into a downloadable `.md` file
