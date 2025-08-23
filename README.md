# Excel Automation

---

## 📋 Table of Contents
- ️🏷️ [Introduction](Introduction)
- ✨ [Features](Features)
- 🗂️ [Project structure](Projectstructure)
- ⚙️ [Requirements](Requirements)
- 💾 [Installation](Installation)
- ▶️ [Usage](Usage)
- 🧪 [Running tests](#running-tests)
- 🫱🏻‍🫲🏼‍ [Contributing](Contributing)
- 📜 [License](License)
- [👨🏻‍💻 Author / 🙏🏻 Acknowledgments / 📩 Contact](Author/Acknowledgments/Contact)

---

## 🏷️ Introduction
Automated Excel processing script written in Python.  
This project demonstrates how to read, process, and manipulate Excel files using Python libraries such as `openpyxl`.

<!-- ## 🛡️ Badges -->
<!-- ## 💻️ Live Demo -->
<!-- ## 📷️ Screenshots -->

---

## ✨ Features
- Load Excel workbooks and sheets
- Read and process transaction data
- Automate updates to Excel files
- Extendable for reporting or data transformation

---

## 🗂️ Project structure
- │ 📂 excel-automation/
- ├── app.py
- ├── tests/
- │   └── test_app.py
- ├── requirements.txt
- ├── README.md
- ├── LICENSE
- └── .gitignore

---

## ⚙️ Requirements
- Python 3.10+
- Dependencies listed in [requirements.txt](requirements.txt)

---

## 💾 Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/xAndreiix/Excel-Automation.git
cd excel-automation
pip install -r requirements.txt
```

---

## ▶️ Usage
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
<!-- ## 🔧 Configuration -->

---

## 🧪 Running tests
```bash
pytest
```
<!-- ## 📦 Deployment -->
<!-- ## ⚠️ Notes -->
<!-- ## 🛣️ Road Map -->
<!-- ## ❓ FAQ -->

---

## 🫱🏻‍🫲🏼 Contributing
Pull requests are welcome.
For major changes, please open an issue first to discuss what you’d like to change.
<!-- ## 📝 Changelog -->

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE)

---

## 👨🏻‍💻 Author / 🙏🏻 Acknowledgments / 📩 Contact
**Author:** 
Andrei Iliescu

[![Website](https://img.shields.io/badge/Website-PORTFOLIO-gold?style=for-the-badge&logo=about-dot-me&logoColor=white)](https://xandreiix.github.io/Andrei-Iliescu-Portfolio/)

**Acknowledgments:**  
- Inspired by Mosh Hamedani's tutorial on YouTube.

[![Python Full Course for Beginners](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/watch?v=_uQrJ0TkZlc&ab_channel=ProgrammingwithMosh)
- All thanks to him for the training and examples!

**Contact:**  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrei-iliescu-aa7910214)<br>
[![Email Yahoo](https://img.shields.io/badge/Email-andrey_iliescu%40yahoo.com-6001D2?style=for-the-badge&logoColor=white)](mailto:andrey_iliescu@yahoo.com)<br>
[![Email Gmail](https://img.shields.io/badge/Gmail-andrei.iliescu13102000%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andrei.iliescu13102000@gmail.com)

---

## 💰 If you want to support me
[![PayPal](https://img.shields.io/badge/PayPal-xAndreiix-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/xAndreiix)<br>
[![Revolut](https://img.shields.io/badge/Revolut-xAndreiix-001B2E?style=for-the-badge&logoColor=white)](https://revolut.me/xandreiix)
