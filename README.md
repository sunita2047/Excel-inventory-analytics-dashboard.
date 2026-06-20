# Excel Inventory Analytics Dashboard

An end-to-end Excel system that tracks daily production, sales, and stock movement for a mineral processing business across 11 bag products, with an automated analytical layer built on top of the raw register.

This is a real operational tool, originally built for a family mineral/mining business, then adapted into a portfolio project to demonstrate Excel data modeling, formula automation, and dashboard design.

## 📂 Workbook Structure

| Sheet | Purpose |
|---|---|
| `Jan 2026` – `Jun 2026` | Daily production & dispatch registers — one sheet per month, tracking Opening Stock, Production, Sales, and Closing Stock per product per day |
| `Data` | A single flat data table (1,991 rows) consolidating all six monthly registers into one analysis-ready dataset — Month, Date, Day, Weekday/Weekend, Product, Opening Stock, Production, Sales, Closing Stock, Efficiency % |
| `PIVOT` | The analysis layer — Pivot Tables and Pivot Charts built on the flat data, with slicers for interactive filtering |
| `FY Summary 2026-27` | A rolled-up monthly summary (Jan–Jun 2026) showing Opening Stock, Total Production, Total Sales, and Closing Stock, with fiscal year-to-date totals |

## 🧱 What's Inside

- **11 products tracked**: -100#, 14/30#, 16/30#, 1mm, 24/60#, 2mm, 30/80#, 3mm, 50/150#, 5mm, Dust/150#
- **6 months of daily data**: January 2026 – June 2026
- **1,991 rows** in the consolidated flat data table
- **Cross-sheet formula automation**: monthly registers feed into the flat `Data` sheet and the `FY Summary`, so closing stock automatically rolls forward as opening stock for the next period
- **Efficiency %** calculated per row (Sales as a percentage of Production) to flag under/over-performing days
- **Weekday/Weekend tagging** to support day-type pattern analysis
- **Interactive Pivot dashboard** with slicers for filtering by Month/Product, and Pivot Charts visualizing Sales and Production trends across the fiscal year

## 🛠️ Skills Demonstrated

- Multi-sheet workbook architecture and cross-sheet formula referencing
- Data consolidation (6 separate daily registers → 1 flat table) for analysis readiness
- Pivot Table & Pivot Chart design
- Slicer-based interactive filtering
- Fiscal year summary reporting and stock roll-forward logic

Author
** SUNITA SUTHAR **
