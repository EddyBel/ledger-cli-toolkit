---
# Reporte de prueba - 2025-08-05 21:04:08
Generado por: `test_doc.py`
Ruta del archivo: `/home/eddybel/Documentos/dev/personales/LedgerApp/ledger-cli-toolkit/test/ledgers/test_4.ledger`

Archivo fuente: `test/ledgers/test_4.ledger`

---

# Reporte generado el 2025-08-05 21:04:08

# Clase: `LedgerParser`


## parse()

Convierte las transacciones del archivo ledger a estructura JSON.

```json
[
    {
        "date": "2025-01-01",
        "time": null,
        "verified": true,
        "description": "Opening Balances",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 10000.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Savings",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Savings"
                ],
                "unit": "$",
                "amount": 25000.0,
                "taxes": []
            },
            {
                "account": "Assets:Cash",
                "subAccounts": [
                    "Assets",
                    "Cash"
                ],
                "unit": "$",
                "amount": 1000.0,
                "taxes": []
            },
            {
                "account": "Assets:Investments:Stocks",
                "subAccounts": [
                    "Assets",
                    "Investments",
                    "Stocks"
                ],
                "unit": "$",
                "amount": 15000.0,
                "taxes": []
            },
            {
                "account": "Liabilities:CreditCard:Visa",
                "subAccounts": [
                    "Liabilities",
                    "CreditCard",
                    "Visa"
                ],
                "unit": "$",
                "amount": -2500.0,
                "taxes": []
            },
            {
                "account": "Liabilities:Loan:CarLoan",
                "subAccounts": [
                    "Liabilities",
                    "Loan",
                    "CarLoan"
                ],
                "unit": "$",
                "amount": -10000.0,
                "taxes": []
            },
            {
                "account": "Equity:OpeningBalances",
                "subAccounts": [
                    "Equity",
                    "OpeningBalances"
                ],
                "unit": "$",
                "amount": -38500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-15",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": [
            {
                "key": "tags",
                "value": "salary"
            }
        ]
    },
    {
        "date": "2025-01-20",
        "time": null,
        "verified": true,
        "description": "Grocery Shopping",
        "accounts": [
            {
                "account": "Expenses:Food:Groceries",
                "subAccounts": [
                    "Expenses",
                    "Food",
                    "Groceries"
                ],
                "unit": "$",
                "amount": 100.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-22",
        "time": null,
        "verified": true,
        "description": "Rent Payment",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-23",
        "time": null,
        "verified": true,
        "description": "Dinner Out",
        "accounts": [
            {
                "account": "Expenses:Food:DiningOut",
                "subAccounts": [
                    "Expenses",
                    "Food",
                    "DiningOut"
                ],
                "unit": "$",
                "amount": 75.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -75.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-25",
        "time": null,
        "verified": true,
        "description": "Credit Card Payment",
        "accounts": [
            {
                "account": "Liabilities:CreditCard:Visa",
                "subAccounts": [
                    "Liabilities",
                    "CreditCard",
                    "Visa"
                ],
                "unit": "$",
                "amount": 1200.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-03",
        "time": null,
        "verified": true,
        "description": "Utilities Bill",
        "accounts": [
            {
                "account": "Expenses:Utilities",
                "subAccounts": [
                    "Expenses",
                    "Utilities"
                ],
                "unit": "$",
                "amount": 300.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -300.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-10",
        "time": null,
        "verified": true,
        "description": "Gasoline",
        "accounts": [
            {
                "account": "Expenses:Transportation:Gas",
                "subAccounts": [
                    "Expenses",
                    "Transportation",
                    "Gas"
                ],
                "unit": "$",
                "amount": 120.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -120.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-15",
        "time": null,
        "verified": true,
        "description": "Freelance Project",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 3200.0,
                "taxes": []
            },
            {
                "account": "Income:Freelance",
                "subAccounts": [
                    "Income",
                    "Freelance"
                ],
                "unit": "$",
                "amount": -3200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-20",
        "time": null,
        "verified": true,
        "description": "Car Loan Payment",
        "accounts": [
            {
                "account": "Liabilities:Loan:CarLoan",
                "subAccounts": [
                    "Liabilities",
                    "Loan",
                    "CarLoan"
                ],
                "unit": "$",
                "amount": 500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-22",
        "time": null,
        "verified": true,
        "description": "Stock Dividend",
        "accounts": [
            {
                "account": "Assets:Bank:Savings",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Savings"
                ],
                "unit": "$",
                "amount": 1000.0,
                "taxes": []
            },
            {
                "account": "Income:Investments:Dividends",
                "subAccounts": [
                    "Income",
                    "Investments",
                    "Dividends"
                ],
                "unit": "$",
                "amount": -1000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-28",
        "time": null,
        "verified": true,
        "description": "Vacation Trip",
        "accounts": [
            {
                "account": "Expenses:Travel",
                "subAccounts": [
                    "Expenses",
                    "Travel"
                ],
                "unit": "$",
                "amount": 2800.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -2800.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-02",
        "time": null,
        "verified": true,
        "description": "Health Insurance",
        "accounts": [
            {
                "account": "Expenses:Insurance:Health",
                "subAccounts": [
                    "Expenses",
                    "Insurance",
                    "Health"
                ],
                "unit": "$",
                "amount": 450.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -450.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-10",
        "time": null,
        "verified": true,
        "description": "Maintenance: Oil Change",
        "accounts": [
            {
                "account": "Expenses:Transportation:Maintenance",
                "subAccounts": [
                    "Expenses",
                    "Transportation",
                    "Maintenance"
                ],
                "unit": "$",
                "amount": 90.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -90.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-15",
        "time": null,
        "verified": true,
        "description": "Monthly Rent",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-18",
        "time": null,
        "verified": true,
        "description": "Course Subscription",
        "accounts": [
            {
                "account": "Expenses:Education",
                "subAccounts": [
                    "Expenses",
                    "Education"
                ],
                "unit": "$",
                "amount": 300.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -300.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-25",
        "time": null,
        "verified": true,
        "description": "Entertainment - Concert",
        "accounts": [
            {
                "account": "Expenses:Entertainment",
                "subAccounts": [
                    "Expenses",
                    "Entertainment"
                ],
                "unit": "$",
                "amount": 200.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-02",
        "time": null,
        "verified": true,
        "description": "Dentist Appointment",
        "accounts": [
            {
                "account": "Expenses:Medical",
                "subAccounts": [
                    "Expenses",
                    "Medical"
                ],
                "unit": "$",
                "amount": 1200.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-10",
        "time": null,
        "verified": true,
        "description": "Gasoline",
        "accounts": [
            {
                "account": "Expenses:Transportation:Gas",
                "subAccounts": [
                    "Expenses",
                    "Transportation",
                    "Gas"
                ],
                "unit": "$",
                "amount": 130.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -130.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-15",
        "time": null,
        "verified": true,
        "description": "Monthly Rent",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-20",
        "time": null,
        "verified": true,
        "description": "Shopping - Electronics",
        "accounts": [
            {
                "account": "Expenses:Shopping",
                "subAccounts": [
                    "Expenses",
                    "Shopping"
                ],
                "unit": "$",
                "amount": 3000.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -3000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-25",
        "time": null,
        "verified": true,
        "description": "Dinner Out",
        "accounts": [
            {
                "account": "Expenses:Food:DiningOut",
                "subAccounts": [
                    "Expenses",
                    "Food",
                    "DiningOut"
                ],
                "unit": "$",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-03",
        "time": null,
        "verified": true,
        "description": "Utilities",
        "accounts": [
            {
                "account": "Expenses:Utilities",
                "subAccounts": [
                    "Expenses",
                    "Utilities"
                ],
                "unit": "$",
                "amount": 310.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -310.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-06",
        "time": null,
        "verified": true,
        "description": "Travel - Family Emergency",
        "accounts": [
            {
                "account": "Expenses:Travel",
                "subAccounts": [
                    "Expenses",
                    "Travel"
                ],
                "unit": "$",
                "amount": 5800.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -5800.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-10",
        "time": null,
        "verified": true,
        "description": "Grocery Shopping",
        "accounts": [
            {
                "account": "Expenses:Food:Groceries",
                "subAccounts": [
                    "Expenses",
                    "Food",
                    "Groceries"
                ],
                "unit": "$",
                "amount": 270.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -270.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-15",
        "time": null,
        "verified": true,
        "description": "Monthly Rent",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-25",
        "time": null,
        "verified": true,
        "description": "Car Repair (transmission)",
        "accounts": [
            {
                "account": "Expenses:Transportation:Maintenance",
                "subAccounts": [
                    "Expenses",
                    "Transportation",
                    "Maintenance"
                ],
                "unit": "$",
                "amount": 2200.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -2200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-03",
        "time": null,
        "verified": true,
        "description": "Health Insurance",
        "accounts": [
            {
                "account": "Expenses:Insurance:Health",
                "subAccounts": [
                    "Expenses",
                    "Insurance",
                    "Health"
                ],
                "unit": "$",
                "amount": 450.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -450.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-10",
        "time": null,
        "verified": true,
        "description": "Freelance Payment",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 4500.0,
                "taxes": []
            },
            {
                "account": "Income:Freelance",
                "subAccounts": [
                    "Income",
                    "Freelance"
                ],
                "unit": "$",
                "amount": -4500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-15",
        "time": null,
        "verified": true,
        "description": "Monthly Rent",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-20",
        "time": null,
        "verified": true,
        "description": "Luxury Watch Purchase",
        "accounts": [
            {
                "account": "Expenses:Shopping",
                "subAccounts": [
                    "Expenses",
                    "Shopping"
                ],
                "unit": "$",
                "amount": 6500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -6500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-30",
        "time": null,
        "verified": true,
        "description": "Entertainment - Festival",
        "accounts": [
            {
                "account": "Expenses:Entertainment",
                "subAccounts": [
                    "Expenses",
                    "Entertainment"
                ],
                "unit": "$",
                "amount": 350.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -350.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 200.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Gasolina",
        "accounts": [
            {
                "account": "Expenses:Transport",
                "subAccounts": [
                    "Expenses",
                    "Transport"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-30",
        "time": null,
        "verified": true,
        "description": "Gasolina",
        "accounts": [
            {
                "account": "Expenses:Transport",
                "subAccounts": [
                    "Expenses",
                    "Transport"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Assets:Cash",
                "subAccounts": [
                    "Assets",
                    "Cash"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-31",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-31",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Expenses:Education",
                "subAccounts": [
                    "Expenses",
                    "Education"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Gasolina",
        "accounts": [
            {
                "account": "Expenses:Transport",
                "subAccounts": [
                    "Expenses",
                    "Transport"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Assets:Cash",
                "subAccounts": [
                    "Assets",
                    "Cash"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    }
]
```

