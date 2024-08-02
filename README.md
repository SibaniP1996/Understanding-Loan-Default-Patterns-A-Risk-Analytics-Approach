Loan Defaulter Analysis: A Risk Analytics Approach
Business Understanding:
Loan providers often struggle with approving loans for individuals with insufficient or non-existent credit histories, leading to potential defaults. As an employee of a consumer finance company specializing in urban lending, your task is to use Exploratory Data Analysis (EDA) to identify patterns in the data to ensure that applicants who can repay the loan are not unjustly rejected.
When processing a loan application, the company faces two primary risks:
•	Not approving a loan for a creditworthy applicant results in lost business.
•	Approving a loan for a likely defaulter results in financial loss.

The provided dataset includes loan application information, capturing two scenarios:
	Clients with payment difficulties (late payments beyond X days on at least one of the first Y installments).
	Clients who paid on time.

Loan application outcomes can be categorized as:
1.	Approved
2.	Cancelled (by the client)
3.	Refused (by the company)
4.	Unused offer (cancelled at different stages by the client)

Business Objectives:
The goal is to identify patterns that indicate a client's likelihood of default, which can inform actions such as loan denial, reduced loan amounts, or higher interest rates for risky applicants. This ensures that creditworthy consumers are not rejected. Understanding the driving factors behind loan default through EDA is essential for portfolio and risk assessment.

Data Files
	application_data.csv: Client information at the time of application, indicating payment difficulties.
	previous_application.csv: Client’s previous loan data, including approval status.
	columns_description.csv: Data dictionary describing the variables.
