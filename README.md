# Amazon End-to-End Data Analysis with Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

## 🚀 Project Overview

This project demonstrates an end-to-end data analysis workflow, from raw data extraction to interactive dashboard creation. The primary goal is to scrape product data from Amazon, process it through a custom ETL pipeline, and visualize the findings in Power BI. The resulting dashboard provides actionable insights that can help an e-commerce business understand product performance, pricing strategies, and customer feedback to drive effective growth.

---

## 📋 Project Workflow

The project is broken down into four main stages:

1.  **Data Extraction (Scraping):**
    * A Python script using the `BeautifulSoup` library scrapes a target Amazon product listing page.
    * Key data points are extracted for each product: **Title, Price, Rating, Number of Reviews, and Availability**.

2.  **Data Transformation (ETL Pipeline):**
    * The raw scraped data is processed and structured using the `Pandas` and `NumPy` libraries.
    * This simple ETL process ensures the data is clean and in a suitable format before loading.

3.  **Data Loading:**
    * The cleaned data is loaded into a local file (e.g., a `.csv` or `.xlsx` file), making it ready for analysis.

4.  **Data Visualization & Analysis (Power BI):**
    * The dataset is imported into Power BI.
    * Further transformations are performed using **Power Query** to handle null values, format data types, and create new calculated columns.
    * An interactive dashboard is built to visualize the data, uncovering trends and insights related to product performance and customer sentiment.

---

## ✨ Key Features of the Dashboard

The Power BI dashboard provides a comprehensive view of the product data, with key insights such as:

* **KPIs:** High-level metrics like Total Products Analyzed, Average Price, and Average Customer Rating.
* **Price Distribution:** Analysis of how product prices are distributed across the dataset.
* **Rating Analysis:** A breakdown of products by their customer ratings.
* **Reviews vs. Ratings:** Correlation between the number of reviews and the average rating.
* **Product Availability:** A summary of in-stock vs. out-of-stock items.
* **Interactive Filtering:** Slicers and filters allow users to drill down into the data by category, price range, and more.

---

## 🛠️ Technologies Used

* **Data Scraping:** Python, BeautifulSoup
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Microsoft Power BI
* **IDE:** VS Code, Jupyter Notebook

---

## ⚙️ How to Use This Project

To replicate this project on your local machine, follow these steps:

### Prerequisites

* [Python 3.8+](https://www.python.org/downloads/)
* [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)
* The necessary Python libraries.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Aryan-Christian27/Amazon-End-to-End-Data-Analysis-with-Power-BI.git](https://github.com/Aryan-Christian27/Amazon-End-to-End-Data-Analysis-with-Power-BI.git)
    cd Amazon-End-to-End-Data-Analysis-with-Power-BI
    ```

2.  **Install the required Python libraries:**
    ```
    pip install pandas, numpy, beautifulsoup4, requests
    ```

3.  **Execute the Python scraping script:**
    Execute the Python script to start the ETL process and generate the data file (e.g., `amazon_data.csv`).
    ```bash
    python amazon_df.py Or
    (in Jupyter notebook) amazon_df
    ```

4.  **Open the Power BI report:**
    * Launch Power BI Desktop.
    * Open the `.pbix` file included in this repository.
    * If prompted, update the data source to point to the location of the `.csv` file you generated in the previous step.

---

## 👤 Author

* **[Aryan Khristi]** - [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](linkedin.com/in/christian-aryan2710/)
  
Feel free to reach out with any questions or feedback!
