# LSP_REPO_2
hw assignment 2

Reads 'data/products.csv', transforms product data, and writes 'data/transformed_products.csv'.

Project Structure:
LSP_Project/
├── src/org/howard/edu/lsp/assignment2/ETLPipeline.java

└── data/
├── products.csv
└── transformed_products.csv

How I Ran it: 
1. Ensured 'data/products.csv' exists relative to project root.  
2. Ran ETLPipeline.java in Eclipse.
3. Output was written to 'data/transformed_products.csv'. Run summary was printed. 


References: 
- Java File I/O: https://docs.oracle.com/javase/8/docs/api/java/nio/file/package-summary.html  (Learned file read/write; adapted for CSV parsing and handling empty/missing files) 
- BigDecimal rounding: https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html  
  (Learned HALF_UP rounding; adapted to round transformed prices to 2 decimals)

