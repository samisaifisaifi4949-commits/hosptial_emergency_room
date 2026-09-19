# 🏥 Hospital Emergency Room Analytics Dashboard

A Power BI–style interactive dashboard (built with pure HTML, CSS & [Chart.js](https://www.chartjs.org/)) analyzing Emergency Room patient flow, wait times, satisfaction, and demographics.

🔗 **Live Demo:** Enable GitHub Pages (see below) and the link will appear here.

## 📸 Preview

Open `index.html` in any browser — no build step, no server required.

## ✨ Features

- **3 report pages**: Overview, Wait & Satisfaction, Demographics
- **KPI cards**: Total Patients, Admission Rate, Avg Wait Time, Avg Satisfaction, Avg Age
- **Interactive slicers**: filter by Gender, Age Group, Department, Admission Status
- **Charts**: monthly trend, gender split, department volume, day-of-week traffic, wait-vs-satisfaction scatter, wait time by department, satisfaction by age, admission rate by department, race distribution, age vs admission (stacked)
- Fully **client-side** — all data and logic embedded in a single `index.html` file
- Responsive layout with a Power BI–inspired theme

## 🛠️ Tech Stack

- HTML5 / CSS3
- Vanilla JavaScript
- [Chart.js 4.4.1](https://www.chartjs.org/) (loaded via CDN)

## 🚀 Getting Started

### Option 1 — Just open it
Download/clone the repo and open `index.html` directly in your browser.

### Option 2 — Local server (optional)
```bash
git clone https://github.com/<your-username>/hospital-er-dashboard.git
cd hospital-er-dashboard
python3 -m http.server 8000
# then visit http://localhost:8000
```

### Option 3 — GitHub Pages (free hosting)
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", select **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Your dashboard will be live at `https://<your-username>.github.io/hospital-er-dashboard/`.

## 📁 Project Structure

```
hospital-er-dashboard/
├── index.html      # Full dashboard (markup + styles + data + charts)
├── README.md
├── LICENSE
└── .gitignore
```

## 📊 Data

The dataset is embedded directly in `index.html` as a JavaScript array for demo purposes — no external data file or backend needed.

## 📄 License

Released under the [MIT License](LICENSE).