## resolve()

Lista de transacciones.

```json
[
    {
        "date": "2025-01-01",
        "time": null,
        "verified": true,
        "description": "Opening Balances",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 10000.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Savings",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Savings"
                ],
                "unit": "$",
                "amount": 25000.0,
                "taxes": []
            },
            {
                "account": "Assets:Cash",
                "subAccounts": [
                    "Assets",
                    "Cash"
                ],
                "unit": "$",
                "amount": 1000.0,
                "taxes": []
            },
            {
                "account": "Assets:Investments:Stocks",
                "subAccounts": [
                    "Assets",
                    "Investments",
                    "Stocks"
                ],
                "unit": "$",
                "amount": 15000.0,
                "taxes": []
            },
            {
                "account": "Liabilities:CreditCard:Visa",
                "subAccounts": [
                    "Liabilities",
                    "CreditCard",
                    "Visa"
                ],
                "unit": "$",
                "amount": -2500.0,
                "taxes": []
            },
            {
                "account": "Liabilities:Loan:CarLoan",
                "subAccounts": [
                    "Liabilities",
                    "Loan",
                    "CarLoan"
                ],
                "unit": "$",
                "amount": -10000.0,
                "taxes": []
            },
            {
                "account": "Equity:OpeningBalances",
                "subAccounts": [
                    "Equity",
                    "OpeningBalances"
                ],
                "unit": "$",
                "amount": -38500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-15",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": [
            {
                "key": "tags",
                "value": "salary"
            }
        ]
    },
    {
        "date": "2025-01-20",
        "time": null,
        "verified": true,
        "description": "Grocery Shopping",
        "accounts": [
            {
                "account": "Expenses:Food:Groceries",
                "subAccounts": [
                    "Expenses",
                    "Food",
                    "Groceries"
                ],
                "unit": "$",
                "amount": 100.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -116.0,
                "taxes": []
            },
            {
                "account": "Assets:Taxes:IVA",
                "subAccounts": [
                    "Assets",
                    "Taxes",
                    "IVA"
                ],
                "unit": "$",
                "amount": 16.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-22",
        "time": null,
        "verified": true,
        "description": "Rent Payment",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-23",
        "time": null,
        "verified": true,
        "description": "Dinner Out",
        "accounts": [
            {
                "account": "Expenses:Food:DiningOut",
                "subAccounts": [
                    "Expenses",
                    "Food",
                    "DiningOut"
                ],
                "unit": "$",
                "amount": 75.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -75.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-25",
        "time": null,
        "verified": true,
        "description": "Credit Card Payment",
        "accounts": [
            {
                "account": "Liabilities:CreditCard:Visa",
                "subAccounts": [
                    "Liabilities",
                    "CreditCard",
                    "Visa"
                ],
                "unit": "$",
                "amount": 1200.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-03",
        "time": null,
        "verified": true,
        "description": "Utilities Bill",
        "accounts": [
            {
                "account": "Expenses:Utilities",
                "subAccounts": [
                    "Expenses",
                    "Utilities"
                ],
                "unit": "$",
                "amount": 300.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -300.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-10",
        "time": null,
        "verified": true,
        "description": "Gasoline",
        "accounts": [
            {
                "account": "Expenses:Transportation:Gas",
                "subAccounts": [
                    "Expenses",
                    "Transportation",
                    "Gas"
                ],
                "unit": "$",
                "amount": 120.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -120.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-15",
        "time": null,
        "verified": true,
        "description": "Freelance Project",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 3200.0,
                "taxes": []
            },
            {
                "account": "Income:Freelance",
                "subAccounts": [
                    "Income",
                    "Freelance"
                ],
                "unit": "$",
                "amount": -3200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-20",
        "time": null,
        "verified": true,
        "description": "Car Loan Payment",
        "accounts": [
            {
                "account": "Liabilities:Loan:CarLoan",
                "subAccounts": [
                    "Liabilities",
                    "Loan",
                    "CarLoan"
                ],
                "unit": "$",
                "amount": 500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-22",
        "time": null,
        "verified": true,
        "description": "Stock Dividend",
        "accounts": [
            {
                "account": "Assets:Bank:Savings",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Savings"
                ],
                "unit": "$",
                "amount": 1000.0,
                "taxes": []
            },
            {
                "account": "Income:Investments:Dividends",
                "subAccounts": [
                    "Income",
                    "Investments",
                    "Dividends"
                ],
                "unit": "$",
                "amount": -1000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-02-28",
        "time": null,
        "verified": true,
        "description": "Vacation Trip",
        "accounts": [
            {
                "account": "Expenses:Travel",
                "subAccounts": [
                    "Expenses",
                    "Travel"
                ],
                "unit": "$",
                "amount": 2800.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -2800.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-02",
        "time": null,
        "verified": true,
        "description": "Health Insurance",
        "accounts": [
            {
                "account": "Expenses:Insurance:Health",
                "subAccounts": [
                    "Expenses",
                    "Insurance",
                    "Health"
                ],
                "unit": "$",
                "amount": 450.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -450.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-10",
        "time": null,
        "verified": true,
        "description": "Maintenance: Oil Change",
        "accounts": [
            {
                "account": "Expenses:Transportation:Maintenance",
                "subAccounts": [
                    "Expenses",
                    "Transportation",
                    "Maintenance"
                ],
                "unit": "$",
                "amount": 90.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -90.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-15",
        "time": null,
        "verified": true,
        "description": "Monthly Rent",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-18",
        "time": null,
        "verified": true,
        "description": "Course Subscription",
        "accounts": [
            {
                "account": "Expenses:Education",
                "subAccounts": [
                    "Expenses",
                    "Education"
                ],
                "unit": "$",
                "amount": 300.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -300.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-03-25",
        "time": null,
        "verified": true,
        "description": "Entertainment - Concert",
        "accounts": [
            {
                "account": "Expenses:Entertainment",
                "subAccounts": [
                    "Expenses",
                    "Entertainment"
                ],
                "unit": "$",
                "amount": 200.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-02",
        "time": null,
        "verified": true,
        "description": "Dentist Appointment",
        "accounts": [
            {
                "account": "Expenses:Medical",
                "subAccounts": [
                    "Expenses",
                    "Medical"
                ],
                "unit": "$",
                "amount": 1200.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-10",
        "time": null,
        "verified": true,
        "description": "Gasoline",
        "accounts": [
            {
                "account": "Expenses:Transportation:Gas",
                "subAccounts": [
                    "Expenses",
                    "Transportation",
                    "Gas"
                ],
                "unit": "$",
                "amount": 130.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -130.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-15",
        "time": null,
        "verified": true,
        "description": "Monthly Rent",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-20",
        "time": null,
        "verified": true,
        "description": "Shopping - Electronics",
        "accounts": [
            {
                "account": "Expenses:Shopping",
                "subAccounts": [
                    "Expenses",
                    "Shopping"
                ],
                "unit": "$",
                "amount": 3000.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -3000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-04-25",
        "time": null,
        "verified": true,
        "description": "Dinner Out",
        "accounts": [
            {
                "account": "Expenses:Food:DiningOut",
                "subAccounts": [
                    "Expenses",
                    "Food",
                    "DiningOut"
                ],
                "unit": "$",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-03",
        "time": null,
        "verified": true,
        "description": "Utilities",
        "accounts": [
            {
                "account": "Expenses:Utilities",
                "subAccounts": [
                    "Expenses",
                    "Utilities"
                ],
                "unit": "$",
                "amount": 310.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -310.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-06",
        "time": null,
        "verified": true,
        "description": "Travel - Family Emergency",
        "accounts": [
            {
                "account": "Expenses:Travel",
                "subAccounts": [
                    "Expenses",
                    "Travel"
                ],
                "unit": "$",
                "amount": 5800.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -5800.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-10",
        "time": null,
        "verified": true,
        "description": "Grocery Shopping",
        "accounts": [
            {
                "account": "Expenses:Food:Groceries",
                "subAccounts": [
                    "Expenses",
                    "Food",
                    "Groceries"
                ],
                "unit": "$",
                "amount": 270.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -270.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-15",
        "time": null,
        "verified": true,
        "description": "Monthly Rent",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-05-25",
        "time": null,
        "verified": true,
        "description": "Car Repair (transmission)",
        "accounts": [
            {
                "account": "Expenses:Transportation:Maintenance",
                "subAccounts": [
                    "Expenses",
                    "Transportation",
                    "Maintenance"
                ],
                "unit": "$",
                "amount": 2200.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -2200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-01",
        "time": null,
        "verified": true,
        "description": "Paycheck",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 7500.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -7500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-03",
        "time": null,
        "verified": true,
        "description": "Health Insurance",
        "accounts": [
            {
                "account": "Expenses:Insurance:Health",
                "subAccounts": [
                    "Expenses",
                    "Insurance",
                    "Health"
                ],
                "unit": "$",
                "amount": 450.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -450.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-10",
        "time": null,
        "verified": true,
        "description": "Freelance Payment",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 4500.0,
                "taxes": []
            },
            {
                "account": "Income:Freelance",
                "subAccounts": [
                    "Income",
                    "Freelance"
                ],
                "unit": "$",
                "amount": -4500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-15",
        "time": null,
        "verified": true,
        "description": "Monthly Rent",
        "accounts": [
            {
                "account": "Expenses:Rent",
                "subAccounts": [
                    "Expenses",
                    "Rent"
                ],
                "unit": "$",
                "amount": 1500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -1500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-20",
        "time": null,
        "verified": true,
        "description": "Luxury Watch Purchase",
        "accounts": [
            {
                "account": "Expenses:Shopping",
                "subAccounts": [
                    "Expenses",
                    "Shopping"
                ],
                "unit": "$",
                "amount": 6500.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -6500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-06-30",
        "time": null,
        "verified": true,
        "description": "Entertainment - Festival",
        "accounts": [
            {
                "account": "Expenses:Entertainment",
                "subAccounts": [
                    "Expenses",
                    "Entertainment"
                ],
                "unit": "$",
                "amount": 350.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": -350.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 200.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -200.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "$",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "$",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Gasolina",
        "accounts": [
            {
                "account": "Expenses:Transport",
                "subAccounts": [
                    "Expenses",
                    "Transport"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-30",
        "time": null,
        "verified": true,
        "description": "Gasolina",
        "accounts": [
            {
                "account": "Expenses:Transport",
                "subAccounts": [
                    "Expenses",
                    "Transport"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Assets:Cash",
                "subAccounts": [
                    "Assets",
                    "Cash"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-31",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-31",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Expenses:Education",
                "subAccounts": [
                    "Expenses",
                    "Education"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Sueldo",
        "accounts": [
            {
                "account": "Assets:Bank:Checking",
                "subAccounts": [
                    "Assets",
                    "Bank",
                    "Checking"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Income:Salary",
                "subAccounts": [
                    "Income",
                    "Salary"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-07-29",
        "time": null,
        "verified": true,
        "description": "Gasolina",
        "accounts": [
            {
                "account": "Expenses:Transport",
                "subAccounts": [
                    "Expenses",
                    "Transport"
                ],
                "unit": "N/A",
                "amount": 100.0,
                "taxes": []
            },
            {
                "account": "Assets:Cash",
                "subAccounts": [
                    "Assets",
                    "Cash"
                ],
                "unit": "N/A",
                "amount": -100.0,
                "taxes": []
            }
        ],
        "properties": []
    }
]
```

