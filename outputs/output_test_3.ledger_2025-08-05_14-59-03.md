---
# Reporte de prueba - 2025-08-05 14:59:03
Generado por: `test_doc.py`
Ruta del archivo: `/home/eddybel/Documentos/dev/personales/LedgerApp/ledger-cli-toolkit/test/ledgers/test_3.ledger`

Archivo fuente: `test/ledgers/test_3.ledger`

---

# Reporte generado el 2025-08-05 14:59:03

# Clase: `LedgerParser`


## parse()

Convierte las transacciones del archivo ledger a estructura JSON.

```json
[
    {
        "date": "2025/01/01",
        "time": null,
        "verified": false,
        "description": "Salario Mensual",
        "accounts": [
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": 25000.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "+"
                    },
                    {
                        "name": "RET_ISR",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Ingresos:Salarios",
                "subAccounts": [
                    "Ingresos",
                    "Salarios"
                ],
                "unit": "MXN",
                "amount": -25000.0,
                "taxes": []
            }
        ],
        "properties": [
            {
                "key": "tags",
                "value": "salary, income"
            },
            {
                "key": "uuid",
                "value": "f2c2a-3bd1"
            },
            {
                "key": "responsible",
                "value": "Eduardo"
            }
        ]
    },
    {
        "date": "2025-01-02",
        "time": null,
        "verified": false,
        "description": "Compra de alimentos",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 1200.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "-"
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -1200.0,
                "taxes": []
            }
        ],
        "properties": [
            {
                "key": "tags",
                "value": "shopping, groceries, food"
            },
            {
                "key": "uuid",
                "value": "f2c2a-3bd1"
            },
            {
                "key": "ticket",
                "value": "[ticket](./tickets/compu-2025.jpg)"
            },
            {
                "key": "responsible",
                "value": "Eduardo"
            }
        ]
    },
    {
        "date": "2025-01-03",
        "time": null,
        "verified": false,
        "description": "Transporte público",
        "accounts": [
            {
                "account": "Gastos:Transporte",
                "subAccounts": [
                    "Gastos",
                    "Transporte"
                ],
                "unit": "MXN",
                "amount": 500.0,
                "taxes": [
                    {
                        "name": "RET_ISR",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-05",
        "time": null,
        "verified": false,
        "description": "Cena en restaurante",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 750.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -750.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-07",
        "time": null,
        "verified": false,
        "description": "Pago de tarjeta de crédito",
        "accounts": [
            {
                "account": "Pasivos:Tarjeta",
                "subAccounts": [
                    "Pasivos",
                    "Tarjeta"
                ],
                "unit": "MXN",
                "amount": 5000.0,
                "taxes": [
                    {
                        "name": "RET_ISR",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -5000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-08",
        "time": null,
        "verified": false,
        "description": "Suscripción de streaming",
        "accounts": [
            {
                "account": "Gastos:Entretenimiento",
                "subAccounts": [
                    "Gastos",
                    "Entretenimiento"
                ],
                "unit": "MXN",
                "amount": 250.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "="
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -250.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-10",
        "time": null,
        "verified": false,
        "description": "Transporte (taxi)",
        "accounts": [
            {
                "account": "Gastos:Transporte",
                "subAccounts": [
                    "Gastos",
                    "Transporte"
                ],
                "unit": "MXN",
                "amount": 300.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -300.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-12",
        "time": null,
        "verified": false,
        "description": "Supermercado",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 2100.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -2100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-15",
        "time": null,
        "verified": false,
        "description": "Salario extra",
        "accounts": [
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": 10000.0,
                "taxes": []
            },
            {
                "account": "Ingresos:Salarios",
                "subAccounts": [
                    "Ingresos",
                    "Salarios"
                ],
                "unit": "MXN",
                "amount": -10000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-16",
        "time": null,
        "verified": false,
        "description": "Pago parcial tarjeta de crédito",
        "accounts": [
            {
                "account": "Pasivos:Tarjeta",
                "subAccounts": [
                    "Pasivos",
                    "Tarjeta"
                ],
                "unit": "MXN",
                "amount": 3000.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -3000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-17",
        "time": null,
        "verified": false,
        "description": "Cine",
        "accounts": [
            {
                "account": "Gastos:Entretenimiento",
                "subAccounts": [
                    "Gastos",
                    "Entretenimiento"
                ],
                "unit": "MXN",
                "amount": 400.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -400.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-17",
        "time": null,
        "verified": false,
        "description": "Gasolina",
        "accounts": [
            {
                "account": "Gastos:Transporte",
                "subAccounts": [
                    "Gastos",
                    "Transporte"
                ],
                "unit": "MXN",
                "amount": 1000.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -1000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-18",
        "time": null,
        "verified": false,
        "description": "Pago de luz",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 600.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -600.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-18",
        "time": null,
        "verified": false,
        "description": "Comida rápida",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 800.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -800.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-18",
        "time": null,
        "verified": false,
        "description": "Transporte privado",
        "accounts": [
            {
                "account": "Gastos:Transporte",
                "subAccounts": [
                    "Gastos",
                    "Transporte"
                ],
                "unit": "MXN",
                "amount": 450.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -450.0,
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
        "date": "2025/01/01",
        "time": null,
        "verified": false,
        "description": "Salario Mensual",
        "accounts": [
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": 25000.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "+"
                    },
                    {
                        "name": "RET_ISR",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Ingresos:Salarios",
                "subAccounts": [
                    "Ingresos",
                    "Salarios"
                ],
                "unit": "MXN",
                "amount": -18500.0,
                "taxes": []
            },
            {
                "account": "Taxes:IVA",
                "subAccounts": [
                    "Taxes",
                    "IVA"
                ],
                "unit": "MXN",
                "amount": 4000.0,
                "taxes": []
            },
            {
                "account": "Taxes:RET_ISR",
                "subAccounts": [
                    "Taxes",
                    "RET_ISR"
                ],
                "unit": "MXN",
                "amount": 2500.0,
                "taxes": []
            }
        ],
        "properties": [
            {
                "key": "tags",
                "value": "salary, income"
            },
            {
                "key": "uuid",
                "value": "f2c2a-3bd1"
            },
            {
                "key": "responsible",
                "value": "Eduardo"
            }
        ]
    },
    {
        "date": "2025-01-02",
        "time": null,
        "verified": false,
        "description": "Compra de alimentos",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 1200.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "-"
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -1392.0,
                "taxes": []
            },
            {
                "account": "Taxes:IVA",
                "subAccounts": [
                    "Taxes",
                    "IVA"
                ],
                "unit": "MXN",
                "amount": 192.0,
                "taxes": []
            }
        ],
        "properties": [
            {
                "key": "tags",
                "value": "shopping, groceries, food"
            },
            {
                "key": "uuid",
                "value": "f2c2a-3bd1"
            },
            {
                "key": "ticket",
                "value": "[ticket](./tickets/compu-2025.jpg)"
            },
            {
                "key": "responsible",
                "value": "Eduardo"
            }
        ]
    },
    {
        "date": "2025-01-03",
        "time": null,
        "verified": false,
        "description": "Transporte público",
        "accounts": [
            {
                "account": "Gastos:Transporte",
                "subAccounts": [
                    "Gastos",
                    "Transporte"
                ],
                "unit": "MXN",
                "amount": 500.0,
                "taxes": [
                    {
                        "name": "RET_ISR",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -450.0,
                "taxes": []
            },
            {
                "account": "Taxes:RET_ISR",
                "subAccounts": [
                    "Taxes",
                    "RET_ISR"
                ],
                "unit": "MXN",
                "amount": 50.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-05",
        "time": null,
        "verified": false,
        "description": "Cena en restaurante",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 750.0,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -630.0,
                "taxes": []
            },
            {
                "account": "Taxes:IVA",
                "subAccounts": [
                    "Taxes",
                    "IVA"
                ],
                "unit": "MXN",
                "amount": 120.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-07",
        "time": null,
        "verified": false,
        "description": "Pago de tarjeta de crédito",
        "accounts": [
            {
                "account": "Pasivos:Tarjeta",
                "subAccounts": [
                    "Pasivos",
                    "Tarjeta"
                ],
                "unit": "MXN",
                "amount": 5000.0,
                "taxes": [
                    {
                        "name": "RET_ISR",
                        "mode": "+"
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -4500.0,
                "taxes": []
            },
            {
                "account": "Taxes:RET_ISR",
                "subAccounts": [
                    "Taxes",
                    "RET_ISR"
                ],
                "unit": "MXN",
                "amount": 500.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-08",
        "time": null,
        "verified": false,
        "description": "Suscripción de streaming",
        "accounts": [
            {
                "account": "Gastos:Entretenimiento",
                "subAccounts": [
                    "Gastos",
                    "Entretenimiento"
                ],
                "unit": "MXN",
                "amount": 215.52,
                "taxes": [
                    {
                        "name": "IVA",
                        "mode": "="
                    }
                ]
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -250.0,
                "taxes": []
            },
            {
                "account": "Taxes:IVA",
                "subAccounts": [
                    "Taxes",
                    "IVA"
                ],
                "unit": "MXN",
                "amount": 34.48,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-10",
        "time": null,
        "verified": false,
        "description": "Transporte (taxi)",
        "accounts": [
            {
                "account": "Gastos:Transporte",
                "subAccounts": [
                    "Gastos",
                    "Transporte"
                ],
                "unit": "MXN",
                "amount": 300.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -300.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-12",
        "time": null,
        "verified": false,
        "description": "Supermercado",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 2100.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -2100.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-15",
        "time": null,
        "verified": false,
        "description": "Salario extra",
        "accounts": [
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": 10000.0,
                "taxes": []
            },
            {
                "account": "Ingresos:Salarios",
                "subAccounts": [
                    "Ingresos",
                    "Salarios"
                ],
                "unit": "MXN",
                "amount": -10000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-16",
        "time": null,
        "verified": false,
        "description": "Pago parcial tarjeta de crédito",
        "accounts": [
            {
                "account": "Pasivos:Tarjeta",
                "subAccounts": [
                    "Pasivos",
                    "Tarjeta"
                ],
                "unit": "MXN",
                "amount": 3000.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -3000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-17",
        "time": null,
        "verified": false,
        "description": "Cine",
        "accounts": [
            {
                "account": "Gastos:Entretenimiento",
                "subAccounts": [
                    "Gastos",
                    "Entretenimiento"
                ],
                "unit": "MXN",
                "amount": 400.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -400.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-17",
        "time": null,
        "verified": false,
        "description": "Gasolina",
        "accounts": [
            {
                "account": "Gastos:Transporte",
                "subAccounts": [
                    "Gastos",
                    "Transporte"
                ],
                "unit": "MXN",
                "amount": 1000.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -1000.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-18",
        "time": null,
        "verified": false,
        "description": "Pago de luz",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 600.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -600.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-18",
        "time": null,
        "verified": false,
        "description": "Comida rápida",
        "accounts": [
            {
                "account": "Gastos:Comida",
                "subAccounts": [
                    "Gastos",
                    "Comida"
                ],
                "unit": "MXN",
                "amount": 800.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -800.0,
                "taxes": []
            }
        ],
        "properties": []
    },
    {
        "date": "2025-01-18",
        "time": null,
        "verified": false,
        "description": "Transporte privado",
        "accounts": [
            {
                "account": "Gastos:Transporte",
                "subAccounts": [
                    "Gastos",
                    "Transporte"
                ],
                "unit": "MXN",
                "amount": 450.0,
                "taxes": []
            },
            {
                "account": "Activos:Banco",
                "subAccounts": [
                    "Activos",
                    "Banco"
                ],
                "unit": "MXN",
                "amount": -450.0,
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
    "Assets": "Activos",
    "Liabilities": "Pasivos",
    "Equity": "Unknown-Equity",
    "Income": "Ingresos",
    "Expenses": "Gastos"
}
```

