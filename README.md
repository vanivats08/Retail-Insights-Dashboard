# Retail-Insights-Dashboard
Built a Power BI dashboard replacing manual Excel workflows. Used DAX and time intelligence to identify 3+ seasonal patterns and added slicers and drill-through for 2x faster data navigation.

Problem Statement

	– The objective of this project is to analyze Myntra’s retail sales data to understand overall sales performance, customer purchasing behavior, and product category trends.
	– This analysis aims to answer the following business questions:
		▪ How are total sales performing over time?
		▪ Which product categories and subcategories contribute the most to revenue?
		▪ Which brands generate the highest sales?
		▪ How do different age groups contribute to total sales?
		▪ What is the relationship between product ratings and sales?
		▪ How does current year performance compare with last year (YoY growth)?

		– The insights from this analysis help in identifying:
		▪ High-performing products
		▪ Profitable customer segments
		▪ Potential areas for business improvement

Workflow

	• Data Collection
		– Collected Myntra retail sales dataset containing product, category, brand, customer age group, ratings, and sales values.

	• Data Cleaning & Preprocessing
		– Removed missing and duplicate values
		– Standardized category and brand names
		– Converted date fields into Year-Month format
		– Ensured numerical fields (sales, ratings, orders) were properly formatted

	• Exploratory Data Analysis (EDA)
		– Analyzed sales distribution by category, subcategory, and brand
		– Studied customer age group behavior
		– Examined rating vs sales relationship
		– Performed time-series analysis of monthly sales

	• Feature Engineering
		– Created calculated fields such as:
			▪ Total Sales
			▪ Average Order Value
			▪ YoY Growth %
			▪ Sales by Category and Brand
			▪ Sales by Age Group

	• Dashboard Development (Power BI / Tableau)
		– Designed interactive dashboard with:
			▪ KPI cards (Total Sales, Avg Order Value, Total Orders)
			▪ Sales trend by Year-Month
			▪ Category & Subcategory breakdown
			▪ Brand-wise performance
			▪ Age group analysis
			▪ Rating vs Sales comparison
			▪ Filters for Category, State, and Brand

	• Insights Generation
		– Interpreted dashboard results to extract business insights
		– Identified top-performing categories, brands, and customer segments

Major Insights

	• Overall Sales Performance
		– Total sales recorded: 1.88M
		– Average Order Value: 18.83K
		– Total Orders: 100

	• Sales Trend (Time Series)
		– Sales show a gradual decline over months, indicating possible seasonality or reduced demand over time.

	• Top-Selling Products
		– Highest revenue-generating products:
			▪ Jeans
			▪ Shorts
			▪ T-Shirts
			▪ Sandals
		– These products contribute the largest share of total sales.

	• Category-wise Sales
		– Men’s category contributes the highest sales
		– Followed by Women’s and Kids
		– Beauty category has the lowest contribution

	• Subcategory Performance
		– Bottomwear and boys’ clothing dominate within Men and Kids segments
		– Women’s category shows strong contribution from mixed apparel segments

	• Brand-wise Performance
		– Puma is the top-performing brand in terms of total sales
		– Followed by H&M and Roadster
		– Adidas and other brands show comparatively lower contribution

	• Customer Age Group Analysis
		– Millennials contribute the highest sales (~52%)
		– Gen X and Gen Z contribute nearly equal shares
		– Indicates Millennials are the primary revenue-driving customer segment

	• Ratings vs Sales Relationship
		– Products with ratings around 4.0 – 4.5 generate higher sales
		– Suggests customer ratings positively influence purchase behavior

	• Year-on-Year Growth
		– YoY growth shows a decline compared to last year, indicating need for improved marketing or pricing strategies