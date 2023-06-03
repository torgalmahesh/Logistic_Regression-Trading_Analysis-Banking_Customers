# Logistic Regression : Trading_Analysis-Banking_Customers
The client name is AE Corp who is a retail banking institution.

---
<a name = Section1></a>
# **1. Company Introduction**
---

- The client name is **AE Corp** who is a retail banking institution.
- They are going to float a stock trading facility for their existing customers.
- The idea is to use data to classify whether a customer belongs to a high net worth or low net worth group.
- They will have to incentivize their customers to adopt their offerings.
- One way to incentivize is to offer discounts on the commission for trading transactions.

<center><img width=10% src="https://www.bing.com/th?id=OIP.0tedQhMeBulqD0A0CsantAHaHa&w=250&h=250&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2"></center>

---
### **Current Scenario**

- The company rolled out this service to about 10,000+ of its customers and observed their trading behavior for 6 months and after that, they labeled them into two revenue grids 1 and 2.

---
<a name = Section2></a>
# **2. Problem Statement**
---
The current process suffers from the following problems:
   - One issue is that only about 10% of the customers do enough trades for earnings after discounts to be profitable.
   - The company wants to figure out, which are those 10% customers so that it can selectively offer them a discount.
   
The marketing department has hired me as a data science consultant because they want to supplement their campaigns with a more proactive approach.

### My Role
- I have given datasets of past customers and their status (Revenue Grid 1 or 2).
- My task is to build a classification model using the datasets.
- Because there was no machine learning model for this problem in the company, I don’t have a quantifiable win condition. I need to build the best possible model.

### Project Deliverables
- Deliverable: Predict whether a customer belongs to a high net worth or low net worth group.
- Machine Learning Task: Classification
- Target Variable: Status (high net worth (1) / low net worth (2))
- Win Condition: N/A (best possible model)

### Evaluation Metric
- The model evaluation will be based on the F1 Score.
