# Air BNB Hotel Booking Analysis

## Description
The hospitality industry has undergone a significant transformation with the rise of online platforms facilitating short-term lodging and tourism. Leading this revolution is Airbnb, Inc., a pioneering American company that has reshaped travel accommodation through its innovative online marketplace. Established in 2008 in San Francisco, California, Airbnb provides a diverse range of lodging options, offering guests a unique and personalized experience. Unlike traditional hospitality providers, Airbnb operates on a commission-based model, facilitating transactions between hosts and guests without owning the properties listed on its platform.

This project involves a comprehensive analysis of an Airbnb open dataset containing over 100,000 listings for New York City. The process begins with data cleaning and preprocessing, followed by an exploratory data analysis (EDA) to answer key business questions and uncover insights through data visualization.

## Problem Statement
This research analysis delves into the New York City Airbnb dataset to extract meaningful insights. Through rigorous data cleaning, exploratory analysis, and visualization techniques, the study aims to illuminate the dynamics of the city’s lodging market. By discerning factors influencing listing availability, pricing strategies, and overall customer satisfaction, the research contributes to a deeper understanding of Airbnb's operations in one of the world's most dynamic urban environments.

## Technology Used
* **Language:** Python
* **Libraries:**
    * Pandas
    * NumPy
    * Matplotlib
    * Seaborn
    * Plotly Express

## Analysis and Visualizations
The exploratory data analysis focuses on answering the following questions:
* What are the different property types available and their distribution?
* Which neighborhood groups (boroughs) have the highest number of listings?
* How do average listing prices vary across different neighborhood groups?
* Is there a relationship between the construction year of a property and its price?
* Who are the top 10 hosts based on the number of listings they manage?
* Does a host's verified identity status correlate with higher review ratings?
* What is the correlation between the listing price and the service fee?
* How does the average review rate vary by neighborhood group and room type?

## Key Findings
* **Property Distribution:** Brooklyn and Manhattan have the highest concentration of Airbnb listings.
* **Pricing Insights:** Manhattan is, on average, the most expensive borough for Airbnb stays.
* **Price vs. Service Fee:** There is a near-perfect positive correlation (0.9999) between the listing price and the service fee, suggesting the fee is a direct percentage of the price.
* **Host Verification:** There is no significant difference in the average review rate between hosts with verified and unconfirmed identities.

## How to Run the Code
1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd [Your Repository Name]
    ```
3.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn plotly
    ```
4.  **Run the Jupyter Notebook:**
    Open and run the `give_me_the_whole_code_shown_in_the_video.ipynb` file in a Jupyter environment. Ensure the `Airbnb_Open_Data.csv` dataset is in the same directory.

## File Structure
* `give_me_the_whole_code_shown_in_the_video.ipynb`: The main Jupyter Notebook containing the Python code for analysis and visualization.
* `Airbnb_Open_Data.csv`: The dataset used for the analysis.
* `README.md`: This file.
