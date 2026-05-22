# Netflix Content Analysis & Visualization Dashboard

![Netflix](https://img.shields.io/badge/Netflix-E50914?style=for-the-badge&logo=netflix&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## 📋 Project Overview

This project presents a comprehensive analysis and visualization dashboard of Netflix's content library using the "Netflix Movies and TV Shows" dataset from Kaggle. The analysis explores content distribution patterns, geographical trends, genre preferences, rating classifications, and temporal addition patterns to provide actionable insights into Netflix's content strategy.

**🎯 Objective:** Create professional data visualizations and extract meaningful business insights from Netflix's content catalog spanning 2008-2021.

## 👨‍💻 Intern Details

- **Name:** Karthik Neduri
- **Company:** Horizon TechX
- **Domain:** AI & Data Science
- **Task:** Task 4 - Data Visualization Dashboard
- **Faculty Guide:** Vani Prasanna
- **Contact:** vkanapal@gitam.edu | 9177751765
- **Date:** May 2026

## 📊 Dataset Information

- **Source:** [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
- **Format:** CSV
- **Size:** 8,807 rows × 12 columns
- **Time Period:** January 2008 - September 2021
- **Geographic Coverage:** 87 countries
- **Content Types:** Movies and TV Shows

### Dataset Columns
| Column | Description |
|--------|-------------|
| show_id | Unique identifier |
| type | Movie or TV Show |
| title | Content title |
| director | Director(s) |
| cast | Main cast |
| country | Production country |
| date_added | Date added to Netflix |
| release_year | Original release year |
| rating | Content rating |
| duration | Duration (minutes/seasons) |
| listed_in | Genres |
| description | Brief description |

## 🛠️ Technology Stack

- **Programming Language:** Python 3.x
- **Development Environment:** Google Colab
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Version Control:** Git, GitHub

## 📁 Project Structure
HorizonTechX_Visualization_Netflix/
├── README.md # Project documentation
├── Netflix_Dashboard.ipynb # Main analysis notebook
├── data/
│ └── netflix_titles.csv # Raw dataset
├── visualizations/
│ ├── 01a_donut_content_distribution.png
│ ├── 01b_bar_content_count.png
│ ├── 02_top_countries.png
│ ├── 02b_top_countries_pie.png
│ ├── 03_yearly_trend.png
│ ├── 03b_monthly_pattern.png
│ ├── 04_top_genres.png
│ ├── 04b_genre_comparison.png
│ ├── 05_rating_distribution.png
│ ├── 05b_rating_by_type.png
│ ├── 06_movie_duration.png
│ ├── 06b_tv_seasons.png
│ ├── 07_monthly_heatmap.png
│ └── 08_top_directors.png
└── reports/
└── Netflix_Dashboard_Report.pdf # Detailed project report


## 🔧 Installation & Usage

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn plotly

Running the Analysis
Clone this repository
Upload netflix_titles.csv to the data/ folder
Open Netflix_Dashboard.ipynb in Google Colab or Jupyter
Run all cells to generate visualizations
Charts will be saved automatically in PNG format
📈 Key Findings
Content Distribution
Movies: 6,131 titles (69.7%)
TV Shows: 2,666 titles (30.3%)
Geographic Analysis
Top Producer: United States (2,818 titles - 35.3%)
Second: India (972 titles - 12.2%)
Third: United Kingdom (419 titles - 5.2%)
Temporal Trends
Peak Addition Year: 2021 (2,012 titles)
Exponential Growth: 2016-2021
Peak Months: January & December
Content Strategy
Most Popular Genre: International Movies (2,752 titles)
Target Audience: Adults (TV-MA: 36.4%)
Average Movie Duration: 99 minutes
Common TV Format: 1 season (60.5%)
📊 Visualization Portfolio
This project includes 14 professional visualizations:

Content Type Distribution - Donut & bar charts
Top Countries Analysis - Horizontal bar & pie charts
Temporal Trends - Line charts & monthly patterns
Genre Performance - Bar charts & comparisons
Rating Distribution - Grouped bar charts
Duration Analysis - Histograms & distributions
Addition Heatmap - Year-month patterns
Top Directors - Horizontal bar chart
Note: All visualizations use Netflix brand colors (#E50914) and professional styling for business presentation.

🎯 Business Insights
Strategic Recommendations
Diversify Geographic Content - Reduce US dependency (35.3%)
Expand Family Content - Only 12.8% family-friendly content
Seasonal Strategy - Leverage January/December peak patterns
Multi-Season Development - Build longer series for engagement
Genre Localization - Leverage regional production strengths
Market Opportunities
European Expansion - Underrepresented markets
Family Segment - Significant growth potential
Premium Series - Multi-season content development
Regional Content - Country-specific strategies
📋 Data Processing Summary
Metric	Value
Original Records	8,807
Cleaned Records	8,797
Missing Values Handled	4,307
New Features Created	8
Countries Analyzed	87
Visualizations Created	14
🏆 Project Achievements
✅ Data Analysis: Processed 8,797 Netflix titles
✅ Visualization: Created 14 professional charts
✅ Insights: Generated 7 business recommendations
✅ Technical: Demonstrated end-to-end data science workflow
✅ Documentation: Comprehensive project reporting

📝 Reports
Detailed Analysis Report: Available in reports/Netflix_Dashboard_Report.pdf
Technical Documentation: Included in Jupyter notebook
Business Insights: Summary available in this README
🔗 References
Netflix Dataset - Kaggle
Matplotlib Documentation
Seaborn Documentation
Pandas Documentation
👤 Author
Karthik Neduri
AI & Data Science Intern
Horizon TechX
