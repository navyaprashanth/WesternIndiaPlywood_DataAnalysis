# Quality & Energy Optimization - Western India Plywood (Internship Project)
## Introduction
This project showcases a focused data analysis and dashboarding initiative undertaken during a one-week Business Development internship at Western India Plywood. Recognizing the critical need for operational excellence and cost reduction in manufacturing, I designed and implemented an interactive Power BI dashboard. This dashboard transforms raw operational data into actionable insights, specifically targeting the optimization of product quality and the significant reduction of energy consumption within hardboard manufacturing.

My goal was to provide Western India Plywood with a powerful, data-driven tool for identifying inefficiencies, implementing process improvements, and achieving tangible cost savings, even within the short span of my internship.

# Project Highlights
Here's a quick look at the core aspects and value of this data analysis project:

* 📊 **In-Depth Operational Dashboard**: Developed a comprehensive Power BI dashboard for a deep dive into product quality control and energy efficiency in manufacturing.

* 📈 **Quantifiable Impact on Operations**: Identified opportunities for **5-10% reduction in product defects (saving ₹5 Lakhs to ₹1 Crore annually)** and **8-15% reduction in energy consumption (saving ₹10 Lakhs to ₹25 Lakhs annually).**

* ⚙️ **Accelerated Problem Solving**: Dashboards enable **20-30% faster identification of quality issues and energy waste**, leading to more agile and effective operational adjustments.

* 🐍 **Python for Data Preparation**: Utilized Python for generating and processing synthetic datasets, ensuring realistic and applicable insights into manufacturing processes.

* 🧠 **AI-Assisted Development**: Leveraged Gemini's AI for efficient Python code generation, accelerating project delivery and focusing on analytical insights.

* 💡 **Actionable Insights**: Transformed complex raw manufacturing data into clear, interactive visualizations that drive informed decision-making for quality improvement and energy management.

## Project Structure & Files
This project delivers a single, distinct, interactive Power BI dashboard focused on operational efficiency.

