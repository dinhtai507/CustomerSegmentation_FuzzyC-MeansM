# Customer Segmentation using Fuzzy C-Means and Analytic Hierarchy Process (AHP)
CustomerSegmentation_FuzzyC-Means is a customer segmentation project that employs the Fuzzy C-Means clustering algorithm along with the Analytic Hierarchy Process (AHP). This methodology combines two powerful techniques to categorize a customer base into distinct groups based on their characteristics and preferences. The integration of Fuzzy C-Means allows for flexible membership assignments, accommodating customers with varying degrees of similarity, while AHP aids in prioritizing and weighting different criteria.

## Overview
This project aims to analyze Olist store data spanning 2016 to 2018 to formulate a market strategy using customer segmentation based on the RFM model. The key project steps include:

1. **Data Loading and Preprocessing:** Utilizing Python to ensure data quality and prepare it for effective analysis.

2. **Data Visualization with Tableau:** Employing Tableau to visualize and extract insights from the data.

3. **Customer Segmentation with Hybrid RFM and Fuzzy C-means:** Applying a hybrid approach that combines the RFM model with Fuzzy C-means clustering for accurate segmentation.

4. **Analytic Hierarchy Process (AHP):** Calculating weights for Recency (R), Frequency (F), and Monetary Value (M) criteria using AHP.

5. **Customer Lifetime Value (CLV) Calculation:** Using the derived weights to compute CLV for each customer segment.

The ultimate goal is to leverage RFM model-based customer segmentation and CLV to craft a tailored marketing strategy for diverse customer segments. Additionally, the project involves the implementation of targeted email marketing campaigns through Mailchimp to enhance the overall market strategy.

## Methodology

### Fuzzy C-Means Clustering
![image](https://github.com/dinhtai507/CustomerSegmentation_FuzzyC-Means/assets/101158366/1e72c5a8-2c57-4ae0-a92c-fc5e36fecd8d)

Fuzzy C-Means is a clustering algorithm that assigns customers to clusters based on their similarity. Unlike traditional hard clustering techniques, Fuzzy C-Means allows for overlapping membership, recognizing that customers may exhibit characteristics that span multiple segments. This flexibility is particularly valuable in situations where customers cannot be exclusively assigned to a single group due to ambiguous or diverse preferences.

### Analytic Hierarchy Process (AHP)
![image](https://github.com/dinhtai507/CustomerSegmentation_FuzzyC-Means/assets/101158366/4f1731d4-bc19-49af-9ee0-abd7bf003482)

The Analytic Hierarchy Process is a decision-making framework used to prioritize and weight different criteria in a hierarchical structure. In the context of customer segmentation, AHP assists in determining the importance of various segmentation variables. This hierarchical approach enables businesses to consider and balance multiple factors when defining customer segments.
### Customer Lifetime Value (CLV) Calculation

Customer Lifetime Value (CLV) is a pivotal metric in business and marketing that gauges the total revenue a business can anticipate earning from a customer over the entire duration of their relationship. This metric offers valuable insights into the long-term profitability of a customer, guiding businesses in making informed decisions related to customer acquisition costs, retention strategies, and overall marketing investments. Once the weights are established, they are applied to compute the CLV for each customer segment. This calculated CLV serves as a critical metric for understanding the long-term value of each customer group, assisting in the development of targeted marketing strategies. The overarching goal is to leverage insights gained from customer segmentation and CLV to tailor marketing efforts, thereby maximizing customer satisfaction and optimizing marketing resources.
In summary, Customer Lifetime Value is a powerful metric that aids businesses in understanding the long-term value of their customers, enabling strategic decision-making to enhance customer relationships and maximize profitability.

![image](https://github.com/dinhtai507/CustomerSegmentation_FuzzyC-Means/assets/101158366/ccadcaa0-2fcf-4db0-ae59-0b40f0e0d7ab)


## Business Benefits
By integrating Fuzzy C-Means and AHP, businesses can achieve the following benefits:

- **Enhanced Marketing Strategies:** The ability to assign customers to multiple groups allows for diverse and tailored marketing strategies based on their memberships in different clusters.

- **Personalized Offerings:** Understanding the diverse needs and preferences of the customer base enables businesses to personalize their offerings, leading to improved customer satisfaction.

## Why Fuzzy C-Means?

Hard segmentation techniques like K-Means may not be effective in scenarios where customers possess ambiguous characteristics. Fuzzy C-Means addresses this limitation by allowing customers to have varying degrees of membership in each cluster. This capability is essential for businesses aiming to cater to a customer base with diverse and nuanced preferences.

## Implementation

To implement this project, follow the instructions in the [Installation Guide](./INSTALL.md). Make sure to customize the parameters and criteria according to your specific business context.

## License

This project is licensed under the [License] - see the [LICENSE.md](./LICENSE.md) file for details.
