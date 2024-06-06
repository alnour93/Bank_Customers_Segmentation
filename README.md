# Credit Card Usage Clustering Analysis

## Overview

This project involves analyzing credit card usage data by clustering customers based on their behaviors and usage patterns. The data has been segmented into four distinct clusters, each characterized by unique patterns in attributes such as balance, purchases, cash advances, payments, and credit limits.

## Dataset

The dataset consists of the following attributes:
- **BALANCE**: The balance amount on the card.
- **BALANCE_FREQUENCY**: Frequency of balance checking.
- **PURCHASES**: Total amount of purchases.
- **INSTALLMENTS_PURCHASES**: Amount of purchases made in installments.
- **CASH_ADVANCE**: Amount of cash advances taken.
- **PURCHASES_FREQUENCY**: Frequency of purchases.
- **ONEOFF_PURCHASES_FREQUENCY**: Frequency of one-off purchases.
- **CASH_ADVANCE_FREQUENCY**: Frequency of cash advances.
- **CASH_ADVANCE_TRX**: Number of cash advance transactions.
- **PURCHASES_TRX**: Number of purchase transactions.
- **CREDIT_LIMIT**: Credit limit on the card.
- **PAYMENTS**: Total payments made.
- **MINIMUM_PAYMENTS**: Minimum payments made.
- **PRC_FULL_PAYMENT**: Percentage of full payments made.
- **TENURE**: Tenure of the credit card account.
- **cluster**: Cluster label assigned to each entry.

## Clusters Description

### Overall Description of the Clusters

1. **Cluster 0**: Comprises 3192 entries
2. **Cluster 1**: Comprises 4149 entries
3. **Cluster 2**: Comprises 309 entries
4. **Cluster 3**: Comprises 1300 entries

### Cluster Details

#### Cluster 0
- **Number of Entries**: 3192
- **Behavior**:
  - Moderate balance with regular purchases.
  - High balance frequency indicating frequent checking of balance.
  - Lower cash advances compared to other clusters.
  - High purchases frequency, often involving installment purchases.
  - Generally have higher credit limits.
  - Regular payments with notable minimum payments.
  - Low full payment percentage.

#### Cluster 1
- **Number of Entries**: 4149
- **Behavior**:
  - Lower balance compared to other clusters.
  - High balance frequency indicating regular balance checking.
  - Very low purchases, with very few installments.
  - Minimal or no cash advances.
  - Very low purchases frequency, suggesting infrequent use of credit for purchases.
  - Generally lower credit limits.
  - Irregular payments and often lower minimum payments.
  - Low or no full payment percentage, indicating that full balance is seldom paid off.

#### Cluster 2
- **Number of Entries**: 309
- **Behavior**:
  - High balance with very frequent purchases.
  - Extremely high balance frequency indicating daily or near-daily checking.
  - High one-off purchase frequency and large number of transactions.
  - No cash advances.
  - Generally have higher credit limits.
  - Regular and substantial payments with high minimum payments.
  - Low full payment percentage.

#### Cluster 3
- **Number of Entries**: 1300
- **Behavior**:
  - Very high cash advances compared to all other clusters.
  - Low balance frequency indicating infrequent checking of balance.
  - Minimal purchases and installment purchases.
  - Regular cash advance transactions.
  - Lower number of purchase transactions.
  - Generally have moderate credit limits.
  - Regular but often substantial payments with high minimum payments.
  - Moderate full payment percentage, indicating occasional full payment of the balance.

## Summary

- **Cluster 0**: Regular users with moderate usage and frequent payments.
- **Cluster 1**: Low usage, low balance users who rarely use credit for purchases.
- **Cluster 2**: High balance, frequent purchasers with regular and substantial payments.
- **Cluster 3**: High cash advance users with infrequent checking of balance and minimal purchases.

## Usage

To understand and analyze customer behaviors based on credit card usage data, this clustering analysis can be beneficial for:

- Identifying different segments of customers.
- Tailoring marketing strategies to specific customer groups.
- Managing credit risk by understanding customer usage patterns.

## Contact

For any questions or feedback, please contact [Your Name] at [your email address].
