# Exploratory Data Analysis (EDA) Project

This project focuses on conducting an Exploratory Data Analysis (EDA) on a retail dataset. The dataset contains information about product transactions, including invoice details, product quantities, unit prices, customer IDs, and countries.

## Dataset Description

The dataset consists of the following columns:

- InvoiceNo: Invoice number of the transaction
- StockCode: Unique code of the product
- Description: Description of the product
- Quantity: Quantity of the product in the transaction
- InvoiceDate: Date and time of the transaction
- UnitPrice: Unit price of the product
- CustomerID: Unique identifier of the customer
- Country: Country where the transaction occurred

## Goals of the Analysis

The primary goals of this EDA project are as follows:

1. Explore the central tendency and dispersion of the Quantity and UnitPrice columns.
2. Identify and handle outliers in the dataset.
3. Visualize the data using various plots and charts.
4. Identify the top customers based on their CustomerID.
5. Conduct spatial analysis by plotting countries on a map and coloring them based on Quantity and UnitPrice.
6. Identify the top days and months in terms of transaction volume.
7. Generate insights and draw conclusions from the EDA findings.

## Repository Contents

This repository contains the following files:

- `data.csv`: The retail dataset used for the analysis.
- `analysis.ipynb`: Jupyter Notebook containing the EDA code.
- `README.md`: This README file providing an overview of the project.

## Getting Started

To replicate the analysis on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/eda-project.git`
2. Navigate to the project directory: `cd eda-project`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Open and run the Jupyter Notebook `analysis.ipynb` to execute the EDA code.

## Results and Conclusions

The EDA conducted on the retail dataset revealed the following key findings:

- The average quantity purchased is 7.55 units, with a standard deviation of 6.78. The most commonly purchased quantity is 12 units.
- The average unit price is 2.19, with a standard deviation of 1.55. The most common unit price is 1.25.
- The top three days with the highest transaction volume are November 6th, December 5th, and November 20th.
- The top three months with the highest transaction volume are November, October, and September.
- The United Kingdom is the country with the highest quantity of products sold, followed by Germany, France, Ireland, Spain, Switzerland, Belgium, Portugal, Norway, and the Netherlands.

These findings provide valuable insights into the dataset and can be further used for business decision-making and further analysis.

## References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Geopandas Documentation](https://geopandas.org/)

