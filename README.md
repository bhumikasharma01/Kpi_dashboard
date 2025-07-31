# 📊 KPI Dashboard Web Application

A robust, user-friendly web application for managing and analyzing monthly performance data using interactive dashboards, built with **FastAPI** (backend) and **Streamlit** (frontend).

---

## 🚀 Overview

The KPI Dashboard enables organizations to track, compare, and visualize key performance indicators across departments or clusters. It supports Excel report uploads, secure user access, historical data analysis, and PDF report generation — all from a clean and intuitive interface.

---

## ✨ Key Features

- 🔐 **Role-Based User Authentication**  
  Secure login for Admin and Employee roles using JWT tokens.

- 📁 **Excel Report Upload**  
  Admins can upload monthly performance reports in Excel format. Data is parsed and stored in a SQL database.

- 📊 **Interactive Dashboards**  
  - View KPIs in tabular format  
  - Monthly trend analysis  
  - Cluster-wise comparison  
  - Visual highlights for top performers

- 📉 **3-Month Performance Comparison**  
  Automatically fetches and compares the past 3 months’ reports (excluding the current month).

- 🧾 **PDF Report Generation**  
  Generate and download PDF versions of uploaded reports. Past reports are stored and accessible.

---

## 🛠️ Tech Stack

| Layer     | Technology         |
|-----------|--------------------|
| Frontend  | Streamlit          |
| Backend   | FastAPI            |
| Database  | SQLite / PostgreSQL|
| Auth      | JWT Token Auth     |
| Reports   | Pandas, ReportLab  |

---



