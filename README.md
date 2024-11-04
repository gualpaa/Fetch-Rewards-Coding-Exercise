# Fetch-Rewards-Coding-Exercise

Solutions for these Exercises

1. Reviewing Existing Unstructured Data and Diagraming a New Structured Relational Data Model

   - I have cleaned and structured three datasets: Users, Brands, and Receipts.
   - This process allowed me to analyze the original unstructured data and organize it for easier analysis.
   - The new data model clearly defines each table, listing their fields, primary keys, and foreign keys:
         - Users: Contains user account information (user_id (Primary Key), creation date, last login, active status, role)
         - Receipts: Contains receipt and transaction data for each user (receipt_id, user_id (Foreign Key), transaction data)
         - ReceiptItems: Contains details about items on each receipt (receiptItem_id, receipt_id (Foreign Key), barcode (Foreign Key), price, description)
         - Brands: Contains brand information related to products (brand_id, barcode, category, CPG (Foreign Key), name)
         - CPG: Contains company information for consumer product groups (cpg_id, topBrand, name, linked to the Brands table)
   - A user can have multiple receipts, creating a 1-to-many relationship between Users and Receipts.

Please refer to Part 1 New Data Model.pdf for the full representation of the data model

2. Steps in the Jupyter Notebook
   - I have completed steps 1-3 in a Jupyter notebook, which is included in this repository. Each step is labeled for clarity.
   - The first step involves converting unstructured JSON files into a cleaned, structured format, which is done in the notebook.
   - Note: Be sure to upload the original JSON files into the working directory to ensure the notebook runs smoothly.
  
   3. Stakeholder Communication
      - The last step which is the email to a stakeholder is label as "StakeholdersEmail.txt" in this repository. 

