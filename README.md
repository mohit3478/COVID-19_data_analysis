# COVID-19 Data Analysis

This project involves a comprehensive data analysis of the COVID-19 pandemic using Python. The analysis is performed in a Jupyter Notebook and focuses on tracking, visualizing, and understanding the spread and impact of the virus over time and across different regions.

## 📈 Key Visualizations

This analysis includes several visualizations to illustrate the pandemic's trends.

*(**Your action:** Run your notebook, take screenshots of your best charts, and upload them to your repository. Then, link one or two of them here.)*

**Example:**
![Cases Over Time](img/cases_over_time.png)
![Top 10 Countries by Cases](img/top_10_countries.png)

## 🚀 Key Analyses Performed

This notebook explores the data to answer several key questions:

* **Global Trends:** Tracking the total number of confirmed cases, deaths, and recoveries worldwide over time.
* **Country-wise Comparison:** Analyzing and ranking countries based on their total cases and mortality rates.
* **Trend Analysis:** Visualizing the curve of new cases and new deaths to see the pandemic's progression.
* **Active Cases:** Calculating and plotting the number of active cases (Confirmed - Deaths - Recovered).
* **Geographical Spread:** (If you created one) Plotting the case distribution on a world map.

## 💾 Data Source

This analysis is based on time-series data, which typically includes:

* `covid_19_data.csv` (or similar name): The main dataset containing daily records of cases, deaths, and recoveries by region/country.

*(**Your action:** Make sure to list the actual `.csv` file names you used, and briefly mention the source, e.g., "Data sourced from the Johns Hopkins University CSSE GitHub repository.")*

## 🛠️ Technology Stack

* **Language:** Python
* **Libraries:**
    * **Jupyter Notebook:** For interactive analysis.
    * **Pandas:** For data loading, manipulation, and cleaning.
    * **NumPy:** For numerical operations.
    * **Matplotlib & Seaborn:** For static data visualizations (line charts, bar charts, histograms).
    * **Plotly:** (If used) For interactive charts and maps.

## ⚙️ How to Use This Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mohit3478/COVID-19_data_analysis.git](https://github.com/mohit3478/COVID-19_data_analysis.git)
    cd COVID-19_data_analysis
    ```

2.  **Install requirements:**
    *(**Your action:** You should create a `requirements.txt` file. Run this command in your terminal and then upload the new file to GitHub:)*
    ```bash
    pip freeze > requirements.txt
    ```
    ...and then a new user can install them:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the analysis:**
    Open and run the `.ipynb` notebook file using Jupyter Lab or Jupyter Notebook.
