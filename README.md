# Iphone-Sales-Analysis-of-Indian-Market
This project focuses on performing an Exploratory Data Analysis (EDA) on a dataset containing information about various Apple products, including their sales prices, technical specifications (RAM, storage), and customer engagement (number of ratings, star rating). The goal is to uncover trends in pricing, performance, and customer satisfaction.
 Key Analyses Performed

The project focuses on answering key business questions derived from the dataset:

Pricing Analysis: Determined the most and least expensive products available and visualized the overall distribution of sale prices.

Customer Engagement: Analyzed products based on the Star Rating and the Number of Ratings to identify high-satisfaction and high-volume products.

Product Specification Impact: Investigated the breakdown of products across different RAM and Storage configurations.

Data Quality: Performed initial data cleaning steps, including handling missing values and ensuring consistent data types.

🛠️ Technology Stack

This project is built entirely in Python and utilizes the following data science and visualization libraries:

Pandas: Core library for data manipulation, cleaning, and structured analysis.

NumPy: Essential for high-performance numerical operations.

Plotly Express (px): Used extensively for creating interactive, publication-quality visualizations, particularly bar charts and distributions.

Matplotlib & Seaborn: Used for generating standard static statistical visualizations.

Jupyter Notebook: The environment used for documentation, execution, and presentation of the analysis workflow.

📊 Example Insights (from the Notebook)

The analysis reveals valuable insights into the product landscape:

Most & Least Expensive Products

The notebook successfully identified the exact product details for the extremes of the price range, providing immediate context on the premium and entry-level offerings in the dataset.

Ratings vs. Popularity

A key visualization was developed to compare the average Star Rating against the sheer Number Of Ratings, helping to distinguish between niche, high-quality items and universally popular market drivers.

Distribution by Configuration

Visualizations show the density of products released at specific price points and the prevalence of different hardware configurations (e.g., the most common RAM size offered).

🚀 How to Run the Analysis

To reproduce this analysis locally, follow these steps:

Clone the Repository:

git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
cd your-repository-name


Install Dependencies:
It is recommended to use a virtual environment. Install the required libraries using pip:

pip install pandas numpy matplotlib seaborn plotly jupyter


Launch Jupyter:

jupyter notebook


Open the Notebook:
Navigate to and open the apple sales analysis.ipynb file to view and execute the analysis cell by cell.
