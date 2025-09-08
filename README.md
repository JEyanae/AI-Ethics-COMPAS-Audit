# 🌍⚖️ AI Ethics Assignment – Designing Responsible and Fair AI Systems  

## 📌 Overview
This repository contains my **solo submission** for the **PLP AI Ethics Assignment**.  
The theme of the assignment is:  
**“Designing Responsible and Fair AI Systems.”**

The project demonstrates theoretical understanding, case study analysis, a fairness audit of the COMPAS dataset, ethical reflection, and a bonus policy proposal.  

---

## 🎯 Assignment Structure  

### **Part 1: Theoretical Understanding (30%)**
📄 [Part1_Theory.pdf](./Part1_Theoretical_AI_Ethics.pdf)  
- Q1: Definition and examples of **algorithmic bias**  
- Q2: Difference between **transparency** and **explainability** in AI  
- Q3: Impact of **GDPR** on AI development  
- Ethical Principles Matching (justice, non-maleficence, autonomy, sustainability)  

---

### **Part 2: Case Study Analysis (40%)**
📄 [CaseStudies.pdf](./CaseStudies.pdf)  
- **Case 1: Amazon Hiring Tool** – source of bias, proposed fixes, fairness metrics  
- **Case 2: Facial Recognition in Policing** – ethical risks, deployment policies  

---

### **Part 3: Practical Audit (25%)**
📊 Files:  
- Dataset: [compas-scores-two-years.csv](./compas-scores-two-years.csv)  
- Notebook: [compas_analysis.ipynb](./compas_analysis.ipynb)  
- Report: [COMPAS_Report.pdf](./COMPAS_Report.pdf)  

Performed a fairness audit of the **COMPAS Recidivism Dataset** using Python and fairness metrics.  
- Findings: racial disparities in COMPAS scores, with African-American defendants disproportionately labeled as high-risk.  
- Visualizations: score distributions by race, logistic regression analysis.  
- Remediation steps: fairness-aware ML, auditing, transparency, and contextual review.  

---

### **Part 4: Ethical Reflection (5%)**
📄 [Part4_Ethical_Reflection.pdf](./Part4_Ethical_Reflection.pdf)  
Reflection on how I will apply **ethical AI principles** in my own projects, ensuring fairness, accountability, and human-centric design.  

---

### **Bonus Task (Extra 10%)**
📄 [BonusTask_Ethical_AI_in_Healthcare.pdf](./BonusTask_Ethical_AI_in_Healthcare.pdf)  
Policy proposal for **ethical AI in healthcare**, including:  
- Patient consent protocols  
- Bias mitigation strategies  
- Transparency requirements  

---

## 📂 Repository Files  

AI-Ethics-COMPAS-Audit/
│
├── compas-scores-two-years.csv # Dataset
├── compas_analysis.ipynb # Bias audit notebook
│
├── Part1_Theory.pdf # Theoretical Q&A + principles
├── CaseStudies.pdf # Case study analyses
├── COMPAS_Report.pdf # Practical audit report
├── Part4_Ethical_Reflection.pdf # Personal reflection
├── BonusTask_Ethical_AI_in_Healthcare.pdf # Bonus policy proposal
│
├── Final_Assignment.pdf # Consolidated submission
└── README.md # Assignment guide


## ⚙️ How to Reproduce Practical Audit  

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/AI-Ethics-COMPAS-Audit.git
   cd AI-Ethics-COMPAS-Audit
Open the notebook:

bash
Copy code
jupyter notebook compas_analysis.ipynb
Or upload it to Google Colab.

Install dependencies:

bash
Copy code
pip install pandas matplotlib seaborn scikit-learn aif360
🏆 Final Submission
All parts (theory, case studies, practical audit, reflection, and bonus) have been merged into one document:
👉 Final_Assignment.pdf

🙏 Acknowledgements
ProPublica for the COMPAS dataset.

IBM AI Fairness 360 Toolkit for bias detection methods.

PLP Academy for guidance on ethical AI learning.


This README is **assignment-oriented**:  
- Sections match the **grading rubric** (theory, case studies, audit, reflection, bonus).  
- Each file is linked under the correct part.  
- Includes reproduction instructions for the practical part.  
