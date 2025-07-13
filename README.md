
# ⚽ FIFA Stock Analysis 📈

## 🔍 Project Summary

**FIFA Stock Analysis** is a unique Python-powered project that blends sports analytics with financial data science. By exploring historical FIFA player ratings and stock market trends, it uncovers potential correlations, delivers strategic insights, and powers predictive modeling — all through a cohesive pipeline of data engineering, machine learning, and real-time visualization.

This project reflects a deep understanding of data preprocessing, NLP, financial modeling, and web deployment, offering a compelling demonstration of interdisciplinary analytics and end-to-end application development.

---

## 🚀 Key Features

- 📊 **Dual-Domain Analysis:** Combines FIFA performance data with historical stock prices via `yfinance`.
- 🧠 **Insightful Explorations:** Uses Matplotlib, Seaborn, and Plotly for comprehensive EDA and correlation discovery.
- 📰 **Sentiment Intelligence:** Applies NLTK and Transformers for natural language sentiment analysis on sports and financial news.
- 🔮 **ML Forecasting:** Builds predictive models with scikit-learn for trend and rating forecasting.
- 🌐 **Interactive Dashboard:** Flask-powered web interface for exploring data live and customizing analysis.

---

## 🛠 Technologies Used

| Area | Tools & Libraries |
|------|--------------------|
| Language | Python 3.13+ |
| Data & ML | Pandas, NumPy, scikit-learn |
| NLP | NLTK, HuggingFace Transformers |
| Visualization | Matplotlib, Seaborn, Plotly |
| Financial Data | yfinance |
| Web Framework | Flask |
| Version Control | Git & GitHub |

---

## ⚙️ Setup & Installation

### Prerequisites

- Python ≥ 3.13  
- Git  
- Optional: `venv` or `conda` for virtual environments

### Installation Steps

```bash
git clone https://github.com/sk8ergurnoor27/FIFA_STOCK_ANALYSIS.git
cd FIFA_STOCK_ANALYSIS
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## ▶️ Running the Application

```bash
python app.py
```

Visit [`http://127.0.0.1:5000/`](http://127.0.0.1:5000/) to launch the dashboard and start your exploration.

---

## 🌍 Deployment Guide (Heroku)

1. Add `requirements.txt` and a `Procfile` to the root:
    ```
    web: python app.py
    ```

2. Modify `app.py`:
    ```python
    import os
    app.run(host="0.0.0.0", port=int(os.environ.get("PORT", 5000)))
    ```

3. Push to GitHub and deploy via Heroku’s GitHub integration.

---

## 🧭 Project Structure

```
FIFA_STOCK_ANALYSIS/
│
├── app.py                  # Flask application
├── requirements.txt        # Package dependencies
├── static/                 # CSS 
├── templates/              # HTML templates
├── PROCFILE/               # Saved ML models

```

---

## 🤝 Contributing

Want to build with me?

1. Fork this repo  
2. Create your branch: `git checkout -b feature-name`  
3. Commit changes: `git commit -m 'Add feature'`  
4. Push: `git push origin feature-name`  
5. Submit a pull request

---

## 📬 Contact

**Gurnoor Kaur**  
GitHub: [sk8ergurnoor27](https://github.com/sk8ergurnoor27)  
Email: your.email@example.com

---

## 🙌 Acknowledgments

- [yfinance](https://github.com/ranaroussi/yfinance) for financial data
- Open-source FIFA datasets
- Python & ML community for tools and inspiration

---

## 💡 Interviewer's Note

This project showcases not only technical fluency across multiple domains (data analytics, ML, NLP, web dev) but also real-world initiative in connecting unconventional datasets to build actionable insights. The interactive dashboard reflects full-stack deployment skills, and the structured approach—from data acquisition to model visualization—demonstrates end-to-end ownership.

---

*Happy analyzing and coding! ⚽📈 Let the data games begin.*

---