## detected_parents_accounts()

Lista de cuentas padres.

```json
{
    "Assets": "Assets",
    "Liabilities": "Liabilities",
    "Equity": "Equity",
    "Income": "Income",
    "Expenses": "Expenses"
}
```

## parse_accounts()

Lista de cuentas contables detectadas.

```json
[
    "Assets:Bank:Checking",
    "Assets:Bank:Savings",
    "Assets:Cash",
    "Assets:Investments:Stocks",
    "Assets:AccountsReceivable",
    "Liabilities:CreditCard:Visa",
    "Liabilities:Loan:CarLoan",
    "Equity:OpeningBalances",
    "Equity:Owner",
    "Income:Salary",
    "Income:Investments:Dividends",
    "Income:Freelance",
    "Expenses:Rent",
    "Expenses:Utilities",
    "Expenses:Food:Groceries",
    "Expenses:Food:DiningOut",
    "Expenses:Transportation:Gas",
    "Expenses:Transportation:Maintenance",
    "Expenses:Entertainment",
    "Expenses:Travel",
    "Expenses:Insurance:Car",
    "Expenses:Insurance:Health",
    "Expenses:Education",
    "Expenses:Medical",
    "Expenses:Shopping"
]
```

## parse_accounts_advance()

Lista de cuentas contables con metadatos detectadas.

```json
[
    {
        "account": "Assets:Bank:Checking"
    },
    {
        "account": "Assets:Bank:Savings"
    },
    {
        "account": "Assets:Cash"
    },
    {
        "account": "Assets:Investments:Stocks"
    },
    {
        "account": "Assets:AccountsReceivable"
    },
    {
        "account": "Liabilities:CreditCard:Visa"
    },
    {
        "account": "Liabilities:Loan:CarLoan"
    },
    {
        "account": "Equity:OpeningBalances"
    },
    {
        "account": "Equity:Owner"
    },
    {
        "account": "Income:Salary"
    },
    {
        "account": "Income:Investments:Dividends"
    },
    {
        "account": "Income:Freelance"
    },
    {
        "account": "Expenses:Rent"
    },
    {
        "account": "Expenses:Utilities"
    },
    {
        "account": "Expenses:Food:Groceries"
    },
    {
        "account": "Expenses:Food:DiningOut"
    },
    {
        "account": "Expenses:Transportation:Gas"
    },
    {
        "account": "Expenses:Transportation:Maintenance"
    },
    {
        "account": "Expenses:Entertainment"
    },
    {
        "account": "Expenses:Travel"
    },
    {
        "account": "Expenses:Insurance:Car"
    },
    {
        "account": "Expenses:Insurance:Health"
    },
    {
        "account": "Expenses:Education"
    },
    {
        "account": "Expenses:Medical"
    },
    {
        "account": "Expenses:Shopping"
    }
]
```

## calculate_balances()

Cálculo de balances por cuenta detallada.

```json
{
    "Assets:Bank:Checking": {
        "$": 29055.0,
        "N/A": 500.0
    },
    "Assets:Bank:Savings": {
        "$": 26000.0
    },
    "Assets:Cash": {
        "$": 1000.0,
        "N/A": -200.0
    },
    "Assets:Investments:Stocks": {
        "$": 15000.0
    },
    "Liabilities:CreditCard:Visa": {
        "$": -1300.0
    },
    "Liabilities:Loan:CarLoan": {
        "$": -9500.0
    },
    "Equity:OpeningBalances": {
        "$": -38500.0
    },
    "Income:Salary": {
        "$": -45300.0,
        "N/A": -500.0
    },
    "Income:Investments:Dividends": {
        "$": -1000.0
    },
    "Income:Freelance": {
        "$": -7700.0
    },
    "Expenses:Rent": {
        "$": 7500.0
    },
    "Expenses:Utilities": {
        "$": 610.0
    },
    "Expenses:Food:Groceries": {
        "$": 370.0
    },
    "Expenses:Food:DiningOut": {
        "$": 175.0
    },
    "Expenses:Transportation:Gas": {
        "$": 250.0
    },
    "Expenses:Transportation:Maintenance": {
        "$": 2290.0
    },
    "Expenses:Entertainment": {
        "$": 550.0
    },
    "Expenses:Travel": {
        "$": 8600.0
    },
    "Expenses:Insurance:Health": {
        "$": 900.0
    },
    "Expenses:Education": {
        "$": 300.0,
        "N/A": -100.0
    },
    "Expenses:Medical": {
        "$": 1200.0
    },
    "Expenses:Shopping": {
        "$": 9500.0
    },
    "Expenses:Transport": {
        "N/A": 300.0
    }
}
```

