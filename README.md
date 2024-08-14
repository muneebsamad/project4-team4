# Video Game Sales Prediction Project

## Problem Statement
For our project, we have decided to take an incisive look at the video game industry, focusing on the task of predicting future sales. Accurate sales forecasting is essential for developers, publishers, and marketers to make informed decisions about game development and marketing strategies. Our goal is to develop a machine learning model that predicts future video game sales based on historical data. We’ll analyze key factors such as genre, platform, region, release timing, along with economic conditions, to create a predictive model that provides valuable insights.

## Dataset Descriptions

### GDP Dataset

#### Overview
The GDP dataset provides annual Gross Domestic Product (GDP) data for various countries over multiple years. The data is structured in a wide format, with each row representing a country and each column corresponding to a specific year.

#### Structure
- **Number of Entries**: 266
- **Columns**:
  - `Country Name`: Name of the country.
  - `Country Code`: Unique identifier for each country.
  - `Indicator Name`: Describes the economic indicator (GDP-related in this case).
  - `Indicator Code`: A code representing the indicator.
  - `Years (1960-2023)`: Annual GDP data for each year, represented as floating-point numbers. Some years may have missing data.

#### Source: [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)

#### Usage
This dataset is used to identify the influence of GDP on video game sales. By analyzing GDP trends, we can explore the correlation between economic conditions and consumer spending on video games, which helps in making informed predictions about future sales trends.

### Population Dataset

#### Overview
The Population dataset provides population statistics for various countries over a range of years, similar in structure to the GDP dataset. The data is also in a wide format.

#### Structure
- **Number of Entries**: 306
- **Columns**:
  - `Country Name`: Name of the country.
  - `Country Code`: Unique identifier for each country.
  - `Indicator Name`: Describes the population-related indicator.
  - `Indicator Code`: A code corresponding to the indicator.
  - `Years (1960-2023)`: Annual population data for each year, represented as floating-point numbers. Some years may have missing data.
 
#### Source: [World Bank](https://data.worldbank.org/indicator/SP.POP.1564.TO.ZS) 

#### Usage
This dataset is used to analyze population demographics and their impact on video game sales. Specifically, it focuses on the 15-64 age group, which is considered the primary target audience for video games. By understanding population trends within this demographic, we can assess the potential market size and tailor sales predictions accordingly. This analysis helps in determining the influence of population dynamics on consumer demand for video games.

### Video Game Sales Dataset

#### Overview
The Video Game Sales dataset offers a comprehensive look at sales data for various video games across different platforms and regions. The data is structured in a long format with each row representing a game and its sales figures.

#### Structure
- **Number of Entries**: 16,598
- **Columns**:
  - `Rank`: The rank of the game based on global sales.
  - `Name`: The title of the video game.
  - `Platform`: The gaming platform (e.g., Wii, NES).
  - `Year`: The year of release.
  - `Genre`: The genre of the video game (e.g., Sports, Platform, Racing).
  - `Publisher`: The company that published the game.
  - `NA_Sales`: Sales in North America (in millions).
  - `EU_Sales`: Sales in Europe (in millions).
  - `JP_Sales`: Sales in Japan (in millions).
  - `Other_Sales`: Sales in other regions (in millions).
  - `Global_Sales`: Total worldwide sales (in millions).

#### Source: [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)

#### Usage
This dataset oofers potential for analyzing trends in video game sales across different regions, genres, and platforms over time. 