## parse_accounts()

Lista de cuentas contables detectadas.

```json
[
    "Activos:Banco",
    "Pasivos:Tarjeta",
    "Ingresos:Salarios",
    "Gastos:Comida",
    "Gastos:Transporte",
    "Gastos:Entretenimiento"
]
```

## parse_accounts_advance()

Lista de cuentas contables con metadatos detectadas.

```json
[
    {
        "account": "Activos:Banco"
    },
    {
        "account": "Pasivos:Tarjeta"
    },
    {
        "account": "Ingresos:Salarios"
    },
    {
        "account": "Gastos:Comida"
    },
    {
        "account": "Gastos:Transporte"
    },
    {
        "account": "Gastos:Entretenimiento"
    }
]
```

## calculate_balances()

Cálculo de balances por cuenta detallada.

```json
{
    "Activos:Banco": {
        "MXN": 18650.0
    },
    "Pasivos:Tarjeta": {
        "MXN": 8000.0
    },
    "Ingresos:Salarios": {
        "MXN": -35000.0
    },
    "Gastos:Comida": {
        "MXN": 5450.0
    },
    "Gastos:Transporte": {
        "MXN": 2250.0
    },
    "Gastos:Entretenimiento": {
        "MXN": 650.0
    }
}
```

## calculate_balances_by_parents_accounts()