## calculate_balances_by_parents_accounts()

Balance agrupado por cuentas padre.

```json
{
    "Assets": {
        "$": 71055.0,
        "N/A": 300.0
    },
    "Liabilities": {
        "$": -10800.0
    },
    "Equity": {
        "$": -38500.0
    },
    "Income": {
        "$": -54000.0,
        "N/A": -500.0
    },
    "Expenses": {
        "$": 32245.0,
        "N/A": 200.0
    }
}
```

## calculate_status_results()

Estado de resultados (ingresos, gastos, utilidad).

```json
{
    "total_income_by_currency": {
        "$": 54000.0,
        "N/A": 500.0
    },
    "total_expenses_by_currency": {
        "$": -32245.0,
        "N/A": -200.0
    },
    "utility_by_currency": {
        "$": 21755.0,
        "N/A": 300.0
    },
    "income_details": [
        {
            "Income:Salary": {
                "currency": "$",
                "amount": 45300.0
            }
        },
        {
            "Income:Salary": {
                "currency": "N/A",
                "amount": 500.0
            }
        },
        {
            "Income:Investments:Dividends": {
                "currency": "$",
                "amount": 1000.0
            }
        },
        {
            "Income:Freelance": {
                "currency": "$",
                "amount": 7700.0
            }
        }
    ],
    "expenses_details": [
        {
            "Expenses:Rent": {
                "currency": "$",
                "amount": -7500.0
            }
        },
        {
            "Expenses:Utilities": {
                "currency": "$",
                "amount": -610.0
            }
        },
        {
            "Expenses:Food:Groceries": {
                "currency": "$",
                "amount": -370.0
            }
        },
        {
            "Expenses:Food:DiningOut": {
                "currency": "$",
                "amount": -175.0
            }
        },
        {
            "Expenses:Transportation:Gas": {
                "currency": "$",
                "amount": -250.0
            }
        },
        {
            "Expenses:Transportation:Maintenance": {
                "currency": "$",
                "amount": -2290.0
            }
        },
        {
            "Expenses:Entertainment": {
                "currency": "$",
                "amount": -550.0
            }
        },
        {
            "Expenses:Travel": {
                "currency": "$",
                "amount": -8600.0
            }
        },
        {
            "Expenses:Insurance:Health": {
                "currency": "$",
                "amount": -900.0
            }
        },
        {
            "Expenses:Education": {
                "currency": "$",
                "amount": -300.0
            }
        },
        {
            "Expenses:Education": {
                "currency": "N/A",
                "amount": 100.0
            }
        },
        {
            "Expenses:Medical": {
                "currency": "$",
                "amount": -1200.0
            }
        },
        {
            "Expenses:Shopping": {
                "currency": "$",
                "amount": -9500.0
            }
        },
        {
            "Expenses:Transport": {
                "currency": "N/A",
                "amount": -300.0
            }
        }
    ]
}
```

## calculate_balances_by_details_accounts()

Balance por subcuentas detalladas.

```json
{
    "Assets": {
        "balances": {
            "$": 71055.0,
            "N/A": 300.0
        },
        "sub_accounts": {
            "Bank": {
                "balances": {
                    "$": 55055.0,
                    "N/A": 500.0
                },
                "sub_accounts": {
                    "Checking": {
                        "balances": {
                            "$": 29055.0,
                            "N/A": 500.0
                        },
                        "sub_accounts": {}
                    },
                    "Savings": {
                        "balances": {
                            "$": 26000.0
                        },
                        "sub_accounts": {}
                    }
                }
            },
            "Cash": {
                "balances": {
                    "$": 1000.0,
                    "N/A": -200.0
                },
                "sub_accounts": {}
            },
            "Investments": {
                "balances": {
                    "$": 15000.0
                },
                "sub_accounts": {
                    "Stocks": {
                        "balances": {
                            "$": 15000.0
                        },
                        "sub_accounts": {}
                    }
                }
            }
        }
    },
    "Liabilities": {
        "balances": {
            "$": -10800.0
        },
        "sub_accounts": {
            "CreditCard": {
                "balances": {
                    "$": -1300.0
                },
                "sub_accounts": {
                    "Visa": {
                        "balances": {
                            "$": -1300.0
                        },
                        "sub_accounts": {}
                    }
                }
            },
            "Loan": {
                "balances": {
                    "$": -9500.0
                },
                "sub_accounts": {
                    "CarLoan": {
                        "balances": {
                            "$": -9500.0
                        },
                        "sub_accounts": {}
                    }
                }
            }
        }
    },
    "Equity": {
        "balances": {
            "$": -38500.0
        },
        "sub_accounts": {
            "OpeningBalances": {
                "balances": {
                    "$": -38500.0
                },
                "sub_accounts": {}
            }
        }
    },
    "Income": {
        "balances": {
            "$": -54000.0,
            "N/A": -500.0
        },
        "sub_accounts": {
            "Salary": {
                "balances": {
                    "$": -45300.0,
                    "N/A": -500.0
                },
                "sub_accounts": {}
            },
            "Freelance": {
                "balances": {
                    "$": -7700.0
                },
                "sub_accounts": {}
            },
            "Investments": {
                "balances": {
                    "$": -1000.0
                },
                "sub_accounts": {
                    "Dividends": {
                        "balances": {
                            "$": -1000.0
                        },
                        "sub_accounts": {}
                    }
                }
            }
        }
    },
    "Expenses": {
        "balances": {
            "$": 32245.0,
            "N/A": 200.0
        },
        "sub_accounts": {
            "Food": {
                "balances": {
                    "$": 545.0
                },
                "sub_accounts": {
                    "Groceries": {
                        "balances": {
                            "$": 370.0
                        },
                        "sub_accounts": {}
                    },
                    "DiningOut": {
                        "balances": {
                            "$": 175.0
                        },
                        "sub_accounts": {}
                    }
                }
            },
            "Rent": {
                "balances": {
                    "$": 7500.0
                },
                "sub_accounts": {}
            },
            "Utilities": {
                "balances": {
                    "$": 610.0
                },
                "sub_accounts": {}
            },
            "Transportation": {
                "balances": {
                    "$": 2540.0
                },
                "sub_accounts": {
                    "Gas": {
                        "balances": {
                            "$": 250.0
                        },
                        "sub_accounts": {}
                    },
                    "Maintenance": {
                        "balances": {
                            "$": 2290.0
                        },
                        "sub_accounts": {}
                    }
                }
            },
            "Travel": {
                "balances": {
                    "$": 8600.0
                },
                "sub_accounts": {}
            },
            "Insurance": {
                "balances": {
                    "$": 900.0
                },
                "sub_accounts": {
                    "Health": {
                        "balances": {
                            "$": 900.0
                        },
                        "sub_accounts": {}
                    }
                }
            },
            "Education": {
                "balances": {
                    "$": 300.0,
                    "N/A": -100.0
                },
                "sub_accounts": {}
            },
            "Entertainment": {
                "balances": {
                    "$": 550.0
                },
                "sub_accounts": {}
            },
            "Medical": {
                "balances": {
                    "$": 1200.0
                },
                "sub_accounts": {}
            },
            "Shopping": {
                "balances": {
                    "$": 9500.0
                },
                "sub_accounts": {}
            },
            "Transport": {
                "balances": {
                    "N/A": 300.0
                },
                "sub_accounts": {}
            }
        }
    }
}
```

## get_date_range()

Periodo detectado en las transacciones.

Desde: `2025/01/01` hasta `2025/07/31`

## parse_metadata()

Metadatos del archivo.

```json
{}
```

## parse_metadata_yaml()

Metadatos del archivo en formato YAML.

```json
{
    "data": {
        "title": "Demo de archivo ledger",
        "year": 2025
    },
    "taxes": {
        "IVA": 0.16,
        "ISR": 0.3
    },
    "snippets": {
        "gasolina": "$DATE * Gasolina\n    Expenses:Transport  $monto\n    Assets:Cash\n",
        "sueldo": "$DATE * Sueldo\n    Assets:Bank:Checking  $monto\n    Income:Salary"
    }
}
```

## parse_map()

Mapa de cuentas.

