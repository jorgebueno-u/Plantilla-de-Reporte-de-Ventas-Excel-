# Plantilla de Reporte de Ventas — Excel

A ready-to-use Excel template for small businesses to log sales and get an automatic dashboard — no manual calculations, no pivot tables required. Built as a freelance portfolio piece.

## Overview

Small retail businesses often track sales in a spreadsheet with no formulas — totals get calculated by hand and errors creep in. This template solves that: enter each sale once, and every number in the dashboard updates automatically.

## What's inside

**Sheet 1 — Ventas (data entry)**
- Log each sale: date, product, category, quantity, unit price
- The `Total` column calculates itself (`=Cantidad*Precio Unitario`)
- Category dropdown menu to keep entries consistent
- Input cells are marked in blue, with one example row included

**Sheet 2 — Resumen (dashboard)**
- Total revenue, units sold, and average ticket size
- Revenue broken down by category
- A bar chart that updates automatically as new sales are entered

## How the automation works

Every number in the "Resumen" sheet is a live formula, not a static value:

| Metric | Formula used |
|---|---|
| Total revenue | `SUM` |
| Average ticket | `IFERROR` (avoids errors on empty data) |
| Revenue by category | `SUMIFS` |

This means the template can be reused indefinitely — just clear the example row and start entering real data.

## Use it

1. Download `Plantilla_Reporte_Ventas.xlsx`
2. Open it in Excel or Google Sheets
3. Replace the example row in the "Ventas" sheet with your own sales
4. Check the "Resumen" sheet — it updates automatically

## Why this project

This demonstrates practical Excel skills that small businesses actually need: clean data entry design, formula-driven reporting, and a dashboard that non-technical users can maintain themselves. Adaptable to inventory tracking, expense logging, or any recurring report a small business needs.
