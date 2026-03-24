# Python RPA – Sales Automation

Scripts for automating a sales reporting workflow: reads Excel data, analyzes it, generates a chart, and sends the report via WhatsApp.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## What it does

| File | Role |
|---|---|
| `rpa_ventas.py` | Main script — orchestrates the full pipeline |
| `data_analyzer.py` | Reads `ventas.xlsx`, computes totals, averages and trends |
| `report_generator.py` | Generates `ventas_grafico.png` from the analyzed data |
| `whatsapp_sender.py` | Sends the chart report via WhatsApp using pywhatkit |

---

## Requirements

```bash
pip install pandas matplotlib openpyxl pywhatkit
```

## Usage

```bash
python rpa_ventas.py
```

Make sure `ventas.xlsx` is in the root directory before running.

---

## Author

[Carlos Díaz](https://github.com/cgds1)
