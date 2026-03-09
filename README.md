# HouseLens — Housing Market Analysis Website

A comprehensive Flask web application delivering in-depth housing market insights through interactive Tableau visualizations. This project analyzes 21,609+ real estate records to uncover trends in sale prices, renovation impacts, and property features.

## 📊 Project Overview

**HouseLens** is a data analytics project developed as part of the Data Analytics with Tableau program. It combines robust data preparation, interactive visualization, and modern web design to help real estate professionals, analysts, and stakeholders make data-driven decisions.

### Key Features
- **Interactive Tableau Dashboard** — Live embedded visualization with drill-down capabilities
- **4 Analysis Scenarios** — Comprehensive breakdown of housing market trends
- **Responsive Web Design** — Modern UI with smooth navigation and mobile-friendly layout
- **Real Data Insights** — Analysis of 21,609 records with $511,619 average sale price
- **Visual Storytelling** — Screenshot gallery showcasing key findings

## 🎯 Analysis Scenarios

1. **Overall Data Overview** — Summary metrics and foundational statistics across all records
2. **Sales by Renovation** — Impact of renovation timing on property values and total sales
3. **House Age Distribution** — Renovation status analysis across different property ages (50-118 years)
4. **Feature Analysis** — Correlation between bedrooms, bathrooms, floors, and house age

## 🛠️ Technologies Used

- **Backend**: Flask 3.0.0 (Python web framework)
- **Visualization**: Tableau Public (Interactive dashboards)
- **Frontend**: HTML5, CSS3 (Custom responsive design)
- **Data Processing**: CSV data transformation and analysis
- **Version Control**: Git & GitHub

## 📈 Dataset Information

- **Total Records**: 21,609 housing transactions
- **Average Sale Price**: $511,619
- **Total Basement Area**: 38.6M sqft
- **Age Range**: 50-118 years
- **Key Metrics**: Price, renovation year, bedrooms, bathrooms, floors, sqft

## 🚀 Setup & Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Installation Steps

1. **Clone the repository**:
```bash
git clone https://github.com/JayDaftardar/tableau_housing.git
cd tableau_housing
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

3. **Run the Flask application**:
```bash
python app.py
```

4. **Open in browser**: 
```
http://localhost:5000
```

## 📁 Project Structure
```
housing_project/
├── app.py                              # Flask application entry point
├── requirements.txt                     # Python dependencies
├── README.md                           # Project documentation
├── templates/
│   ├── base.html                       # Base template with navigation
│   ├── index.html                      # Home page
│   ├── dashboard.html                  # Tableau dashboard page
│   └── team.html                       # Team information page
└── static/
    ├── img/                            # Visualization screenshots
    │   ├── s1_overview.png
    │   ├── s2_renovation.png
    │   ├── s3_pie.png
    │   └── s4_bar.png
    └── Transformed_Housing_Data2.csv   # Clean dataset
```

## 🌐 Application Pages

- **`/`** — Home page with project overview, key scenarios, and technology stack
- **`/dashboard`** — Interactive Tableau dashboard with embedded visualization
- **`/team`** — Team members and project contribution details

## 📊 Live Dashboard

View the interactive Tableau dashboard: [Housing Market Analysis Dashboard](https://public.tableau.com/app/profile/jay.daftardar/viz/Book2_17729773041440/Dashboard2?publish=yes)

## 🎯 Key Insights

- **$1.3B** in total sales from homes priced above $1.1M
- **68%** of transactions fall in the $250K-$450K mid-range bracket
- **2,100+** peak bedroom count in 4-year-old properties
- Strong correlation between renovation timing and property valuation

## 📝 Project Goals

This project addresses the challenge of understanding housing market dynamics by:
- Transforming raw data into actionable insights
- Creating intuitive visualizations for non-technical stakeholders
- Providing interactive tools for market trend exploration
- Delivering a professional web interface for data presentation

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📄 License

This project is part of an educational program. All rights reserved.

## 👤 Developer

**Jay Daftardar**
- GitHub: [@JayDaftardar](https://github.com/JayDaftardar)
- Project Link: [tableau_housing](https://github.com/JayDaftardar/tableau_housing)

---

*Developed as part of Data Analytics with Tableau program — SkillWallet*
