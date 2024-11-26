# COVID-19 Pandemic Impact Analysis
Global Pandemic Dynamics: Analyzing COVID-19 Impacts Across Nations.

## Project Overview
This project aims to analyze the impact of the COVID-19 pandemic on various global aspects, such as population, COVID-19 cases, pandemic handling (stringency index), and its impact on the economy (GDP per capita). This analysis was conducted using a global dataset containing COVID-19-related indicators and economic data.


## Table of Contents
1. [Business Problem](#business-problem)
2. [Objective](#objective)
3. [Data](#data)
4. [Step Taken](#step-taken)
5. [Data Preparation](#data-preparation)
6. [Exploratory Data Analysis](#exploratory-data-analysis)
7. [Advanced Data Analysis](#advanced-data-analysis)
8. [Result of Insight](#result-of-insight)
9. [Business Recommendation](#business-recommendation)
10. [Conclusion](#conclusion)


## Business Problem
The COVID-19 pandemic has had a significant impact on various sectors, including the economy, health, and public well-being. Many countries face the challenge of balancing effective pandemic response and maintaining economic stability.

The main questions this project seeks to answer are as follows.
- What is the relationship between pandemic handling policies (stringency index) and economic conditions (GDP per capita)?
- Do countries with larger populations experience higher rates of COVID-19 cases?
- How can insights from this data help policymakers to deal with future pandemics?

By answering these questions, this project aims to provide data-driven recommendations to governments or organizations to prepare better mitigation strategies for global health emergencies.


## Objective
The objectives of this project are as shown below.
- Identify the relationship between a country's population and the number of COVID-19 cases.
- Evaluate the level of pandemic handling (stringency index) based on its impact on GDP per capita.
- Provide insights based on the results of data analysis to support data-driven decision making.


## Data
The data used in this project includes:
- [**Country Index Dataset:**](/data/country-index.csv) This dataset includes economic and human development information for each country.
- [**COVID-19 Dataset:**](/data/covid-19-data.csv) This dataset includes COVID-19 case data and pandemic management policies for each country.


## Step Taken
The stages of this project are as shown below.
1. Data Preparation
2. Exploratory Data Analysis
3. Advanced Data Analysis


## Data Preparation
At this stage, some processes are performed, which are shown below.
- Merge Data: Merge the datasets based on the CODE and DATE columns.
- Handling Missing Value: Handling missing values with the appropriate method for each feature.
- Handling Duplicate Data: Handling duplicate values by removing one of them.
- Feature Engineering: Created some new features for further analysis, such as case rate and death rate features.


## Exploratory Data Analysis
The Exploratory data analysis (EDA) stage will focus on descriptive and correlative analysis according to the information needed by the client, such as the development of covid-19 cases, the impact on the economy, population, and comparisons between countries. The following are the processes carried out.

1. **Descriptive Analysis COVID-19 Case Updates:** This analysis is carried out to see a comparison of the level of covid-19 cases and death rates globally and per country.
2. **Trend Analysis The Growth of COVID-19 Cases & Deaths Over Time:** This analysis was performed to look at global trends in the number of cases and deaths over time, including significant spikes or declines in cases. 
3. **Correlation of GDP per Capita & COVID-19 Cases/Deaths:** This analysis provides a way to understand the relationship between economic variables such as GDP and trends in covid-19 cases across countries.
4. **Analysis of Stringency Index & COVID-19 Cases:** This analysis helps understand how government policies in handling a pandemic or social restrictions (Stringency index) affect the number of cases in a country.
5. **Correlation between Population & COVID-19 Cases:** This analysis aims to look at the relationship between a country's population and the number of reported cases.


## Advanced Data Analysis
In the Advanced Data Analysis stage, further analysis is performed into several related sectors that can provide more comprehensive insights. The focus sectors to be analyzed include the economy and the environment, which are important sectors in monitoring the impact of the covid-19 pandemic. This analysis uses available data and links it to relevant global trends. An explanation of the analysis for each sector is shown below.

- Analysis of Economic Impact

    The impact of COVID-19 on the world economy is significant. The decline in economic activity, especially in countries that implemented strict lockdowns, led to a decrease in GDP, increased unemployment, and changes in global trade patterns. This can be seen from the correlation between GDP per Capita and the Pandemic Response Rate (Stringency Index). 

- Analysis of Environmental Impact

    The COVID-19 pandemic has indirectly impacted the global environment. With factory closing, reduced air travel, and lockdowns, global carbon emissions significantly decreased during 2020. Data from the International Energy Agency (IEA) shows that global carbon emissions decreased by more than 5% in 2020 due to reduced economic activity and transportation. Here is a visualization of the graph.

    ![Global Energy & CO2](images/global%20energy%20&%20co2.png)
    
    Source: https://www.iea.org/reports/global-energy-review-2020/global-energy-and-co2-emissions-in-2020


## Result of Insight
- The United States of America (USA) is the country with the highest case rate.
    
    ![Top 10 Countries by COVID-19 Cases Rate](images/top%2010%20countries%20by%20covid-19%20cases%20rate.png)

- Italy (ITA) is the country with the highest COVID-19 death rate.

    ![Top 10 Countries by COVID-19 Deaths Rate](images/top%2010%20countries%20by%20covid-19%20deaths%20rate.png)

- April to June 2020 was the highest period for both total cases and total deaths. 

    ![The Growth of COVID-19 Cases & Deaths](images/the%20growth%20of%20covid-19%20cases%20&%20deaths.png)

- There is a positive correlation between GDP per capita and case rate/death rate.
    - GDP per Capita vs COVID-19 Cases Rate
        ![GDP per Capita vs COVID-19 Cases Rate](images/gdp%20per%20capita%20vs%20covid-19%20cases%20rate.png)

        Countries with higher GDP per capita tend to have higher average COVID-19 case rates than countries with lower GDP per capita.
    
    - GDP per Capita vs COVID-19 Death Rate
        ![GDP per Capita vs COVID-19 Death Rate](images/gdp%20per%20capita%20vs%20covid-19%20death%20rate.png)

        Countries with higher GDP per capita also tend to have higher average COVID-19 death rates.
    
- The Stringency Index has no clear correlation with the COVID-19 Case Rate.

    ![Stringency Index vs COVID-19 Cases Rate](images/stringency%20index%20vs%20covid-19%20cases%20rate.png)

- Population has a significant impact on the total number of COVID-19 cases. 

    ![Population vs Total COVID-19 Cases](images/population%20vs%20total%20covid-19%20cases.png)

- Each country's response to the pandemic is not entirely dependent on GDP levels.

    ![Stringency Index vs Total COVID-19 Cases](images/stringency%20index%20vs%20total%20covid-19%20cases.png)


## Business Recommendation
- Focus on Health System Reinforcement for High-Income Countries
    
    Countries with high GDP per capita, such as the United States and Italy, show high rates of COVID-19 cases and deaths. These countries should invest in better health infrastructure, such as increased hospital capacity and medical equipment.

- Pandemic Policy Strategy Review and Adjustment
    
    Based on the analysis of the weak correlation between the Stringency Index and case rates, countries need to reassess the effectiveness of pandemic policies, such as adopting an evidence-based approach to determine lockdown policies.

- Improving Early Detection Systems in Highly Populated Countries
    
    With the influence of population on the total number of cases, countries with large populations should improve their testing facilities to detect cases quickly and widely. In addition, countries can also promote educational programs to increase public awareness of health protocols.

- Crisis Resistant Economic Development
    
    The positive correlation between GDP per capita and case/death rates shows the need for economic diversification to minimize the socio-economic impact of the pandemic, such as promoting digital and e-commerce sectors that are more resilient to pandemic disruptions.

- Development of Future Prevention Programs
    
    Looking at the high number of cases in April to June 2020, companies/governments should prepare for the initial wave of the pandemic in the future. Companies/governments can design prediction models to anticipate the surge in cases.


## Conclusion
This project successfully explore the impact of the COVID-19 pandemic on global health and economy by utilizing real-time data from countries. The Exploratory Data Analysis (EDA) and Advanced Data Analysis stages provided in-depth insights into the factors affecting COVID-19 cases and deaths, and the effectiveness of pandemic policies. In addition, the business recommendations can help governments, international organizations, and companies design better strategies to deal with future crises.

This project also shows the importance of data-driven decision-making in dealing with global challenges such as pandemics, while providing valuable lessons on how data can be used to make more effective and inclusive policies.