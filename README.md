# Excel Automation

Automated Excel processing script written in Python.  
This project demonstrates how to read, process, and manipulate Excel files using Python libraries such as `openpyxl`.

---

## Project structure

- │excel-automation/
- ├── app.py
- ├── tests/
- │   └── test_app.py
- ├── requirements.txt
- ├── README.md
- ├── LICENSE
- └── .gitignore

---

## Features
- Load Excel workbooks and sheets
- Read and process transaction data
- Automate updates to Excel files
- Extendable for reporting or data transformation

---

## Requirements
- Python 3.10+
- Dependencies listed in [requirements.txt](requirements.txt)

---

## Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/xAndreiix/Excel-Automation.git
cd excel-automation
pip install -r requirements.txt
```

---

## Running tests
```bash
pytest
```

---

## Usage

Place your Excel files in the project directory (e.g. transactions.xlsx) and run:

```bash 
python app.py

The script will read the input Excel file, process the data, and update the workbook or create a new one depending on your use case.

Example
Input (transactions.xlsx)
Date	        Description	       Amount
2025-01-05	Office Supplies	       120.50
2025-01-10	Client Payment	       950.00
2025-01-15	Software License       300.00

Output (automated update by script)
Date	        Description	   Amount	Category
2025-01-05	Office Supplies	   120.50	Expense
2025-01-10	Client Payment	   950.00	Income
2025-01-15	Software License   300.00	Expense

The script automatically categorizes transactions and can be extended to add more rules, generate reports, or export summaries.
```

---

## Project Structure

```bash
app.py              # Main automation script
transactions.xlsx   # Example input file
requirements.txt    # Python dependencies
```

---

## Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you’d like to change.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)