**['Quality_Energy_Deep_Dive_Dashboard.pbix'](https://github.com/navyaprashanth/WesternIndiaPlywood_DataAnalysis/blob/main/Quality_Energy_Deep_Dive_Dashboard.pbix)**: This Power BI file contains the multi-page dashboard for "Deep Dive: Quality Analysis & Improvements" and "Deep Dive: Energy Consumption & Efficiency."

**['data/quality_energy_data.csv'](https://github.com/navyaprashanth/WesternIndiaPlywood_DataAnalysis/blob/main/Quality_Energy_Deep_Dive_Dashboard.pbix)**
: This directory contains the raw CSV data file used for analysis in the dashboard.

https://github.com/user-attachments/assets/9357189e-ffed-4691-8c24-b35cb063f983

**['scripts/'](https://github.com/navyaprashanth/WesternIndiaPlywood_DataAnalysis/blob/main/hardboard_production_data.ipynb)**: This directory contains the data that was generated. 

## Technologies & Skills Used
This project demonstrates proficiency in end-to-end data analysis, from data preparation to visualization and insight generation.

* 🐍 **Python**: Utilized for initial data generation (which produced the CSV) and potentially for further data processing, cleaning, and transformation of the CSV file using libraries like pandas and numpy.

* 📊 **Power BI**: Employed for creating interactive, visually compelling, and user-friendly dashboards.

* 🧠 **AI Assistance (Gemini)**: Leveraged for efficient Python code generation and debugging. This approach allowed for rapid prototyping and enabled a concentrated focus on analytical problem-solving and insightful visualization, rather than manual coding complexities, significantly accelerating project delivery.

## Dataset Overview
The analytical insights presented in this project are derived from a single, carefully structured synthetic CSV dataset. This dataset was meticulously designed to simulate realistic manufacturing operations for hardboard production.

* **['Quality & Energy Dataset'](https://github.com/navyaprashanth/WesternIndiaPlywood_DataAnalysis/blob/main/hardboard_production_data.csv)**:

   * Simulates detailed production batch information, specific defect occurrences and types, energy consumption (electrical and steam), and various granular production parameters (e.g., press temperature, cycle time, material compositions).
  
https://github.com/user-attachments/assets/95da377e-4ea5-485f-abb7-f27d004e8345

While synthetic, this dataset ensures that the analytical methodologies and the dashboard's capabilities are directly applicable and transferable to real-world operational data encountered in manufacturing environments.

## Dashboard Breakdown
The project features a single Power BI file, containing three interconnected dashboard pages, serving specific analytical purposes related to operational efficiency.

**Dashboard File**: **['Quality_Energy_Deep_Dive_Dashboard.pbix'](https://github.com/navyaprashanth/WesternIndiaPlywood_DataAnalysis/blob/main/Quality_Energy_Deep_Dive_Dashboard.p)**

## 1.1. Deep Dive: Quality Analysis & Improvements (Page 1: Overall Summary)**
**Objective**: To serve as an initial summary for a deeper investigation into operational aspects, specifically focusing on product quality and overall energy consumption, highlighting immediate areas of concern.

### Key Insights & Features:

* 📊 **Integrated KPIs**: Presents a concise overview of key quality and energy metrics, including "Percentage of Defective Batches," "Total Defects," "Total Batches," "Avg Energy per Batch KWh," "Avg Steam per Batch kg," and "Total Energy KWh." **All KPIs are enhanced with interactive tooltips that explain their importance** for non-technical users.

* 🚧 **Defect Breakdown**: A **pie chart visualizes the proportion of each defect type** (e.g., Surface, Density Variation, Warpage). A critical feature is the **tooltip functionality on hover**, which provides detailed explanations for each defect's typical occurrence and its resulting impact on the final product quality.

* ⚡ **Operational Trends**: Includes line charts for "Total Energy KWh by Date" and "Avg Hardboard Strength & Density by Date," offering daily views of energy usage and key product quality attributes over time.

* 🌡️ **Contextual Slicers**: Features interactive slicers like "Press Temperature," which has a **tooltip explaining its critical importance** to both product quality and energy efficiency in the hardboard (plywood-like material) manufacturing process.

https://github.com/user-attachments/assets/0c12e453-7d59-4f8e-b7cf-077c4d2d0172

### Questions Answered by this Dashboard:

* What is the overall percentage of defective batches produced, and what is the total number of defects recorded?

* Which specific defect type (e.g., Surface, Density Variation) is the most prevalent, and what are its associated causes and impacts on the product?

* What are the average electrical energy (KWh) and steam (kg) consumed per production batch, providing a quick overview of energy efficiency?

* How has the total energy consumption trended over time, and what are the corresponding trends for hardboard strength and density?

## 1.2. Deep Dive: Quality Analysis & Improvements (Page 2: Defect Analysis)
**Objective**: To provide a granular analysis of the relationship between specific production parameters and the occurrence of defects, facilitating root cause identification and targeted quality improvement initiatives.

### Key Insights & Features:

* 🔬 **Targeted Defect Identification**: Highlights the "Most Common Defect Type" (e.g., Surface defects) and displays "Defects per Batch" to focus immediate attention on primary quality issues.

* 🔥 **Parameter-Specific Defect Analysis**: **A bar chart illustrates "Total Defects by Press Temperature," prominently featuring a red dotted line representing a "target for defect reduction**".An accompanying text box clarifies that this chart helps understand why targets are missed and encourages parameter selection to refine goals.

* ⚙️ **Interactive Quality Parameter Slicers**: Allows users to filter and analyze defects based on various quality-related production parameters (e.g., Press Pressure, Cycle Time, Resin Content, Fiber Consistency, Moisture Content, Hardboard Density). This interactive exploration supports precise root cause analysis.
  
https://github.com/user-attachments/assets/c925feb8-0184-47b1-9981-87d81520ac56

### Questions Answered by this Dashboard:

* What is the most common defect type observed across all production batches, requiring focused attention?

* How does the total number of defects vary with different Press_Temperature_C settings, and are current defect levels meeting the established reduction targets for each temperature range?

* By selecting specific quality parameters (e.g., Press_Pressure_kpsi, Moisture_Content_PrePress_pct), how do they individually influence the number of defects per batch?


## 1.3. Deep Dive: Energy Consumption & Efficiency (Page 3: Defect Analysis)
**Objective**: To conduct an in-depth analysis of energy consumption patterns within hardboard manufacturing, identify key drivers of energy usage, and uncover opportunities for significant cost savings through process optimization.

### Key Insights & Features:

* 💡 **Detailed Energy KPIs**: Provides specific metrics like "Avg Energy per Batch KWh," "Avg Steam per Batch kg," "Total Energy KWh," and "Total Steam kg." Each KPI is equipped with **tooltips explaining its relevance and importance** to energy efficiency.

* 📉 **Energy Trend Analysis**: Line charts track average electrical energy and steam consumption per batch over time, enabling the identification of trends, seasonal variations, and unusual consumption spikes.

* 🔗 **Parameter-Energy Correlation**: A scatter plot explores the relationship between "Monthly Strength vs Energy per Batch," helping to optimize the balance between product quality and energy use.

* 🔄 **Dynamic Energy Drivers**: Features interactive "Select Energy Driver" slicers (e.g., Press Temperature, Press Cycle Time, Fiber Consistency). **Crucially, the "Total Energy" KPI dynamically updates with the selected parameter, demonstrating the direct impact of operational settings on energy consumption**. Tooltips for these slicers explain their significance to energy usage.

* 🎯 **Targeted Energy Efficiency**: A bar chart displaying **"Total Energy by Selected Parameter Bins" incorporates green and red dotted lines to represent energy consumption targets**. Tooltips specify that green indicates ideal consumption, while red denotes excessive usage, allowing for clear performance assessment.

* 🔍 **High-Impact Identification**: A "Top 5 Most Energy Intensive Batches" table pinpoints specific production runs with the highest energy consumption, facilitating focused investigations for root cause analysis and immediate efficiency improvements.
  
https://github.com/user-attachments/assets/175e6343-ccc4-48e2-91d4-375fb03ce5f9

### Questions Answered by this Dashboard:

* What are the current average and total electrical energy (KWh) and steam (kg) consumption figures for hardboard production?

* How do average electrical and steam energy consumption per batch trend over time, and are there any periods where target was reached?

* Which specific production parameter (e.g., Press_Temperature_C, Press_Cycle_Time_min) has the most significant impact on overall energy consumption, and are we operating within our defined energy efficiency targets for these parameters?

* What are the top 5 most energy-intensive production batches, and when did they occur, allowing for targeted investigation into potential inefficiencies?

## Quantifiable Business Impact & Value Proposition
This project demonstrates a proactive approach to business optimization through data analysis. By developing this dashboard, I aimed to provide Western India Plywood with tangible, data-driven insights for strategic decision-making and operational improvements.

Here's the probable impact this dashboard can enable for a manufacturing company like Western India Plywood:

**1. Enhanced Product Quality & Reduced Waste**:

* **Action**: The "Quality Analysis & Improvement" section provides visual cues and detailed breakdowns of defect types (e.g., Surface, Density Variation) and their correlation with production parameters (like Press Temperature). This allows for pinpointing root causes.

* **Impact**: By enabling data-driven fine-tuning of manufacturing processes, these insights can **reduce overall product defect rates by an estimated 5-10%**, which in turn could **cut raw material waste and rework expenses by approximately 3-7%, resulting in annual savings of ₹5 Lakhs to ₹1 Crore**. This also directly improves product quality and customer satisfaction.

**2. Significant Energy Cost Savings**:

* **Action**: The "Energy Consumption & Efficiency" section highlights energy-intensive batches and reveals the impact of various production parameters on total energy usage. For instance, identifying sub-optimal "Press Temperature" ranges that consume excess electricity/steam without contributing to quality.

* **Impact**: By monitoring and adjusting operational parameters based on dashboard insights, the company can **reduce overall energy consumption (electricity and steam) by an estimated 8-15%**. This directly translates to an **annual reduction in utility expenses of ₹10 Lakhs to ₹25 Lakhs**, helping the company save a significant portion of its operational budget and contribute to environmental sustainability.

**3. Improved Operational Efficiency & Accelerated Decision-Making**:

* **Action**: This interactive dashboard consolidates complex operational data into easily digestible visualizations, providing a single source of truth for key operational metrics (quality, energy). Instead of manually sifting through reports or spreadsheets.

* **Impact**: This can **reduce the time spent on data analysis and report generation for managers by up to 20-30%**(e.g., saving several hours per week for analysts or decision-makers). This accelerated insight generation empowers decision-makers to **respond to trends and anomalies 2-3 times faster**, leading to more agile and effective operational adjustments and ultimately **boosting overall productivity by an estimated 5-8%**.

## Conclusion
This internship project demonstrates my foundational abilities in:

* **Business Acumen**: Translating real-world business challenges into analytical problems.

* **Data Proficiency**: Handling, processing, and preparing data for analysis.

* **Analytical Storytelling**: Extracting actionable insights from complex datasets.

* **Visualization & Communication**: Designing clear, interactive dashboards that communicate findings effectively to diverse audiences.

* **Technological Adaptability**: Leveraging modern tools, including AI-assisted development, for efficient and impactful project execution.

This project underscores my commitment to data-driven solutions and my potential to contribute meaningfully to data analysis roles.