Balance agrupado por cuentas padre.

```json
{
    "Assets": {
        "MXN": 18650.0
    },
    "Liabilities": {
        "MXN": 8000.0
    },
    "Equity": {
        "N/A": 0.0
    },
    "Income": {
        "MXN": -35000.0
    },
    "Expenses": {
        "MXN": 8350.0
    }
}
```

## calculate_status_results()

Estado de resultados (ingresos, gastos, utilidad).

```json
{
    "total_income_by_currency": {
        "MXN": 35000.0
    },
    "total_expenses_by_currency": {
        "MXN": -8350.0
    },
    "utility_by_currency": {
        "MXN": 26650.0
    },
    "income_details": [
        {
            "Ingresos:Salarios": {
                "currency": "MXN",
                "amount": 35000.0
            }
        }
    ],
    "expenses_details": [
        {
            "Gastos:Comida": {
                "currency": "MXN",
                "amount": -5450.0
            }
        },
        {
            "Gastos:Transporte": {
                "currency": "MXN",
                "amount": -2250.0
            }
        },
        {
            "Gastos:Entretenimiento": {
                "currency": "MXN",
                "amount": -650.0
            }
        }
    ]
}
```

## calculate_balances_by_details_accounts()

Balance por subcuentas detalladas.

```json
{
    "Activos": {
        "balances": {
            "MXN": 18650.0
        },
        "sub_accounts": {
            "Banco": {
                "balances": {
                    "MXN": 18650.0
                },
                "sub_accounts": {}
            }
        }
    },
    "Ingresos": {
        "balances": {
            "MXN": -35000.0
        },
        "sub_accounts": {
            "Salarios": {
                "balances": {
                    "MXN": -35000.0
                },
                "sub_accounts": {}
            }
        }
    },
    "Gastos": {
        "balances": {
            "MXN": 8350.0
        },
        "sub_accounts": {
            "Comida": {
                "balances": {
                    "MXN": 5450.0
                },
                "sub_accounts": {}
            },
            "Transporte": {
                "balances": {
                    "MXN": 2250.0
                },
                "sub_accounts": {}
            },
            "Entretenimiento": {
                "balances": {
                    "MXN": 650.0
                },
                "sub_accounts": {}
            }
        }
    },
    "Pasivos": {
        "balances": {
            "MXN": 8000.0
        },
        "sub_accounts": {
            "Tarjeta": {
                "balances": {
                    "MXN": 8000.0
                },
                "sub_accounts": {}
            }
        }
    }
}
```

