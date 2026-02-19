🚛 Truck Fleet Risk Analysis
Big Data Analytics Project
📌 Project Overview

The Truck Fleet Risk Analysis project is a big data analytics initiative designed to analyze large-scale fleet operations data to identify high-risk drivers, unsafe driving patterns, geographic accident hotspots, and vehicle model performance risks.

The project leverages distributed data storage, statistical modeling, and machine learning to provide actionable insights that help reduce traffic accidents, improve driver safety, and optimize fleet management strategies.

🎯 Problem Statement

Truck-related traffic accidents contribute significantly to road fatalities and operational costs.

A trucking company committed to minimizing accident risk by analyzing historical fleet data to:

Identify dangerous driving behaviors

Detect high-risk geographic zones

Evaluate truck model safety performance

Build predictive models to estimate driver risk

📊 Project Objectives
1️⃣ Driver Risk Analysis

Identify the most dangerous drivers using overspeeding, lane deviation, and unsafe following distance metrics

Rank drivers by risk factor and violation frequency

Detect outliers impacting fleet safety

2️⃣ Geographic Risk Assessment

Evaluate risk distribution across California cities

Identify highest-risk zones

Detect geographic clustering patterns

3️⃣ Truck Model Performance Evaluation

Compare truck models using average risk factor

Identify safest and most dangerous vehicle models

Analyze violation frequency by model type

4️⃣ Driving Incident Analysis

Break down violations by type

Analyze incident patterns across locations

Identify dominant risk behaviors

5️⃣ Mileage & Speed Correlation Analysis

Categorize drivers into high-risk and low-risk groups

Analyze relationship between:

Total miles driven

Maximum speed

Average mileage (MPG)

6️⃣ Predictive Modeling

Develop Linear Regression model for driver risk prediction

Identify statistically significant variables

Validate model assumptions

🛠️ Methodology & Big Data Pipeline
🔄 Data Processing Workflow

Data Procurement

Hadoop HDFS Integration

Data Cleaning & Transformation

Risk Factor Calculation

Exploratory Data Analysis

Statistical Modeling

Predictive Model Validation

🧰 Technologies Used

Hadoop HDFS – Distributed storage

Big Data Processing Frameworks

Python (Pandas, NumPy)

Statistical Analysis

Data Visualization

Machine Learning (Linear Regression)

📈 Key Findings
🚨 Driver Risk Analysis

Outlier detected: Driver A97 (Risk Factor: 31.69)

Most common violation: Lane Departure

Top 5 High-Risk Drivers:

A35

A43

A92

A94

A11

📌 Insight: Personalized training required based on violation patterns.

🗺️ Geographic Risk Assessment
City	Violations
Santa Rosa, CA	53
Willits, CA	28

Majority of violations concentrated in Northwestern California

Clear geographic clustering observed

🚚 Truck Model Performance
Model	Avg Risk Factor
Oshkosh	10.45 (Highest Risk)
Navistar	5.862 (Lowest Risk)

Ford involved in bulk of infractions

Crane model recorded minimal violations

🚦 Incident Distribution
Santa Rosa Incident Breakdown:

Lane Departure – 15

Overspeed – 11

Unsafe Following – 15

Unsafe Tail Distance – 12

Overall Incident Distribution:

Lane Departures – 33.33%

Unsafe Following – 32.80%

📊 Mileage & Speed Analysis

High-risk drivers typically showed:

620,000 – 680,000 total miles

70 – 95 mph maximum speed

4.5 – 6.0 MPG

📌 However, similar patterns were observed among some low-risk drivers, indicating complex interactions between experience and behavior.

🤖 Predictive Modeling Results
📌 Linear Regression Performance
Significant Variables (p < 0.05):

Events

Total Miles

Truck Model

Key Insights:

+1 event → +1.559 risk factor increase

+10,000 miles → -0.1138 risk factor decrease

Peterbilt vs Caterpillar → -0.07426 risk reduction

✔ All VIF values < 10 → No multicollinearity detected

💡 Strategic Recommendations
🎯 Driver-Level Actions

Personalized training programs

Intensive monitoring for high-risk drivers

Experience-based performance recognition

🗺️ Geographic Mitigation

Focus safety protocols in Northwestern California

Enhanced monitoring in Santa Rosa & Willits

Route optimization through safer corridors

🚚 Fleet Optimization

Reduce Oshkosh deployment

Increase Navistar / Peterbilt usage

Implement electronic distance monitoring systems

📊 Operational Enhancements

Lane discipline training

Automated following distance enforcement

Speed monitoring in high-risk areas

🌟 Business Impact
🚦 Risk Reduction Potential

35% reduction in lane departure incidents

40% improvement in following distance compliance

25% decrease in high-risk city violations

💰 Cost Benefits

Reduced accident-related costs

Lower insurance premiums

Improved fleet efficiency

Enhanced driver retention

🔮 Future Enhancements

Real-time fleet monitoring dashboard

Advanced ML models (Random Forest, Neural Networks)

IoT-based sensor integration

Mobile driver feedback applications

Blockchain-based secure performance tracking

📊 Data Sources & Scope

Large-scale fleet operations data

California geographic coverage

Historical driving records

Variables included:

Driver ID

Location

Truck model

Violation types

Mileage

Speed

Limitations:

Limited to California

Historical (non real-time) data

Model accuracy dependent on data completeness

🏆 Key Achievements

✔ Multi-dimensional fleet safety assessment
✔ Geographic intelligence discovery
✔ Statistically validated predictive model
✔ Actionable safety strategy recommendations
✔ Evidence-based decision support system
