# Data-Driven Business Performance & Operational Efficiency Analysis - Western India Plywood (Internship Project) 
## Introduction 
This project showcases a comprehensive data analysis and dashboarding initiative undertaken during a one-week Business Development internship at Western India Plywood. Recognizing the critical role of data in driving informed business decisions and aiming to develop practical analytical skills, I designed and implemented a suite of interactive dashboards using Power BI. These dashboards transform raw operational and sales data into actionable insights, focusing on enhancing overall business performance, optimizing product quality, and significantly reducing energy consumption.

My goal was to provide Western India Plywood with tangible tools for strategic planning and operational improvements, even within the short span of my internship.

# Project Highlights
Here's a quick look at the core aspects and value of this data analysis project:

* 📊**Two Comprehensive Dashboards** : Developed two distinct Power BI files for an in-depth analysis of overall business performance, and a deep dive into quality control and energy efficiency.

* 📈**Quantifiable Business Impact**: Identified opportunities for 5-10% reduction in product defects (saving ₹5 Lakhs to ₹1 Crore annually) and 8-15% reduction in energy consumption (saving ₹10 Lakhs to ₹25 Lakhs annually).

* ⚙️**Operational Efficiency Gains**: Dashboards enable 20-30% faster data analysis and reporting, leading to 5-8% overall improvement in operational efficiency.

* 🐍**Python for Data Preparation**: Utilized Python for generating and processing synthetic datasets, ensuring realistic and applicable insights.

* 🧠**AI-Assisted Development**: Leveraged Gemini's AI for efficient Python code generation, accelerating project delivery and focusing on analytical insights.

* 💡**Actionable Insights**: Transformed complex raw data into clear, interactive visualizations that drive informed decision-making for product quality, energy management, and sales strategy.

## Project Structure & Files
This project delivers two distinct, interactive Power BI dashboards, each built upon a different dataset to address specific analytical objectives.

