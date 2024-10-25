# Fetch-Rewards-Coding-Exercise

Solutions for these exercises

1. Reviewing Existing Unstructured Data and Diagraming a New Structured Relational Data Model

   - Reviewed Existing Data
      - I have cleaned and structed three datasets: Users, Brands and Receipts
      - This allowed me to understand the data's orginal unstructured form and organize it.
      - The model includes a clear define of each table listing their fields and primary keys and foreign keys.
      - Users: Contains user account information (user_id (Primary Key), creation, last login, active/non,role )
      - Receipts: contains receipt and transaction data for each user (receipt_id, useer_Id, transaction data, linked to Users through Id)
      - ReceiptItems: contains informations such as ReceiptItems_id, receiptid (foreign key), barcode (foreign key), price, description
      - Brands: contains information about the brands that go along with the products (brand_id, barcode, category, cpg (foreign key, name)
      - CPG: contains information cpg_id, topbrand, name linking to brands table 
      - A user can have multiple receipts which is 1 to many relationships between Users and Receipts
      - 
Please refer to ------ for the full representation of the data model