## get_date_range()

Periodo detectado en las transacciones.

Desde: `2025/01/01` hasta `2025/01/18`

## parse_metadata()

Metadatos del archivo.

```json
{}
```

## parse_metadata_yaml()

Metadatos del archivo en formato YAML.

```json
{
    "currency": [
        "MXN",
        "USD",
        "EUR"
    ],
    "Taxes": {
        "IVA": 16,
        "RET_ISR": 1.25
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
        "line": "currency:"
    },
    {
        "type": "line",
        "index": 2,
        "line": "  - MXN"
    },
    {
        "type": "line",
        "index": 3,
        "line": "  - USD"
    },
    {
        "type": "line",
        "index": 4,
        "line": "  - EUR"
    },
    {
        "type": "line",
        "index": 5,
        "line": ""
    },
    {
        "type": "line",
        "index": 6,
        "line": "Taxes:"
    },
    {
        "type": "line",
        "index": 7,
        "line": "  IVA: 16"
    },
    {
        "type": "line",
        "index": 8,
        "line": "  RET_ISR: 1.25"
    },
    {
        "type": "line",
        "index": 9,
        "line": ""
    },
    {
        "type": "line",
        "index": 10,
        "line": "snippets:"
    },
    {
        "type": "line",
        "index": 11,
        "line": "  gasolina: |"
    },
    {
        "type": "line",
        "index": 12,
        "line": "    $DATE * Gasolina"
    },
    {
        "type": "line",
        "index": 13,
        "line": "        Expenses:Transport  $monto"
    },
    {
        "type": "line",
        "index": 14,
        "line": "        Assets:Cash"
    },
    {
        "type": "line",
        "index": 15,
        "line": ""
    },
    {
        "type": "line",
        "index": 16,
        "line": "  sueldo: |"
    },
    {
        "type": "line",
        "index": 17,
        "line": "    $DATE * Sueldo"
    },
    {
        "type": "line",
        "index": 18,
        "line": "        Assets:Bank:Checking  $monto"
    },
    {
        "type": "line",
        "index": 19,
        "line": "        Income:Salary"
    },
    {
        "type": "line",
        "index": 20,
        "line": "---"
    },
    {
        "type": "line",
        "index": 21,
        "line": ""
    },
    {
        "type": "line",
        "index": 22,
        "line": ""
    },
    {
        "type": "line",
        "index": 23,
        "line": "; Archivo de ejemplo para Ledger"
    },
    {
        "type": "line",
        "index": 24,
        "line": "; Fecha: 2025-01-18"
    },
    {
        "type": "line",
        "index": 25,
        "line": "; Moneda: MXN"
    },
    {
        "type": "line",
        "index": 26,
        "line": ""
    },
    {
        "type": "line",
        "index": 27,
        "line": ""
    },
    {
        "type": "line",
        "index": 28,
        "line": "; Definición de cuentas"
    },
    {
        "type": "line",
        "index": 29,
        "line": "account Activos:Banco  "
    },
    {
        "type": "line",
        "index": 30,
        "line": "account Pasivos:Tarjeta"
    },
    {
        "type": "line",
        "index": 31,
        "line": "account Ingresos:Salarios"
    },
    {
        "type": "line",
        "index": 32,
        "line": "account Gastos:Comida"
    },
    {
        "type": "line",
        "index": 33,
        "line": "account Gastos:Transporte"
    },
    {
        "type": "line",
        "index": 34,
        "line": "account Gastos:Entretenimiento"
    },
    {
        "type": "line",
        "index": 35,
        "line": ""
    },
    {
        "type": "line",
        "index": 36,
        "line": "; Transacciones de ejemplo"
    },
    {
        "type": "line",
        "index": 37,
        "line": ""
    },
    {
        "type": "transaction",
        "index": [
            38,
            39,
            40,
            41,
            42,
            43
        ],
        "lines": [
            "2025/01/01 Salario Mensual",
            "    Activos:Banco                      25,000.00 MXN +{IVA, RET_ISR}",
            "    Ingresos:Salarios",
            "    -tags: salary, income",
            "    -uuid: f2c2a-3bd1",
            "    -responsible: Eduardo"
        ]
    },
    {
        "type": "line",
        "index": 45,
        "line": ""
    },
    {
        "type": "transaction",
        "index": [
            46,
            47,
            48,
            49,
            50,
            51,
            52
        ],
        "lines": [
            "2025-01-02 Compra de alimentos",
            "    Gastos:Comida                     MXN 1,200.00  -{IVA}",
            "    Activos:Banco",
            "    -tags: shopping, groceries, food",
            "    -uuid: f2c2a-3bd1",
            "    -ticket: [ticket](./tickets/compu-2025.jpg)",
            "    -responsible: Eduardo"
        ]
    },
    {
        "type": "transaction",
        "index": [
            54,
            55,
            56
        ],
        "lines": [
            "2025-01-03 Transporte público",
            "    Gastos:Transporte                  MXN 500.00 +{RET_ISR}",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            58,
            59,
            60
        ],
        "lines": [
            "2025-01-05 Cena en restaurante",
            "    Gastos:Comida                     MXN 750.00 +{IVA}",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            62,
            63,
            64
        ],
        "lines": [
            "2025-01-07 Pago de tarjeta de crédito",
            "    Pasivos:Tarjeta                   MXN 5,000.00 +{RET_ISR}",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            66,
            67,
            68
        ],
        "lines": [
            "2025-01-08 Suscripción de streaming",
            "    Gastos:Entretenimiento             MXN 250.00 ={IVA}",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            70,
            71,
            72
        ],
        "lines": [
            "2025-01-10 Transporte (taxi)",
            "    Gastos:Transporte                  MXN 300.00",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            74,
            75,
            76
        ],
        "lines": [
            "2025-01-12 Supermercado",
            "    Gastos:Comida                     MXN 2,100.00",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            78,
            79,
            80
        ],
        "lines": [
            "2025-01-15 Salario extra",
            "    Activos:Banco                     MXN 10,000.00",
            "    Ingresos:Salarios"
        ]
    },
    {
        "type": "transaction",
        "index": [
            82,
            83,
            84
        ],
        "lines": [
            "2025-01-16 Pago parcial tarjeta de crédito",
            "    Pasivos:Tarjeta                   MXN 3,000.00",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            86,
            87,
            88
        ],
        "lines": [
            "2025-01-17 Cine",
            "    Gastos:Entretenimiento             MXN 400.00",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            90,
            91,
            92
        ],
        "lines": [
            "2025-01-17 Gasolina",
            "    Gastos:Transporte                  MXN 1,000.00",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            94,
            95,
            96
        ],
        "lines": [
            "2025-01-18 Pago de luz",
            "    Gastos:Comida                     MXN 600.00",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            98,
            99,
            100
        ],
        "lines": [
            "2025-01-18 Comida rápida",
            "    Gastos:Comida                     MXN 800.00",
            "    Activos:Banco"
        ]
    },
    {
        "type": "transaction",
        "index": [
            102,
            103,
            104
        ],
        "lines": [
            "2025-01-18 Transporte privado",
            "    Gastos:Transporte                  MXN 450.00",
            "    Activos:Banco"
        ]
    },
    {
        "type": "line",
        "index": 106,
        "line": "; Balance final en Activos:Banco: MXN 19,000.00"
    }
]
```

