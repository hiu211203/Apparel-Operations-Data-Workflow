# Apparel Operations Data Workflow

## Overview
An Excel-based portfolio project for organizing and validating apparel merchandising and production data. The project uses raw operational data to build a traceable workflow from item and order information through BOM, purchasing, cost review, and production analysis.

## Objective
Demonstrate practical skills in:
- Structuring raw operational data in Excel
- Maintaining item master and order information
- Organizing BOM details and material consumption
- Estimating material cost from BOM and supplier price references
- Tracking purchase orders and supplier-related information
- Comparing order, PO, and cost data for accuracy
- Preparing operational summaries and dashboards

## Workbook Structure
| Sheet | Purpose |
|---|---|
| `Raw_Order` | Original order-level data |
| `Raw_Item` | Original item master data |
| `Raw_BOM` | Original BOM and consumption data |
| `Raw_Price` | Supplier price references |
| `Raw_PO` | Purchase order data |
| `Raw_Cost` | Cost sheet data |
| `Raw_Production` | Production records |
| `Item_Master` | Structured item information |
| `Order_Sheet` | Order tracking and basic validation |
| `BOM` | Structured BOM worksheet |
| `BOM_Estimation` | Material cost estimation by order/style |
| `PO_Tracker` | Purchase tracking and data checks |
| `Cost_Sheet` | Cost review and cost-per-piece calculation |
| `Accuracy_Check` | Cross-check between order, PO and cost records |
| `Dashboard` | Operational and data-quality summary |

## Data Logic
- Raw source fields are preserved in `Raw_*` sheets.
- Derived fields are used only for analysis, validation, and reporting.
- Supplier prices are treated as reference values rather than approved purchasing prices.
- BDT and USD are kept separate because the source data does not contain an FX rate.
- Order, PO, style, and cost quantities are cross-checked to identify potential inconsistencies.
- The workbook avoids inventing business fields that are not available in the raw data.

## Key Excel Techniques
- XLOOKUP / VLOOKUP
- SUMIF / SUMIFS
- SUMPRODUCT
- IF / IFERROR / OR
- Data validation and consistency checks
- Conditional formatting
- Structured worksheets and traceability
- KPI summaries and dashboard reporting