```json
[
    {
        "type": "line",
        "index": 0,
        "line": "---"
    },
    {
        "type": "line",
        "index": 1,
        "line": "data:"
    },
    {
        "type": "line",
        "index": 2,
        "line": "  title: \"Demo de archivo ledger\""
    },
    {
        "type": "line",
        "index": 3,
        "line": "  year: 2025"
    },
    {
        "type": "line",
        "index": 4,
        "line": ""
    },
    {
        "type": "line",
        "index": 5,
        "line": "taxes:"
    },
    {
        "type": "line",
        "index": 6,
        "line": "  IVA: .16"
    },
    {
        "type": "line",
        "index": 7,
        "line": "  ISR: .3"
    },
    {
        "type": "line",
        "index": 8,
        "line": ""
    },
    {
        "type": "line",
        "index": 9,
        "line": "snippets:"
    },
    {
        "type": "line",
        "index": 10,
        "line": "  gasolina: |"
    },
    {
        "type": "line",
        "index": 11,
        "line": "    $DATE * Gasolina"
    },
    {
        "type": "line",
        "index": 12,
        "line": "        Expenses:Transport  $monto"
    },
    {
        "type": "line",
        "index": 13,
        "line": "        Assets:Cash"
    },
    {
        "type": "line",
        "index": 14,
        "line": ""
    },
    {
        "type": "line",
        "index": 15,
        "line": "  sueldo: |"
    },
    {
        "type": "line",
        "index": 16,
        "line": "    $DATE * Sueldo"
    },
    {
        "type": "line",
        "index": 17,
        "line": "        Assets:Bank:Checking  $monto"
    },
    {
        "type": "line",
        "index": 18,
        "line": "        Income:Salary"
    },
    {
        "type": "line",
        "index": 19,
        "line": "---"
    },
    {
        "type": "line",
        "index": 20,
        "line": ""
    },
    {
        "type": "line",
        "index": 21,
        "line": ""
    },
    {
        "type": "line",
        "index": 22,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 23,
        "line": ";         Plan de cuentas"
    },
    {
        "type": "line",
        "index": 24,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 25,
        "line": ""
    },
    {
        "type": "line",
        "index": 26,
        "line": "; Activos"
    },
    {
        "type": "line",
        "index": 27,
        "line": "account Assets:Bank:Checking"
    },
    {
        "type": "line",
        "index": 28,
        "line": "account Assets:Bank:Savings"
    },
    {
        "type": "line",
        "index": 29,
        "line": "account Assets:Cash"
    },
    {
        "type": "line",
        "index": 30,
        "line": "account Assets:Investments:Stocks"
    },
    {
        "type": "line",
        "index": 31,
        "line": "account Assets:AccountsReceivable"
    },
    {
        "type": "line",
        "index": 32,
        "line": ""
    },
    {
        "type": "line",
        "index": 33,
        "line": "; Pasivos"
    },
    {
        "type": "line",
        "index": 34,
        "line": "account Liabilities:CreditCard:Visa"
    },
    {
        "type": "line",
        "index": 35,
        "line": "account Liabilities:Loan:CarLoan"
    },
    {
        "type": "line",
        "index": 36,
        "line": ""
    },
    {
        "type": "line",
        "index": 37,
        "line": "; Capital"
    },
    {
        "type": "line",
        "index": 38,
        "line": "account Equity:OpeningBalances"
    },
    {
        "type": "line",
        "index": 39,
        "line": "account Equity:Owner"
    },
    {
        "type": "line",
        "index": 40,
        "line": ""
    },
    {
        "type": "line",
        "index": 41,
        "line": "; Ingresos"
    },
    {
        "type": "line",
        "index": 42,
        "line": "account Income:Salary"
    },
    {
        "type": "line",
        "index": 43,
        "line": "account Income:Investments:Dividends"
    },
    {
        "type": "line",
        "index": 44,
        "line": "account Income:Freelance"
    },
    {
        "type": "line",
        "index": 45,
        "line": ""
    },
    {
        "type": "line",
        "index": 46,
        "line": "; Egresos"
    },
    {
        "type": "line",
        "index": 47,
        "line": "account Expenses:Rent"
    },
    {
        "type": "line",
        "index": 48,
        "line": "account Expenses:Utilities"
    },
    {
        "type": "line",
        "index": 49,
        "line": "account Expenses:Food:Groceries"
    },
    {
        "type": "line",
        "index": 50,
        "line": "account Expenses:Food:DiningOut"
    },
    {
        "type": "line",
        "index": 51,
        "line": "account Expenses:Transportation:Gas"
    },
    {
        "type": "line",
        "index": 52,
        "line": "account Expenses:Transportation:Maintenance"
    },
    {
        "type": "line",
        "index": 53,
        "line": "account Expenses:Entertainment"
    },
    {
        "type": "line",
        "index": 54,
        "line": "account Expenses:Travel"
    },
    {
        "type": "line",
        "index": 55,
        "line": "account Expenses:Insurance:Car"
    },
    {
        "type": "line",
        "index": 56,
        "line": "account Expenses:Insurance:Health"
    },
    {
        "type": "line",
        "index": 57,
        "line": "account Expenses:Education"
    },
    {
        "type": "line",
        "index": 58,
        "line": "account Expenses:Medical"
    },
    {
        "type": "line",
        "index": 59,
        "line": "account Expenses:Shopping"
    },
    {
        "type": "line",
        "index": 60,
        "line": ""
    },
    {
        "type": "line",
        "index": 61,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 62,
        "line": ";         Transacciones"
    },
    {
        "type": "line",
        "index": 63,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 64,
        "line": ""
    },
    {
        "type": "transaction",
        "index": [
            65,
            66,
            67,
            68,
            69,
            70,
            71,
            72
        ],
        "lines": [
            "2025-01-01 * Opening Balances",
            "  Assets:Bank:Checking              $10,000.00",
            "  Assets:Bank:Savings               $25,000.00",
            "  Assets:Cash                        $1,000.00",
            "  Assets:Investments:Stocks         $15,000.00",
            "  Liabilities:CreditCard:Visa       $-2,500.00",
            "  Liabilities:Loan:CarLoan         $-10,000.00",
            "  Equity:OpeningBalances           $-38,500.00"
        ]
    },
    {
        "type": "transaction",
        "index": [
            74,
            75,
            76,
            77
        ],
        "lines": [
            "2025-01-15 * Paycheck",
            "  Assets:Bank:Checking              $7,500.00",
            "  Income:Salary",
            "  -tags: salary "
        ]
    },
    {
        "type": "transaction",
        "index": [
            79,
            80,
            81
        ],
        "lines": [
            "2025-01-20 * Grocery Shopping",
            "  Expenses:Food:Groceries           $100.00 +{IVA} ",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            83,
            84,
            85
        ],
        "lines": [
            "2025-01-22 * Rent Payment",
            "  Expenses:Rent                   $1,500.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            87,
            88,
            89
        ],
        "lines": [
            "2025-01-23 * Dinner Out",
            "  Expenses:Food:DiningOut            $75.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            91,
            92,
            93
        ],
        "lines": [
            "2025-01-25 * Credit Card Payment",
            "  Liabilities:CreditCard:Visa     $1,200.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            95,
            96,
            97
        ],
        "lines": [
            "2025-02-01 * Paycheck",
            "  Assets:Bank:Checking              $7,500.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            99,
            100,
            101
        ],
        "lines": [
            "2025-02-03 * Utilities Bill",
            "  Expenses:Utilities                $300.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            103,
            104,
            105
        ],
        "lines": [
            "2025-02-10 * Gasoline",
            "  Expenses:Transportation:Gas       $120.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            107,
            108,
            109
        ],
        "lines": [
            "2025-02-15 * Freelance Project",
            "  Assets:Bank:Checking              $3,200.00",
            "  Income:Freelance"
        ]
    },
    {
        "type": "transaction",
        "index": [
            111,
            112,
            113
        ],
        "lines": [
            "2025-02-20 * Car Loan Payment",
            "  Liabilities:Loan:CarLoan         $500.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            115,
            116,
            117
        ],
        "lines": [
            "2025-02-22 * Stock Dividend",
            "  Assets:Bank:Savings               $1,000.00",
            "  Income:Investments:Dividends"
        ]
    },
    {
        "type": "transaction",
        "index": [
            119,
            120,
            121
        ],
        "lines": [
            "2025-02-28 * Vacation Trip",
            "  Expenses:Travel                 $2,800.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            123,
            124,
            125
        ],
        "lines": [
            "2025-03-01 * Paycheck",
            "  Assets:Bank:Checking              $7,500.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            127,
            128,
            129
        ],
        "lines": [
            "2025-03-02 * Health Insurance",
            "  Expenses:Insurance:Health         $450.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            131,
            132,
            133
        ],
        "lines": [
            "2025-03-10 * Maintenance: Oil Change",
            "  Expenses:Transportation:Maintenance $90.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            135,
            136,
            137
        ],
        "lines": [
            "2025-03-15 * Monthly Rent",
            "  Expenses:Rent                   $1,500.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            139,
            140,
            141
        ],
        "lines": [
            "2025-03-18 * Course Subscription",
            "  Expenses:Education                $300.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            143,
            144,
            145
        ],
        "lines": [
            "2025-03-25 * Entertainment - Concert",
            "  Expenses:Entertainment            $200.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "line",
        "index": 147,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 148,
        "line": "; Abril 2025"
    },
    {
        "type": "line",
        "index": 149,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 150,
        "line": ""
    },
    {
        "type": "transaction",
        "index": [
            151,
            152,
            153
        ],
        "lines": [
            "2025-04-01 * Paycheck",
            "  Assets:Bank:Checking              $7,500.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            155,
            156,
            157
        ],
        "lines": [
            "2025-04-02 * Dentist Appointment",
            "  Expenses:Medical                  $1,200.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            159,
            160,
            161
        ],
        "lines": [
            "2025-04-10 * Gasoline",
            "  Expenses:Transportation:Gas       $130.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            163,
            164,
            165
        ],
        "lines": [
            "2025-04-15 * Monthly Rent",
            "  Expenses:Rent                   $1,500.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            167,
            168,
            169
        ],
        "lines": [
            "2025-04-20 * Shopping - Electronics",
            "  Expenses:Shopping                 $3,000.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            171,
            172,
            173
        ],
        "lines": [
            "2025-04-25 * Dinner Out",
            "  Expenses:Food:DiningOut           $100.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "line",
        "index": 175,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 176,
        "line": "; Mayo 2025"
    },
    {
        "type": "line",
        "index": 177,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 178,
        "line": ""
    },
    {
        "type": "transaction",
        "index": [
            179,
            180,
            181
        ],
        "lines": [
            "2025-05-01 * Paycheck",
            "  Assets:Bank:Checking              $7,500.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            183,
            184,
            185
        ],
        "lines": [
            "2025-05-03 * Utilities",
            "  Expenses:Utilities                $310.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            187,
            188,
            189
        ],
        "lines": [
            "2025-05-06 * Travel - Family Emergency",
            "  Expenses:Travel                 $5,800.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            191,
            192,
            193
        ],
        "lines": [
            "2025-05-10 * Grocery Shopping",
            "  Expenses:Food:Groceries           $270.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            195,
            196,
            197
        ],
        "lines": [
            "2025-05-15 * Monthly Rent",
            "  Expenses:Rent                   $1,500.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            199,
            200,
            201
        ],
        "lines": [
            "2025-05-25 * Car Repair (transmission)",
            "  Expenses:Transportation:Maintenance $2,200.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "line",
        "index": 203,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 204,
        "line": "; Junio 2025"
    },
    {
        "type": "line",
        "index": 205,
        "line": "; =============================="
    },
    {
        "type": "line",
        "index": 206,
        "line": ""
    },
    {
        "type": "transaction",
        "index": [
            207,
            208,
            209
        ],
        "lines": [
            "2025-06-01 * Paycheck",
            "  Assets:Bank:Checking              $7,500.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            211,
            212,
            213
        ],
        "lines": [
            "2025-06-03 * Health Insurance",
            "  Expenses:Insurance:Health         $450.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            215,
            216,
            217
        ],
        "lines": [
            "2025-06-10 * Freelance Payment",
            "  Assets:Bank:Checking              $4,500.00",
            "  Income:Freelance"
        ]
    },
    {
        "type": "transaction",
        "index": [
            219,
            220,
            221
        ],
        "lines": [
            "2025-06-15 * Monthly Rent",
            "  Expenses:Rent                   $1,500.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            223,
            224,
            225
        ],
        "lines": [
            "2025-06-20 * Luxury Watch Purchase",
            "  Expenses:Shopping                 $6,500.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            227,
            228,
            229
        ],
        "lines": [
            "2025-06-30 * Entertainment - Festival",
            "  Expenses:Entertainment            $350.00",
            "  Assets:Bank:Checking"
        ]
    },
    {
        "type": "transaction",
        "index": [
            231,
            232,
            233
        ],
        "lines": [
            "2025-07-29 * Sueldo",
            "  Assets:Bank:Checking  $200",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            235,
            236,
            237
        ],
        "lines": [
            "2025-07-29 * Sueldo",
            "  Assets:Bank:Checking  $100",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            239,
            240,
            241
        ],
        "lines": [
            "2025-07-29 * Gasolina",
            "  Expenses:Transport  100.00",
            "  Assets:Bank:Checking "
        ]
    },
    {
        "type": "transaction",
        "index": [
            243,
            244,
            245
        ],
        "lines": [
            "2025-07-30 * Gasolina",
            "  Expenses:Transport  100.00",
            "  Assets:Cash"
        ]
    },
    {
        "type": "transaction",
        "index": [
            247,
            248,
            249
        ],
        "lines": [
            "2025-07-31 * Sueldo",
            "  Assets:Bank:Checking  100.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            251,
            252,
            253
        ],
        "lines": [
            "2025-07-31 * Sueldo",
            "  Assets:Bank:Checking  100.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            255,
            256,
            257
        ],
        "lines": [
            "2025-07-29 * Sueldo",
            "  Assets:Bank:Checking  100.00",
            "  Expenses:Education"
        ]
    },
    {
        "type": "transaction",
        "index": [
            259,
            260,
            261
        ],
        "lines": [
            "2025-07-29 * Sueldo",
            "  Assets:Bank:Checking  100.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            263,
            264,
            265
        ],
        "lines": [
            "2025-07-29 * Sueldo",
            "  Assets:Bank:Checking  100.00",
            "  Income:Salary"
        ]
    },
    {
        "type": "line",
        "index": 267,
        "line": ""
    },
    {
        "type": "transaction",
        "index": [
            268,
            269,
            270
        ],
        "lines": [
            "2025-07-29 * Sueldo",
            "    Assets:Bank:Checking  100.00",
            "    Income:Salary"
        ]
    },
    {
        "type": "transaction",
        "index": [
            272,
            273,
            274
        ],
        "lines": [
            "2025-07-29 * Gasolina",
            "    Expenses:Transport  100.00",
            "    Assets:Cash"
        ]
    }
]
```

