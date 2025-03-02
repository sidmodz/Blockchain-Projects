# **Ethereum Transaction Analysis (November 8-14, 2017)**

## **Overview**
This project analyzes Ethereum blockchain transactions over a one-week period (November 8-14, 2017). The dataset is sourced from Blockchair and contains detailed transaction records, including block IDs, timestamps, transaction values, fees, and gas usage. The analysis provides insights into transaction trends, fees, and block creation patterns.

## **Dataset**
The dataset consists of seven `.tsv` files, each representing one day's worth of Ethereum transactions. These files are merged into a single DataFrame for analysis.

## **Key Analyses**

### **1. Data Loading and Preprocessing**
- Merging daily transaction data into a single DataFrame.
- Extracting relevant columns and converting data types for analysis.

### **2. Transaction and Block Statistics**
- Counting the total number of transactions and unique blocks.
- Analyzing the number of transactions per block and summarizing transaction fees.
- Computing the average transaction fee per day and hour.

### **3. Temporal Analysis**
- Daily and hourly distribution of transactions.
- Total number of blocks created each day and each hour.
- Visualizing transaction activity trends over time.

### **4. Ethereum Price Trend**
- Calculating the Ethereum price (USD per Ether) based on transaction values.
- Analyzing the daily average Ethereum price throughout the week.

## **Visualizations**
- Bar charts for daily and hourly transaction counts.
- Average transaction fees by day and hour.
- Block creation frequency over time.
- Ethereum price trends during the analysis period.

   ```

