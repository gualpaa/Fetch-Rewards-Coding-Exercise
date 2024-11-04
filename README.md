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
Please refer to Part 1 New Data Model.pdf for the full representation of the data model


I have completed steps 1-3 on a ipython notebook and included it into my repository. I have labeled every 
step in the notebook. the first step was to convert a unstructured file to a clean one which is done in 
the notebook. Make sure to upload the orginal JSON files into the working space for the notebook to run 
smoothly. 

The last step which is the email to a stakeholder is label as in this repository. 

