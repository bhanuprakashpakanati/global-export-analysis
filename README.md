# Global Export Analysis

## 📖 Project Overview
Comprehensive analysis of export data was conducted to identify key trends, calculate financial metrics, and optimize trade operations.

## 🎯 Business Objectives
- Export patterns and regional performance were analyzed
- Financial metrics were calculated: Total Sales, Freight Charges, Duty Charges, Net Sales
- Top-performing commodities and suppliers were identified
- Gold and Iron/Steel commodities were excluded
- Year-over-year growth insights were provided

## 📊 Key Calculations
1. **Total Sales** = Price × Quantity
2. **Freight Charges** = Total Sales × (Freight Charges % / 100)
3. **Duty Charges** = Total Sales × Duty Rate (based on quantity tiers)
4. **Net Sales** = Total Sales - Freight Charges - Duty Charges
5. **Total Cost to Company** = Total Sales + Freight Charges + Duty Charges

## 🔧 Technical Requirements
- **Currency Conversion**: Exchange rate table was utilized
- **Data Cleaning**: Prices were rounded to 2 decimals, "NA" material types were replaced with "UNDER PROCESSING"
- **Regional Hierarchy**: Namibia (NM) and Morocco (MA) were classified under "EAST AFRICA"
- **Exclusions**: Gold and Iron/Steel commodities were removed

## 📈 Data Columns Analyzed
- HS Code, Commodity Codes, State/Region/Country Codes
- Supplier details, Pricing, Quantities, Export modes
- Time dimensions (Month, Year), Currency data
- Material types, Freight charges, Export destinations

## 🛠️ Technologies Used
- SQL Server
- Multiple dimension tables
- Complex joins and business logic were implemented