# Clase: `LedgerAnalyst`


## detect_unusual_expenses()

Detecta gastos que exceden significativamente su promedio histórico.

```json
[]
```

## get_daily_incomes_expenses()

Muestra ingresos y gastos diarios.

```json
[
    {
        "date": "2025-01-01",
        "incoming": 25000.0,
        "expenses": 0.0
    },
    {
        "date": "2025-01-02",
        "incoming": 0.0,
        "expenses": 1200.0
    },
    {
        "date": "2025-01-03",
        "incoming": 0.0,
        "expenses": 500.0
    },
    {
        "date": "2025-01-05",
        "incoming": 0.0,
        "expenses": 750.0
    },
    {
        "date": "2025-01-08",
        "incoming": 0.0,
        "expenses": 250.0
    },
    {
        "date": "2025-01-10",
        "incoming": 0.0,
        "expenses": 300.0
    },
    {
        "date": "2025-01-12",
        "incoming": 0.0,
        "expenses": 2100.0
    },
    {
        "date": "2025-01-15",
        "incoming": 10000.0,
        "expenses": 0.0
    },
    {
        "date": "2025-01-17",
        "incoming": 0.0,
        "expenses": 1400.0
    },
    {
        "date": "2025-01-18",
        "incoming": 0.0,
        "expenses": 1850.0
    }
]
```

