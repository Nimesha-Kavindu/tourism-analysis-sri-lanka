# 📊 Statistical Analysis of Determinants Influencing Tourist Arrivals and Revenue in Sri Lanka

This project investigates the key factors influencing **tourist arrivals** and **tourism revenue** in Sri Lanka over the last decade, using official data from the **Sri Lanka Tourism Development Authority (SLTDA)**.  
We apply probability distributions, confidence intervals, hypothesis testing, correlation, and regression modeling in **Python** to uncover insights and provide policy recommendations.

---

## 🎯 Objectives
- Identify factors significantly affecting tourist arrivals and tourism revenue.
- Fit probability distributions to tourism data (e.g., daily expenditure).
- Construct confidence intervals for key tourism metrics (e.g., average stay).
- Test hypotheses on seasonal and regional tourism differences.
- Model relationships using correlation and regression.
- Predict future tourism revenue based on historical trends and influencing variables.

---

## 📂 Repository Structure
sri-lanka-tourism-stats/</br>
├── 📄 README.md # Project overview & instructions</br>
├── 📄 LICENSE # License (MIT)</br>
├── 📄 .gitignore # Git ignore rules</br>
├── 📄 requirements.txt # Python dependencies</br>
│</br>
├── 📂 data/ # Datasets</br>
│ ├── 📂 raw/ # Original SLTDA datasets (keep untouched)</br>
│ └── 📂 processed/ # Cleaned & transformed datasets</br>
│</br>
├── 📂 src/ # Source code</br>
│ ├── 📓 eda.ipynb # Exploratory data analysis</br>
│ ├── 📓 models.ipynb # Regression & forecasting</br>
│ └── 🛠️ utils.py # Helper functions</br>
│</br>
├── 📂 reports/ # Reports & presentations</br>
│ ├── 📂 paper/ # Final paper</br>
│ │ ├── 📄 main.tex # LaTeX main file</br>
│ │ ├── 📄 refs.bib # References</br>
│ │ └── 📂 figs/ # Figures for paper</br>
│ └── 📂 presentation/ # Slides</br>
│ ├── 📄 slides.tex # Beamer slides (or PPTX)</br>
│ └── 📂 figs/ # Figures for slides</br>
│</br>
├── 📂 notebooks/ # Experimental Jupyter notebooks</br>
│ └── 📓 data_exploration.ipynb</br>
│</br>
└── 📂 docs/ # (Optional) Extra documentation</br>

---

## 📊 Data Source
- **Sri Lanka Tourism Development Authority Annual Reports**  
  Website: [https://www.sltda.gov.lk/](https://www.sltda.gov.lk/)  

Data includes:
- Tourist arrivals (monthly/annual)
- Tourism revenue
- Average length of stay
- Daily expenditure
- Source market distribution
- Flight and accommodation capacity
- Policy changes/events

---

## ⚙️ Installation & Usage
Clone the repository:
```bash
git clone https://github.com/YourUsername/sri-lanka-tourism-stats.git
cd sri-lanka-tourism-stats