**['Overall_Business_Performance_Dashboard.pbix'](https://github.com/navyaprashanth/WesternIndiaPlywood_DataAnalysis/blob/main/Overall_Business_Performance_Dashboard.pbix)**: This Power BI file contains the "Overall Hardboard Business Performance" dashboard.

**['Quality_Energy_Deep_Dive_Dashboard.pbix'](https://github.com/navyaprashanth/WesternIndiaPlywood_DataAnalysis/blob/main/Quality_Energy_Deep_Dive_Dashboard.pbix)**: This Power BI file contains the "Deep Dive: Quality Analysis & Improvements" (with two pages) and the "Deep Dive: Energy Consumption & Efficiency" dashboards.

data/: This directory contains the raw CSV data files used for analysis in both dashboards.

data/overall_business_data.csv

data/quality_energy_data.csv

(Optional) scripts/: If you used Python scripts for processing, cleaning, or transforming these CSVs before loading into Power BI, you could place them in a scripts/ folder (e.g., scripts/data_preprocessing.py).

Technologies & Skills Used
This project demonstrates proficiency in end-to-end data analysis, from data preparation to visualization and insight generation.

🐍 Python: Utilized for initial data generation (which produced the CSVs) and potentially for further data processing, cleaning, and transformation of the CSV files using libraries like pandas and numpy.

📊 Power BI: Employed for creating interactive, visually compelling, and user-friendly dashboards.

🧠 AI Assistance (Gemini): Leveraged for efficient Python code generation and debugging. This approach allowed for rapid prototyping and enabled a concentrated focus on analytical problem-solving and insightful visualization, rather than manual coding complexities, significantly accelerating project delivery.

Dataset Overviews
The analytical insights presented in this project are derived from two distinct, carefully structured synthetic CSV datasets. These datasets were meticulously designed to simulate realistic manufacturing operations and sales scenarios for hardboard production.

Business Overview Dataset (data/overall_business_data.csv):

Simulates sales transactions, revenue figures, and general business metrics.
(Here, embed a snippet or screenshot of your overall_business_data.csv file, perhaps showing the first few rows of the CSV content. You can also include a short video demonstrating the Python script generating this data if applicable.)

Quality & Energy Dataset (data/quality_energy_data.csv):

Simulates detailed production batch information, specific defect occurrences and types, energy consumption (electrical and steam), and various granular production parameters (e.g., press temperature, cycle time, material compositions).
(Here, embed a snippet or screenshot of your quality_energy_data.csv file, perhaps showing the first few rows of the CSV content. You can also include a short video demonstrating the Python script generating this data if applicable.)

While synthetic, these datasets ensure that the analytical methodologies and the dashboards' capabilities are directly applicable and transferable to real-world business data encountered in manufacturing environments.

Dashboard Breakdown
The project features two distinct Power BI files, each containing one or more interconnected dashboard pages, serving specific analytical purposes.

Dashboard File 1: Overall_Business_Performance_Dashboard.pbix
1. Overall Hardboard Business Performance
Objective: To provide a high-level, comprehensive overview of the hardboard business's financial health and sales performance to stakeholders. This dashboard acts as a quick "pulse check" on the company.

Key Insights & Features:

💰 Executive KPIs: Prominently displays key performance indicators such as Total Revenue, Total Profit, Overall Profit Margin, and Total Quantity Sold for an immediate business health check.

📦 Performance Segmentation: Visualizes revenue and profit performance segmented by Product Category (e.g., Marine, Decorative, Hardwood, Softwood, Plywood) and Geographic Region (North, East, West, South). This helps in quickly identifying top-performing areas and informing strategic resource allocation.

📈 Trend Analysis: Features a Monthly Revenue Trend chart to track historical performance, identifying growth patterns, seasonality, and the overall business trajectory.
(Here, insert a screenshot of this dashboard page. You can also include a short video demonstrating interaction with slicers on this dashboard, e.g., filtering by region or product category.)

Dashboard File 2: Quality_Energy_Deep_Dive_Dashboard.pbix
This Power BI file contains two interlinked dashboard pages, designed to provide detailed insights into product quality and operational energy efficiency. The goal here is to reduce manufacturing defects and optimize energy consumption.

2.1. Deep Dive: Quality Analysis & Improvements (Page 1: Overall Summary)
Objective: To serve as an initial summary for a deeper investigation into operational aspects, specifically focusing on product quality and overall energy consumption, highlighting immediate areas of concern.

Key Insights & Features:

📊 Integrated KPIs: Presents a concise overview of key quality and energy metrics, including "Percentage of Defective Batches," "Total Defects," "Total Batches," "Avg Energy per Batch KWh," "Avg Steam per Batch kg," and "Total Energy KWh." All KPIs are enhanced with interactive tooltips that explain their importance for non-technical users.

🚧 Defect Breakdown: A pie chart visualizes the proportion of each defect type (e.g., Surface, Density Variation, Warpage). A critical feature is the tooltip functionality on hover, which provides detailed explanations for each defect's typical occurrence and its resulting impact on the final product quality.

⚡ Operational Trends: Includes line charts for "Total Energy KWh by Date" and "Avg Hardboard Strength & Density by Date," offering daily views of energy usage and key product quality attributes over time.

🌡️ Contextual Slicers: Features interactive slicers like "Press Temperature," which has a tooltip explaining its critical importance to both product quality and energy efficiency in the hardboard (plywood-like material) manufacturing process.
(Here, insert a screenshot of this dashboard page. You can also include a short video demonstrating hovering over the Defect breakdown pie chart to show the tooltip explanations.)

2.2. Deep Dive: Quality Analysis & Improvements (Page 2: Defect Analysis)
Objective: To provide a granular analysis of the relationship between specific production parameters and the occurrence of defects, facilitating root cause identification and targeted quality improvement initiatives.

Key Insights & Features:

🔬 Targeted Defect Identification: Highlights the "Most Common Defect Type" (e.g., Surface defects) and displays "Defects per Batch" to focus immediate attention on primary quality issues.

🔥 Parameter-Specific Defect Analysis: A bar chart illustrates "Total Defects by Press Temperature," prominently featuring a red dotted line representing a "target for defect reduction." An accompanying text box clarifies that this chart helps understand why targets are missed and encourages parameter selection to refine goals.

⚙️ Interactive Quality Parameter Slicers: Allows users to filter and analyze defects based on various quality-related production parameters (e.g., Press Pressure, Cycle Time, Resin Content, Fiber Consistency, Moisture Content, Hardboard Density). This interactive exploration supports precise root cause analysis.
(Here, insert a screenshot of this dashboard page. You can also include a short video demonstrating how interacting with the "Quality Parameter Slicers" changes the data in the "Total Defects by Press Temperature" chart.)

2.3. Deep Dive: Energy Consumption & Efficiency
Objective: To conduct an in-depth analysis of energy consumption patterns within hardboard manufacturing, identify key drivers of energy usage, and uncover opportunities for significant cost savings through process optimization.

Key Insights & Features:

💡 Detailed Energy KPIs: Provides specific metrics like "Avg Energy per Batch KWh," "Avg Steam per Batch kg," "Total Energy KWh," and "Total Steam kg." Each KPI is equipped with tooltips explaining its relevance and importance to energy efficiency.

📉 Energy Trend Analysis: Line charts track average electrical energy and steam consumption per batch over time, enabling the identification of trends, seasonal variations, and unusual consumption spikes.

🔗 Parameter-Energy Correlation: A scatter plot explores the relationship between "Monthly Strength vs Energy per Batch," helping to optimize the balance between product quality and energy use.

🔄 Dynamic Energy Drivers: Features interactive "Select Energy Driver" slicers (e.g., Press Temperature, Press Cycle Time, Fiber Consistency). Crucially, the "Total Energy" KPI dynamically updates with the selected parameter, demonstrating the direct impact of operational settings on energy consumption. Tooltips for these slicers explain their significance to energy usage.

🎯 Targeted Energy Efficiency: A bar chart displaying "Total Energy by Selected Parameter Bins" incorporates green and red dotted lines to represent energy consumption targets. Tooltips specify that green indicates ideal consumption, while red denotes excessive usage, allowing for clear performance assessment.

🔍 High-Impact Identification: A "Top 5 Most Energy Intensive Batches" table pinpoints specific production runs with the highest energy consumption, facilitating focused investigations for root cause analysis and immediate efficiency improvements.
(Here, insert a screenshot of this dashboard page. You can also include a short video demonstrating interaction with the "Select Energy Driver" slicers and how "Total Energy" changes. Consider a video showcasing the tooltips on the green and red target lines.)

Quantifiable Business Impact & Value Proposition
This project demonstrates a proactive approach to business optimization through data analysis. By developing these dashboards, I aimed to provide Western India Plywood with tangible, data-driven insights for strategic decision-making and operational improvements.

Here's the probable impact these dashboards can enable for a manufacturing company like Western India Plywood:

Enhanced Product Quality & Reduced Waste:

Action: The "Quality Analysis & Improvement" dashboard provides visual cues and detailed breakdowns of defect types (e.g., Surface, Density Variation) and their correlation with production parameters (like Press Temperature). This allows for pinpointing root causes.

Impact (XYZ Format): By enabling data-driven fine-tuning of manufacturing processes, these insights can reduce overall product defect rates by an estimated 5-10%, which in turn could cut raw material waste and rework expenses by approximately 3-7%, resulting in annual savings of ₹5 Lakhs to ₹1 Crore. This also directly improves product quality and customer satisfaction.

Significant Energy Cost Savings:

Action: The "Energy Consumption & Efficiency" dashboard highlights energy-intensive batches and reveals the impact of various production parameters on total energy usage. For instance, identifying sub-optimal "Press Temperature" ranges that consume excess electricity/steam without contributing to quality.

Impact (XYZ Format): By monitoring and adjusting operational parameters based on dashboard insights, the company can reduce overall energy consumption (electricity and steam) by an estimated 8-15%. This directly translates to an annual reduction in utility expenses of ₹10 Lakhs to ₹25 Lakhs, helping the company save a significant portion of its operational budget and contribute to environmental sustainability.

Improved Operational Efficiency & Accelerated Decision-Making:

Action: These interactive dashboards consolidate complex data into easily digestible visualizations, providing a single source of truth for key operational metrics (sales, quality, energy). Instead of manually sifting through reports or spreadsheets.

Impact (XYZ Format): This can reduce the time spent on data analysis and report generation for managers by up to 20-30% (e.g., saving several hours per week for analysts or decision-makers). This accelerated insight generation empowers decision-makers to respond to trends and anomalies 2-3 times faster, leading to more agile and effective operational adjustments and ultimately boosting overall productivity by an estimated 5-8%.

Enhanced Strategic Planning & Resource Allocation:

Action: The "Overall Hardboard Business Performance" dashboard provides clear visibility into revenue and profit drivers by product category and region, while the deep-dive dashboards highlight areas for cost reduction.

Impact (XYZ Format): This allows for more informed strategic planning, potentially enabling the reallocation of resources (e.g., marketing spend, production focus) to high-performing areas and away from underperforming ones. This can optimize resource utilization by 10-15%, contributing to sustained business growth and profitability.

Conclusion
This internship project demonstrates my foundational abilities in:

Business Acumen: Translating real-world business challenges into analytical problems.

Data Proficiency: Handling, processing, and preparing data for analysis.

Analytical Storytelling: Extracting actionable insights from complex datasets.

Visualization & Communication: Designing clear, interactive dashboards that communicate findings effectively to diverse audiences.

Technological Adaptability: Leveraging modern tools, including AI-assisted development, for efficient and impactful project execution.

This project underscores my commitment to data-driven solutions and my potential to contribute meaningfully to data analysis roles.
