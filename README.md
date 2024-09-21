# Amazon Delivery Data Analysis

## Project Overview
This project analyzes real Amazon delivery data to derive insights into factors influencing delivery times. By employing techniques such as PCA (Principal Component Analysis), K-means clustering, and correlation analysis, we aim to identify key drivers of delivery efficiency.

## Data Used
The dataset consists of various features related to delivery, including:
- **Agent_Age**: Age of the delivery agent.
- **Agent_Rating**: Rating of the agent by customers.
- **Delivery_Time**: Time taken for delivery.
- **Distance**: Distance of the delivery.
- **Weather_encoded**: Encoded representation of weather conditions.
- **Traffic_encoded**: Encoded representation of traffic conditions.
- **Vehicle_encoded**: Type of vehicle used for delivery.
- **Area_encoded**: Area from which the delivery is made.
- **Category_encoded**: Category of the delivered item.

## Key Insights
1. **Agent Rating**:
   - There is a strong negative correlation (-0.31) between agent ratings and delivery times, indicating that higher-rated agents deliver faster.

2. **Agent Age**:
   - A positive correlation (0.26) with agent age suggests that older agents may take longer to complete deliveries.

3. **Cluster Analysis**:
   - K-means clustering reveals distinct groups of deliveries, with certain characteristics correlating to longer delivery times.

4. **Impact of Weather and Traffic**:
   - Both weather and traffic have slight negative correlations with delivery time, suggesting these external factors can influence delivery efficiency.

## Proposal
**Proposal**: "Improving agent training and support for older agents will significantly reduce delivery times, particularly for those with lower agent ratings."

This proposal suggests that targeted training programs for agents, especially older ones, could enhance overall delivery efficiency.

## Conclusion
The analysis provides valuable insights into how agent characteristics and external factors influence delivery times. Implementing targeted strategies based on these findings could enhance operational efficiency and improve customer satisfaction.

## Future Work
Further research could explore real-time data integration for traffic and weather conditions, and implement training programs to test the effectiveness of the proposal.

## Acknowledgments
This project utilizes real Amazon delivery data and aims to contribute to better understanding and improvement of delivery operations.
