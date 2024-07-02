# Customer Market Segmentation using Unsupervised Machine Learning

This repository contains my completed guided project from Coursera's "Unsupervised Machine Learning for Customer Market Segmentation." In this project, I applied unsupervised learning techniques to segment a customer market, identifying distinct groups of customers based on their purchasing behavior and other characteristics.

## Project Overview

### Objectives
- Apply unsupervised learning techniques to segment customers.
- Analyze and interpret the results of the segmentation.
- Provide insights and recommendations based on the segmented data.

### Dataset
The project uses a dataset containing customer information such as:
- CUSTID: Identification of Credit Card holder 
- BALANCE: Balance amount left in customer's account to make purchases
- BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- PURCHASES: Amount of purchases made from account
- ONEOFFPURCHASES: Maximum purchase amount done in one-go
- INSTALLMENTS_PURCHASES: Amount of purchase done in installment
- CASH_ADVANCE: Cash in advance given by the user
- PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
- ONEOFF_PURCHASES_FREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
- PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- CASH_ADVANCE_FREQUENCY: How frequently the cash in advance being paid
- CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advance"
- PURCHASES_TRX: Number of purchase transactions made
- CREDIT_LIMIT: Limit of Credit Card for user
- PAYMENTS: Amount of Payment done by user
- MINIMUM_PAYMENTS: Minimum amount of payments made by user  
- PRC_FULL_PAYMENT: Percent of full payment paid by user
- TENURE: Tenure of credit card service for user

### Techniques and Tools
- **K-means Clustering**: Used to segment customers into distinct groups.
- **Data Visualization**: Libraries such as Matplotlib and Seaborn were used to visualize the results.
- **Python**: The entire project is implemented in Python, utilizing libraries like Pandas, NumPy, Scikit-learn, and others.

## Repository Structure

- `Bank_Customer_Segmentation`: Contains the Jupyter notebook with the code and analysis.
- `marketing_data`: Includes the dataset used for the project.
- `README.md`: This file, providing an overview of the project.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/devanshisaraf/Customer-Market-Segmentation-using-Unsupervised-Machine-Learning.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Customer-Market-Segmentation-using-Unsupervised-Machine-Learning
   ```

### Running the Project
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the notebook `Bank_Customer_Segmentation` and run the cells to see the analysis and results.

## Results
The project successfully segmented customers into distinct groups. Visualizations and detailed analysis can be found in the notebooks, providing insights into the characteristics of each segment.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Any contributions are welcome!

## Acknowledgements
- Coursera and the instructors of the "Unsupervised Machine Learning for Customer Market Segmentation" course.
- The open-source community for providing the tools and libraries used in this project.