## get_expenses_pie()

Distribución de gastos por cuenta.

```json
[
    {
        "account": "Gastos:Comida",
        "amount": 5450.0
    },
    {
        "account": "Gastos:Transporte",
        "amount": 2250.0
    },
    {
        "account": "Gastos:Entretenimiento",
        "amount": 650.0
    }
]
```

## get_incomes_pie()

Distribución de ingresos por cuenta.

```json
[
    {
        "account": "Ingresos:Salarios",
        "amount": 35000.0
    }
]
```

## get_assets_summary()

Resumen del total de activos.

```json
[
    {
        "account": "Activos:Banco",
        "amount": 51350.0
    }
]
```

## get_liabilities_summary()

Resumen del total de pasivos.

```json
[
    {
        "account": "Pasivos:Tarjeta",
        "amount": 8000.0
    }
]
```

## get_balance_by_day()

Evolución del balance diario (ingresos - gastos).

```json
[
    {
        "date": "2025-01-01",
        "incoming": 25000.0,
        "expenses": 0.0,
        "balance": 25000.0
    },
    {
        "date": "2025-01-02",
        "incoming": 0.0,
        "expenses": 1200.0,
        "balance": 23800.0
    },
    {
        "date": "2025-01-03",
        "incoming": 0.0,
        "expenses": 500.0,
        "balance": 23300.0
    },
    {
        "date": "2025-01-05",
        "incoming": 0.0,
        "expenses": 750.0,
        "balance": 22550.0
    },
    {
        "date": "2025-01-08",
        "incoming": 0.0,
        "expenses": 250.0,
        "balance": 22300.0
    },
    {
        "date": "2025-01-10",
        "incoming": 0.0,
        "expenses": 300.0,
        "balance": 22000.0
    },
    {
        "date": "2025-01-12",
        "incoming": 0.0,
        "expenses": 2100.0,
        "balance": 19900.0
    },
    {
        "date": "2025-01-15",
        "incoming": 10000.0,
        "expenses": 0.0,
        "balance": 29900.0
    },
    {
        "date": "2025-01-17",
        "incoming": 0.0,
        "expenses": 1400.0,
        "balance": 28500.0
    },
    {
        "date": "2025-01-18",
        "incoming": 0.0,
        "expenses": 1850.0,
        "balance": 26650.0
    }
]
```

