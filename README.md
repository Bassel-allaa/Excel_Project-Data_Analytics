## 🔍 Data Science Job Market Analysis

As a job seeker, I undertook this project to analyze the data science job market and understand which skills are most valued by top employers and how professionals can maximize their pay.

The analysis uses a dataset of **2023 real-world data science job postings** from an Excel course, including details on:

* 👨‍💼 **Job titles**
* 💰 **Salaries**
* 📍 **Locations**
* 🛠️ **Skills**

### 💻 Key Excel Tools Used

This project relied on advanced Excel features for data preparation and analysis:

| Excel Tool | Primary Function |
| :--- | :--- |
| **🔍 Power Query** | Used for Extract, Transform, and Load (ETL) data cleaning. |
| **💪 Power Pivot** | Used to create a **Data Model** and relationships between tables. |
| **🧮 DAX** | Used for advanced calculations (like Median Salary) and measures. |
| **📊 Pivot Tables & Charts** | Used to summarize and visualize the results. |

---

## ❓ Questions and Key Findings

### 1. Do more skills get you better pay?

* **Method:** Used **Power Query** to clean and prepare two main datasets (job information and job skills).
* **Key Insight:** **Yes.** There is a **positive connection between the number of skills** listed in a job posting and the median salary.
    * Higher-paying roles (like Senior Data Engineer) require more skills.
    * Lower-paying roles (like Business Analyst) require fewer skills.
* **Takeaway:** Acquiring a **wider range of relevant skills** is crucial for targeting high-paying positions.

### 2. What's the salary for data jobs in different regions?

* **Method:** Used **Pivot Tables and DAX formulas** to calculate median salaries for US and Non-US jobs.
* **Key Insight:** High-level roles (like Data Scientist) have higher median salaries globally, but there is a **notable salary difference between US and Non-US roles**, which is likely due to the concentration of major tech industries in the US.
* **Takeaway:** These salary insights are vital for **planning and salary negotiations**, highlighting market differences based on location.

### 3. What are the top skills of data professionals?

* **Method:** Used **Power Pivot** to create a **data model** connecting the jobs and skills tables.
* **Key Insight:**
    * **SQL and Python are the dominant, foundational skills** required across the industry.
    * **Cloud technologies (like AWS and Azure) are also highly present**, showing a clear shift towards big data and cloud services.
* **Takeaway:** Professionals need to focus on **SQL and Python** to stay competitive, while also learning **cloud services** for future relevance.


### 4. What’s the pay of the top 10 skills?

* **Method:** Used an **Advanced PivotChart** (a combo chart) to compare the median salary against the likelihood (frequency) of a skill.
* **Key Insight:**
    * Skills like **Python, Oracle, and SQL** are associated with the **highest median salaries**, confirming their high value in tech jobs.
    * General skills like PowerPoint and Word are linked to the lowest salaries and have low demand in high-salary sectors.
* **Takeaway:** **Invest time in learning high-value, specialized skills like Python and SQL** to maximize earning potential in the tech industry.

---

## 🎯 Conclusion

This project successfully used advanced Excel tools (Power Query, Power Pivot, DAX, and Charts) to provide practical guidance on the data science job market. The key finding is the clear correlation between **specialized skills (especially Python, SQL, and Cloud)** and **higher salaries**. This analysis serves as a practical map for data professionals aiming for higher-paying roles.
