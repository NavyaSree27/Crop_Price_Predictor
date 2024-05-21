# Crop Price Prediction/Farming Made Easy Using ML
# Overview
This project uses machine learning to forecast future crop prices. This tool helps farmers and businesses make informed decisions by integrating historical price data, weather patterns, and market trends to provide accurate predictions and actionable insights.

# Features
1.**Data Collection and Integration**: Aggregates historical crop prices, weather data, soil conditions, and geographical information.

2.**Machine Learning Algorithms**: Utilizes K-Nearest Neighbors (KNN), Random Forests, and Decision Tree algorithms for accurate predictions.

3.**User-Friendly Interface**: Intuitive dashboard with visualization tools for a clear display of predicted price trends.

4.**Custom Alerts and Notifications**: Personalized alerts for significant price changes or trends.

5.**Decision Support System**: Recommendations for optimal planting and harvesting times, and risk assessment reports.
   
# Technical Details
**Programming Languages**: Python, R

**Python Frameworks**: Django

**Machine Learning Frameworks**: Scikit-learn

**Data Sources**: USDA databases, FAO statistics, local agricultural markets, meteorological data

**Database Management**: MySql

**Deployment**: Cloud-based platforms like AWS or Google Cloud

# Usage
1.Prepare Data Sources and Configuration Files

2.Run Data Collection Script

3.Execute the data collection script (data_collection.py) to gather and preprocess data from your sources. Ensure that the collected data is compatible with the Django models.

4.Install Django and Required Packages

5.Create a MySQL Database

6.Configure Django Settings

7.Run Migrations

8.Run the Development Server:

 python manage.py runserver
 
9.Access the Web Interface:

 Open a web browser and navigate to the specified URL (usually http://localhost:8000/) to access the web interface for visualizing predictions and interacting with the application.

