# 🕸️ More Web Scraping Project Tasks – IBM Data Analyst Capstone

This project is part of **Module 1** of the **IBM Data Analyst Capstone**, which is also part of the main course [IBM Data Analyst Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-analyst) that demonstrates real-world web scraping techniques using Python.
It focuses on **more web scraping tasks** techniques and deeper data gathering, cleaning, and analysis.

---

## 📜 About the Project

- Scraped a programming languages table from an IBM-hosted open-access webpage.
- Extracted key fields: Language Name, Created By, Average Annual Salary, and Learning Difficulty.
- Cleaned and organized the scraped data into structured datasets.
- Exported data into both `.csv` and `.xlsx` formats.
- Visualized salary data with a bar chart.
- Generated HTML and PDF dashboard reports from Jupyter Notebooks.

---

## 📊 Tasks Performed

- Fetch webpage content using `requests`
- Parse HTML with `BeautifulSoup`
- Locate and extract HTML table data
- Create a clean `pandas` DataFrame
- Export DataFrame as `.csv` and `.xlsx`
- Visualize data: Bar chart of Average Annual Salaries
- Save final reports as HTML and PDF files

---

## 📜 Dataset Source

The data for this project was scraped from an open-access educational page provided by IBM.

- **Source URL:**  
  [Programming Languages Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/datasets/Programming_Languages.html)

The dataset contains information about:
- Popular programming languages
- Their creators
- Average annual salaries
- Learning difficulty levels

📌 **Important:** This scraping activity was conducted ethically for educational purposes, in compliance with the site's public data access permissions.

---
## 🛠️ Tools Used

- Python 3
- `requests`
- `BeautifulSoup`
- `pandas`
- `matplotlib`
- `nbconvert` (for HTML/PDF export)
- Jupyter Notebook

---

## 📈 Key Insights from Scraped Data

- **Swift** offers the **highest average annual salary** at **$130,801**, followed closely by **Python** ($114,383) and **C++** ($113,865).
- Most **high-paying languages** like **Swift**, **Python**, and **Javascript** are also considered **Easy to Learn**.
- **SQL** and **PHP** offer relatively lower average salaries compared to others, but are among the **easiest to learn**.
- Languages like **R**, **C++**, and **C#** have **higher learning difficulties** yet still offer **strong earning potential**.
- **Go (Golang)** balances moderate salary (**$94,082**) with a **Difficult** learning curve.

---

## 🖥️ Browser's Viewing

Explore the full project with visuals and insights via the hosted dashboard:

[![View in Browser](https://img.shields.io/badge/View-Dashboard-blue?style=for-the-badge&logo=plotly)](https://kelechiede.github.io/Project_6_Web-Scraping-Lab/browser-view/Web-Scraping-More-Labs.html)
- 📄 [Download as PDF](browser-view/Web-Scraping-More-Labs.pdf)

> 💡 This notebook includes bar charts, job demand visualizations, and clean API data analysis — best viewed on a desktop browser.

---

- 📁 **Original Jupyter Notebook**: `notebooks/Web-Scraping-More-Labs.ipynb`
- 📄 **Static HTML Version**: [`Web-Scraping-More-Labs.html`](https://kelechiede.github.io/Project_6_Web-Scraping-Lab/browser-view/Web-Scraping-More-Labs.html)


---

## 📜 Certification

This project was completed as part of the **IBM Data Analyst Capstone Certificate** on Coursera.

[![IBM Certificate Thumbnail](certification/ibm-data-visualization-thumbnail.png)](https://www.coursera.org/account/accomplishments/verify/ARTLBRAPJ68Q)

> [Verify Capstone Certificate on Credly](https://www.credly.com/badges/259d69a8-bd52-47fb-b02e-19947b158dc6/public_url)

---

## 🧑‍💼 Author

**Kelechukwu Innocent Ede and Ramesh Sannareddy**  
IBM Certified Data Analyst  
🔗 GitHub: [@Kelechiede](https://github.com/Kelechiede)  
🔗 LinkedIn: [Kelechukwu Innocent Ede](https://www.linkedin.com/in/kelechukwu-innocent-ede-b448aa134/)  
📧 Email: kelechukwuede@gmail.com

---

## 📂 Project Structure
```plaintext
ibm_capstone_data_analyst_2025/
└── module_1_real_world_projects/
    └── Project_6_Web-Scraping-Lab/
        ├── data/
        │   ├── popular-languages.csv
        │   └── spopular-languages.xlsx
        ├── notebooks/
        │   └── Web-Scraping-More-Labs.ipynb
        ├── browser viewing/
        │   ├── Web-Scraping-More-Labs.html
        │   └── Web-Scraping-More-Labs.pdf
        ├── certificate/
        │   ├── data-analyst-capstone-badge-project.png
        │   ├── ibm_capstone_certificate_thumbnail.png
        │   └── ibm_capstone_coursera_certificate_thumbnail.png
        ├── visuals/
        │   ├── popular_languages_salary_chart.png
            ├── popular_languages_ave-salary_chart.png
        │   └── popular_languages_creators_chart.png
        └── README.md


