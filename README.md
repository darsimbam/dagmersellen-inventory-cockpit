# Baselstrasse Co. LTD – Inventory & Service Cockpit

A small Streamlit app I built on an open beauty distribution dataset to practice
modern supply chain analytics and AI-style decision support.

## What it does

- Detects **dead/slow inventory** (slow movers with high Days of Supply)
- Shows **Days of Supply** per SKU (overstock vs stockout risk)
- Calculates simplified **inventory turns** by product type
- Compares **forecast vs actual** using order quantities vs sales quantities
- Includes an **AI Suggestions** tab (rule-based “ML”) to recommend new days-of-supply
- Includes a **Planner Copilot** tab (mock GenAI) that explains issues in plain language

## Tech stack

- Python
- pandas
- Streamlit

## How to run

```bash
pip install -r requirements.txt
streamlit run Dagmersellen.py
