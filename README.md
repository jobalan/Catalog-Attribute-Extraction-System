# Catalog Attribute Extraction System
## End-to-End Hybrid NLP Pipeline using Python, SQL Server, spaCy & Excel Delivery
---

## 📌 What is this project?

E-commerce platforms receive **unstructured product descriptions** from different vendors.  
These descriptions are messy, inconsistent, and difficult to use directly.

This project converts those **raw text descriptions** into **structured product attributes** such as:
- Brand  
- Weight  
- Power  
- Color  
- Material  
- Warranty  
- Country of origin  
- and more…

The final output is a **clean Excel file** that business teams can directly use for:
- Search & filtering  
- Analytics  
- Catalog standardization  

---

## 🎯 Why this project exists

In real companies:
- Product data comes in **free text**
- Business teams need **structured columns**
- Manual extraction does not scale

This system automates that process using **Python, SQL Server, and NLP** — in a way that is:
- Accurate  
- Explainable  
- Easy to extend  

---

## 🧠 How it works (Simple Explanation)
Raw product text
↓
Stored in SQL Server
↓
Hybrid NLP engine extracts attributes
↓
Confidence & quality metrics added
↓
Results stored in SQL (scalable format)
↓
Final Excel generated for business users

---

## 🧩 Key Design Ideas

### 1️⃣ SQL-first architecture  
SQL Server is used as the **source of truth**, just like in real production systems.

### 2️⃣ Hybrid NLP (Smart, not overkill)
- **spaCy NLP** is used where language understanding is needed
- **Rule-based logic** is used as a reliable fallback
- This avoids blindly trusting ML

### 3️⃣ Confidence-aware extraction  
Each extracted value has a **confidence score**, so the system knows:
- What it’s sure about
- What it should leave empty

### 4️⃣ Business-ready output  
The final result is an **Excel file**, not a notebook or JSON — because that’s what business users actually use.

---



