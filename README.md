# DSA Data Analysis Capstone Project

## Project Topic: Amazon-Product-Review-Analysis

### Project Description:
Analysis of the products of Amazon using product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

### Data Source
The data source is an Amazon Case Study Excel file extracted from Amazon product pages

### Tools Used
Microsoft excel was the tool used in the analysis of the provided dataset. The dataset contains 1465rows with 16columns.
 - For Data Collection
 - For Data Cleaning
 - For Data Analysis
 - For Presentation

### Assumptions
The dataset contains duplicated columns with two blank cells and one containing a symbol. The dataset was cleaned up using excel functions to remove the duplicated rows which was 114rows in total while the two blank & one symbol cells were assumed to have the figure zero and so were replaced with “0”.

### Analysis & Inferences
Based on the dataset and insights given additional 10columns were created by adding calculated columns. Looking at the product link column it was discovered that these products were from Amazon in India and so all the calculations related to currency were identified with the symbol (₹) which is the Indian Rupee sign. Eventually the analysis was with 26columns and 1,351rows. These rows contain different products names with unique product IDs.
The supplied category from the raw dataset was separated into Main Category, Level2, Level3 & Level4 categories for easier identification. The rate count was also assumed to be the number of reviews for each of the product.

Findings from the analysis of the dataset shows that there are nine categories of product analysed and the Home Improvement category has the highest percentage discount with 58% while the Toys&Games has no discount. There are 1,351 products with Electronics category having the highest with 36.27% followed by the Home & Kitchen with 33.16% while Car&Motorbike and Toys&Games constitute only 0.07% each. The Electronics category has the highest number of reviews with three of its products toping the products review chart with equal amounts of number of reviews. There are 662 products where customers enjoy more than 50% discount while 225products have ratings of 4.1 each. 

There are 850products with prices >₹500 which is more than half of the whole number of products, this goes to show that it is either they essential products or has quality that beats other similar products. Potentially products in the Electronics category have the capacity to generate over ₹91.3m which represents about 80% of potential revenue when considering a combination of the number of reviews and actual price. The products under the Computer & Accessories category have the highest discounts of 94% while the top 3 products that enjoyed the highest rating & number of reviews combined all fell under the Electronics Category.

### Conclusion/Recommendation
In conclusion, the company should pay more attention to the reviews for the products that fall under the Electronics especially on how to improve on those products because these constitute more than 60% of the company’s revenue when you compare Electronics price to the entire products prices both actual and discounted values with 80% potential revenue leaving 20% for other categories.

| Category | Discounted Price ₹ | Actual Price ₹ |
| --------- | ------------------- | -------------- |
| Electronics | 3,050,676 | 5,104,861 |
| Entire Categories	| 4,464,787.17	| 7,688,779.62 |
| Electronics % to Entire Categories | 68.33%	| 66.39% |





