# 2024-25 Spring Term 90800 - B2 Group 2

#### **Team Members: Clarice Ann Bagsic Santos (cbagsics), Liufei Chen (liufeic), Kanika Selvapandian (kselvapa), Zhixuan Jiang (zhixuanj)**

## Research Question and Motivation

##### ***How does the unemployment rate affect the real GDP growth rate across different continents, countries, sex, and age groups from 2014 to 2023?***

The interplay between the unemployment rate and real GDP growth rate, as described by Okun's Law, is a cornerstone of macroeconomic analysis. Okun's Law suggests an inverse relationship between changes in unemployment and changes in GDP, with a reduction in unemployment typically correlating with an increase in economic output. Understanding this dynamic is essential for identifying how fluctuations in labor market conditions influence economic performance. By examining this relationship through the lenses of geography, sex, and age, this study aims to uncover nuanced patterns that traditional aggregate analyses might overlook, providing a deeper insight into how labor market variations impact growth across different demographic groups.

Importance of assessing this topic:

* **Macroeconomic Stability** : Insights will support better forecasting and policymaking to mitigate economic downturns and foster sustainable growth.
* **Demographic Equity** : Disaggregating by sex and age offers a deeper understanding of how economic shocks affect different segments of the population, ensuring that policies address the needs of all groups.
* **Comparative Analysis** : Evaluating the relationship across continents and countries allows for the identification of best practices in mitigating unemployment's impact on GDP.

In this study, we conducted a comprehensive analysis of the relationship between the unemployment rate and real GDP growth rate from 2014 to 2023 using both visualizations and panel regression techniques. We began by exploring the data through interactive visualizations created with plotly, seaborn and matplotlib, which allowed us to identify trends and patterns across continents, countries, sex, and age groups. Building on these insights, we employed panel regression models to control for both time and country-specific effects, enabling a more robust understanding of the causal dynamics at play. This mixed-method approach provided a multifaceted view of how labor market fluctuations influence economic performance, uncovering both global trends and localized differences in impact.

## Conclusion and Future Work

<h4> Conclusion <h4>

Given the various types of analysis performed, there are several conclusions derived:

1. **Overall Trends:** Global Economic events impact all continents, with variations in economic recovery influenced by geographical region, land size, and government policies, while GDP growth rates were similar within continents, unemployment rates varied, suggesting other factors contribute significantly to GDP performance.
2. **Correlation:** There is a negative correlation between GDP growth rate and unemployment rate in most of the countries. The positive correlation in AS/EU and SAM areas can be attributed to high agricultural Employment Share, high proportion of informal employment, increase unpaid family labor and labor market protection
3. **Sex and Age Groups**: Overall GDP growth was similar across all groups, even as females and youth faced higher unemployment, the correlation between unemployment and GDP growth was weak. This suggests that while groups face greater employment challenges, these do not strongly influence overall growth. Other factors likely have a more decisive impact on GDP trends.
4. **Regression:** The regression analysis indicates that while the unemployment rate weakly predicts GDP growth, regional economic characteristics and other factors play a more significant role in shaping economic performance.

<h4> Future Work </h4>

Taking into considerations the limitations of our analysis, below are approaches to make our analysis more reliable and accurate:

* **Include other independent variables that affect Real GDP such as consumer spending, business investment, government expenditure, etc.**
  * Additional variables like consumer spending, business investment, and government expenditure influence GDP by affecting demand and supply dynamics, providing a more comprehensive understanding of economic growth.
* **Find data for Real GDP growth rates sex and age group specific**
  * Analyzing Real GDP growth by sex and age groups highlights demographic-specific economic trends, revealing disparities in employment and economic outcomes across different populations.
* **Utilize dynamic modeling to  capture the time-lagged and reciprocal effects between unemployment and real GDP growth**
  * Dynamic modeling, such as Vector Autoregression (VAR) or Autoregressive Distributed Lag (ARDL), helps capture the lagged and reciprocal relationships between unemployment and GDP growth, allowing for a more accurate understanding of how these variables interact over time.
* **Explore how global economic shocks, like COVID-19 or financial crises, impact the relationship between unemployment and real GDP growth across regions and demographics**
  * A deeper study of global economic shocks, such as the COVID-19 pandemic and the 2008 Financial Crisis, will provide insights into how these disruptions reshape the unemployment-GDP relationship over time. By analyzing the long-term and short-term effects across different regions and demographic groups, this approach helps identify patterns in how economic shocks influence labor markets and economic growth, revealing varying recovery trajectories and resilience factors.

## User Instructions

<h3> Environment Setup </h3>

To run this program, it is recommended that you use either Jupyter Notebook or Spyder in an Anaconda environment. Anaconda provides a comprehensive package management system and comes pre-installed with many essential data science libraries. The **Code** folder includes 6 notebooks that were utilised to draw conclusions and the **Data** folder includes the datasets pre-cleaned and post-cleaned.

<h3>Required Libraries</h3>

The table below shows the Python libraries that must be installed to ensure the program runs smoothly. You can install them via pip or through Anaconda.

<h4> pandas </h4>

```
pip install pandas
```

<h4> numpy </h4>

```
pip install numpy
```

<h4> seaborn </h4>

```
pip install seaborn
```

<h4> Matplotlib </h4>

```
pip install Matplotlib
```

<h4>statsmodels</h4>

```
pip install statsmodels
```

<h4> linearmodels </h4>

```
pip install linearmodels
```

<h4> scipy </h4>

```
pip install scipy
```

<h4> plotly </h4>

```
pip install plotly
```

<h3> Order of Files to run </h3>

To ensure a smooth story to explain the processes and findings, our team. high recommend running the files in the order specified below. The files are also numbered accordingly to assist with the sequence. Navigate to the **Code** file and run the files below:

1. **Clean_Script.ipynb**
2. **General_Analysis.ipynb**
3. **GDPRate_UnemploymentRate_Analysis.ipynb**
4. **AgeGroup_Analysis.ipynb**
5. **Sex_Analysis.ipynb**
6. **Regression.ipynb**
