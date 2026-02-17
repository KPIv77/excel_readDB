# excel_readDB

## Concept
Converted from an Excel file with large amounts of data and multiple sheets to improve data retrieval efficiency and reduce memory usage from keeping the Excel file open all the time.

The process starts by converting the file into a database and using SQLite3 in Python to query the data through Jupyter Notebook, making it easier to read and analyze.

---
<pre>
## 🗂️ Project Structure
excel_readDB/
│
├── README.md # Project overview and documentation
│
├── file_read/ # Modules for reading Excel files (.xlsx, .csv)
│   └── file_read.xlsx
│
├── file_exportDB/ # Modules for exporting processed data to database or CSV
│   └── export_csv.DB
│
└── src/ # Main application logic (controllers, main script)
    ├── 1_to_DB.ipynb
    └── 2_query.ipynb
</pre>