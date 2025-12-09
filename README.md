# Ship Engine Anomaly Detection

## Project Overview
I worked on a project that focused on spotting unusual patterns in a ship engine's activity. The goal was to help a shipping company catch risks early and plan maintenance before things went wrong.

## Business Problem
The company wanted a way to track engine behaviour in real time. They were losing money from delays, fuel waste, and unexpected breakdowns. They needed a system that could spot trouble before it became a major issue.

## Dataset
The data set covered key engine signals:
- rpm
- lubrication oil pressure
- fuel pressure
- coolant pressure
- lubrication oil temperature
- coolant temperature

## Exploratory Data Analysis
I explored the data to look for clear trends, extreme values, and warning signs. I checked how each feature behaved, where the normal range sat, and which readings drifted into unsafe territory.

## Methodology
I built two layers of checks:
- A statistical method to flag outliers based on IQR
- ML models such as one class SVM and Isolation Forest to detect unusual behaviour

I scaled the features, ran PCA for a two dimensional view, and compared how each method separated normal readings from abnormal ones. I tuned parameters until the models produced a realistic share of anomalies.

## Results & Impact
The outcome was a system that could alert the business when two or more engine readings crossed risky levels. This kind of early signal helps the company cut downtime, reduce fuel waste, and avoid costly breakdowns. It also keeps deliveries on track and builds trust with clients.

## Deliverables
I produced a detailed report with insights, findings, and visuals that show how the models highlight unusual activity.
