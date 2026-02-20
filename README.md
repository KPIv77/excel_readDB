# excel_readDB
Working with data in table formats such as CSV or Excel files has become much more convenient nowadays.
However, if the file we need to work with contains tens of thousands or even hundreds of thousands of rows, would it still be convenient to handle?

## Concept
Converted from an Excel file with large amounts of data and multiple sheets to improve data retrieval efficiency and reduce memory usage from keeping the Excel file open all the time.

The process starts by converting the file into a database and using SQLite3 in Python to query the data through Jupyter Notebook, making it easier to read and analyze.

---

## 🗂️ Project Structure
<pre>
excel_readDB/
│
├── README.md 
│
├── file_read/ 
│   └── iris_example_data.xlsx
│
├── file_exportDB/
│   └── iris_data.db
│
└── src/ 
    ├── 1_to_DB.ipynb
    └── 2_query.ipynb
</pre>