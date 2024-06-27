# Project 1
Project Name: Swiggy Restaurants Data Analysis

Description:
The "Swiggy Restaurants Data Analysis" project involves analyzing restaurant data from the Swiggy food delivery platform.

The project encompasses the following key aspects:
1. Data Collection:
   - Access Swiggy's restaurant data, which includes details such as restaurant names, cuisines, ratings, reviews, delivery times, and       locations.
   - Retrieve relevant data points that will provide insights into the variety of restaurants and their offerings.

2. Data Cleansing and Preparation:
   - Clean and preprocess the collected data to remove any inconsistencies or errors.
   - Organize the data into a structured format that can be easily analyzed.

3. Restaurant Performance Analysis:
   - Calculate average ratings, review counts, and other metrics to assess the overall performance of restaurants.
   - Identify highly-rated restaurants and those with a significant number of customer reviews.

4. Cuisine and Menu Analysis:
   - Analyze the distribution of cuisines offered by restaurants to determine popular and niche food choices.
   - Explore the menu items that receive the most attention and positive feedback from customers.

# Project 2
Project Name: GeeksforGeeks Data Analysis

Description:
The "GeeksforGeeks Data Analysis" project involves scraping and analyzing the video dataset from the GeeksforGeeks YouTube channel.
The project consists of the following main steps:

  1. Data Gathering:
        Utilize the YouTube Data API to fetch video details from the GeeksforGeeks YouTube channel.
        Specify the time range of the past 6 months to filter relevant videos.
        Retrieve video titles, views, upload dates, video lengths, and other relevant information.

  2. Data Processing and Analysis:
        Calculate the total views and video lengths for each topic.
        Identify the most viewed topics during the specified time period.
        Determine the correlation between the number of views and video lengths.

  3. Visualization:
        Create graphical representations using libraries like matplotlib to visualize the relationship between views and video lengths.
        Generate bar plots, scatter plots, or other relevant visualizations to showcase trends and patterns.

  4. Insights and Findings:
        Analyze the data to uncover insights such as the most popular topics and their associated video lengths.
        Provide insights into user preferences, engagement patterns, and potential correlations between views and video lengths.

# Cardekho Used Car Price Analysis

## Introduction
This analysis aims to explore the Cardekho used car dataset to uncover insights about the factors influencing the selling price of used cars.

## Data Cleaning and Preprocessing
The data cleaning and preprocessing steps included:
- Handling missing values by dropping rows with any null values.
- Removing duplicate entries.
- Standardizing text columns (fuel_type, seller_type, transmission_type).
- Removing outliers from the selling_price column using the IQR method.

## Exploratory Data Analysis (EDA)

### Univariate Analysis
- **Distribution of Selling Price**:
  ![Distribution of Selling Price](images/selling_price_distribution.png)
- **Distribution of Vehicle Age**:
  ![Distribution of Vehicle Age](images/vehicle_age_distribution.png)
- **Distribution of KM Driven**:
  ![Distribution of KM Driven](images/km_driven_distribution.png)
- **Distribution of Engine**:
  ![Distribution of Engine](images/engine_distribution.png)
- **Distribution of Max Power**:
  ![Distribution of Max Power](images/max_power_distribution.png)
- **Distribution of Seats**:
  ![Distribution of Seats](images/seats_distribution.png)

### Bivariate Analysis
- **Vehicle Age vs. Selling Price**:
  ![Vehicle Age vs. Selling Price](images/vehicle_age_vs_selling_price.png)
- **KM Driven vs. Selling Price**:
  ![KM Driven vs. Selling Price](images/km_driven_vs_selling_price.png)

### Categorical Variable Analysis
- **Fuel Type Distribution**:
  ![Fuel Type Distribution](images/fuel_type_distribution.png)
- **Selling Price Variations Across Different Fuel Types**:
  ![Selling Price by Fuel Type](images/selling_price_by_fuel_type.png)
- **Selling Price Variations Across Different Seller Types**:
  ![Selling Price by Seller Type](images/selling_price_by_seller_type.png)
- **Selling Price Variations Across Different Transmission Types**:
  ![Selling Price by Transmission Type](images/selling_price_by_transmission_type.png)

### Correlation Analysis
- **Correlation Heatmap**:
  ![Correlation Heatmap](images/correlation_heatmap.png)

## Conclusions
- **Key Findings**:
  - Newer vehicles tend to have higher selling prices.
  - Vehicles with lower KM driven have higher selling prices.
  - Fuel type, seller type, and transmission type all influence the selling price.
  - There is a strong correlation between engine size, max power, and selling price.
- **Recommendations for Buyers**:
  - Consider newer vehicles with lower KM driven for better value.
  - Understand the impact of fuel type, seller type, and transmission type on price.
- **Recommendations for Sellers**:
  - Highlight low KM driven and vehicle age in listings to justify higher prices.
  - Understand market trends for different fuel types and transmission types.

## How to Use This Notebook
1. **Download the Dataset**: Download the dataset from the provided link on Kaggle.
2. **Run the Notebook**: Run the notebook to see the analysis and visualizations.
3. **Modify for Your Analysis**: Feel free to modify the notebook for your specific analysis needs.

## Repository Structure
- `data/`: Contains the dataset (not included, download from Kaggle).
- `notebooks/`: Contains the Jupyter notebook with the analysis.
- `images/`: Contains the images used in this README for visualizations.

## Acknowledgements
- Dataset provided by Cardekho on Kaggle.

## License
This project is licensed under the MIT License.
