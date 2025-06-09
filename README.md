# 📊 Grade Analysis Lab

**Author:** Sami Kader-Yettefti  
**Repository:** [r-101-grade-analysis](https://github.com/kaderrsami/r-101-grade-analysis)

The goal of this lab is to **analyze a real-world collection of grades** obtained by students during a semester. The analysis explores performance patterns, attendance issues, and correlations using R and data visualization.

---

## 📁 About the Project

This lab is part of a course assignment focused on data exploration and visualization in R. It answers a series of structured questions using a dataset of student grades and groups.

---

## 📂 Repository Contents

- `grades.csv` — Dataset containing student IDs, group info, and grades.
- `lab.qmd` or `lab.Rmd` — Source document with all code and analysis.
- `output.html` — Rendered version of the lab with plots and tables.
- `README.md` — Project overview and instructions.

---

## 🧰 Tools & Packages

- `R` and `RStudio`
- `tidyverse`: For data manipulation and plotting
- `vroom`: Fast CSV import
- `here`: File path management
- `knitr`: Nicely formatted tables
- `stringr`: String utilities
- `quarto` or `rmarkdown`: Reproducible report generation

---

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/kaderrsami/r-101-grade-analysis
cd r-101-grade-analysis
```
2. Open in RStudio
Open the .Rproj file for a project-scoped environment.

3. Install Dependencies
install.packages(c("vroom", "ggplot2", "dplyr", "tidyr", "knitr", "stringr", "here"))

4. Run or Render the Lab Report
quarto::quarto_render("lab.qmd")   # for Quarto
# or
rmarkdown::render("lab.Rmd")       # for R Markdown

🔍 Analysis Overview
| Question | Focus                                                   |
| -------- | ------------------------------------------------------- |
| Q1       | Load data                                               |
| Q2–3     | Summary stats + missing exam grades                     |
| Q4       | Distribution of exam grades                             |
| Q5–6     | Student count per group                                 |
| Q7       | Grade distribution by group (bar and boxplot)           |
| Q8–9     | Exam attendance per group                               |
| Q10–12   | Missing grades per student                              |
| Q13–17   | Missing MCQ analysis                                    |
| Q18      | Correlation between MCQ attendance and exam performance |

📊 Sample Visualizations
Includes:

Bar plots

Histograms

Box plots

Faceted charts

Dual-axis comparisons

All charts are made with ggplot2 and dynamically generated from the dataset.

📝 License & Contributions
This lab is a personal academic project.
If you find ways to improve the analysis, feel free to fork the repo and submit a pull request.

📌 Note
You can view the rendered HTML file locally or host it on GitHub Pages if desired.





  

