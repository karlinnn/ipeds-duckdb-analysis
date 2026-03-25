# Multi-Domain IPEDS Analysis: Enrollment, Finance & Student Outcomes
> Built as part of a data analytics assignment to demonstrate DuckDB-based large dataset processing.

## 📊 Overview
This project analyzes U.S. higher education data from the IPEDS (Integrated Postsecondary Education Data System) dataset for the years 2019–2021 using DuckDB.

The goal of this analysis is to understand how institutional factors such as funding, staffing, and admissions impact student outcomes like graduation rates.

---

## 🗂️ Datasets Used
The following IPEDS datasets were integrated:
- Institutional Characteristics (HD)
- Enrollment (EF)
- Graduation (GR)
- Admissions (ADM)
- Finance (F1A)
- Staff (HR)

---

## ⚙️ Tools & Technologies
- DuckDB (for fast SQL-based querying)
- Python (Colab environment)
- SQL (data transformation and analysis)

---

## 🧹 Data Processing
- Loaded multiple CSV datasets into DuckDB
- Combined multi-year data (2019–2021)
- Cleaned and aggregated data to avoid duplication
- Joined datasets using `unitid` and `year`

---

## 🧠 Feature Engineering
The following key metrics were derived:
- **Graduation Rate** = Graduates / Enrollment  
- **Acceptance Rate** = Admissions / Applications  
- **Spending per Student** = Total Expenses / Enrollment  
- **Student–Staff Ratio** = Enrollment / Staff Count  

---

## 📈 Analysis Performed
- Year-wise trends in enrollment and graduation
- Relationship between institutional spending and student outcomes
- Impact of student–staff ratio on graduation rates
- Comparison of institutions based on performance metrics
- Efficiency analysis (cost per graduate)

---

## 🔍 Key Insights
- Institutions with higher spending per student tend to show better graduation outcomes  
- Lower student–staff ratios are associated with improved student performance  
- Financial and human resources both play a significant role in institutional success  
- Variations across institutions highlight differences in efficiency and resource allocation  

---

## 📌 Conclusion
This project demonstrates how integrating multiple educational datasets can provide meaningful insights into institutional performance. The use of DuckDB enabled efficient querying and handling of large datasets.

---

## 🚀 Future Improvements
- Add visualization (charts/graphs)
- Extend analysis to more years
- Include additional IPEDS datasets for deeper insights

---

## 📎 Author
Karlin Francis