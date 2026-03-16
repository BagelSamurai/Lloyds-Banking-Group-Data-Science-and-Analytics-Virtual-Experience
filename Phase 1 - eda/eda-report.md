Customer_Demographics — who customers are (age, gender, income, marital status)
Transaction_History — what they buy (5,054 rows, must aggregate before merging — avg 5 transactions per customer)
Customer_Service — their complaints/inquiries (332 customers have NO record — those need to be filled with 0 after merging)
Online_Activity — how engaged they are (login frequency is a strong churn signal)
Churn_Status — your target variable (20.4% churned — moderately imbalanced, so don't use plain accuracy