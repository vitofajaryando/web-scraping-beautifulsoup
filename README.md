# 📈 Ethereum Volume Tracker — Web Scraping with BeautifulSoup

A data scraping project that collects **Ethereum trading volume data** from CoinGecko and visualizes it through an interactive **Flask web dashboard**.

Built as a capstone project for the **Algoritma Academy Data Analytics Specialization**.

---

## 🖥️ Demo

> Flask dashboard running locally — scrapes data and renders volume trend chart in real time.

---

## 🔧 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup4-informational?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white)

---

## 📁 Project Structure

```
web-scraping-beautifulsoup/
├── notebooks/
│   └── analysis-ethereum-volume.ipynb   # Exploratory scraping & analysis
├── static/
│   └── css/                             # Styling for Flask dashboard
├── templates/
│   └── index.html                       # Dashboard HTML template
├── app.py                               # Flask app & scraping logic
├── requirements.txt                     # Python dependencies
└── README.md
```

---

## ⚙️ Installation & Running Locally

**1. Clone the repository**
```bash
git clone https://github.com/vitofajaryando/web-scraping-beautifulsoup.git
cd web-scraping-beautifulsoup
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the Flask app**
```bash
python app.py
```

**4. Open in browser**
```
http://127.0.0.1:5000
```

---

## 📊 What It Does

- Scrapes **Ethereum historical trading volume** data (Jan 2020 – Jun 2021) from CoinGecko
- Extracts `Date` and `Volume` columns using BeautifulSoup
- Cleans and processes data with Pandas
- Renders an interactive **volume trend chart** via Matplotlib on a Flask dashboard

---

## 📦 Dependencies

```
beautifulsoup4
pandas
flask
matplotlib
requests
```

> Or install all at once: `pip install -r requirements.txt`

---

## 👤 Author

**Vito Fajaryando**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/vitofajaryando)
[![GitHub](https://img.shields.io/badge/GitHub-vitofajaryando-181717?style=flat&logo=github)](https://github.com/vitofajaryando)