# Clase: `LedgerAnalyst`


## detect_unusual_expenses()

Detecta gastos que exceden significativamente su promedio histórico.

```json
[
    {
        "account": "Expenses:Transportation:Maintenance",
        "month": "2025-05",
        "amount": 2200.0,
        "average": 1145.0,
        "alert": "Gasto inusualmente alto"
    }
]
```

## get_daily_incomes_expenses()

Muestra ingresos y gastos diarios.

```json
[
    {
        "date": "2025-01-15",
        "incoming": 7500.0,
        "expenses": 0.0
    },
    {
        "date": "2025-01-20",
        "incoming": 0.0,
        "expenses": 100.0
    },
    {
        "date": "2025-01-22",
        "incoming": 0.0,
        "expenses": 1500.0
    },
    {
        "date": "2025-01-23",
        "incoming": 0.0,
        "expenses": 75.0
    },
    {
        "date": "2025-02-01",
        "incoming": 7500.0,
        "expenses": 0.0
    },
    {
        "date": "2025-02-03",
        "incoming": 0.0,
        "expenses": 300.0
    },
    {
        "date": "2025-02-10",
        "incoming": 0.0,
        "expenses": 120.0
    },
    {
        "date": "2025-02-15",
        "incoming": 3200.0,
        "expenses": 0.0
    },
    {
        "date": "2025-02-22",
        "incoming": 1000.0,
        "expenses": 0.0
    },
    {
        "date": "2025-02-28",
        "incoming": 0.0,
        "expenses": 2800.0
    },
    {
        "date": "2025-03-01",
        "incoming": 7500.0,
        "expenses": 0.0
    },
    {
        "date": "2025-03-02",
        "incoming": 0.0,
        "expenses": 450.0
    },
    {
        "date": "2025-03-10",
        "incoming": 0.0,
        "expenses": 90.0
    },
    {
        "date": "2025-03-15",
        "incoming": 0.0,
        "expenses": 1500.0
    },
    {
        "date": "2025-03-18",
        "incoming": 0.0,
        "expenses": 300.0
    },
    {
        "date": "2025-03-25",
        "incoming": 0.0,
        "expenses": 200.0
    },
    {
        "date": "2025-04-01",
        "incoming": 7500.0,
        "expenses": 0.0
    },
    {
        "date": "2025-04-02",
        "incoming": 0.0,
        "expenses": 1200.0
    },
    {
        "date": "2025-04-10",
        "incoming": 0.0,
        "expenses": 130.0
    },
    {
        "date": "2025-04-15",
        "incoming": 0.0,
        "expenses": 1500.0
    },
    {
        "date": "2025-04-20",
        "incoming": 0.0,
        "expenses": 3000.0
    },
    {
        "date": "2025-04-25",
        "incoming": 0.0,
        "expenses": 100.0
    },
    {
        "date": "2025-05-01",
        "incoming": 7500.0,
        "expenses": 0.0
    },
    {
        "date": "2025-05-03",
        "incoming": 0.0,
        "expenses": 310.0
    },
    {
        "date": "2025-05-06",
        "incoming": 0.0,
        "expenses": 5800.0
    },
    {
        "date": "2025-05-10",
        "incoming": 0.0,
        "expenses": 270.0
    },
    {
        "date": "2025-05-15",
        "incoming": 0.0,
        "expenses": 1500.0
    },
    {
        "date": "2025-05-25",
        "incoming": 0.0,
        "expenses": 2200.0
    },
    {
        "date": "2025-06-01",
        "incoming": 7500.0,
        "expenses": 0.0
    },
    {
        "date": "2025-06-03",
        "incoming": 0.0,
        "expenses": 450.0
    },
    {
        "date": "2025-06-10",
        "incoming": 4500.0,
        "expenses": 0.0
    },
    {
        "date": "2025-06-15",
        "incoming": 0.0,
        "expenses": 1500.0
    },
    {
        "date": "2025-06-20",
        "incoming": 0.0,
        "expenses": 6500.0
    },
    {
        "date": "2025-06-30",
        "incoming": 0.0,
        "expenses": 350.0
    },
    {
        "date": "2025-07-29",
        "incoming": 600.0,
        "expenses": 300.0
    },
    {
        "date": "2025-07-30",
        "incoming": 0.0,
        "expenses": 100.0
    },
    {
        "date": "2025-07-31",
        "incoming": 200.0,
        "expenses": 0.0
    }
]
```

