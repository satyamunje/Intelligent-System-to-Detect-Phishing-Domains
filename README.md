# 🛡️ Intelligent System to Detect Phishing Domains  
An AI/ML-powered system designed to identify and detect phishing domains with high accuracy.  
This project helps protect users from deceptive websites that imitate legitimate ones to steal sensitive information.

---

## 📌 Overview  
Phishing attacks are one of the most widespread and dangerous cybersecurity threats.  
Attackers create websites that closely mimic trusted domains, tricking users into revealing login credentials, financial data, or other personal information.

This project uses **Machine Learning + Feature Engineering + Domain Analysis** to accurately classify whether a given website/domain is **Legitimate** or **Phishing**.

---

## 🎯 Objectives  

- ✔ Detect phishing domains using intelligent ML techniques  
- ✔ Reduce false positives and improve detection confidence  
- ✔ Analyze domain-level features (URL structure, SSL, patterns, etc.)  
- ✔ Build a scalable system usable in browsers or security tools  

---

## ⚠️ Why Phishing Attacks Are Dangerous  
Phishing attacks exploit human trust.  
They often involve:

- Fake login pages  
- Email scam links  
- Misleading domain names  
- Social-engineering tricks  

Such attacks lead to:

- 🔓 Data breaches  
- 💸 Financial fraud  
- 🛑 Identity theft  
- 📉 Reputational loss  

---

## 🧠 How Attackers Imitate Genuine Domains  
Cybercriminals often:

- Mimic UI of trusted websites  
- Use visually similar domain names  
  - Example: `paypa1.com` vs `paypal.com`  
- Use fake SSL certificates  
- Redirect users to malicious pages  

Our system detects such manipulations through ML-based analysis.

---

## 🧬 Technical Approach  

### ✔ Dataset  
- Phishing & legitimate domain datasets collected from:  
  - PhishTank  
  - UCI repository  
  - Manually curated domain lists  

### ✔ Feature Engineering  
Extracted key web-features such as:

- URL length  
- Suspicious characters (“@”, “//”, “-”)  
- Presence of HTTPS  
- Domain age  
- Subdomain count  
- IP-based URLs  
- Redirection count  

### ✔ Machine Learning Models Used  
- Logistic Regression  
- Random Forest  
- Decision Tree  
- XGBoost  
- SVM  

> Achieved high accuracy by comparing model performances and optimizing hyperparameters.

---

## 🛠️ Tech Stack  

| Category | Technologies |
|---------|--------------|
| **Languages** | Python |
| **Libraries** | NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn |
| **Tools** | Jupyter Notebook, VS Code |
| **Domain** | Cybersecurity, Machine Learning |

---

## 📊 Results & Insights  
- High accuracy in detecting phishing patterns  
- URL-based features were most influential  
- Random Forest & XGBoost delivered the best performance  
- Effective at detecting newly created malicious domains  

(Add charts here if available)

---

## 🚀 How to Run the Project  

1. Clone the repo  
git clone https://github.com/satyamunje/Intelligent System to Detect Phishing Domains

markdown
Copy code

2. Install requirements  
pip install -r requirements.txt

markdown
Copy code

3. Run the notebook  
jupyter notebook phishing_detection.ipynb

yaml
Copy code

4. Test with a sample URL/domain  

---

## 📁 Folder Structure  
phishing-detection/
│── data/
│── models/
│── notebooks/
│── phishing_detection.ipynb
│── README.md
│── requirements.txt

yaml
Copy code

---

## 🎯 Future Enhancements  
- Deploy as a real-time browser extension  
- Add deep learning models (LSTM, BERT)  
- Integrate live domain lookup APIs  
- Improve UI with a web dashboard  
- Real-time phishing alert system  

---

## 👨‍💻 Author

**Satya Munje**  
CSE Student | AI/ML Researcher | Cybersecurity Enthusiast  

🔗 LinkedIn: https://www.linkedin.com/in/satyamunje/  
📧 Email: satyamunje@gmail.com  

---

⭐ *If you find this project useful, please give it a star!*
