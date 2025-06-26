Customer Churn Prediction Project
This project aims to understand why customers stop using a service (this is called "churn") and to predict which customers are likely to leave in the future. By doing this, we can help businesses keep more of their customers.

What is this project about?
Imagine a company that offers a subscription service (like a streaming service, phone plan, or software). Sometimes, customers stop paying for the service – they "churn." This project builds tools to:

Figure out why customers leave.

Predict which customers will leave soon.

Help the company act early to keep those customers.

Why is this important?
Keeping existing customers is usually much cheaper than finding new ones. By predicting churn, businesses can offer help or incentives to at-risk customers, improving customer satisfaction and saving money.

How We Did It (Project Steps)
This project followed a clear set of steps, organized in different files:

1. Cleaning the Data
File: Cleaning_Customer Churn Strategy Code1.ipynb

What it does: Real-world data can be messy! This first step involved taking the raw customer information (in JSON format) and cleaning it up. We fixed errors, handled missing parts, and made sure the data was ready for analysis. The clean data was saved as OUTPUT_CLEANED_telco_customer_churn.json.

2. Analyzing and Visualizing Data
File: ANALYSIS AND VISULATION2.ipynb

What it does: With clean data, we explored it to find interesting patterns. This notebook created charts and graphs (like seeing how monthly charges affect churn) to understand what leads customers to leave. This helps us understand the problem better.

3. Building a Prediction Model
File: APPLYING ML.ipynb

What it does: This is where we built the "brain" of the project – a machine learning model. We used the patterns found in the cleaned data to "teach" a computer how to predict churn. This model can now look at a customer's information and estimate their likelihood of churning. We also checked how accurate our model's predictions are.

What This Project Achieved
This project successfully delivered:

A clean and ready-to-use dataset of customer information.

Key insights into the factors that drive customer churn.

A working machine learning model that can predict individual customer churn with tested accuracy.

This project provides a strong foundation for any business looking to reduce customer churn and improve customer retention strategies.

Project Files
Cleaning_Customer Churn Strategy Code1.ipynb: Contains code for cleaning and preparing the customer data.

ANALYSIS AND VISULATION2.ipynb: Contains code for exploring the data and creating visualizations to understand churn factors.

APPLYING ML.ipynb: Contains code for building and evaluating the machine learning model that predicts customer churn.

Customer segimentation strategy.docx: The original document outlining the project plan and objectives.