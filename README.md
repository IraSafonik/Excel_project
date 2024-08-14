# Excel_project
PWC

## 💡 Project Overview
This project involves cleaning, transforming, and analyzing a detailed transaction listing in Excel. The data includes supplier transactions with various currencies, and the goal is to prepare the data for further financial analysis and reporting.

## ☝️ Project Goals
- Organize and clean the transaction data for ease of analysis.
- Format the data for quick reference and use in financial reporting.
- Implement formulas to automatically categorize transactions, calculate amounts in UAH, and associate suppliers with their names.
- Remove unnecessary data to focus on relevant transactions for FY2023.

## 💼 Tasks
- Separate Supplier Number: Use Text to Columns to split the Supplier Number from the rest of the data.
- Extract Account and Currency: Use Excel's Flash Fill (CTRL + E) to separate the Account from the Currency.
- Add a "CCY AP" Column: Mark foreign currency transactions with an "x" using the IF formula.
- Add an "Amount, UAH" Column: Convert foreign currency amounts to UAH using either the IF formula or XLOOKUP.
- Add Supplier Name: Use VLOOKUP to match and insert supplier names from a Master Data list.
- Remove Duplicate Balances: Identify and remove duplicate balances from the data.
- Filter Data for FY2023: Use Excel’s Find & Select >> Go to Special >> Visible Cells Only to exclude non-FY2023 balances.

## 🛠️ Tools and Technologies
- Microsoft Excel: For data cleaning, transformation, and analysis.
- Excel Formulas: Including IF, VLOOKUP, SUMIFS, XLOOKUP.
- Pivot Tables: For summarizing and analyzing data.

## 🗂️ Data Sources
- Detailed Listing (txt file): Contains the raw transaction data.
- Master Data (Excel file): Includes supplier details for VLOOKUP operations.

## 💻 Process and Steps
### 1️⃣ Step 1: Data Preparation
- Import Data: Begin by importing the txt file into Excel and converting it to a structured table.
- Separate Columns: Use the Text to Columns feature to split the Supplier Number and other relevant data fields.
- Account/Currency Separation: Utilize Flash Fill to cleanly separate the Account and Currency fields.

### 2️⃣ Step 2: Data Transformation
- Add "CCY AP" Column: Use the IF formula to mark transactions in foreign currencies.
- Add "Amount, UAH" Column: Convert foreign currency transactions to UAH using either the IF formula or XLOOKUP with a conversion rate table.
- Add "Supplier Name": Match and insert supplier names using VLOOKUP based on Supplier Numbers.

### 3️⃣ Step 3: Data Cleaning
- Remove Duplicates: Identify and delete any duplicate balances from the listing.
- Filter FY2023 Data: Use Find & Select to focus on transactions relevant to the current fiscal year.

### 4️⃣ Step 4: Analysis
- Pivot Tables: Create pivot tables to summarize the total amount payable by each supplier and analyze currency distribution.

## 🌿 Results and Conclusion
Through this project, I successfully transformed a detailed transaction listing into a clean, organized dataset ready for financial analysis. The use of Excel's powerful formulas and data tools allowed me to automate the categorization and conversion processes, ensuring accuracy and efficiency. By removing irrelevant data and focusing on FY2023, I ensured that the dataset is up-to-date and relevant for current financial reporting.

