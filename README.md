# 📘 Code Book

## 📌 Overview
**Code Book** is a Data Science project focused on cleaning structured JSON user data and building a recommendation system.

It generates:
- 👥 People You May Know (mutual friend suggestions)
- 📄 Pages You May Like (interest-based recommendations)

The project demonstrates data preprocessing and collaborative filtering using Python.

---

## 🧠 Features

### 🧹 Data Cleaning
- Removed duplicate and inconsistent records
- Standardized user–friend relationships
- Structured raw JSON data
- Optimized lookups using sets

### 👥 Friend Recommendation
- Identifies mutual friends
- Ranks users by shared connections
- Excludes existing friends and self

### 📄 Page Recommendation
- Detects shared interests between users
- Scores pages based on common likes
- Filters already liked pages
- Sorts results by recommendation strength

---

## 🛠 Tech Stack
- Python
- Jupyter Notebook
- JSON
- Set Operations
- Dictionary-based Scoring

---

## 📂 Project Structure

