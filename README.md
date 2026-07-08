FedEx-Logistics-Performance-Analysis-in-Python (EDA)---End-to-End-Project

Project Type  - EDA/Regression/Classification/Unsupervised

**Project Summary**

FedEx is one of the world’s largest and most trusted logistics and transportation companies, known for its global express shipping network, innovation in supply chain solutions, and commitment to reliable, time-bound delivery services. Operating across more than 220 countries and territories, FedEx manages millions of shipments every day through a complex ecosystem of air, ground, and freight operations. In such a vast and high-velocity logistics environment, performance monitoring is essential to ensure on-time delivery, cost efficiency, and continuous improvement. This project, FedEx Logistics Performance Analysis, focuses on evaluating key operational metrics that influence delivery reliability, shipping cost structures, vendor efficiency, and overall supply chain effectiveness.

The dataset provided contains detailed shipment history information such as delivery-related dates, freight charges, weight, product descriptions, vendors, shipment modes, and route destinations. These data points enable a comprehensive assessment of FedEx’s logistics performance from request generation to final delivery. The goal of this analysis is to transform the dataset into meaningful insights that reflect service quality, operational bottlenecks, cost drivers, and shipment trends.

To prepare the dataset for analysis, several data cleaning and transformation steps were performed. Date fields with inconsistent or non-standard entries were standardized and converted into proper datetime formats. Numerical columns such as freight cost and weight, which may contain text-based inconsistencies, were cleaned and cast into usable numeric types. New variables were engineered to capture logistics KPIs—such as lead times between procurement stages, schedule delays, delivery timeliness, cost per kilogram, freight-to-commodity value ratios, and monthly or yearly time indicators. These transformed metrics allow for robust comparisons and trend analysis across routes, vendors, shipment modes, and product categories.

The core of this project centers on evaluating FedEx’s logistics KPIs across four major dimensions:

Service Performance:
On-time delivery rate, average lead time, delay duration, and timeliness score provide insights into service reliability. These KPIs help identify countries or regions where FedEx faces delivery challenges and shipment modes that consistently perform better or worse.

Cost Efficiency:
Logistics cost analysis includes total freight spend, freight cost per kilogram, and freight cost as a proportion of total shipment value. These metrics reveal how efficiently FedEx manages transportation costs and highlight potential optimization opportunities, such as evaluating weight-based cost disparities or high-cost vendor relationships.

Shipment Volume and Operational Load:
Trends in shipment counts, total quantity delivered, and monthly shipment value reflect workload distribution and seasonal demand patterns. This analysis helps identify peak periods, route congestion, and capacity planning requirements within FedEx’s operations.

Vendor, Route, and Product Performance:
Vendor-wise performance indicators reveal whether certain partners contribute to delays or higher freight costs. Country and route-level analysis exposes geographic challenges and opportunities. Product-level insights, based on product group or classification, show which items drive the most value, weight, or complexity within the logistics chain.

Visualizations—including interactive time series plots, cost vs. performance scatter charts, boxplots for lead times by shipment mode, bar charts for country-wise KPIs, and distribution analyses—translate the dataset into intuitive, decision-ready insights. Correlation heatmaps further uncover relationships between freight cost, value, weight, and delivery timelines.

Overall, this project provides a detailed and data-driven evaluation of FedEx’s logistics performance, highlighting areas of operational excellence along with systemic inefficiencies. By turning raw shipment data into actionable insights, the analysis supports strategic decision-making for improving delivery reliability, optimizing freight costs, strengthening vendor management, and enhancing FedEx’s global supply chain efficiency. This performance analysis ultimately reinforces FedEx’s mission to deliver every shipment with speed, accuracy, and guaranteed reliability.


**Problem Statement**

FedEx manages a high volume of global shipments, making it essential to continuously evaluate logistics performance to ensure timely deliveries and cost-efficient operations. However, variations in delivery times, freight costs, vendor performance, and shipment modes can create inefficiencies that impact service quality and operational expenses. This project aims to analyze historical shipment data to identify delays, cost drivers, performance gaps, and operational trends within FedEx’s logistics network. By transforming raw delivery records into actionable KPIs, the analysis seeks to uncover patterns affecting reliability and efficiency. The ultimate objective is to provide data-driven insights that support strategic decision-making and improve FedEx’s overall logistics performance.

**Business Objective**

The primary objective of this project is to evaluate FedEx’s logistics performance using historical shipment data to identify operational inefficiencies and areas for improvement. By analyzing delivery timelines, freight costs, shipment modes, and vendor performance, the goal is to uncover patterns that influence service reliability and cost-effectiveness. This analysis aims to generate meaningful KPIs that measure lead times, on-time delivery rates, and logistics cost efficiency across regions and product categories. Insights from the study will help FedEx optimize transportation strategies, reduce delays, lower operational costs, and enhance customer satisfaction. Ultimately, the objective is to support data-driven decision-making for strengthening FedEx’s global supply chain operations.
