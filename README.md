# digital-political-advertising-sports-analysis
Analyzed digital political advertising performance during live sports using Python, identifying key drivers of engagement, CTR, and ad recall across platforms and audiences.
# Digital Political Advertising During Live Sports Events

##  Overview
This project analyzes digital political advertising performance during live sports events. The goal is to evaluate how audience engagement, click-through rates (CTR), and advertising recall vary across sports leagues, digital platforms, and audience demographics.

Live sports create a highly engaged environment where viewers frequently use second-screen devices such as mobile phones and social media, providing unique opportunities for targeted digital advertising.

---

##  Problem Statement
Political campaigns invest heavily in digital advertising, but effectiveness varies depending on platform, audience, and timing. This project explores how different sports environments and digital channels influence advertising performance.

---

##  Objectives
- Analyze engagement rates across sports leagues
- Compare performance across digital platforms
- Evaluate the impact of game timing on ad recall
- Study audience behavior using mobile usage and demographics
- Identify optimal strategies for digital political advertising

---

##  Dataset Description
The dataset includes advertising performance metrics across multiple sports and platforms.

Key features:
- Sport (NFL, NBA, MLB, NHL, Soccer, College Football)
- Platform (Social Media, Streaming, Sports Apps, Betting Apps, Connected TV)
- Game Moment (Pre-game, Quarters, Halftime, Post-game)
- Audience Age Group
- Mobile Usage %
- Ad Impressions
- Click-Through Rate (CTR)
- Engagement Rate
- Advertising Spend
- Ad Recall

---

##  Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Methodology

- Cleaned and validated dataset (250 records, no missing values)  
- Aggregated performance metrics across sports, platforms, and game moments  
- Calculated average engagement rates, CTR, and ad recall across dimensions  
- Built pivot tables to analyze sport-platform performance combinations  
- Conducted correlation analysis between:
  - Ad spend and CTR  
  - Mobile usage and engagement  
- Visualized trends using bar charts and scatter plots

---

##  Key Analysis Performed
- Engagement rate by sport
- CTR comparison across platforms
- Ad recall by game moment
- Geographic analysis of ad impressions
- Relationship between ad spend and CTR
- Mobile usage vs engagement analysis
- Audience engagement by age group
- Sport-platform performance comparison

---

## Key Insights

- Average CTR across dataset ≈ 2.39%, with variation by platform  
- Social media and sports apps consistently generate higher engagement and CTR  
- Halftime and pre-game moments produce the highest ad recall  
- Mobile usage (avg ≈ 74%) is strongly associated with higher engagement  
- Younger audiences (18–34) show the highest interaction with digital ads  

---

## Target Audience

- Political campaign strategists  
- Digital marketing teams  
- Media planners  
- Advertising analysts

---

##  Business Value
This project demonstrates how data analytics can optimize digital advertising strategies by identifying the most effective platforms, timing, and audience segments.

---

##  Project Structure
- `.ipynb` → Full analysis notebook
- `.pdf` → Final report
- `.docx` → Written documentation
- `.csv` → Datasets
- Dataset → Advertising performance data

---

##  How to Run
1. Open the notebook file
2. Install dependencies:
   ```bash
   pip install pandas matplotlib
