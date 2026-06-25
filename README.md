# DecodeLabs-Internship
Virtual internship project repository for DecodeLabs Industrial Training, Batch 2026.

Covers data analytics tasks and weekly assignments.
**Analyst:** Courage Cobbinah

**GitHub:** courage-analytics-glitch
---
## Project 1: Data Cleaning and Preparation
**Dataset:** E-Commerce Orders (1,200 rows, 14 columns)
### What Was Done
- Filled 309 null values in the CouponCode column with "NONE"

- Standardised all dates to ISO 8601 format (YYYY-MM-DD)

- Corrected floating point precision errors in UnitPrice and TotalPrice (29 rows)

- Verified zero duplicate OrderIDs

- Verified zero negative values

- Verified TotalPrice calculation accuracy across all 1,200 rows
### Deliverables
- Cleaned_Dataset_DecodeLabs_Project1_Courage.xlsx

- Change_Log_DecodeLabs_Project1.pdf
### Outcome
All integrity checks passed. Zero records deleted. Dataset is clean and ready for analysis.
---
## Project 2: Coming Soon
---
*Built by Courage Cobbinah | DecodeLabs Industrial Training | Batch 2026*


## Project 2: Exploratory Data Analysis (EDA)

**Dataset:** E-Commerce Orders (1,200 rows, 14 columns)

### What Was Done

- Profiled all 14 columns across data types, null counts, and unique values
- Calculated descriptive statistics for all 4 numeric columns (Quantity, UnitPrice, ItemsInCart, TotalPrice)
- Performed categorical analysis across Order Status, Product, Referral Source, Payment Method, and Coupon Code
- Applied IQR outlier detection method across all numeric columns
- Identified 8 high-value TotalPrice outliers above $3,330
- Produced 8 key findings with business diagnosis for each

### Key Findings

- 41.4% of orders are Cancelled or Returned. Only 19.3% are Delivered
- Instagram is the top acquisition channel at 21.6%
- TotalPrice is right-skewed. Median ($824) is the reliable revenue benchmark, not the mean ($1,054)
- Quantity and TotalPrice have a strong positive correlation (r = 0.62)

### Deliverables

- DecodeLabs_Project2_EDA.xlsx
- DecodeLabs_Project2_EDA_Report.docx

### Outcome

8 actionable business insights produced. Dataset fully analysed across 5 structured sheets.