## get_expenses_pie()

Distribución de gastos por cuenta.

```json
[
    {
        "account": "Expenses:Food:Groceries",
        "amount": 370.0
    },
    {
        "account": "Expenses:Rent",
        "amount": 7500.0
    },
    {
        "account": "Expenses:Food:DiningOut",
        "amount": 175.0
    },
    {
        "account": "Expenses:Utilities",
        "amount": 610.0
    },
    {
        "account": "Expenses:Transportation:Gas",
        "amount": 250.0
    },
    {
        "account": "Expenses:Travel",
        "amount": 8600.0
    },
    {
        "account": "Expenses:Insurance:Health",
        "amount": 900.0
    },
    {
        "account": "Expenses:Transportation:Maintenance",
        "amount": 2290.0
    },
    {
        "account": "Expenses:Education",
        "amount": 400.0
    },
    {
        "account": "Expenses:Entertainment",
        "amount": 550.0
    },
    {
        "account": "Expenses:Medical",
        "amount": 1200.0
    },
    {
        "account": "Expenses:Shopping",
        "amount": 9500.0
    },
    {
        "account": "Expenses:Transport",
        "amount": 300.0
    }
]
```

## get_incomes_pie()

Distribución de ingresos por cuenta.

```json
[
    {
        "account": "Income:Salary",
        "amount": 45800.0
    },
    {
        "account": "Income:Freelance",
        "amount": 7700.0
    },
    {
        "account": "Income:Investments:Dividends",
        "amount": 1000.0
    }
]
```

## get_assets_summary()

Resumen del total de activos.

```json
[
    {
        "account": "Assets:Bank:Checking",
        "amount": 97645.0
    },
    {
        "account": "Assets:Bank:Savings",
        "amount": 26000.0
    },
    {
        "account": "Assets:Cash",
        "amount": 1200.0
    },
    {
        "account": "Assets:Investments:Stocks",
        "amount": 15000.0
    }
]
```

## get_liabilities_summary()

Resumen del total de pasivos.

```json
[
    {
        "account": "Liabilities:CreditCard:Visa",
        "amount": 3700.0
    },
    {
        "account": "Liabilities:Loan:CarLoan",
        "amount": 10500.0
    }
]
```

## get_balance_by_day()

Evolución del balance diario (ingresos - gastos).

```json
[
    {
        "date": "2025-01-15",
        "incoming": 7500.0,
        "expenses": 0.0,
        "balance": 7500.0
    },
    {
        "date": "2025-01-20",
        "incoming": 0.0,
        "expenses": 100.0,
        "balance": 7400.0
    },
    {
        "date": "2025-01-22",
        "incoming": 0.0,
        "expenses": 1500.0,
        "balance": 5900.0
    },
    {
        "date": "2025-01-23",
        "incoming": 0.0,
        "expenses": 75.0,
        "balance": 5825.0
    },
    {
        "date": "2025-02-01",
        "incoming": 7500.0,
        "expenses": 0.0,
        "balance": 13325.0
    },
    {
        "date": "2025-02-03",
        "incoming": 0.0,
        "expenses": 300.0,
        "balance": 13025.0
    },
    {
        "date": "2025-02-10",
        "incoming": 0.0,
        "expenses": 120.0,
        "balance": 12905.0
    },
    {
        "date": "2025-02-15",
        "incoming": 3200.0,
        "expenses": 0.0,
        "balance": 16105.0
    },
    {
        "date": "2025-02-22",
        "incoming": 1000.0,
        "expenses": 0.0,
        "balance": 17105.0
    },
    {
        "date": "2025-02-28",
        "incoming": 0.0,
        "expenses": 2800.0,
        "balance": 14305.0
    },
    {
        "date": "2025-03-01",
        "incoming": 7500.0,
        "expenses": 0.0,
        "balance": 21805.0
    },
    {
        "date": "2025-03-02",
        "incoming": 0.0,
        "expenses": 450.0,
        "balance": 21355.0
    },
    {
        "date": "2025-03-10",
        "incoming": 0.0,
        "expenses": 90.0,
        "balance": 21265.0
    },
    {
        "date": "2025-03-15",
        "incoming": 0.0,
        "expenses": 1500.0,
        "balance": 19765.0
    },
    {
        "date": "2025-03-18",
        "incoming": 0.0,
        "expenses": 300.0,
        "balance": 19465.0
    },
    {
        "date": "2025-03-25",
        "incoming": 0.0,
        "expenses": 200.0,
        "balance": 19265.0
    },
    {
        "date": "2025-04-01",
        "incoming": 7500.0,
        "expenses": 0.0,
        "balance": 26765.0
    },
    {
        "date": "2025-04-02",
        "incoming": 0.0,
        "expenses": 1200.0,
        "balance": 25565.0
    },
    {
        "date": "2025-04-10",
        "incoming": 0.0,
        "expenses": 130.0,
        "balance": 25435.0
    },
    {
        "date": "2025-04-15",
        "incoming": 0.0,
        "expenses": 1500.0,
        "balance": 23935.0
    },
    {
        "date": "2025-04-20",
        "incoming": 0.0,
        "expenses": 3000.0,
        "balance": 20935.0
    },
    {
        "date": "2025-04-25",
        "incoming": 0.0,
        "expenses": 100.0,
        "balance": 20835.0
    },
    {
        "date": "2025-05-01",
        "incoming": 7500.0,
        "expenses": 0.0,
        "balance": 28335.0
    },
    {
        "date": "2025-05-03",
        "incoming": 0.0,
        "expenses": 310.0,
        "balance": 28025.0
    },
    {
        "date": "2025-05-06",
        "incoming": 0.0,
        "expenses": 5800.0,
        "balance": 22225.0
    },
    {
        "date": "2025-05-10",
        "incoming": 0.0,
        "expenses": 270.0,
        "balance": 21955.0
    },
    {
        "date": "2025-05-15",
        "incoming": 0.0,
        "expenses": 1500.0,
        "balance": 20455.0
    },
    {
        "date": "2025-05-25",
        "incoming": 0.0,
        "expenses": 2200.0,
        "balance": 18255.0
    },
    {
        "date": "2025-06-01",
        "incoming": 7500.0,
        "expenses": 0.0,
        "balance": 25755.0
    },
    {
        "date": "2025-06-03",
        "incoming": 0.0,
        "expenses": 450.0,
        "balance": 25305.0
    },
    {
        "date": "2025-06-10",
        "incoming": 4500.0,
        "expenses": 0.0,
        "balance": 29805.0
    },
    {
        "date": "2025-06-15",
        "incoming": 0.0,
        "expenses": 1500.0,
        "balance": 28305.0
    },
    {
        "date": "2025-06-20",
        "incoming": 0.0,
        "expenses": 6500.0,
        "balance": 21805.0
    },
    {
        "date": "2025-06-30",
        "incoming": 0.0,
        "expenses": 350.0,
        "balance": 21455.0
    },
    {
        "date": "2025-07-29",
        "incoming": 600.0,
        "expenses": 300.0,
        "balance": 21755.0
    },
    {
        "date": "2025-07-30",
        "incoming": 0.0,
        "expenses": 100.0,
        "balance": 21655.0
    },
    {
        "date": "2025-07-31",
        "incoming": 200.0,
        "expenses": 0.0,
        "balance": 21855.0
    }
]
```

## get_cashflow_by_month()

Flujo de caja mensual (ingresos - gastos).

