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
sri-lanka-tourism-stats/
│
├── README.md # Overview, objectives, instructions
├── LICENSE # MIT License
├── .gitignore # Ignore unnecessary files
├── requirements.txt # Python dependencies
│
├── data/
│ ├── raw/ # Original SLTDA datasets (not tracked in Git)
│ └── processed/ # Cleaned datasets
│
├── src/
│ ├── eda.ipynb # Exploratory analysis
│ ├── models.ipynb # Regression & forecasting
│ └── utils.py # Helper functions
│
├── reports/
│ ├── paper/
│ │ ├── main.tex # LaTeX report
│ │ ├── refs.bib # References
│ │ └── figs/ # Report figures
│ └── presentation/
│ ├── slides.tex # Beamer slides (or PPTX)
│ └── figs/ # Slide figures
│
├── notebooks/ # Sandbox/experiments
│ └── data_exploration.ipynb


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