## get_cashflow_by_month()

Flujo de caja mensual (ingresos - gastos).

```json
[
    {
        "month": "2025-01",
        "in": 35000.0,
        "out": 8350.0,
        "net": 26650.0
    }
]
```

## get_expense_trends_by_category()

Tendencias de gastos por categoría mensual.

```json
{
    "Gastos:Comida": {
        "2025-01": 5450.0
    },
    "Gastos:Transporte": {
        "2025-01": 2250.0
    },
    "Gastos:Entretenimiento": {
        "2025-01": 650.0
    }
}
```

## get_monthly_incomes_expenses()

Resumen mensual de ingresos y gastos.

```json
[
    {
        "month": "2025-01",
        "incoming": 35000.0,
        "expenses": 8350.0
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
    }
]
```

## get_monthly_expense_ratio()

Tasa de gastos mensual.

```json
[
    {
        "month": "2025-01",
        "expense_ratio": 23.86
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
    }
]
```

## get_trend_slope()

Pendiente de la tendencia.

```json
0.0
```

## predict_future_months()

Predicción de meses futuros.

```json
[
    {
        "month": "2025-02",
        "predicted_in": 0.0
    },
    {
        "month": "2025-03",
        "predicted_in": 0.0
    },
    {
        "month": "2025-04",
        "predicted_in": 0.0
    }
]
```

## get_extreme_months()

Meses extremos.

```json
{
    "highest_income": {
        "month": "2025-01",
        "in": 35000.0,
        "out": 8350.0,
        "net": 26650.0
    },
    "highest_expense": {
        "month": "2025-01",
        "in": 35000.0,
        "out": 8350.0,
        "net": 26650.0
    },
    "best_balance": {
        "month": "2025-01",
        "in": 35000.0,
        "out": 8350.0,
        "net": 26650.0
    }
}
```

## classify_months_by_balance()

Clasificación de meses según balance.

```json
{
    "positive": [
        "2025-01"
    ],
    "negative": [],
    "neutral": []
}
```

## compare_months()

Comparación de meses.

```json
{}
```

## get_income_dependency_ratio()

Ratio de dependencia de ingresos.

```json
[
    {
        "month": "2025-01",
        "dependency_ratio": 23.86
    }
]
```

## get_cumulative_net_income()

Acumulación de ingresos netos.

```json
[
    {
        "month": "2025-01",
        "cumulative_net": 26650.0
    }
]
```

## get_accounts_used()

Listado de todas las cuentas utilizadas.

- Activos:Banco
- Gastos:Comida
- Gastos:Entretenimiento
- Gastos:Transporte
- Ingresos:Salarios
- Pasivos:Tarjeta