```json
[
    {
        "month": "2025-01",
        "in": 7500.0,
        "out": 1675.0,
        "net": 5825.0
    },
    {
        "month": "2025-02",
        "in": 11700.0,
        "out": 3220.0,
        "net": 8480.0
    },
    {
        "month": "2025-03",
        "in": 7500.0,
        "out": 2540.0,
        "net": 4960.0
    },
    {
        "month": "2025-04",
        "in": 7500.0,
        "out": 5930.0,
        "net": 1570.0
    },
    {
        "month": "2025-05",
        "in": 7500.0,
        "out": 10080.0,
        "net": -2580.0
    },
    {
        "month": "2025-06",
        "in": 12000.0,
        "out": 8800.0,
        "net": 3200.0
    },
    {
        "month": "2025-07",
        "in": 800.0,
        "out": 400.0,
        "net": 400.0
    }
]
```

## get_expense_trends_by_category()

Tendencias de gastos por categoría mensual.

```json
{
    "Expenses:Food:Groceries": {
        "2025-01": 100.0,
        "2025-05": 270.0
    },
    "Expenses:Rent": {
        "2025-01": 1500.0,
        "2025-03": 1500.0,
        "2025-04": 1500.0,
        "2025-05": 1500.0,
        "2025-06": 1500.0
    },
    "Expenses:Food:DiningOut": {
        "2025-01": 75.0,
        "2025-04": 100.0
    },
    "Expenses:Utilities": {
        "2025-02": 300.0,
        "2025-05": 310.0
    },
    "Expenses:Transportation:Gas": {
        "2025-02": 120.0,
        "2025-04": 130.0
    },
    "Expenses:Travel": {
        "2025-02": 2800.0,
        "2025-05": 5800.0
    },
    "Expenses:Insurance:Health": {
        "2025-03": 450.0,
        "2025-06": 450.0
    },
    "Expenses:Transportation:Maintenance": {
        "2025-03": 90.0,
        "2025-05": 2200.0
    },
    "Expenses:Education": {
        "2025-03": 300.0,
        "2025-07": 100.0
    },
    "Expenses:Entertainment": {
        "2025-03": 200.0,
        "2025-06": 350.0
    },
    "Expenses:Medical": {
        "2025-04": 1200.0
    },
    "Expenses:Shopping": {
        "2025-04": 3000.0,
        "2025-06": 6500.0
    },
    "Expenses:Transport": {
        "2025-07": 300.0
    }
}
```

## get_monthly_incomes_expenses()

Resumen mensual de ingresos y gastos.

```json
[
    {
        "month": "2025-01",
        "incoming": 7500.0,
        "expenses": 1675.0
    },
    {
        "month": "2025-02",
        "incoming": 11700.0,
        "expenses": 3220.0
    },
    {
        "month": "2025-03",
        "incoming": 7500.0,
        "expenses": 2540.0
    },
    {
        "month": "2025-04",
        "incoming": 7500.0,
        "expenses": 5930.0
    },
    {
        "month": "2025-05",
        "incoming": 7500.0,
        "expenses": 10080.0
    },
    {
        "month": "2025-06",
        "incoming": 12000.0,
        "expenses": 8800.0
    },
    {
        "month": "2025-07",
        "incoming": 800.0,
        "expenses": 400.0
    }
]
```

## get_monthly_growth_rates()

Tasa de crecimiento mensual.

```json
[
    {
        "month": "2025-01",
        "in_growth": 0.0,
        "out_growth": 0.0,
        "net_growth": 0.0
    },
    {
        "month": "2025-02",
        "in_growth": 56.0,
        "out_growth": 92.24,
        "net_growth": 45.58
    },
    {
        "month": "2025-03",
        "in_growth": -35.9,
        "out_growth": -21.12,
        "net_growth": -41.51
    },
    {
        "month": "2025-04",
        "in_growth": 0.0,
        "out_growth": 133.46,
        "net_growth": -68.35
    },
    {
        "month": "2025-05",
        "in_growth": 0.0,
        "out_growth": 69.98,
        "net_growth": -264.33
    },
    {
        "month": "2025-06",
        "in_growth": 60.0,
        "out_growth": -12.7,
        "net_growth": -224.03
    },
    {
        "month": "2025-07",
        "in_growth": -93.33,
        "out_growth": -95.45,
        "net_growth": -87.5
    }
]
```

## get_monthly_expense_ratio()

Tasa de gastos mensual.

```json
[
    {
        "month": "2025-01",
        "expense_ratio": 22.33
    },
    {
        "month": "2025-02",
        "expense_ratio": 27.52
    },
    {
        "month": "2025-03",
        "expense_ratio": 33.87
    },
    {
        "month": "2025-04",
        "expense_ratio": 79.07
    },
    {
        "month": "2025-05",
        "expense_ratio": 134.4
    },
    {
        "month": "2025-06",
        "expense_ratio": 73.33
    },
    {
        "month": "2025-07",
        "expense_ratio": 50.0
    }
]
```

## get_moving_average()

Promedio móvil.

```json
[
    {
        "month": "2025-01",
        "in_moving_avg": 0.0
    },
    {
        "month": "2025-02",
        "in_moving_avg": 0.0
    },
    {
        "month": "2025-03",
        "in_moving_avg": 8900.0
    },
    {
        "month": "2025-04",
        "in_moving_avg": 8900.0
    },
    {
        "month": "2025-05",
        "in_moving_avg": 7500.0
    },
    {
        "month": "2025-06",
        "in_moving_avg": 9000.0
    },
    {
        "month": "2025-07",
        "in_moving_avg": 6766.67
    }
]
```

## get_trend_slope()

Pendiente de la tendencia.

```json
-696.43
```

## predict_future_months()

Predicción de meses futuros.

```json
[
    {
        "month": "2025-08",
        "predicted_in": 4999.99
    },
    {
        "month": "2025-09",
        "predicted_in": 4303.56
    },
    {
        "month": "2025-10",
        "predicted_in": 3607.13
    }
]
```

## get_extreme_months()

Meses extremos.

```json
{
    "highest_income": {
        "month": "2025-06",
        "in": 12000.0,
        "out": 8800.0,
        "net": 3200.0
    },
    "highest_expense": {
        "month": "2025-05",
        "in": 7500.0,
        "out": 10080.0,
        "net": -2580.0
    },
    "best_balance": {
        "month": "2025-02",
        "in": 11700.0,
        "out": 3220.0,
        "net": 8480.0
    }
}
```

## classify_months_by_balance()

Clasificación de meses según balance.

```json
{
    "positive": [
        "2025-01",
        "2025-02",
        "2025-03",
        "2025-04",
        "2025-06",
        "2025-07"
    ],
    "negative": [
        "2025-05"
    ],
    "neutral": []
}
```

## compare_months()

Comparación de meses.

```json
{
    "in_diff": 4200.0,
    "out_diff": 1545.0,
    "net_diff": 2655.0
}
```

## get_income_dependency_ratio()

Ratio de dependencia de ingresos.

```json
[
    {
        "month": "2025-01",
        "dependency_ratio": 22.33
    },
    {
        "month": "2025-02",
        "dependency_ratio": 27.52
    },
    {
        "month": "2025-03",
        "dependency_ratio": 33.87
    },
    {
        "month": "2025-04",
        "dependency_ratio": 79.07
    },
    {
        "month": "2025-05",
        "dependency_ratio": 134.4
    },
    {
        "month": "2025-06",
        "dependency_ratio": 73.33
    },
    {
        "month": "2025-07",
        "dependency_ratio": 50.0
    }
]
```

## get_cumulative_net_income()

Acumulación de ingresos netos.

```json
[
    {
        "month": "2025-01",
        "cumulative_net": 5825.0
    },
    {
        "month": "2025-02",
        "cumulative_net": 14305.0
    },
    {
        "month": "2025-03",
        "cumulative_net": 19265.0
    },
    {
        "month": "2025-04",
        "cumulative_net": 20835.0
    },
    {
        "month": "2025-05",
        "cumulative_net": 18255.0
    },
    {
        "month": "2025-06",
        "cumulative_net": 21455.0
    },
    {
        "month": "2025-07",
        "cumulative_net": 21855.0
    }
]
```

## get_accounts_used()

Listado de todas las cuentas utilizadas.

- Assets:Bank:Checking
- Assets:Bank:Savings
- Assets:Cash
- Assets:Investments:Stocks
- Equity:OpeningBalances
- Expenses:Education
- Expenses:Entertainment
- Expenses:Food:DiningOut
- Expenses:Food:Groceries
- Expenses:Insurance:Health
- Expenses:Medical
- Expenses:Rent
- Expenses:Shopping
- Expenses:Transport
- Expenses:Transportation:Gas
- Expenses:Transportation:Maintenance
- Expenses:Travel
- Expenses:Utilities
- Income:Freelance
- Income:Investments:Dividends
- Income:Salary
- Liabilities:CreditCard:Visa
- Liabilities:Loan:CarLoan
