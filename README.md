A robust, user-friendly Python desktop application designed to compare master and slave CSV/Excel datasets, detect field-level changes, identify new entries, and export formatted comparison reports to Excel. 

Developed during the **Vocational Training (VT) Program** at **Steel Authority of India Limited (SAIL), Bokaro Steel Plant (BSL)** under the **Computer & IT (C&IT)** department.

---

## 📌 Project Overview

In large industrial organizations like SAIL, accurate synchronization of employee datasets, payroll records, and human resource databases is critical. Manually auditing large files is time-consuming and prone to human error. 

The **CSV Comparison Tool** solves this challenge by enabling automated, key-based, field-level data comparison across large datasets (validated with **932+ employee records**).

---

## ✨ Key Features

- **Field-Level Comparison:** Compare two datasets column-by-column based on a unique identifier (e.g., Employee ID).
- **Discrepancy & New Entry Detection:** Automatically highlights modified fields and detects newly added records.
- **Multi-Format Support:** Seamlessly processes both `.csv` and `.xlsx` files.
- **Handling Missing Values:** Robust logic to handle `NULL` or missing values cleanly without breaking comparison logic.
- **Excel Report Export:** Generates clear, structured Excel reports (`.xlsx`) containing detailed discrepancy analysis.
- **User-Friendly GUI:** Simple and clean Tkinter-based interface built for HR, Finance, and IT operations.

---

## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.x
- **GUI Framework:** `tkinter`
- **Data Manipulation & Analysis:** `pandas`
- **File Handling:** `csv`, `openpyxl`

---

## 🚀 Getting Started

### Prerequisites

Ensure Python 3.x is installed on your system. You can install the required dependencies via `pip`:

```bash
pip install pandas openpyxl

Installation & Execution
 * Clone the Repository:
   git clone [https://github.com/your-username/csv-comparison-tool.git](https://github.com/your-username/csv-comparison-tool.git)
cd csv-comparison-tool

 * Run the Application:
   python main.py

📂 Usage Workflow
 * Upload Datasets: Select the Master File and the Updated/Slave File (.csv or .xlsx).
 * Set Primary Key: Choose the key column (e.g., Employee ID or URN) to map records.
 * Run Comparison: The tool scans for added records, deleted entries, or field updates.
 * View & Search Results: Inspect discrepancies through the interactive interface.
 * Export Report: Save the detailed comparison report as an .xlsx spreadsheet for audit or administrative records.
🏗️ Project Architecture & Challenges Solved
| Challenge | Solution Implemented |
|---|---|
| Format Handling | Integrated pandas file readers to smoothly ingest both .csv and .xlsx. |
| Field-Level Granularity | Created key-value mapping logic to compare entries row-by-row and column-by-column. |
| Null Value Mismatches | Applied explicit logic conditions to prevent false positives when comparing empty (NaN/NULL) vs. non-empty cells. |
| Export Integrity | Designed robust error-handling for smooth file creation via openpyxl. |
🎓 Internship & Author Details
 * Author: Ankit Kumar
 * Class / Batch Roll No.: 4CSE11 (CS-23411414)
 * URN: 5913893
 * Degree: B.Tech in Computer Science & Engineering
 * Institution: IILM University, Greater Noida
 * Organization: Steel Authority of India Limited (SAIL), Bokaro Steel City
 * Department: Computer & IT (C&IT) / HRD
 * Training Guide: Mr. Chandan Kumar, Assistant General Manager (AGM), C & IT
 * Training Duration: 02-06-2025 to 28-06-2025 (4 Weeks)
🙏 Acknowledgments
Grateful acknowledgment to the Department of Human Resources & IT (C&IT) at Bokaro Steel Plant (SAIL) for their guidance and for providing real-world dataset contexts. Special thanks to my mentor Mr. Chandan Kumar (AGM, C&IT) and the open-source Python community.
📜 License
This project was developed for educational and vocational training evaluation purposes under SAIL.
