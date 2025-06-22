# 🧾 Fundraising Data Analytics & Reporting Project

This project analyzes real-world donation data made to not-for-profit organizations affiliated with elected officials. It includes data cleaning (in Excel and Python), data modeling, and dynamic dashboards in Power BI to uncover trends in donor behavior, political affiliations, and donation distribution across regions.

---

## Completion Criteria

- Clean and preprocess raw fundraising donation data
- Normalize data and design a relational model in 3NF
- Analyze donor contributions and organizational fundraising patterns
- Create interactive Power BI dashboards for insights
- Document and showcase the full data analytics pipeline

---

## Dataset Overview

**Source:** [Donations Dataset](https://data.world/city-of-ny/dx8z-6nev)

**Key Columns:**
- Donation ID
- Donor Name, Donors_city_of_residence, Donors_state_of_residence
- Date of Donation
- Donation Amount
- Value_of_in_kind_donation / Description_of_in_kind_donation
- Organization Name
- Elected Official Name / Title

---

## 🛠️ Tools & Technologies Used

| Tool         | Purpose                         |
|--------------|----------------------------------|
| **Excel**    | Initial cleaning and exploration |
| **Python (pandas)** | Automated cleaning & transformation |
| **Power BI** | Visual analytics dashboard       |
| **SQL**      | Querying, modeling, and analysis |
| **Git/GitHub** | Version control and documentation |
| **dbdiagram.io** | ERD and data modeling         |

---

## 🧼 Data Cleaning Steps

- Removed duplicates and null values
- Formatted dates and standardized text fields
- Converted donation values to numeric types
- Unified city/state naming conventions

---

## 📐 Data Modeling

Data was normalized into **3NF**, with the following key tables:
- `Donors`
- `Donations`
- `Organizations`
- `Elected_Officials`

**ER Diagram:**  
![ERD](docs/ERD.png)

---

## 📊 Dashboard Highlights (Power BI)

- 💰 Total donations and in-kind contributions
- 📍 Donations by city/state (map)
- 🏛️ Top recipient organizations
- 🧑‍💼 Elected officials affiliated with highest donations
- 📈 Trend analysis over months/years
- 🔄 Filters: year, city, organization, official name

**Preview Screenshot:**  
![Dashboard](docs/screenshots/dashboard_preview.png)

---

## ✅ Project Completion Checklist

- [x] Data Cleaning in Excel
- [x] Data Cleaning with Python
- [x] Normalized Data Model (3NF)
- [x] ER Diagram Created
- [x] Power BI Dashboard Built
- [x] README and GitHub Documentation Complete

---

## 📚 Key Insights

- A large percentage of donations are associated with a few elected officials
- In-kind contributions make up a significant portion in specific regions
- Certain nonprofits consistently receive larger volumes of donations

---

## 📁 Project Structure

