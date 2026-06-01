# Video Game Sales Analysis
 
An exploratory data analysis of global video game sales using R, examining trends across years, regions, genres, and publishers.
 
---
 
## Overview
 
This project analyzes the [Video Game Sales dataset from Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales), which contains sales data for over 16,000 games across multiple platforms, regions, and publishers.
 
**Questions explored:**
- How has the number of game releases changed over time?
- Which games, genres, and publishers dominate global sales?
- How do sales figures differ across regions (NA, EU, Japan, Other)?
---
 
## Key Findings
 
- Game releases peaked between **2005–2010**, reflecting the industry's rapid expansion during the seventh console generation
- **North America** is the largest market by far, accounting for roughly half of total global sales
- **Action** and **Sports** are the best-selling genres globally
- **Nintendo** leads all publishers in total global sales, followed by Electronic Arts and Activision
- The top 10 best-selling games are dominated by Nintendo titles and major franchises like Grand Theft Auto
---
 
## Tools & Technologies
 
| Tool | Purpose |
|------|---------|
| R | Core analysis language |
| ggplot2 | Data visualisation |
| dplyr | Data manipulation |
| R Markdown | Reproducible reporting |
 
---
 
## Dataset
 
**Source:** [Video Game Sales — Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)  
**File:** `vgsales.csv`  
**Records:** ~16,500 games  
**Fields:** Rank, Name, Platform, Year, Genre, Publisher, NA\_Sales, EU\_Sales, JP\_Sales, Other\_Sales, Global\_Sales
 
---
 
## How to Run
 
1. Clone the repository:
   ```bash
   git clone https://github.com/kelinjo/vgsales-analysis.git
   ```
2. Open `vgsales-analysis.Rproj` in RStudio
3. Make sure the following packages are installed:
   ```r
   install.packages(c("readr", "ggplot2", "dplyr"))
   ```
4. Open `analysis.Rmd` and click **Knit** — this will generate `analysis.html` with the full report
---
 
## Author
 
**Dejan Kelečević**  

