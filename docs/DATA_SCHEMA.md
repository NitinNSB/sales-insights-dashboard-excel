# Data Schema Documentation

## Sample Sales Data Structure

The `sample_sales_data.csv` file contains sales transaction records with the following fields:

### Fields Description

| Field Name | Data Type | Description | Example |
|------------|-----------|-------------|---------|
| Order_ID | String | Unique identifier for each order | ORD001 |
| Order_Date | Date | Date when the order was placed (YYYY-MM-DD) | 2024-01-05 |
| Customer_ID | String | Unique identifier for each customer | CUST101 |
| Customer_Name | String | Name of the customer/company | Acme Corporation |
| Region | String | Geographic region of the sale | North, South, East, West |
| Product_Category | String | Category of the product sold | Electronics, Office Supplies, Furniture |
| Product_Name | String | Name of the product | Laptop Pro 15 |
| Quantity | Integer | Number of units sold | 5 |
| Unit_Price | Decimal | Price per unit in USD | 1200.00 |
| Total_Amount | Decimal | Total sale amount (Quantity × Unit_Price) | 6000.00 |
| Sales_Rep | String | Name of the sales representative | John Smith |
| Payment_Method | String | Method of payment used | Credit Card, Wire Transfer, Check |

### Data Statistics

- **Total Records**: 50 orders
- **Date Range**: January 2024 - June 2024
- **Regions**: 4 (North, South, East, West)
- **Product Categories**: 3 (Electronics, Office Supplies, Furniture)
- **Sales Representatives**: 4 (John Smith, Sarah Johnson, Mike Davis, Emily Brown)
- **Payment Methods**: 3 (Credit Card, Wire Transfer, Check)
- **Unique Customers**: 44

### Business Rules

1. Order IDs follow the format: ORD### (sequential numbering)
2. Customer IDs follow the format: CUST### (sequential numbering)
3. Total_Amount = Quantity × Unit_Price
4. All monetary values are in USD
5. Each sales rep is assigned to a specific region:
   - John Smith → North
   - Sarah Johnson → South
   - Mike Davis → East
   - Emily Brown → West

### Data Quality Notes

- No missing values in any field
- All dates are valid and in chronological order
- All calculations are accurate
- Customer names and product names are realistic business entities
