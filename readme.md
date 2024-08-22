
Budget Allocation Calculator

This project is a Python-based budget allocation calculator that helps users distribute their annual income across different expense categories. The application fetches data from the U.S. Bureau of Labor Statistics (BLS) to determine the percentages allocated to categories like housing, transportation, food, and healthcare. Additionally, users can specify the percentages of their income they want to allocate to savings and miscellaneous expenses.

Features

Automatic Expenditure Data Fetching: The program fetches up-to-date expenditure data from the BLS API for essential categories such as housing, transportation, food, and healthcare.
Customizable Savings and Miscellaneous Expenses: Users can specify the percentage of income they want to allocate to savings and miscellaneous expenses.
Pie Chart Visualization: The application generates a pie chart displaying the proportions of income allocated to each category, including the actual amounts and percentages.
Budget Balancing: The program ensures that the total expenditures do not exceed the user's annual income and provides feedback if they do.
Prerequisites
Before you can run this project, ensure you have the following installed:

Python 3.x

Matplotlib: This library is used to generate pie charts. You can install it using pip

	pip install matplotlib

Requests: This library is used to fetch data from the BLS API. You can install it using pip:

	pip install requests

Example Usage

Enter your annual income: $60000
Enter the percentage of income for savings (e.g., 0.15 for 15%): 0.15
Enter the percentage of income for miscellaneous (e.g., 0.10 for 10%): 0.10

Analysis:
Housing takes up 30.12% of your remaining income.
Transportation takes up 17.29% of your remaining income.
Food takes up 12.89% of your remaining income.
Healthcare takes up 9.65% of your remaining income.

Budget based on an income of $60,000:
Housing: $12,048
Transportation: $6,914
Food: $5,153
Healthcare: $3,855
Savings: $9,000
Miscellaneous: $6,000

Total Expenses: $42,970

Your budget balances perfectly!

The pie chart will also be displayed, visually representing the distribution of your income.

BLS API Information

The program uses the following BLS series IDs to fetch expenditure data for different categories:

Housing: CUUR0000SAH
Transportation: CUUR0000SAT
Food: CUUR0000SAF
Healthcare: CUUR0000SAM
Make sure to replace the series IDs with appropriate ones if you need more detailed or localized data.

License

MIT License

Acknowledgments

Bureau of Labor Statistics (BLS): For providing public access to consumer expenditure data via their API.

Matplotlib: For enabling data visualization through pie charts.




