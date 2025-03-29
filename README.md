# Dmart Analysis Using PySpark

## Project Overview
This project aims to analyze Dmart sales data using PySpark. The pipeline integrates and processes data from three different sources: product information, sales transactions, and customer details. The goal is to clean, transform, and analyze the data using PySpark, answering key business questions.

## Technologies Used
- **Programming Language:** Python
- **Big Data Framework:** Apache PySpark
- **Database:** SQL
- **Data Processing Libraries:** PySpark DataFrames

## Dataset
- `products.csv` - Contains product details.
- `sales.csv` - Includes transaction records.
- `customer.csv` - Stores customer information.

## Project Workflow
### Step 1: Establish PySpark Connection
- Set up a PySpark environment.
- Load CSV files into PySpark DataFrames.

### Step 2: Data Transformation and Cleaning
- Rename columns for consistency.
- Handle missing values appropriately.
- Ensure correct data types for each column.
- Perform necessary joins between tables (Product ID and Customer ID).

### Step 3: Data Analysis and Querying
- Answer key business questions using PySpark queries.

### Step 4: Key Analytical Queries
- **Total sales for each product category.**
- **Customer with the highest number of purchases.**
- **Average discount given across all products.**
- **Number of unique products sold in each region.**
- **Total profit generated in each state.**
- **Product sub-category with the highest sales.**
- **Average age of customers in each segment.**
- **Orders shipped in each shipping mode.**
- **Total quantity of products sold in each city.**
- **Customer segment with the highest profit margin.**

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/dmart-pyspark-analysis.git
   ```
2. Install dependencies:
   ```sh
   pip install pyspark pandas
   ```
3. Run the PySpark script:
   ```sh
   python dmart_analysis.py
   ```

## Project Structure
```
📂 Dmart-PySpark-Analysis
├── 📂 data                  # Dataset files
├── 📂 scripts               # PySpark scripts for ETL and analysis
├── 📜 README.md             # Project documentation
├── 📜 requirements.txt      # Dependencies list
├── 📜 dmart_analysis.py     # Main script
```

## Best Practices
- **Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) coding standards.**
- **Ensure modular and maintainable code.**
- **Use environment variables for sensitive configurations.**

## Conclusion
This project provides valuable insights into Dmart sales trends using PySpark, showcasing the power of big data processing.

## Author
Vijay M
