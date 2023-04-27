# **Market Basket Analysis in Python using Apriori Algorithm**

Have you ever noticed how certain products are always positioned together in retail stores? Like how baby diapers and wipes are placed near bread and butter, pizza base and cheese, beer and chips, etc.?

This strategic product placement is not random. It's based on Market Basket Analysis (MBA), a technique used by retailers to analyze the association among products bought together by customers. MBA helps them to optimize their product positioning and promotions to increase sales.

This is a project focused on analyzing the association among products bought together by customers, a process known as market basket analysis. The project is implemented in Python and uses the Apriori algorithm, one of the most popular machine learning algorithms for association learning.

The project uses the Apriori algorithm to identify frequent itemsets and association rules between them. These rules help to identify which items are commonly bought together and can be used to make recommendations to customers or to arrange products in a store to increase sales.

*Programming Languages*
<br/>The project is implemented in Python, a popular programming language for data analysis and machine learning. Python provides a rich set of libraries for data manipulation, including Pandas, Numpy, and Scikit-learn, which are used extensively in this project.

*Usage*
<br/>To run the project, you will need to have Python installed on your machine along with the following libraries:
<br/>Pandas
<br/>Numpy
<br/>matplotlib
<br/>seaborn
<br/>apyori.
<br/>The dataset used in the project can be downloaded from kaggle.

The project includes the following steps:

Data Import and Exploration
<br/>We start by importing the required libraries and the dataset. Then, we explore the dataset and visualize the top-selling products using horizontal and donut charts.

Data Visualization to identify the bestselling products
<br/>We use plotly and seaborn libraries to visualize the top-selling products in the retail store. The horizontal chart displays the number of occurrences for each item, while the donut chart shows the percentage breakdown of popular items.

Data Preprocessing to convert the dataset into a format suitable for MBA
<br/>We preprocess the dataset by converting it into a list of transactions, where each transaction represents a customer's purchase. We also create a co-occurrence matrix to find the top pairs of items that are frequently bought together.

Association Rule Mining using the Apriori Algorithm
<br/>We use the Apriori Algorithm to find the association rules between the items purchased. We set the minimum support, confidence, and lift to filter out the insignificant rules.

Results Interpretation and Insights Generation
<br/>We interpret the results and generate insights that can help the retailer to optimize their product placement and promotions. We identify the most frequent itemsets and the association rules that have high support, confidence, and lift.

In conclusion, Market Basket Analysis using Apriori Algorithm is a powerful technique that can help retailers to understand their customers' purchasing behavior and improve their business strategies.
