# FedEx-Logistics-Performance-Analysis
### GitHub Project Description  FedEx Global Supply Chain Analytics: A project to optimize logistics, reduce costs, and enhance customer satisfaction through in-depth data analysis. It identifies bottlenecks, assesses vendor performance, and offers actionable insights for streamlining operations.


FedEx Global Supply Chain Analytics
📝 Overview
This project provides a comprehensive data-driven analysis of FedEx's global supply chain operations. Utilizing a dataset detailing shipment history, we perform a series of analytical steps to uncover key insights related to cost, delivery performance, and operational efficiency. The goal is to provide actionable recommendations that can help FedEx Logistics optimize its business processes, reduce costs, and enhance customer satisfaction.

🧰 Tools & Technologies
Python: The core programming language for the analysis.

Pandas: Used for data manipulation, cleaning, and preparation.

NumPy: A fundamental library for numerical operations.

Matplotlib & Seaborn: Used for creating visualizations to represent key findings.

Jupyter Notebook / Google Colab: The environment used to perform and document the analysis.

📊 Key Analyses & Findings
The analysis was structured around three key business themes:

Delivery Timeliness and Performance
Analysis: We created a Delivery Delay (Days) feature to measure on-time performance.

Insight: Ocean shipments have a significantly higher average delay compared to Air and Truck, indicating a key area for operational improvement.

Cost-Effectiveness and Vendor Performance
Analysis: We examined the relationship between item value, weight, and freight cost, and compared costs across different vendors and fulfillment methods.

Insight: Direct Drop fulfillment is substantially more expensive than using a Regional Distribution Center (RDC). Furthermore, specific countries and vendors were identified as having higher average freight costs.

Operational Bottlenecks
Analysis: We aggregated data by country, product, and vendor to pinpoint areas of inefficiency.

Insight: Certain vendors and high-volume delivery countries are associated with a higher risk of delays, which can serve as a starting point for strategic vendor management and logistics planning.

🚀 Recommendations
Based on our findings, we recommend the following actions for FedEx Logistics:

Strategic Routing: Prioritize using RDC fulfillment over Direct Drop to achieve significant cost savings.

Vendor Management: Proactively engage with underperforming vendors to improve delivery timelines and mitigate operational risks.

Performance Monitoring: Implement a real-time dashboard to monitor delivery delays and freight costs, enabling continuous optimization of the supply chain.

📁 Repository Structure
SCMS_Delivery_History_Dataset.csv: The raw dataset used for this project.

README.md: This file, providing an overview of the project.

Analysis_Notebook.ipynb: A Jupyter Notebook containing all the Python code for data wrangling, analysis, and visualizations.

📈 Visualizations
The analysis includes a variety of charts to present the findings, such as:

Histogram of delivery delays.

Bar charts comparing average delays and costs by shipment mode and country.

Scatter plots showing the relationship between cost, weight, and item value.

Pie charts illustrating the distribution of products and vendor terms.
